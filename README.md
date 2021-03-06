# Radiocarbon_inc_2012
Analysis of radiocarbon incubation data testing temperature sensitivity of fast-cycling and slow-cycling carbon pools

Data used in this analysis are stored in the NGEE-Arctic data repository.  radiocarbon_incubation_Barrow_2012.csv can be accessed at http://dx.doi.org/10.5440/1364062

Description of files:

(1) Delta_analysis.Rmd uses the Delta2 and Delta3 metrics to evaluate the temperature sensitivity of bulk CO2 and of slow-pool and fast-pool CO2 using the lme4 package.  File included simulation-based power analysis.

(2) TT_calculation.Rmd uses a time-dependent steady state model to evaluate 14C for specified vectors of turnover times, analysis years, and carbon residence times in vegetation.  Code can be used iteratively to model turnover time from radiocarbon data.  Model is based on Torn, M., Swanston, C., Castanha, C. and Trumbore, S.: Storage and turnover of organic matter in soil, Biophys.-Chem. Process. Involv. Nat. Nonliving Org. Matter Environ. Syst., 219–272, 2009.  

(3) atmospheric_14C.csv is the annual summertime values for atmospheric 14CO2 in Barrow, AK.  Dataset has been compiled from the IntCal13 dataset (Reimer, P. J., Bard, E., Bayliss, A., Beck, J. W., Blackwell, P. G., Ramsey, C. B., Buck, C. E., Cheng, H., Edwards, R. L., Friedrich, M., Grootes, P. M., Guilderson, T. P., Haflidason, H., Hajdas, I., Hatté, C., Heaton, T. J., Hoffmann, D. L., Hogg, A. G., Hughen, K. A., Kaiser, K. F., Kromer, B., Manning, S. W., Niu, M., Reimer, R. W., Richards, D. A., Scott, E. M., Southon, J. R., Staff, R. A., Turney, C. S. M. and Plicht, J. van der: IntCal13 and Marine13 Radiocarbon Age Calibration Curves 0–50,000 Years cal BP, Radiocarbon, 55(4), 1869–1887, doi:10.2458/azu_js_rc.55.16947, 2013.), measurements from Fruholmen, Norway (Nydal, R. and Lövseth, K.: Carbon-14 measurements in atmospheric CO2 from northern and southern hemisphere sites, 1962-1993, Oak Ridge National Lab., TN (United States); Oak Ridge Inst. for Science and Education, TN (United States). [online] Available from: http://www.osti.gov/scitech/biblio/461185 (Accessed 24 May 2017), 1996.), and Barrow measurements (unpublished data and data from Graven, H. D., Guilderson, T. P. and Keeling, R. F.: Observations of radiocarbon in CO2 at seven global sampling sites in the Scripps flask network: Analysis of spatial gradients and seasonal cycles, J. Geophys. Res. Atmospheres, 117(D2) [online] Available from: http://onlinelibrary.wiley.com/doi/10.1029/2011JD016535/full (Accessed 24 May 2017), 2012.)

(4) CO2_14C_statistics.Rmd uses linear mixed effects models with the lme4 package to evaluate changes in CO2 emissions and 14C of CO2 over sequential incubations.

(5) CO2_flux_plots.Rmd generates plots summarizing CO2 production and 14C measurements over sequential  incubations
