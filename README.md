# UFOs
Module 12

## 1. Overview of the analysis:

### This is a project to extract data of UFOs observation locations, timestamp and its description using JavaScript, then rearrange a table on webpage with filters that could  enhance enduser's experience for quick lookup based on variety of criteria. 
      
## 2. Results:
#### 1). To naviage the UFOs witness date, locations by city, state or country, UFOs shape, simply apply the searching criteria, then click on "Apply Filter" as shown in image: 
      
![image](https://github.com/jilldvn/UFOs/blob/main/image/filter.png)

#### 2). After apply the filter, then the values based on searching criteria will be displayed on the main table. 
      
![image](https://github.com/jilldvn/UFOs/blob/main/image/filteredresult.png)
      
#### 3). This is also allowed to enter single or multiple criteria according to needs. Click on the left top corner "UFOs Sightings" to return entire data table without filters. 
      
![image](https://github.com/jilldvn/UFOs/blob/main/image/clearfilter.png)
      
      
## 3. Summary:

#### There is one limitation on the page that the strings entered into filter field strign or timestamp format must be exact matched with the table value. For example, if the string is in upper case, the value can't be loaded. 

#### It is recommended to allow similar values entry without exact match, in this case, it can be also first-time user friendly that can benefit the users not familiar with information to promote their nagivating experience.  

#### Second recommenation, for promote visualization, since there are many searching criteria relating to locations, city, state and country, it may be also helpful to dispay the data and tootip on a map, using plotly library such as bubble map, so users can easity identify the densities or distributions with just a quick glance. 
