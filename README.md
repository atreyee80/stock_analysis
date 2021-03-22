# stock_analysis

## Overview of Project
Steve is freshly graduated and his parents wants to invest in stock,his parents believe that if fossil fuel ends
up,there are alternative ways to get energy like Hydro,Geothermal,Wind,Bio ,but his parents has not done 
enough research where to invest ,they finally decide to invest in “DAQO New Energy Corp”,a company
that makes solar panel “DAQO” ticker symbol is “DQ”so Steve will look after “DAQO” stock and  decide
if that will be good to invest  for their parents.
VBA will help to automate the task easily and efficiently without any errors.
Steve will check for "All Stock Analysis" and will conclude which will be a better choiceto invest.Refractoring code will
be used to compare the efficiency of both years 2017 and 2018.


## Results
So from the analysis it shows that in 2017 “DQ” return is 199.4% while in 2018 “DQ” returns drop to -62.6%
Steve will check the total daily volumes of all stocks and yearly return of each stock,the yearly return of
each stock is calculated by the percentage difference in price from the beginning of the year to the end of 
the year.
Color formating helps to give the results easily where “Green” color shows that the return is positive and
“Red” color shows that the return is negative.
The images for both the year 2017 and 2018 shows that in 2017 the yearly return for “DQ” is 199.4% but it
drops abnormally in 2018 -62.6% so this stock is very volatile,however “AY” stock for 2017 is 8.9% and in 2018
“AY” stock drops to -7.3% so this stock neither goes up too much nor does it drops too much,so this can be an option
for his parents if they decide to invest in “AY” provided it gives good dividend support.

![](Resources/Stock_Analysis_2017.png?raw=true)![image](https://user-images.githubusercontent.com/79482680/111933231-055dfe80-8a8d-11eb-9d16-3038016d065f.png)


![](Resources/Stock_Analysis_2018.png?raw=true)![image](https://user-images.githubusercontent.com/79482680/111933089-c29c2680-8a8c-11eb-87e0-bb2b029c6d00.png)


Again from 2017 “ENPH” stock shows an increase of 129.5% and in 2018 “ENPH” stock is at 81.9% which   
can be consider as an option to invest,but definitely not “DQ” as this  stock is more volatile.
So Steve decided to do analysis on multiple stocks using refractoring of “DQ” stock with little change in ticker arrays
the code is running faster in refractoring code which shows that for 2018 the time taken is 0.2021484 and in 2017 the
time taken is 0.197998  but  in original  code it is taking 1.283203s and in 2017 it takes 1.281255s

![](Resources/VBA_Challenge_2017.png?raw=true)


![](Resources/VBA_Challenge_2018.png?raw=true) 

 
## Summary

1.What are the advantages or disadvantages of refactoring code?

  A. The advantages of using refractoring code is that it runs faster,since no nested for loop is working.
  B. The disadvantages of refractoring code is that it will work only if the data are sorted.
  
2.How do these pros and cons apply to refactoring the original VBA script?
 A. The pros of refractoring the original VBA script is that the results can be seen very quickly as it is more efficient way of  writing the code specially if the dataset is very big.
 B. The cons of refractoring code in the original VBA script is that the code will work only if the data is sorted,if data is not sorted then only the volume will be calculated but starting and ending price will not be calculated.

