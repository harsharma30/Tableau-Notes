# JITTER POINTS
Jitter is a random value (or for our purposes pseudo-random) that is assigned to the dots to separate them so that they aren't plotted directly on top of each other. Tableau doesn't offer a check box, a built-in function, or a parameter to apply jitter, and there is no Tableau function to generate a random number.

You may want to spread the dots in your distribution when they are packed together to allow for easy reading of the dots that overlap. Using the jitter plot technique in this way allows you to separate marks or dots into different columns.

 When you’re working with geographic data, it is not advisable to use the jitter plot technique when the exact location of a mark is important to the analysis. If, for example, your data set is measuring when and where gas emissions were detected by a sensor, a jitter plot technique would move overlapping marks to a new point (i.e. the latitude and longitude).
