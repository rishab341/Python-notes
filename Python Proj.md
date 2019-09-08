import pandas as pd
xyz= pd.read_csv(r"E:\Python\XYZCorp_LendingData.csv",sep='\t')
xyz
##### Sep=\t is to avoid delimiter issue#####
xyz.shape
xyz.describe(include='all')
pd.set_option('display.max_columns', None) #### This is to gte maximum rows and cloumns######
pd.set_option('display.max_rows', None)
