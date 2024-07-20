# CONTROL CHART
A Tableau control chart is a graph used to study how a process changes over time.  All processes have some variability.  That’s normal.  But large shifts or swings are cause for study and indicate something has changed about the way your process is behaving.  They are used to pinpoint sources of variation.


Data are plotted in time order. A control chart always has a central line for the average, an upper line for the upper control limit, and a lower line for the lower control limit. These lines are determined from historical data and typically are based on standard deviations from the average or median line in the center.  

TO CREATE

Create a line chart. 
1. Add a reference line, by right clicking on the axis or on the Analytics pane at the left, and set it to be a Line, Per Pane, and set the value to Average (or Median if desired). 
2. Right click on the axis again and add another reference line.  
3. Make this one a Distribution.  Set it to Standard Deviation.  Type in -3,3.  If that seems too wide, you can also choose either -1,1 or -2,2. 
4. Click ok and look for any outliers in your data.
