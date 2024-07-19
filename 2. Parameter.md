# INTRODUCTION TO PARAMETER

A parameter is a workbook variable such as a number, date, or string that can replace a constant value in a calculation, filter, or reference line.

You can even create a dynamic parameter that’s set to automatically refresh its current value (to the result of a single-value, view-independent calculation),
list of values (based on a data source column), or range of values. This will happen each time the workbook is opened and Tableau connects to the data source
referenced by the parameter, or whenever you select Refresh from the data source’s context menu.

Parameters are useful when you want to add interactivity and flexibility to a report, or to experiment with what-if scenarios. Suppose you are unsure which 
fields to include in your view or which layout would work best for your viewers. You can incorporate parameters into your view to let viewers choose how they
want to look at the data.

When you use parameters, you need to tie them to the view in some way:
- You can use parameters in calculations and calculated fields that are used in the view.
- You can display the parameter control in the view for users to select parameters.

