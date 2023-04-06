# Data-Visualization-Challenge

## Prepare the data.
* using the start code 

* import the data and use the method "loc" "len" "groupby" to clear the data

## Generate summary statistics.

### Create bar charts and pie charts.

* based on clear data using different methods: pandas and pyplot to generate bar chart

* using "value_counts" and creating list of female and male mice to create pie chart in pandas and pyplot

### Calculate quartiles, find outliers, and create a box plot.

*  Put treatments into a list for for loop (and later for plot labels) [Capomulin, Ramicane, Infubinol, Ceftamin]

* get the data of tumor volume, drug regimen, mouse id and reshape the form of the data

* Create empty list to fill with tumor vol data (for plotting)

* Locate the rows which contain mice on each drug and get the tumor volumes by loop and using the formula of quartiles to get quartile and outliers.

* using the method boxplot to create box plot

### Create a line plot and a scatter plot

* sort out mouse ID l509

* make sure what put on x_axis is timepoint , y_axis is tumor volume

* using the method "plt.plot" and "plt.scatter"

* Calculate correlation and regression using "correlation = st.pearsonr(x,y)" 
    "(slope, intercept, rvalue, pvalue, stderr) = linregress(x,y)" 
    "regress_values = x['Weight (g)'] * slope + intercept" 
    "line_eq = "y = " + str(round(slope,2)) + "x + " + str(round(intercept,2)) "

### Write down final analysis in the head of the file.
