# belly_button_biodiversity

# Programming Languages
API

JavaScript

Python

Json

# Step 1: Develop an endpoint point using Flask (REQUIRED)

1. Edit the `app.py` file and use Flask to serve up both your web application (through the default or root endpoint)
2. Serve up the data in `samples.json` through an endpoint called `/samples`.  

## Step 2: Build your Web Application with Plotly (REQUIRED)

1. Use the D3 library to read in the `samples` endpoint that was created in step 1.

2. Create a horizontal bar chart with a dropdown menu to display the top 10 OTUs found in that individual.

* Use `sample_values` as the values for the bar chart.

* Use `otu_ids` as the labels for the bar chart.

* Use `otu_labels` as the hovertext for the chart.

  
3. Create a bubble chart that displays each sample.

* Use `otu_ids` for the x values.

* Use `sample_values` for the y values.

* Use `sample_values` for the marker size.

* Use `otu_ids` for the marker colors.

* Use `otu_labels` for the text values.



4. Display the sample metadata, i.e., an individual's demographic information.

5. Display each key-value pair from the metadata JSON object somewhere on the page.


6. Update all of the plots any time that a new sample is selected.

Additionally, you are welcome to create any layout that you would like for your dashboard. An example dashboard is shown below:



## Step 3: Incorporate the Gauge Chart (REQUIRED)

* Adapt the Gauge Chart from <https://plot.ly/javascript/gauge-charts/> to plot the weekly washing frequency of the individual.

* You will need to modify the example gauge code to account for values ranging from 0 through 9.

* Update the chart whenever a new sample is selected.

![image](https://user-images.githubusercontent.com/71161293/110718872-d4064880-81d9-11eb-9c0e-b027351c5b14.png)


Use otu_labels as the hovertext for the chart.
![image](https://user-images.githubusercontent.com/71161293/110718545-298e2580-81d9-11eb-8fdb-04e8654948ff.png)
