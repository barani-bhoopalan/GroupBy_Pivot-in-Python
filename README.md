# GroupBy_Pivot-in-Python
Input data had  transaction Id in one column and different items purchased with each invoice listed in a separate column. I had an issue doing pivot in excel as it just gave me Group by solution. I wanted row containing unique transaction Id and all the items purchased under that transaction listed in separate columns (array under each invoice Id did not have uniform length; not a uniform array = not a fixed column count). Using combined effect of Group by, Dictionary and index function in python, I was able to achieve the desired output.
