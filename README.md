2020 Analysis and Application of Big Data final project  
Dataset used: [Beijing PM2.5 Data Data Set](https://archive.ics.uci.edu/ml/datasets/Beijing%20PM2.5%20Data)  

**Goal: To figure out the correlation of the weather conditions and the pm2.5 indices.**  
Several classifying methods(Random Forest/Baye's/Logiatic Regression) have been applied.  

* Data Preprocessing
    * Missing values replaced by arithmetic mean of the rest of the values.
    * Remove useless/redundant data.
    * Encoding categorical data.
    *  Data binning('excellent', 'good', 'light', 'moderate','heavy',and 'severe')
    *  Data normalization(min-max normalization).
    *  Splitting the dataset into training set and test set.
