# belly-button-challenge

## BACKGROUND

In this assignment, you will build an interactive dashboard to explore the Belly Button Biodiversity dataset Links to an external site., which catalogs the microbes that colonize human navels.

The dataset reveals that a small handful of microbial species (also called operational taxonomic units, or OTUs, in the study) were present in more than 70% of people, while the rest were relatively rare.

## OBJECTIVES


Complete the following steps:

1. Use the D3 library to read in samples.json from the URL https://2u-data-curriculum-team.s3.amazonaws.com/dataviz-classroom/v1.1/14-Interactive-Web-Visualizations/02-Homework/samples.json.

2. Create a horizontal bar chart with a dropdown menu to display the top 10 OTUs found in that individual.

---Use sample_values as the values for the bar chart.

---Use otu_ids as the labels for the bar chart.

---Use otu_labels as the hovertext for the chart.


![Alt text](https://static.bc-edx.com/data/dl-1-2/m14/lms/img/hw01.jpg)


3. Create a bubble chart that displays each sample.

---Use otu_ids for the x values.

---Use sample_values for the y values.

---Use sample_values for the marker size.

---Use otu_ids for the marker colors.

---Use otu_labels for the text values.


![Alt text](https://static.bc-edx.com/data/dl-1-2/m14/lms/img/bubble_chart.jpg)


4. Display the sample metadata, i.e., an individual's demographic information.

5. Display each key-value pair from the metadata JSON object somewhere on the page.


![Alt text](https://static.bc-edx.com/data/dl-1-2/m14/lms/img/hw03.jpg)

6. Update all the plots when a new sample is selected. Additionally, you are welcome to create any layout that you would like for your dashboard. An example dashboard is shown as follows:


![Alt text](https://static.bc-edx.com/data/dl-1-2/m14/lms/img/hw02.jpg)


## RESULTS

![Alt text](result/bellyButtonBiodiversityDashboard.png)

https://mtanguin.github.io/


Sources:

https://courses.bootcampspot.com/courses/2799/assignments/42892?module_item_id=803534
https://2u-data-curriculum-team.s3.amazonaws.com/dataviz-classroom/v1.1/14-Interactive-Web-Visualizations/02-Homework/samples.json
https://maxcdn.bootstrapcdn.com/bootstrap/3.3.7/css/bootstrap.min.css
https://d3js.org/d3.v5.min.js
https://cdn.plot.ly/plotly-latest.min.js
