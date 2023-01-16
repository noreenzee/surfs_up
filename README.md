# surfs_up
# OverView Of The Analysis:
                    Surf's Up analysis is designed to get the data that can be used to convince investors to invest in Surf. This analysis shows the results of the months of June and December that can be compared to make decision how weather change affect the demand of icecream and shake on the whole. so, if investor have any concerns about their investment in Surf this data can be checked to see if their corcerns are really true or not.
# Sources:
        *-Data Hawaii_sqlite
        *-SurfsUp_Challenge_starter_code.ipynb
# Langurage: 
          Sql, python, SQLAlchemy,numpy etc.
# Results:
# Deliverable 1: Determine the Summary Statistics for June:
                                                        In order to determine the summary statistics for June Dependencies are imported first. Then a quary is written to filters the measurementn table to retrieve the temperature of the month of June and this quary shows the following outcomes:
                                                        [(54.0, 85.0, 71.66378066378067)]
  In the next step June temperature is converted into a list that looks like this:
  ![image](https://user-images.githubusercontent.com/112978144/212776014-b876f9fc-5431-4dcd-a40e-416bb5a8a964.png)
After converting the June temperature into a list a DataFrame is created for the month of June that is as follow:
![image](https://user-images.githubusercontent.com/112978144/212776287-642d7644-00ec-4dbb-a842-00ad01140d3d.png)

# Deliverable 2: Determine the Summary Statistics for December:
                                                            To get the statistical results from the month of December first a query is written that filters the Measurement table to retrieve the temperatures for the month of December that provided the temperature from 2010 to 2011. Then December temperature is converted into a list. 
Next the list of December temperature is converted into a pandas DataFrame.
# summary statistics for the month of December:
                                      A quary is written to calculate the summary statistics for the month of December that is as follow:
                                      ![image](https://user-images.githubusercontent.com/112978144/212777627-25b73c66-792a-42a2-a590-d6b786631222.png)
# Additional Merging Data: 
                    Additionally both June and December data is merged to compare both temperatures.
                    
![image](https://user-images.githubusercontent.com/112978144/212777879-7c0fda92-3d60-49d6-b4f8-a6c94db788a3.png)
# summary Of the Findings:
                        Finding from the both months shows that even though temperatures recorded in December vary more than June, December is providing more appropriate weather conditions for surfing and ice cream demand. There is not a big variation is Dec and June temperatures as we can check the merged table so, investor should not have any concerns while investing in Surf's as mean temperature difference between June and December temperature is only about 3 degrees.



