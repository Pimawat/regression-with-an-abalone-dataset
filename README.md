# regression-with-an-abalone-dataset

Predicting the age of abalone from physical measurements.  The age of abalone is determined by cutting the shell through the cone, staining it, and counting the number of rings through a microscope -- a boring and time-consuming task.  Other measurements, which are easier to obtain, are used to predict the age.  Further information, such as weather patterns and location (hence food availability) may be required to solve the problem.

From the original data examples with missing values were removed (the majority having the predicted value missing), and the ranges of the continuous values have been scaled for use with an ANN (by dividing by 200).


Sex :	M, F, and I (infant)
Length :	Longest shell measurement	mm
Diameter :	perpendicular to length	mm
Height :	with meat in shell	mm
Whole_weight :	whole abalone	grams
Shucked_weight :	weight of meat	grams
Viscera_weight :	gut weight (after bleeding)	grams
Shell_weight :	after being dried	grams
Rings	Target :	+1.5 gives the age in years
