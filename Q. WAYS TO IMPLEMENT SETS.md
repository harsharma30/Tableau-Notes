# WAYS TO IMPLEMENT SETS

Create a dynamic set
The members of a dynamic set change when the underlying data changes. Dynamic sets can only be based on a single dimension.

To create a dynamic set:

- In the Data pane, right-click a dimension and select Create > Set.
- In the Create Set dialog box, configure your set. You can configure your set using the following tabs:
General: Use the General tab to select one or more values that will be considered when computing the set

                         Condition: Use the Condition tab to define rules that determine which members to include in the set.

                         Top: Use the Top tab to define limits on what members to include in the set.

Create a fixed set
The members of a fixed set do not change, even if the underlying data changes. A fixed set can be based on a single dimension or multiple dimensions.

To create a fixed set:

1. In the visualization, select one or more marks (or headers) in the view.
2. Right-click the mark(s) and select Create Set.
3. n the Create Set dialog box, type a name for the set.
4. Optionally complete any of the following:
- By default, the set includes the members listed in the dialog box. You can select the option to Exclude these members instead. When you exclude, the set will include all of the members you didn't select.
- Remove any dimensions that you don't want to be considered by clicking the red "x" icon that appears when you hover over a column heading .
- Remove any specific rows that you don't want to include in the set by clicking the red "x" icon that appears when you hover over the row .
- If the marks you selected represent multiple dimensions, each member of the set will be a combination of those dimensions. You can specify the character that separates the dimension values. To do so, for Separate members by, enter a character of your choice.
- Select Add to Filters shelf to automatically move the set to the Filters shelf once it is created.
        5.  When finished, click OK.
             The new set is added to the bottom of the Data pane, under the Sets section. 


 

Add or remove data points from sets
If you created a set using specific data points, you can add more data to or subtract data from the set.

To add or remove data points from a set:

- In the visualization, select the data points you want to add or remove.
- In the tooltip that appears, click the Sets drop-down menu icon, and then select Add to [set name] or Remove from [set name] to add or remove data from a particular set.
After you create a set, it displays at the bottom of the Data pane in the Sets section. You can drag it into the viz like any other field.

