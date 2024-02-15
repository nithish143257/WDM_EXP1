### EX1 Creation of Employee, Weather dataset in WEKA Data Mining and Analysis Tool and perform Preprocessing
### DATE: 15.2.24
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
x,101,low,2,male,250311
y,102,high,3,female,251665
z,103,medium,1,male,240238
a,104,low,5,female,200200
b,105,high,2,male,240240

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
sunny,85.0,85.0,false,no
overcast,80.0,90.0,true,no
sunny,83.0,86.0,false,yes
rainy,70.0,86.0,false,yes
rainy,68.0,80.0,false,yes
rainy,65.0,70.0,true,no
overcast,64.0,65.0,false,yes
sunny,72.0,95.0,true,no
sunny,69.0,70.0,false,yes
rainy,75.0,80.0,false,yes
```
3) After that the file is saved with .arff file format.
4) Minimize the arff file and then open Start -> Programs -> weka-3-4.
5) Click on weka-3-4, then Weka dialog box is displayed on the screen.
6) In that dialog box there are four modes, click on explorer.
7) Explorer shows many options. In that click on ‘open file’ and select the arff file
8) Click on edit button which shows employee table on weka.

### OUTPUT:
Training Data Set -> Employee Table
![image](https://github.com/nithish143257/WDM_EXP1/assets/113762839/2981c52b-fdae-4729-8c78-688ebd5a5d57)

Training Data Set-> Weather Table
![image](https://github.com/nithish143257/WDM_EXP1/assets/113762839/846212c7-8461-4c73-8614-f919c5ffa241)

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

Employee Table after adding new attribute ADDRESS:
![image](https://github.com/nithish143257/WDM_EXP1/assets/113762839/d34636d3-e509-4b7e-add0-668223f5b945)

Weather Table after adding new attribute CLIMATE:
![image](https://github.com/nithish143257/WDM_EXP1/assets/113762839/cfbb8b88-fdb0-4a99-bfcc-56e0dbd51dcd)


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
Employee Table after removing attributes SALARY, GENDER:
![image](https://github.com/nithish143257/WDM_EXP1/assets/113762839/94e0e00a-03e0-4b12-9198-9d548651e1bd)

Weather Table after removing attributes WINDY, PLAY:
![image](https://github.com/nithish143257/WDM_EXP1/assets/113762839/5cb55dff-04dc-4cf2-bbe7-a756d0b1d039)

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
Employee Table after Normalizing ID, EXP, PHONE:
![image](https://github.com/nithish143257/WDM_EXP1/assets/113762839/883a8d05-a9a8-4e63-9ed3-07655752c5ff)

Weather Table after Normalizing TEMPARATURE, HUMIDITY:
![image](https://github.com/nithish143257/WDM_EXP1/assets/113762839/bbea2b90-34a0-4aa3-82cf-6793286e9ab0)


### RESULT: 
  Thus the program for generating employee and weather datasets has been developed, and preprocessing has been accomplished successfully.
