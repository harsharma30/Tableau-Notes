# ADD CALCULATED FIELDS

Sometimes your data source does not contain a field (or column) that you need for your analysis. For example, your data source might contain fields with values for Sales and Profit, but not for Profit Ratio. If this is the case, you can create a calculated field for Profit Ratio using data from the Sales and Profit fields.

**Step 1: Create the calculated field**

In a worksheet in Tableau, select Analysis > Create Calculated Field.

In the Calculation Editor that opens, give the calculated field a name.

In this example, the calculated field is called Profit Ratio.

**Step 2: Enter a formula**

In the Calculation Editor, enter a formula.

This example uses the following formula:

SUM([Profit])/SUM([Sales])

Formulas use a combination of functions, fields, and operators. 

When finished, click OK.

The new calculated field is added to the Data pane. If the new field computes quantitative data, it is added to Measures. If it computes qualitative data, it is added to Dimensions.

You are now ready to use the calculated field in the view.

