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

![image](https://github.com/user-attachments/assets/14783d10-6dce-4ad3-b856-948485abd2bb)


![image](https://github.com/user-attachments/assets/7194928c-863e-4f38-b09f-4f67c87681df)


![image](https://github.com/user-attachments/assets/ae83c2e2-c15b-4c07-a7c4-f5969964f8fa)


![image](https://github.com/user-attachments/assets/4e170ce2-a312-4347-9896-ccd1fb0bc372)

