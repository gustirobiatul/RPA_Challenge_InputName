# RPA_Challenge_InputName
In this project, i created an automation for rpa challenge to input forms based by downloaded excel 
Step: 
1. Read Config ( A file which you can make to be a configuration for this project) 
2. Get Path for downloaded file 
3. download the file from rpachallenge.com 
4. Check whether the Pop up for save is is coming up, if isnt then retry for 3 times. 
5. save the file at the path we write in config file 
6. open the file, and extract the data with for each row
7. using anchor base, input the forms based by the data wee extracted 
    Tips: Choose an accurate selector (like name of the field) and make sure there are no "Index" in selector
8. Click Submit 
