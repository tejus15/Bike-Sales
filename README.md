![image](https://github.com/user-attachments/assets/0ca11238-2072-4796-8ce8-46950e983862)# Bike-Sales
Created dashboard after cleaning Bike Sales data in excel. 

# Dataset

The Original Dataset has the following columns:
ID	
Marital Status	
Gender	
Income	
Children	
Education	
Occupation	
Home Owner	
Cars	
Commute Distance	
Region	
Age	
Purchased Bike

This data underwent pre-processing.
I removed all the duplicate entries in the data. 
I replaced all the values 'M' and 'F' with 'Male' and 'Female' to avoid confusion. Similarly, I replaced 'M' and 'S' in Marital Status with 'Married' and 'Single' to avoid confusion. 
Changed the type of Income from General to Currency. Removed decimal places for simplicity. 
In Commute distance. changed '10+ Miles' to 'More than 10 Miles'. This helps us in sorting the commute distances accurately. 
In the age column, I have got a lot of different values. So I split the ages into 3 categories: Adolescent, Middle age, Old
If age < 31 - Adolescent
If 55 < Age < 30 - Middle age
If age > 55 - Old

I created a new column, 'Age Bracket' which stores these 3 categories. 

After cleaning the data, our modified dataset (Working sheet) contains the following columns:

ID	
Marital Status	
Gender	
Income	
Children	
Education	
Occupation	
Home Owner	
Cars	
Commute Distance	
Region	
Age
Age Bracket	
Purchased Bike

# Pivot Tables

I used the pre-processed data in Working sheet to create pivot tables. These pivot tables can be seen below

Average of Income	Column Labels		
Row Labels	No	Yes	Grand Total
Female	 74,000 	 58,000 	 66,000 
Male	 95,000 	 82,500 	 88,750 
Grand Total	 83,333 	 68,889 	 76,111 
![image](https://github.com/user-attachments/assets/373a1c43-338c-45d7-b4cf-ef1a890200f9)


Count of Purchased Bike	Column Labels		
Row Labels	No	Yes	Grand Total
0-1 Miles	6	4	10
1-2 Miles		1	1
2-5 Miles		1	1
5-10 Miles	1	3	4
More than 10 Miles	2		2
Grand Total	9	9	18
![image](https://github.com/user-attachments/assets/6511cb46-2d0a-4078-91cb-ca9b3f321075)

Count of Purchased Bike	Column Labels		
Row Labels	No	Yes	Grand Total
Middle Aged	6	7	13
Old	3	2	5
Grand Total	9	9	18
![image](https://github.com/user-attachments/assets/5cfc69f6-6c51-4764-9361-83aac5da4f26)

Purchased Bike	(All)					
						
Count of Purchased Bike	Column Labels					
Row Labels	0	1	2	3	4	Grand Total
0-1 Miles	3	1	2	2	2	10
1-2 Miles		1				1
2-5 Miles			1			1
5-10 Miles				3	1	4
More than 10 Miles			1		1	2
Grand Total	3	2	4	5	4	18
![image](https://github.com/user-attachments/assets/50b6ca53-a1de-4cfc-9fc1-998ab9e7d482)

