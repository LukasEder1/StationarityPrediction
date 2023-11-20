# StationarityPrediction
Data contains the annotations from the other task (temporal validity estimation) but we can reuse them here for the binary task of stationarity estimation. 
* vote1 and vote2 are provided by the crowdworkers. vote3 is supplied by a student when there was no agreement between the crowdworkers (otherwise -1). 
* The final_vote is the majority vote if one exists (otherwise -1).
* Class 0 denotes "no time-sensitive information" (i.e., this should usually be stationary or hypothetical information, although in some cases it may also be 
possible that information is contained in the past). One can nevertheless treat it as stationary data. There should be ~1500 such statements that were 
determined to be stationary. 
* Statements of any other class would mean time-changing (time-sensitive) information.

