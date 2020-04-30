# ParkiTech
A parking lot recommendation system. This is the final project of CSE 6242 Data &amp; Visual Anaytics.  
Our project aims to solve the parking spot finding problem in San Francisco. We want to design a user-friendly parking recommendation system to help drivers find the desirable parking spots near their destination. The technical difficulties can be broken down into 3 main problems: time series analysis, geographic data aggregation and risk-distance-cost trade-off problem.

Our team members include Yingfei Chen (webpage construction, assembly of front/back-end), Tianhao Wang (webpage construction, assembly of front/back-end), Yuechen  Wu (recommendation trade-off model design, assembly of front/back-end), Winnie Zheng (final report writing), Jincheng Zhu (data mining, prediction model design, assembly of front/back-end).  

You can view our final presentation video [here](https://youtu.be/-fOp2qo7tDM). Detailed description can be found in [our final project report](https://github.com/Jincheng97/ParkiTech/blob/master/CSE6242_final.pdf).

## Running instructions
### 1. DESCRIPTION:  
#### (1) 'Final Code' folder contains all necessary codes to run our final work.  
'Final Code\code' folder contains all the core code including the back-end part and the server.py to creat a listening handler.  
'Final Code\data' folder contains all the data we use.  
'Final Code\html' folder contains the html file and image source fo rthe web page.  
#### (2) 'Data Clean' folder contains all codes required for data clean. 
You don't need to run them. They are just for reference. Just in case you are interested, before running any notebook file, you should put the data source file (link in section 5) in side the folder.  

### 2. INSTALLATION:  
Download Tornado. Tornado is a Python web framework and asynchronous networking library.   
Please make sure you download the correct version for your system. After downloading it, please unzip and install it under the directory where you installed your python.  
Put 'myfolder' directly under the directory of tornado-master.  
Use Anaconda to execute the server.py script in 'code' folder. It will create a listening handler.  
Use ‘python -m http.server [port number]’ to construct a server on PC. You can use any port number except 8000.  
Because We use it as the URL for receiving request from web page. And if you didn't type in a specific one, cmd will use 
the default number 8000, which will lead to an error by all means.  

### 3. EXECUATION:  
Use FireFox browser to open our html file(in the 'html' folder), and you can operate it now.  

### 4. ABOUT VIDEO:  
According to my own experience, we need to know the python environment explicitly in advance.  
It's because tornado frame requires python’s support and our sophisticated back-end programs also relies on python.  
Make sure you update relative libraries to correct versions.I will also attach a video to show my demo’s good performance.  

### 5. DATA SOURCE:
https://dataverse.harvard.edu/file.xhtml?persistentId=doi:10.7910/DVN/YLWCSU/JR6JYL&version=2.0
