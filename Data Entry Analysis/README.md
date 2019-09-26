# Project Name
 Data Entry Analysis
 
# Project Description
  Data entry analysis of three files which contain the day-night distribution of two species of Zooplankton across multiple years. The type of Zooplankton studied is called rotifers generally, and specifically the genus Conochilus, in which groups of individual rotifers stick together in colonies.
  
# List of data files 
    1. Pond2010.xls
    2. Zoop-temp.xls
    3. Zoop-temp-main.xls
    
# Problems with Data files
 Some of the data are missing from the data files. They are
   1. Time data is unavailable. As we know plankton change their distribution from day to night, its very important to collect at what time the samples were taken.
   2. In Zoop-temp file, Chippo #/L value is negative which is not possible.
   3. In pond2010 file, what the 'z' column contain is not mentioned anywhere.
   4. What is meant by Red and yellow highlights is not mentioned anywhere.
   5. Units for the measurement in not mentioned in any data file. For example - We do not know the the unit measurement of density, temperature, depth, and colony diameter.
   6. In pond2010 file, density and colony diameter are missing for few days.
   7. There are redundancy of data in zoop-temp and zoop-temp-main file. Some of the data are same in these files.
   8. Yellow notebook for map and details are missing.
   9. Graph could not explain any relationship between the x-axis and y-axis variable.
   
# Solutions for a new system 
  1. A time column should include to the file that would store the time in 24 hour format on which the sample would be taken. The time should be HH:MM:SS format.
  2. No negative number should be entered. After entering the data for a particular timestamp one must recheck the data file.
  3. All the column should have a meaningful name for better understanding.
  4. Importance of red and yellow highlights should be mentioned in the data files.
  5. Every column name should include the units as well for measurements.
  6. Each column should have some input. we must not put blank for samples. 
  7. The file size can be reduced. We can achieve the comparison between two species for multiple years by keeping only two files, one for Cuni and one for Chippo.
  8. Yellow notebook for map and details must include in the data file.
  9. Graph must explain the variable name. What variables in the x-axis and y-axis.
  
# Table Template
 Data File 1 : Chippo
 
| Date(MM/DD/YY) | TIME(HH:MM:SS) | DEPTH(cm) | DENSITY(g/cm3) | COLONY SIZE(cms) | CHROPHYL A | TEMP (Fahrenheit) | STATION NAME |
|----------------|----------------|-----------|----------------|------------------|------------|-------------------|--------------|
|                |                |           |                |                  |            |                   |              |
|                |                |           |                |                  |            |                   |              |
 
 Data file 2 :  Cuni
 
 | Date(MM/DD/YY) | TIME(HH:MM:SS) | DEPTH(cm) | DENSITY(g/cm3) | COLONY SIZE(cms) | CHROPHYL A | TEMP (Fahrenheit) | STATION NAME |
|----------------|----------------|-----------|----------------|------------------|------------|-------------------|--------------|
|                |                |           |                |                  |            |                   |              |
|                |                |           |                |                  |            |                   |              |

# External links for more information
 [Phytoplankton](https://en.wikipedia.org/wiki/Phytoplankton)
 
 [Zooplankton](https://en.wikipedia.org/wiki/Zooplankton)
  
 [Conochilus](https://eol.org/pages/43393)
 
 
# Contributor
 Nishi Mahato
 
 Graduate Student (MIS)
 
# License
 License is available [Here](https://choosealicense.com/licenses/mit/)
 
 ![Zooplankton](https://upload.wikimedia.org/wikipedia/commons/e/e3/Meganyctiphanes_norvegica2.jpg)