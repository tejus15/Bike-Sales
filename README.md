# Bike-Sales
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

This pivot table displays the average income of potential customers based on gender.

![image](https://github.com/user-attachments/assets/ad7dc82a-a301-422c-ad65-d6b266a9f476)



This pivot table gives the commute distance of various customers.

![image](https://github.com/user-attachments/assets/a89d72bd-f6ad-422b-b89d-4c70fed22e5d)



This pivot table gives the number of customers of various age brackets. 

![image](https://github.com/user-attachments/assets/80debfea-857f-4030-8d98-27d88633b749)

