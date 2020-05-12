# Electric_motor_temperature

Implementation of machine learning models to predict the temperature of an electric motor based on some other physical values.

The detailed explanations could be found in the report: https://github.com/Massine/Electric_motor_temperature/blob/master/04_Reports/project_report.pdf

##Important instructions
**the code was run on google colab with drive google mounted. Before running the code, some adjustments should be done**
-	If it is run locally: 
..-the cell bellow should be deleted before running the notbook
from google.colab import drive
drive.mount('/content/gdrive')
..-the paths should be updated according the fold structure. Example: the link bellow
df_raw=pd.read_csv('/content/gdrive/My Drive/Data Science/Electric_motor_temperature/01_Data/01_Raw/pmsm_temperature_data.csv') 
-	If it is run on collab with google drive as a storing drive:
..-The paths should be updated according to your folder structure

##Data
The data comes from: https://www.kaggle.com/wkirgsn/electric-motor-temperature

License and use:
The data ower allowed the use of the data under condition of refering to two published papers. The parpers were mentionned in the report file and can be found on there two following places https://www.researchgate.net/publication/331982128_Deep_Residual_Convolutional_and_Recurrent_Neural_Networks_for_Temperature_Estimation_in_Permanent_Magnet_Synchronous_Motors and https://www.researchgate.net/publication/331976678_Empirical_Evaluation_of_Exponentially_Weighted_Moving_Averages_for_Simple_Linear_Thermal_Modeling_of_Permanent_Magnet_Synchronous_Machines

##Folder structure
