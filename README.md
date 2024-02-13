### EX01 -- Creation of Employee, Weather dataset in WEKA Data Mining and Analysis Tool and perform Preprocessing
### DATE: 10.02.2024
### AIM: 
  To Create Employee, Weather dataset in WEKA Data Mining and Analysis Tool and perform preprocessing
### PROCEDURE: 
1) Open Start -> Programs -> Accessories -> Notepad
2) Type the following training data set with the help of Notepad for Employee Table.

```
--------------
Employee Data
---------------
@relation employee
@attribute name {x,y,z,a,b}
@attribute id numeric
@attribute salary {low,medium,high}
@attribute exp numeric
@attribute gender {male,female}
@attribute phone numeric
@data
x,121,low,2,male,278561
y,122,high,3,female,278562
z,123,medium,1,male,278563
a,124,low,5,female,278564
b,125,high,2,male,278565

--------------
Weather Data
---------------
@relation weather
@attribute outlook {sunny,rainy,overcast}
@attribute temparature numeric
@attribute humidity numeric
@attribute windy {true,false}
@attribute play {yes,no}
@data
sunny,65,85,false,no
overcast,82,90,true,no
sunny,89,86,false,yes
rainy,67,86,false,yes
rainy,60,80,false,yes
rainy,89,70,true,no
overcast,65,65,false,yes
sunny,71,95,true,no
sunny,63,70,false,yes
rainy,75,80,false,yes
```
3) After that the file is saved with .arff file format.
4) Minimize the arff file and then open Start -> Programs -> weka-3-4.
5) Click on weka-3-4, then Weka dialog box is displayed on the screen.
6) In that dialog box there are four modes, click on explorer.
7) Explorer shows many options. In that click on ‘open file’ and select the arff file
8) Click on edit button which shows employee table on weka.

### OUTPUT:
### Employee Table
<img width="274" alt="emp" src="https://github.com/Shavedha/WDM_EXP1/assets/93427376/8245e4b0-40b1-45cc-aac2-ca4782075c9b">

### Weather Table
<img width="320" alt="wthr" src="https://github.com/Shavedha/WDM_EXP1/assets/93427376/e7f812f7-0171-4d6f-9203-67e1dee7292e">


### PREPROCESSING
### Procedure:
#### 1) Add -> Pre-Processing Technique:
1) Start -> Programs -> Weka-3-4 -> Weka-3-4
2) Click on explorer.
3) Click on open file.
4) Select Weather.arff file and click on open.
5) Click on Choose button and select the Filters option.
6) In Filters, we have Supervised and Unsupervised data.
7) Click on Unsupervised data.
8) Select the attribute Add.
9) A new window is opened.
10) In that we enter attribute index, type, data format, nominal label values for Climate.
11) Click on OK.
12) Press the Apply button, then a new attribute is added to the Weather Table.
13) Save the file.
14) Click on the Edit button, it shows a new Weather Table on Weka.

### OUTPUT:
### Employee Table after adding attribute Address:
<img width="382" alt="emp add" src="https://github.com/Shavedha/WDM_EXP1/assets/93427376/41a32099-04db-4e72-b5a9-4a16e91d0abb">

### Weather Table after adding attribute Climate:
<img width="357" alt="wthr add" src="https://github.com/Shavedha/WDM_EXP1/assets/93427376/a45b9bcc-a3b5-4221-b027-25e3e7a24677">

### 2) Remove -> Pre-Processing Technique:

1) Start -> Programs -> Weka-3-4 -> Weka-3-4
2) Click on explorer.
3) Click on open file.
4) Select Weather.arff file and click on open.
5) Click on Choose button and select the Filters option.
6) In Filters, we have Supervised and Unsupervised data.
7) Click on Unsupervised data.
8) Select the attribute Remove.
9) Select the attributes windy, play to Remove.
10) Click Remove button and then Save.
11) Click on the Edit button, it shows a new Weather Table on Weka.

### OUTPUT:
### Employee Table after removing attribute Phone:
<img width="316" alt="emp remove" src="https://github.com/Shavedha/WDM_EXP1/assets/93427376/418b377d-f5d7-41ef-993e-ba050f9ec2cc">

### Weather Table after removing attribute Windy:
<img width="342" alt="wthr remove" src="https://github.com/Shavedha/WDM_EXP1/assets/93427376/6079291f-6084-4352-8380-761ecb2592cd">


### Normalize -> Pre-Processing Technique:

1) Start -> Programs -> Weka-3-4 -> Weka-3-4
2) Click on explorer.
3) Click on open file.
4) Select Weather.arff file and click on open.
5) Click on Choose button and select the Filters option.
6) In Filters, we have Supervised and Unsupervised data.
7) Click on Unsupervised data.
8) Select the attribute Normalize.
9) Select the attributes temparature, humidity to Normalize.
10) Click on Apply button and then Save.
11) Click on the Edit button, it shows a new Weather Table with normalized values on Weka.

### OUTPUT:
### Employee Table after Normalizing ID, exp:
<img width="337" alt="emp normalise" src="https://github.com/Shavedha/WDM_EXP1/assets/93427376/5635e108-7d9a-492d-b88b-c194d5d72181">

### Weather Table after Normalizing Temparature,Humidity:
<img width="375" alt="wthr normalize" src="https://github.com/Shavedha/WDM_EXP1/assets/93427376/2d00f79a-6be4-4c74-8c27-54cd3bb9c26f">

### RESULT: 
  Thus the program for generating employee and weather datasets has been developed, and preprocessing has been accomplished successfully.
