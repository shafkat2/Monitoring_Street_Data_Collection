
### Monitoring_Street_Data_Collection

    The project was a large scale collection of data through an app that was build on flutter.A total of 98 agents collected picuters using an app through mobile phone to upload data on the cloud.This project was to monitor the activity of the agents in a map to capture better quality data.

#### Architecture

       | Upload of Data  |                     |                                |
       | ----------------| Script for ETL      |                                |
       |                 |---------------------|                                |   
       |                 |                     | Generate Map Using Co-ordinates|
       |                 |                     |--------------------------------|                  



* User uploads data to the cloud
* Cache data, does ETL on the collected Data
* Map and simple analytic, produces Map where the co-ordinates are shown of the collected data points

#### Sample Pictures
    
![Picture 1](./pictures/Total_Collected_Pics.PNG)


![Picture 2](./pictures/Zoomed_view.PNG)




#### Libarary used

        - Dash
        - Panda
        - Plotly
        
