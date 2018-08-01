# Anonymous-Function-in-Python
## Vision of this code
### To implement Harmonic Mean using Lambda or Anonymous Function.  

---

Before going further please look at the mathematical equation of the **Harmonic Mean**. Please see :arrow_down:  
*n* is the number of terms, *a1* is the first term while *a2* is the second term

<a href="https://www.codecogs.com/eqnedit.php?latex=n/(1/a1&plus;1/a2)" target="_blank"><img src="https://latex.codecogs.com/gif.latex?n/(1/a1&plus;1/a2)" title="n/(1/a1+1/a2)" /></a>


---
### Some Description about the Lambda Function
Lambda operator or lambda function is used for creating small, one-time and anonymous function objects in Python. It returns an object which can be assigned to a variable. Please see the below screenshot. You can solve the equation having multiple variable using lambda like in this code harmonic mean is solved using lambda. To calulate harmonic mean we need number of total terms and value of each term. See how easy it is to solve using lambda function. You just need a single line to solve it :smiley: .

![screenshot from 2018-08-02 00-11-41](https://user-images.githubusercontent.com/35392729/43541730-bb9e1096-95e8-11e8-82b0-3af33f8adb1c.png)

### How to run the code
AI Sangam is providing the file with extenstion .ipynb. This code is run on jupyter notebook so you need to install jupyter notebook to run it. You can download the file in an directory and open such directory using terminal by providing the path for such. At this step please enter the following command
```
jupyter notebook
```
Your file will be opened in the jupyter notebook. You can see the file in the jupyter notebook. It is running file. You can run again and learn the things in steps.

Thanks for sparing some time to read this file.

### Alternative option to jupyter notebook
Wao :heavy_exclamation_mark:  
For some user who donot want to use the jupyter notebook, you can copy the code from below and paste it in a text file with the extention.py. Let it is named as file.py
```
#Anonymous function solving harmonic mean 
a = lambda n,a1,a2:n/(1/float(a1) + 1/float(a2))
# Harmonic Mean Function Object is assigned to variable a
#Real time result is returned by putting the value of parameters passed to harmonin mean equation as discussed above for 2 elements
a(2,4,9)
```
To run this file. Please run the following code
```
python file.py
```
