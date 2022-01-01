#**Surfs Up Overview!**

  The purpose of our statistical analysis was to determine the  key differences between the weather patterns in the Months od June, and December on the island of Oahu, Hawaii. The   reason we needed this information was to show viability for a surf and ice cream shop year round on the island. We used the power of Data retrieval from a SQLlite Database and it's interactions with the SQLAlchemy library to effectively display and analyze our temperature trends.
  
#**Technology and Data Sources**

  - Data Source: hawaii.sqlite
  - Files: SurfsUp_Challlenge.ipynb , climate_analysis.ipynb
  - Software and Packages: SQLlite, Python(pandas, ORM, SQLAlchemy), Flask, Jupyter Notebooks
  
#**Results**

  Mahalo Kiki! 
  -The Summary Statistics of the months of June and December's temperatures are as follows: 
  ![Screenshot 2021-12-29 summary_stats](https://user-images.githubusercontent.com/93295751/147694374-25f1e1d3-e222-4fee-a963-a84aff3276d1.png)

  -As we Can see the average temperature for the month of June was about 75 degrees F, with a low of 64 degrees and a high of 85 degrees. Contrast June with the month of December    and we see that we have an average, low, and high in temperatures Fahrenheit of; 71 degress, 56 degrees, and 83 degrees respectively. 
 - What we can see from these temperature differenetials is that the average temperatures really do not fluctutate widly only about 4 degrees fahrenheit. Looking at the highs for    the months we can see an even smaller difference of only about 2 degrees fahrenheit. 
 - Although it should be noted that the low temperature differentail between the months is defintiely statistically different. if the temperatures were to stay on the lower side,    it could be inferred that it could affect surfing participation during those days. 
 
 #**Summary**
 
  Based on the results it semms that December temperatures vary to a larger degree than they do in June, However the variance is not enough to suggest that surfing participation   and ice cream sales would be affected enough to not justify opening up a surf shop on the island. The temperature differnetial is only a 4 degree differnece. But before        making a   final decision i would suggest looking at the precipitation averages for these months:
  
  The precipitation differences for June and December:
  ![Screenshot 2021-12-29 Summary_prec](https://user-images.githubusercontent.com/93295751/147842732-e1f31126-ffdb-4ae8-a29e-7ac3f6be4e58.png)

![Screenshot 2021-12-29 June_prec](https://user-images.githubusercontent.com/93295751/147842735-8e9e4812-5b3f-4ec5-8659-9f2b1f096fda.png)

![Screenshot 2021-12-29 Dec_prec](https://user-images.githubusercontent.com/93295751/147842740-609e0ef4-4004-413d-b775-2c60740c8e7d.png)

What we can see when looking at these tables is that the standard deviation of rainfall measured in inches, is about .11 differential with December having more rainfall. The mean rainfall differnece is about 8/100ths(.08) of an inch more for December. the max recorded precipitation is nearly 2 inches more in December however which is a very large difference. All in all, with the relatively steady temperature differentials, and the minor variance in precipitation for the months of June and December I would say that precipitation would not be likely to make a big impact on surfing participation except for perhaps in outlying circumstances. 

  
   
