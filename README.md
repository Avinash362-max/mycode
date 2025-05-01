---------------------------------------------------------------------------------------------------------------------------------------------
** Soil Pollution and Associated Health Impacts
---------------------------------------------------------------------------------------------------------------------------------------------
Here I got this dataset at KAGGLE dataset platform, in Excel format. This dataset contains 3000 synthetic records simulating real-world scenarios of soil pollution and related diseases. It captures environmental, agricultural, and demographic variables to analyse correlations between soil contamination and human health outcomes. 
Then I import this dataset in SQL Server Management Studio for cleaning and checking purpose. Now let’s start Analysis Process. At first I give a name for dataset as SOIL
Soil pollution refers to the contamination of soil with anomalous concentrations of toxic substances.

Let’s see what exact in dataset.

![4](https://github.com/user-attachments/assets/f395b88b-a29e-4228-944b-f4af0b39510d)
Now check any null value’s column by column…

![1](https://github.com/user-attachments/assets/9c9babb0-c3f1-49fb-9ccb-07c013008c87)
Check any duplicate value…

![2](https://github.com/user-attachments/assets/9f65d3fc-6968-4fad-b3c8-827cd688e867)

  
It has been seeing that some column has long decimal numbers...
Make it Round

 ![3](https://github.com/user-attachments/assets/b908f349-d51f-4c5e-b27f-30d717d92188)

Arrange all records in ascending order by reporting_date 

![4](https://github.com/user-attachments/assets/d1d3031c-c62f-46e5-aa3e-5a0552964e37)

 
Then I import this cleaning and meaningful dataset in POWER BI. Along with BI toll, I have created two meaningful DASHBOARDs. First one is about findings as below…
 
![11](https://github.com/user-attachments/assets/4243c1ce-fd3e-45c2-af5f-6301bd86b8ec)

And second one is about final conclusion as below…

 ![22](https://github.com/user-attachments/assets/e5ac06f7-80eb-40fa-899e-e1f8a3a9137b)

And at last my final conclusion is that…

•	We can see that, every county has almost same range of cases.
•	Every pollutant type has almost same range of cases.
•	Also all diseases has almost same range of cases.
•	Severity is 50-50 % and male female ration also 50-50%
•	Mitigation measure also in same range.
•	So it’s necessary to take some action, some care and some changes in farming and soil management as below..

Responsible Waste Management

	Reduce, Reuse, Recycle  
		Minimize waste and actively    participate in recycling and reuse programs.
	Proper Disposal
		Ensure hazardous waste, including industrial and medical waste, is handled and disposed of correctly to prevent leaching into the soil. 
Sustainable Agricultural Practices
	Organic Farming
		Embrace organic farming practices, which minimize the use of synthetic fertilizers and pesticides, and instead utilize natural methods like compost and crop rotation	

	Crop Rotation
		Rotate crops to improve soil health, reduce pest and disease pressure, and minimize the need for chemical interventions
	Soil Conservation
		Implement soil conservation techniques like terracing, contour plowing, and windbreaks to prevent erosion and protect topsoil. 
Minimizing Chemical Usage
	Reduce Chemical Fertilizers and Pesticides
		Minimize the use of synthetic fertilizers and pesticides, as they can contaminate the soil and water. 
	Use Natural Alternatives	
		Instead of chemical fertilizers and pesticides, utilize organic fertilizers like compost and natural pest control methods. 
Proper Waste Management:
	Dispose of unused chemicals properly and avoid allowing them to enter the soil or water. 
 
Industrial and Urban Planning
	Implement robust waste management systems in industries and urban areas to prevent pollutants from entering the soil. 


