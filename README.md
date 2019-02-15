# Mobility-Lab-Matlab-API
An API to import metadata and measurements into Matlab from the MobilityLab Software

Place extractMeta.m in the same directory as the exported csvs from mobility lab
extractFeatures.m uses the output of extract.m to generate a design matrix that corresponds to the metadata.

Please note that extractFeatures.m is likely to required modification to account for study specific meaurements (number of features and test types). The example given here is for the common 'Walk' test used in Mobility Lab. However, if alternative tests such as Sway, TUG, or PULL are used the indices of features will need to be modified (such as on lines 25, 26, and 31). The initation size of the design matrix will also need to be changed (Line 6, p=108) to match the number of features exported from Mobility Lab.
