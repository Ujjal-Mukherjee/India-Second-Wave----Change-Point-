# India-Second-Wave----Change-Point-
This repository presents the code, data and output for the likelihood ratio based quickest change point detection test for the India second wave. 
The file descriptions are as follows:
  IndisResid.Rmd --- R code file for the change point analysis. The change point analysis uses generalized likelihood based test for different change points and different stopping times for each change point tested.
  All_District_Change_Point.png --- the graphical output for the joint change point for all districts, the optimal stopping is two weeks for a false discovery rate of 1%.
  ChangePoint.png --- change point plot similar to the previous file. 
  India_Residual_Plot_geom_with_Change_Point.png --- the graphical plot for optimal change points for each district individually. The blue dotted line is the start of the Kumbh Mela event, and the black dashed line is the optimal change point with 15 day stoppint time. 
  LogLikMat.csv --- the output of the code showing the GLR estimate for different change points and different stopping times in matrix format.
  pValue_Mat.csv --- the Chi-square p-values corresponding to the GLR estimates. 
  Change_Point_Test.csv --- hypothesis test output for GLR based change point at the event start date. 
  ErrorResidualIndia.csv --- the beta estimates and the prediction errors for the multivariate SIR model. 
