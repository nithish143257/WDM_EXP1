### EX1 Creation of Employee, Weather dataset in WEKA Data Mining and Analysis Tool and perform Preprocessing
### DATE: 11.2.24
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

<img width="280" alt="Screenshot 2024-02-10 084810" src="https://github.com/Nagadurg/WDM_EXP1/assets/94185707/bb26e847-f77c-4627-95e4-64786e5bfb42">

Training Data Set-> Weather Table

<img width="284" alt="Screenshot 2024-02-10 085221" src="https://github.com/Nagadurg/WDM_EXP1/assets/94185707/40f67cd7-7452-404d-b78d-1bbe67320b32">

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

<img width="325" alt="Screenshot 2024-02-10 092027" src="https://github.com/Nagadurg/WDM_EXP1/assets/94185707/728a86d9-8cf8-4538-b040-610c085728b6">

Weather Table after adding new attribute CLIMATE:


<img width="334" alt="wd 1(c) add" src="https://github.com/Nagadurg/WDM_EXP1/assets/94185707/da9e8c12-5ccb-4a37-b1a6-d095714c7a4a">


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


<img width="253" alt="Screenshot 2024-02-10 092224" src="https://github.com/Nagadurg/WDM_EXP1/assets/94185707/2926a58d-218e-4fa2-a736-49e120f6b27c">

Weather Table after removing attributes WINDY, PLAY:


<img width="212" alt="wd 1(c) remove" src="https://github.com/Nagadurg/WDM_EXP1/assets/94185707/c8319007-4424-4f54-8839-7f6019cab037">

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

<img width="310" alt="Screenshot 2024-02-10 092350" src="https://github.com/Nagadurg/WDM_EXP1/assets/94185707/2ca75794-e116-4fc0-822a-2b54ddfea301">

Weather Table after Normalizing TEMPARATURE, HUMIDITY:


<img width="308" alt="wd 1(c) normalize" src="https://github.com/Nagadurg/WDM_EXP1/assets/94185707/286209ed-e3d2-4eb6-b272-b25a3dc85468">

### RESULT: 
  Thus the program for generating employee and weather datasets has been developed, and preprocessing has been accomplished successfully.
