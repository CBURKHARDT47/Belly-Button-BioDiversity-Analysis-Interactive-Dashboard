# Module 14 Plotly Challenge: Belly Button Biodiversity Dashboard

## Background
In this assignment, you will build an interactive dashboard to explore the Belly Button Biodiversity datasset which can be found here: http://robdunnlab.com/projects/belly-button-biodiversity/results-and-data/ which catalogs the microbes that colonize human navels. The dataset reveals that a small handful of microbial species (also called operational taxonomic units, or OTUs, in the study) were present in more than 70% of people, while the rest were relatively rare. Use console.log inside of your JavaScript code to see what your data looks like at each step. Refer to the Plotly.js documentationLinks to an external site. when building the plots.

## Tools
These are the tools, techniques, and resources used in this project. 
* Plotly is used in combination with D3 and Javascript to generate the plots
* HTML is used for the framework of the page
* Github Pages is used to host the data and final application
* The data is stored in JSON format and imported in

About the Data
Hulcr, J. et al.(2012) A Jungle in There: Bacteria in Belly Buttons are Highly Diverse, but Predictable. Retrieved from: http://robdunnlab.com/projects/belly-button-biodiversity/results-and-data/

## Before You Begin
Inside your local git repository, copy the files from in the StarterCode folder contained within the Module 14 Challenge zip file. i.e. index.html, samples.json, and the static folder. NOTE: You will not be required to access the samples.json file locally, but it is provided for reference.

## Instructions
Complete the following steps:
1. Use the D3 library to read in samples.json from the URL https://2u-data-curriculum-team.s3.amazonaws.com/dataviz-classroom/v1.1/14-Interactive-Web-Visualizations/02-Homework/samples.json.
2.  Create a horizontal bar chart with a dropdown menu to display the top 10 OTUs found in that individual.
  * Use sample_values as the values for the bar chart.
  * Use otu_ids as the labels for the bar chart.
  * Use otu_labels as the hovertext for the chart.
 
  ![hw01](https://github.com/CBURKHARDT47/belly-button-challenge/assets/128064003/4dff146d-a863-43fd-8a3f-c3fea0017b14)

  3. Create a bubble chart that displays each sample.
  * Use otu_ids for the x values.
  * Use sample_values for the y values.
  * Use sample_values for the marker size.
  * Use otu_ids for the marker colors.
  * Use otu_labels for the text values.

<img width="1416" alt="bubble_chart" src="https://github.com/CBURKHARDT47/belly-button-challenge/assets/128064003/bb0aaf08-bad8-4872-8365-e0d8c8ac9cee">

4. Display the sample metadata, i.e., an individual's demographic information.
5. Display each key-value pair from the metadata JSON object somewhere on the page.

![image](https://github.com/CBURKHARDT47/belly-button-challenge/assets/128064003/fdb0ee35-0d30-44e5-b9cd-da4422f5e5a0)

6. Update all the plots when a new sample is selected. Additionally, you are welcome to create any layout that you would like for your dashboard. An example dashboard is shown as follows:
![image](https://github.com/CBURKHARDT47/belly-button-challenge/assets/128064003/c8817938-74cd-4ec0-8e4c-90fb2c36367d)

7. Deploy your app to a free static page hosting service, such as GitHub Pages. Submit the links to your deployment and your GitHub repo. Ensure that your repository has regular commits and a thorough README.md file


References
Hulcr, J. et al. (2012) A Jungle in There: Bacteria in Belly Buttons are Highly Diverse, but Predictable. Retrieved from: http://robdunnlab.com/projects/belly-button-biodiversity/results-and-data/Links to an external site.
