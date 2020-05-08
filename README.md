# accent-classification-deep-learning
 ## augmentation.ipynb:  ##
1. Takes speakers_all.csv
2. Finds top 51 classes
3. For each of these classes, it augments data to get 50 files.(50 files for 51 classes would generate a decent number of samples)
4. Each of these 50 files gets pickled
6. The augmented data filenames are added to csv 
7. Pickle files are read into the df

Since the pickle files generated are in drive, you can skip steps 3,4,6(code lines of these steps are commented in the notebook)
df read from step 7 can further be used to get mfcc,melspec info for your models
