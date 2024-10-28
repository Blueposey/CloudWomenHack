**Project Overview**:
   - A brief summary of the project, its objectives, and the problem it aims to solve.

The Nourish Network is a simple application that assists organizations tackling food waste such as food banks and mutual aid organizations by using AI to connect them with areas of food surplus on demand. Our idea was born out of the desire to make an impact on the 120 billion pounds of food The United States discards — every year. At the same time nearly 35 million people across America — including 10 million children — suffer from food insecurity.
Our project will not handle to logistics of transportation, consumer outreach, or public data disclosure, our proposed goal with the Nourish Network is to streamline connections between organizatitons that handle food excess with food retailers, farmers, and wholesalers. 

**Detailed Objectives**:
   - Specific goals of the project, such as predicting food surplus, optimizing logistics, and identifying areas of food insecurity.

Existing apps which match doners and food banks focus on reducing food waste in real time. Any facility with surplus tries to contact the food bank, and donate the food as possible. 
This doner initiated workflow has a disadvantage - food bank administrators can't plan effectively for their needs as they have no visibility/guidance for probable availability in near future.
Banks are only able to get ~40% donations and need to purchase remaining food from retails/farms.
We are planning to solve this by utilizing AI/ML to predict the surplus availability, and introducing a consumer initiated workflow which would match the food banks to the doners based on the banks requirements. Once matched with the doner facililies, food banks could set up recurring donation from them as applicable which would be offline process, not tracked by the app. 

We have discussed the feasibility of this approach with Feeding America research team and one of the largest food banks in DC (Capital area food bank). They have acknowledged the gap. Based on our initial analysis, even if we are able to get mere 5% increase in donation due to intelligent data matching - it would lead to feeding 1M additional meals and saving $40M in just in DC.  

**Data Sources**:
   - A detailed list of data sources you will use, including links and descriptions of each source.

**Architecture and Workflow**:
   - A high-level overview of the architecture and workflow, including how data flows through the system and how different Azure services are used.



**Technologies and Tools**:
   - A list of technologies and tools used in the project, such as Azure Data Factory, Azure Machine Learning, and any libraries or frameworks.

Front End - 
Reporting - Power BI
UI for food bank administrator to search for potential doners - Web app utilizing Azure maps. The app calls REST API endpoint for the model to get the matches. 

**Implementation Details**:
   - Steps to set up and run the project, including any prerequisites, installation instructions, and configuration details.

**Model Training and Evaluation**:
   - Information on how the AI model is trained and evaluated, including the algorithms used and performance metrics.

**Usage Instructions**:
   - How to use the web API or interface to get recommendations for food banks.

**Future Work and Improvements**:
   - Provide a dashboard for food bank admnistrator to help them plan better.
   - analyze past donations and inform administrators about new possible doner matches. This can be monthly email/in app notification based on the underlying data updates.  
     

**Contributors**:
    - Acknowledgment of team members and contributors to the project.





