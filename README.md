### EX2 Generating Association Rules for transaction dataset using Apriori Algorithm
### DATE: 31-01-2026
### AIM: To generate associate rules for the transaction dataset using Apriori Algorithm.
### Description:
In data mining, association rule learning is a popular and well researched method for discovering interesting
relations between variables in large databases. It can be described as analyzing and presenting strong rules discovered
in databases using different measures of interestingness. In market basket analysis association rules are used and they
are also employed in many application areas including Web usage mining, intrusion detection and bioinformatics.
Creation of Buying Table:
### Procedure:
1) Open Start -> Programs -> Accessories -> Notepad
2) Type the following training data set with the help of Notepad for Buying Table.

```
@relation transaction
@attribute Tid {T100,T200,T300,T400,T500,T600,T700,T800,T900}
@attribute I1 {yes,no}
@attribute I2 {yes,no}
@attribute I3 {yes,no}
@attribute I4 {yes,no}
@attribute I5 {yes,no}
@data
T100,yes,yes,no,no,yes
T200,no,yes,no,yes,no
T300,no,yes,yes,no,no
T400,yes,yes,no,yes,no
T500,yes,no,yes,no,no
T600,no,yes,yes,no,no
T700,yes,no,yes,no,no
T800,yes,yes,yes,no,yes
T900,yes,yes,yes,no,no
```
3) After that the file is saved with .arff file format.
4) Minimize the arff file and then open Start -> Programs -> weka-3-4.
5) Click on weka-3-4, then Weka dialog box is displayed on the screen.
6) In that dialog box there are four modes, click on explorer.
7) Explorer shows many options. In that click on ‘open file’ and select the arff file
8) Click on edit button which shows buying table on weka.
### OUTPUT:
<img width="1228" height="736" alt="image" src="https://github.com/user-attachments/assets/76054c91-ba58-438c-baac-811ac5d88d41" />


### Procedure for Association Rules:
1) Open Start -> Programs -> Accessories -> Notepad
2) Open explorer.
3) Click on open file and select buying.arff
4) Select Associate option on the top of the Menu bar.
5) Select Choose button and then click on Apriori Algorithm.
6) Click on Start button and output will be displayed on the right side of the window.

### OUTPUT:
<img width="1919" height="1018" alt="image" src="https://github.com/user-attachments/assets/b64b5ea4-6f4f-450e-ba0d-c832799ae544" />


### RESULT: 
thus the code was errorless and runed successfully


