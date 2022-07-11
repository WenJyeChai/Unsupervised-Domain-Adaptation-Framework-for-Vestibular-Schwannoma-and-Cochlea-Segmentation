# Unsupervised-Domain-Adaptation-Framework-for-Vestibular-Schwannoma-and-Cochlea-Segmentation
An improved framework that performs domain adaptation on Vestibular Schwannomas and cochlea segmentation


1. Due to the large file size of training and validation data, it is not feasible to upload it on github, users are required to download it from the crossMoDA 2021 challenge website: https://crossmoda.grand-challenge.org/
   - The training ceT1 MRI scans with the naming convention of crossmoda_XXX_ceT1.nii.gz should be placed under the directory of 'dataset\raw_dataset\training_data\source_sample\ceT1_MRI_scans'
   - The training ceT1 MRI segmentation masks with the naming convention of crossmoda_XXX_Label.nii.gz should be placed under the directory of 'dataset\raw_dataset\training_data\source_sample\ceT1_MRI_labels'
   - The target hrT2 MRI scans with the naming convention of crossmoda_XXX_hrT2.nii.gz should be placed under the directory of 'dataset\raw_dataset\training_data\target_sample'
   - The validation hrT2 MRI scans with the naming convention of crossmoda_XXX_hrT2.nii.gz should be placed under the directory of 'dataset\raw_dataset\validation_data'
   
   ** Please remove the sample files in those directories before moving them.
