# This Repo Is About Linear Regression With One feature

You will need python2<br />

script is main.ipyndb<br />

This repo combines two separate examples. The math along with the code<br />

The math example:
[How to calculate linear regression using least square method](https://www.youtube.com/watch?v=JvS2triCgOY&t=343s "How to calculate linear regression using least square method")

Code example:
[How To Implement Simple Linear Regression From Scratch With Python](http://machinelearningmastery.com/implement-simple-linear-regression-scratch-python/ "How To Implement Simple Linear Regression From Scratch With Python")<br />



<br />
We want to find the regression line. The line that BEST fits through all our points.
![Alt text](rmimg/img4.jpg?raw=true "Title")<br />

To find the BEST fit line we must minimize our actual data from our estimated data.
![Alt text](rmimg/img5.jpg?raw=true "Title")<br />



- - - -
The data x,y
```python
//values = [[1,2],[2,4],[3,5],[4,4],[5,5]]
```<br />
![Alt text](rmimg/img1.jpg?raw=true "Title")<br />
<br />

Lets plot the data for visualization(actual plotting is not needed in the code at this point).
![Alt text](rmimg/img2.jpg?raw=true "Title")<br />
what we want to find is the mean of x and the mean of y.
We will write a function for that. 
```python
//def mean(values):
    return sum(values) / float(len(values))     
```
<br />
Now the point at that x and y converge.<br />
![Alt text](rmimg/img3.jpg?raw=true "Title")