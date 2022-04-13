<!-- .slide: data-background="./Images/header.svg" data-background-repeat="none" data-background-size="40% 40%" data-background-position="center 10%" class="header" -->

# Required project log information and map elements. 

Assigments will be submitted to blackboard via a detailed project log and URL to your web map. In addition to assignment specific requirements, each submission expected to contain the below elements for their log and their map.  Additionally the instructor will be evaluating map functionality and that the student demonstrates an understanding of the content. 

**Required Project Log Content**

1. Project Objectives
      - Assignments require students use a specific visualization method, but is not prescriptive in what is being visualized.  Students are expected to describe what they are visualizing in their project log and why.
      - Example: "This project uses ArcGIS online to visually compare the City of Chicago's Hardship Index to the City of Chicago's Covid-19 Vulnerability Index". 
      - Describe why you're doing it. "For policy makers to do x" or "For community members to do x" - It may be the same data, but these two stakeholder groups will need very different visualizations!  
      - "Playing around" or "I was curious if..." is perfectly acceptable and also extremely important- but in fancy talk that would be "an exploratory comparison of x & y". Again, this is a very important step in spatial analysis but results in a very different visualization than for an external stakeholder group.  

2. Data
      - This course is focused on visualization methods. Students are encouraged to use data from other courses/jobs/internships, however prepared data will be available for students to complete assignments. While grading will not be focused on data preparation and cleaning, students are expected to adddress data preparation and sources in their project log. 
      - Include what dataset, and where & when data was accessed (e.g. Chicago Supermarkets.csv, UPP465 Course Page, Accessed June 15, 2022 (with link to page & dataset). Ideally note original source as well). 
      - Geography and Temporal Information of data (e.g. 1995 Chicago Heat Death Locations; US Census Tract Demographic information 5year Est 2014-2019) 
      - Any data cleaning or manipulation conducted. Describe what was done and what tools where used to complete cleaning (e.g. Excel, created new attribute column titled "Minority Population" by subtracting column "White, non-Hispanic" from "Total Population")  
      - Someone should be able to follow these instructions and reproduce your data from the original dataset.  
      - Not required but strongly recommended: A good practice is to save an original, complete untouched copy of the data in your project folder. In your project log, describe where this original data is saved & where the data you're editing is saved so you can access it later.  

3. Detail the visualization method
      - I'm telling you what methods to use, so I know what methods you're going to be using! This section is mostly for future you. I often reference old project logs to remember how I did something. 
      - Required: list what tool you're using (e.g. ArcGIS Online Web Map Builder Classic), and any additional templates/tools (Storybuilder Cascade Template)
      - Strongly Recommended: Note and/or take screenshots of the processes and steps you're using. 
      - There is no singular right way to do this, and what you include/detail will depend on what the future use of the log will be: 
            - An extremely detailed step-by-step process can be useful if you're new or plan to share the log with someone so they can use the same method. 
            - A slightly less detailed section that details critical processes/settings/decisions can be useful if you're planning to publish the results of an analysis. 
            - A relatively sparse log is useful when you're familiar with the process, but need to note the settings/choices/tools used to reference in the future. I promise you, you will forget what you did. 
       - When using a tool like AGOL, I often like to take screenshots of settings I choose. For example, when you make a choropleth map - take a screen shot of the option bar where you select the number of classes, classification method, and ranges for data.  
       - When writing code, I like to copy and paste snippets of the code so I don't need to look it up again.
       - Strongly Recommended: Describe where you struggled and what you did to overcome it/instead of it.  Maybe in the future you'll figure out a way to do it as you initially wanted, or you'll come across the issue again and wish you remembered what you did before, or in the future you might want an answer to "Why the f- did I do that?" 

4. The final product
      - All of your assignments/projects will have a weblink.  Include the URL to your web map.
      - Include a screenshot of the final map. This is for you incase AGOL/your computer/the world crashes. 
      - Recommended: Screenshots of important features. This is for future you. Programs can change and your settings might break, it's good to remember what it did at one point and to identify what needs to be updated.  


**Required Map Elements**
Each homework assignment/project will contain at least one map. In addition to the specific requirements detailed on the rubric, all of them are required to include: 
1. Meaningful Title
      - Map title should decribe what is being visualized and generally include the topic, geography, and dates. Do not use map titles such as "UPP 465 HW 1"  
2. Clear, useful pop-ups
      - AGOL automatically creates pop-ups including every attribute as named in your original data.  This can result in a difficult to read pop-up. For example, what does "NOHSD" mean? While useful for the data set, it will mean nothing to most users. Change to "% Population with No High School Diploma"
      -Here's where things can get tricky. Often times datasets calculate fields such as % Population with No High School Diploma as "Percent of population over age 25 with No High School Diploma" - it's silly to include children in the estimate, but what are the implications of choosing ages over 25 instead of 18? Again, we are not focused on the data part in this course, but a well detailed project log is extremely helpful in this regard. If you're unfamiliar with a dataset, it can be easy to overlook these nuances which can affect your analysis/visualization. (though in a good analysis you would spend a lot of time reading how these attributes were calculated) If you become aware of it in the future, or someone asks you about it, you can reference your log - go back to the original dataset, and investigate. 
The applications will be scored on the inclusion of the above criteria, plus:
3. Well-organized data
      - If you're comparing supermarket locations to neighborhood poverty rates, make sure the supermarket layer is layered on top of the neighborhood layer. 
4. Understandable legend
      - Similar to pop-ups, do not leave the default labels. Make sure they are meaninful to the reader.  
5. Simple, purposeful cartography
      - Rule of thumb: less is more. It can be a lot of fun and extremely tempting to overload your map with data and features, but stick showing things that are critical to displaying the visual to your intended audience. No single map, even fancy interactive ones, can show everything. 
6. Descriptive Text
      - While your map should be mostly self-explanatory from the title, legend, and pop-ups alone, descriptive text is another critical element to a good map.  
            - For AGOL assignments: This will go on the map overview page. 
            - For Leaflet assignments: this will go on the webpage. 
      - It is perfectly acceptable to mostly copy and paste this text from your project log. Just make sure it is modified to make sense to the map user.  
7. Credits/source information
      - Cite your sources!!
            - For AGOL assignments: This will go on the map overview page. 
            - For Leaflet assignments: this will go on the webpage.
      - If using course data, on the public facing page cite the original source (e.g. City of Chicago Data Portal)