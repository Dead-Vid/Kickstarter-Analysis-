# Kickstarter Analysis Challenge

## Overview of Project
----------------------------------------------------------
### Purpose:

- The goal of this project is to manipulate a kickstarter campaign data sheet so that Louise can compare her play to others. More specifically, Louise wants to see how other kickstarter campaigns fared in relation to their launch dates and their funding goals. With the given data, we will be able to determine which campaigns proved to be successful or failures.   

## Analysis and Challenges
----------------------------------------------------------
### Analysis of Outcomes Based on Launch Date

- looking at the outcomes based on launch date we can see two trends occurring. The first being campaigns launched in the early summer months (May and June) tend to be more successful than those launched in late fall/early winter months (November and December). The other trend we can see is that there seems to be more kickstarter campaigns launched in the middle of the year (April - August) as opposed to the start and ending of the regular calender year (September - March). 

### Analysis of Outcomes Based on Goals

- The chart and table we created to depict the outcomes based on goals shows Louise what campaigns were successful and what campaigns failed based off how much money was asked for. It appears that campaigns that required less money tended to be more successful than those asking for much more. If you look at the chart below. 

### Challenges and Difficulties Encountered

- When creating the "Outcomes Based on Goals" Chart, I found it difficult to understand the order the =COUNTIFS function criteria needed to be in. Through trial and error I was able to write a function that not only pulled the correct data from one sheet to another, but also learn what I was doing wrong and apply it to other data sheets. Using the hint given in the challenge outline, Microsoft's excel help page, and youtube tutorials, I was able to grasp the concepts needed to complete the challenge. The sources I used are listed below:

	1. https://youtu.be/CdfHm7YJfwo 
	2. https://support.microsoft.com/en-us/office/countifs-function-dda3dc6e-f74e-4aee-88bc-aa8c2a866842?ui=en-us&rs=en-us&ad=us 

This is the function I used: ![countifs_function](https://user-images.githubusercontent.com/80081906/131269362-577ed6d0-69ad-40bb-8c0b-3f989206c0c0.PNG)
![countifs_functionf](https://user-images.githubusercontent.com/80081906/131269407-d702660d-0016-430c-b454-42d29897115e.PNG)
![countifs_functionc](https://user-images.githubusercontent.com/80081906/131269427-82ebb0b6-b375-42ab-bb3c-94dd1940c877.PNG)



## Results
----------------------------------------------------------
- **What are two conclusions you can draw about the Outcomes based on Launch Date?**

	**1.** We know that Kickstarter campaigns launched in the summer time are more likely to succeed than those launched in the winter. Looking at the chart provided below; we can verify that in May, June, and July we can there were more attempted and more successful campaigns than during any other time of the year.
	
	![Theater_Outcomes_vs_Launch](https://user-images.githubusercontent.com/80081906/131268468-1f5d5605-f3f8-4708-925d-70dee5cbea10.png)

	**2.** We can assume that the best time to launch a Kickstarter Campaign is during the Summer months because of the data shown. More people take time off and spend more money during the Summer; this suggests that people are more likely to seek out campaigns or come across fundraisers. With that said, the Winter months appear the worst time to launch a Kickstarter campaign.  

- **What can you conclude about the Outcomes based on Goals?**

	**1.** We can conclude that the majority of successful campaigns had asking goals of approximately $10,000 and less.  The most successful campaigns had a goal range between **$1,000 and $5,000** show in the graph below:  
	![Outcomes_vs_Goals](https://user-images.githubusercontent.com/80081906/131269001-442049f4-9148-4706-9e2c-0dfad8625222.png)
	Should Louise want to have more Kickstarter campaigns in the future, it is suggested that she have a goal range around $3,000-$4,000 and launched in mid to late May.


- **What are some limitations of this dataset?**
	
	-  Although we have been able to determine the ideal goal and launch time for a kickstarter campaign, this data is limited to theater and plays. 
	- The dataset also doesnt give us what times the donations were given per campaign. 
		- That would allow us to see what times during the day would be best to advertise for the campaign.  
	- This data set is also limited to countires only, there isn't any specific data showing states or regions. 
	- There is no data regarding the demographic of the people donating to any campaign. 
	
- **What are some other possible tables and/or graphs that we could create?**
	
	- This kickstarter can be used to make a line chart depicting pledged amount vs goal amounts.
	- A chart can be made comparing the goals and length of each campaign. 
