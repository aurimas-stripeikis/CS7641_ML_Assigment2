**__If any issues please email astripeikis3@gatech.edu__**


Step 1. Place data in same directory as notebook

  - Data can be found at https://drive.google.com/drive/folders/1R-cPqFMU_nkBzS789-PsoIazwxyMbWeM?usp=sharing

Step 2.a In cell 16, uncomment line "#spark=pyspark.sql.SparkSession.builder.appName("parquetFile").getOrCreate()"

Step 2.b In cell 16, uncomment block under #Problem 2
  "#DATASET 5: ['TSLA','X'] TRAINING_TEST_DATE = '2012-01-01', START_DATE = '2011-01-01', END_DATE = '2013-01-01'"
  ...
  "# save_processed_parquet_version(testing2_set_sdf, cwd+'/testing-m10-tf_vdates_mini5')"

  
Step 3. Run all cells in order until you reach cell that says "SVM"

      

