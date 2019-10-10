# Project Name
 Data Exploration
 
# Project Description
  Some initial data exploration of our project using R. 
  
# List of data files 
  * [2017 Weather Observations (1).xlsx](https://github.com/Nishi-Mahato/8086-Assignments/blob/master/DataExploration/2017%20Weather%20Observations%20(1).xlsx)

# Scatter Plots
    
### Two scatter plots of two different variables
 ![Scatter plots of variable month and current](https://github.com/Nishi-Mahato/8086-Assignments/blob/master/DataExploration/Rplot.png)
 
 Code :
    * ggplot(data=test)+
    
    + geom_point(mapping=aes(x=Month, y=Current), color = "blue")
    
 Observation:
   From the above scatter plot we can see that in the month of july current was maximum and in the month of january it was minimum.
 
 ![Scatter Plots of variable High and Low](https://github.com/Nishi-Mahato/8086-Assignments/blob/master/DataExploration/Rplot01.png)
   
 Code :
    * ggplot(data=test)+
    
    + geom_smooth(mapping=aes(x=High, y=Low), color = "blue")
    
 Observation: 
    From the above scatter plot we can see that the lowest weather temperature was 22 and highest was 75. 
### One scatter plot of two variables with a trend line added in
 ![Scatter Plots with a trend line](https://github.com/Nishi-Mahato/8086-Assignments/blob/master/DataExploration/Rplot03.png)
  
 Code :
    * ggplot(data= test,mapping =aes(x=High, y = Low))+
    
    + geom_point()+
    
    + geom_smooth()
    
 Observation:
    From the above scatter plot we can see that most of the time current was high only.

### One faceted plot of two variables, properly labeled
 ![Faceted plot ](https://github.com/Nishi-Mahato/8086-Assignments/blob/master/DataExploration/Rplot02.png)
 
 Code :
    * ggplot(data=test)+
    
    + geom_point(mapping=aes(x=Precip, y= 'New Snow'))+
    
    + facet_grid(.~Month)
    
 Observation:
    As per my observation, most of the time new snow is 0.


# External links for more information
 [R for Data Science: Data Visualisation](https://r4ds.had.co.nz/data-visualisation.html)
 
 [R for Data Science: Tibbles](https://r4ds.had.co.nz/tibbles.html)
  
 [R for Data Science: Data Import](https://r4ds.had.co.nz/data-import.html)
 
 
# Contributor
 Nishi Mahato
 
 Graduate Student (MIS)
 
# License
 License is available [Here](https://choosealicense.com/licenses/mit/)