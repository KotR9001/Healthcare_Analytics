# Healthcare_Analytics
Created this project to determine the effect of various factors on life expectancy, adult mortality, infant deaths, and under-five deaths.<br />
![Health_and_Wellness](https://github.com/KotR9001/Healthcare_Analytics/assets/57807780/40bdfbd1-a00a-4766-aeec-26489f28d7f2)<br />
<br />
<br />
Read in data from CSV files and performed joins.<br />
![image](https://github.com/KotR9001/Healthcare_Analytics/assets/57807780/4f6be456-45da-4e2c-b717-414c7154b092)<br />
![image](https://github.com/KotR9001/Healthcare_Analytics/assets/57807780/b183d291-7534-40b0-ab5a-df9c76c2b82a)<br />
![image](https://github.com/KotR9001/Healthcare_Analytics/assets/57807780/e9fb7cc8-feb9-46c2-9068-d020522b90e8)<br />
<br />
<br />
Wrote joined data into a CSV file.<br />
![image](https://github.com/KotR9001/Healthcare_Analytics/assets/57807780/0db6fe02-9a57-4f5a-a841-0386c78f5d2d)<br />
<br />
Created a Linear Regression model.<br />
![image](https://github.com/KotR9001/Healthcare_Analytics/assets/57807780/81d2c317-d609-4bbf-9701-a0fdf4b247f7)<br />
<br />
Split the data into train & test sets.<br />
![image](https://github.com/KotR9001/Healthcare_Analytics/assets/57807780/18f50b71-0d9e-4168-843c-6d3ffbb4ec3b)<br />
<br />
Filled in missing values through interpolation.<br />
![image](https://github.com/KotR9001/Healthcare_Analytics/assets/57807780/1df5ee75-d310-409f-97a7-51bd0880b082)<br />
![image](https://github.com/KotR9001/Healthcare_Analytics/assets/57807780/8626d498-803b-410a-aa58-ec09a2e1ab53)<br />
<br />
Trained the model to the training data features and life expectancy columns.<br />
![image](https://github.com/KotR9001/Healthcare_Analytics/assets/57807780/77bf972a-4696-496d-a77f-af23992a39c4)<br />
<br />
Tested the model on the testing data features and life expectancy columns.<br />
![image](https://github.com/KotR9001/Healthcare_Analytics/assets/57807780/9c478174-2aea-424b-91de-52954a88ddff)<br />
<br />
Created a dataframe listing features and their respective coefficients.<br />
![image](https://github.com/KotR9001/Healthcare_Analytics/assets/57807780/7acf2a8a-b05c-4027-8417-4a08480907bd)<br />
<br />
Calculated the mean-squared error, R^2, and R^2 adjusted values, where the difference between the R^2 and R^2 adjusted shows the degree of model overfitting.<br />
![image](https://github.com/KotR9001/Healthcare_Analytics/assets/57807780/852535fa-859b-4e6e-ba60-ca890ee37a51)<br />
<br />
Calculated the descriptive statistics and merged with table with the features and coefficients to make an ANOVA table.<br />
Retained only records for statistically significant features and sorted by coefficient values.<br />
![image](https://github.com/KotR9001/Healthcare_Analytics/assets/57807780/53ba56a5-af23-4f59-a081-480db72480b0)<br />
<br />
Exported the ANOVA table results to a CSV file.<br />
![image](https://github.com/KotR9001/Healthcare_Analytics/assets/57807780/802123af-66c1-47c4-86c4-9951d494f29f)<br />
<br />
Repeated the steps for model creation through ANOVA table exporting for adult mortality, infant mortality, and under five deaths.<br />
<br />
<br />
Showed the ANOVA tables' results in Power BI, ordered by coefficient values.<br />
<br />
<b>Life Expectancy</b>
![image](https://github.com/KotR9001/Healthcare_Analytics/assets/57807780/90ebab85-db54-40de-8eac-92d5861f4efa)<br />
<br />
<b>Adult Mortality</b>
![image](https://github.com/KotR9001/Healthcare_Analytics/assets/57807780/90935af2-479a-4891-b9ad-cb172875311b)<br />
<br />
<b>Infant Deaths</b>
![image](https://github.com/KotR9001/Healthcare_Analytics/assets/57807780/b9143c1b-a598-417c-8111-7f3eab4086a3)<br />
<b>Under Five Deaths</b>
![image](https://github.com/KotR9001/Healthcare_Analytics/assets/57807780/fda4666a-6119-4179-b8e3-9f2ce68e65d9)<br />
<br />
<br />
<b>Conclusions</b>
1. Education is a great way to increase life expectancy and reduce adult mortality.<br />
2. Immunizations against various viruses/diseases improves life expectancy and reduces adult mortality only modestly, but have a relatively more pronounced effect on reducing infant & under five deaths.<br />
3. Calories from animal protein & fat tend to have negligible effects on life expectancy & mortality.<br />
4. BMI has a very pronounced correlation with life expectancy (positive) & mortality (negative). It's unclear why this is the case, so more research may be warranted.<br />
