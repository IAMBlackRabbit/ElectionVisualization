# ElectionVisualization
Commandline Java program that prints a map of the 48 contiguous states' outcomes during presidential elections through 2012

As it is, to use either program the folder "purple" and the StdDraw.java file must be in the same directory as the program file.

Command (after compilation):
```
java RedBlue <region> <year> 
java Pruple <region> <year>
```
Region can be a `state`, the `USA`, or `USA-county` (to ensure accuracy, the "purple" folder can be checked to see how the file is named)
Year can be any presidential election year up through 2012.

RedBlue will show which state or county had predominately Democrat or Republican votes where Purple will show the true mixture of all the votes. This visualization allows us to see just how close many places are in terms of votes for one side vs the other.  

![Output of Purple.java](https://github.com/IAMBlackRabbit/ElectionVisualization/blob/master/purpleUSACounty2012.JPG "Purple.java")
