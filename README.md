# retail-ecommerce_customer-voice-sales-and-behaviour-prediction

### **Scope:**
Contry wide e-commerce company data exploration for fast MVP prototyping with the goal of presenting a business case for the company and posible unfolding scenarios within 1 year horizon.

### **Preface:**
This is a project MVP (minimum viable product) for sales and consumer behavior analysis and follow-up. Featuring full automation of customer voice analysis using NLP (Natural Language Processing) and customer segmentation through unsupervised learning. For this purpose I have used the anonymized data of a retail e-commerce company similar to Ebay.

### **Documents:**
There is a PowerPoint that goes together with a 10 minute presentation in the links below. Together with an Entity-Relationship Diagram to explain the database model I used for this project. The data folder contains all the files (table extracts) to run the code.

### **Methodology:**
I have used Python 3.x in a Jupyter Notebook. Presented the MVP to an audience of 50+ people and recorded it on video in the links below. Asisting documents are the powerpoint presentation and the ERD diagram so that the viewer can follow the presentation along.
Part of the story telling and PowerPoint format are based on the decision to discover the ecommerce, project and results through the presentation bit by bit with no "spoilers".

### **Presentation:**
1. first part, you can skip to minute 2:40 https://youtu.be/hj6SyrlL_HU
2. second part, and Q/Afinale https://youtu.be/MdSmDZkaa7I

### **Small detail:**
The below gif included in the presentation is a breakdown of the revenue generated during the first 2 years of business at below post code level. So basically you are seeing in 35 seconds where are the customers of your company located and how much they bought since it started. Each litte colored pixel is a sub-postal code area with revenue scale in color. Black is no revenue scaling through red, orange, yellow then white which indicates most revenue relative across areas in the whole country. I needed to convert geolocation data to meters in order to adjust it to a real country map and aggregate the data into the corresponding sub-postcode area using revenue. The question being: do you know in which country is the e-commerce company operating? I thought it was a great opener for the presentation and I hope you like the effect.
![](result.gif)
