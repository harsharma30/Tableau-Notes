# APPLYING FILTER TO PLOT
EXTRACT FILTER

Extracts are saved subsets of data that you can use to improve performance or to take advantage of Tableau functionality not available or supported in your original data. When you create an extract of your data, you can reduce the total amount of data by using filters and configuring other limits. After you create an extract, you can refresh it with data from the original data. When refreshing the data, you have the option to either do a full refresh, which replaces all of the contents in the extract, or you can do an incremental refresh, which only adds rows that are new since the previous refresh.

Extracts are advantageous for several reasons:
- Supports large data sets: You can create extracts that contain billions of rows of data.
- Help improve performance: When you interact with views that use extract data sources, you generally experience better performance than when interacting with views based on connections to the original data.
- Support additional functionality: Extracts allow you to take advantage of Tableau functionality that's not available or supported by the original data, such as the ability to compute Count Distinct.

**QUICK FILTER**

In Tableau, many filter types are quickly available using the right-click option on the measure and dimension. These filters have enough functionality to solve most of the everyday filtering needs. These filters are known as Quick filters.
