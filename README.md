# Mobility-Lab-Matlab-API
An API to import metadata and measurements into Matlab from the MobilityLab Software

Place extractMeta.m in the same directory as the exported csvs from mobility lab
extractFeatures.m uses the output of extract.m to generate a design matrix that corresponds to the metadata.

Please note that extractFeatures.m is likely to required modification to account for study specific meaurements (number of features and test types). The example given here is for the common 'Walk' test used in Mobility Lab
