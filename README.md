# TimeSeriesForcasting

keep update : 

docker setup and decided to use google colab instead  

now training prophet to forcast all id  
aprrox. time : 12-24 hours  

![image](https://user-images.githubusercontent.com/26840831/202096283-c07d4dbd-9e8e-4408-948a-a99329fea454.png)

<br>

### 20 nov 2022  

#### Changing plan  

Move the training for ML to other computer (more power)
It taking too long to forcast all ids for 28 days on local machine or google colab.

use docker and set environment to run model training  
#### EDA part  
not show much just cleaning data and some explore then rearrange data to be the right input format to the training with Prophet model 

#### Forcasting result 
save to csv file : [forcasting_result](forcast_allids_df.csv)

#### Evaluation  
cross validation and tuning to find best parameter with WMAPE  
WMAPE would have measure the performance on the forcasting ot the model.

