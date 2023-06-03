import pandas as pd      # import pandas library
data = pd.read_csv('/home/ankit/Downloads/archive/netflix.csv')   
data.shape # TO SHOW NO'S OF ROWS AND COLUMNS
data.head() #SHOW DATA TOP 5
data.tail()  #TO SHOW BOTTOM 5 RECORD 
data.columns   # TO SHOW EACH COLUMN OF DATASET
data.size  # to show  NO OF TOTAL VALUES (ELEMENTS) IN DATA SETS
data.dtypes  # TO SHOW DATA-TYPE EACH COLUMNS
data.info #Gives information about your data
