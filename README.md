**Project Overview**:
The Nourish Network is an application developed to support food banks, mutual aid groups, and related organizations in reducing food waste and addressing food insecurity. By analyzing historical data on food waste and food scarcity, the application predicts areas likely to experience food surplus, enabling better coordination for upcycling and donation. The primary goal is to redirect excess food to communities in need, minimizing waste and saving these organizations money to bolstering resources for other initiatives. This project was inspired by the need to address the 120 billion pounds of food discarded each year in the United States, where nearly 35 million Americans—including 10 million children—face food insecurity.

In the research phase, we studied the systems of large organizations, particularly Feeding America, the largest hunger relief organization in the U.S. Feeding America’s current system connects people experiencing food insecurity with local food banks, ensuring awareness of available resources. However, there is no streamlined system to connect food banks themselves when they are in need of additional food donations. As a result, food banks can lack sufficient supply to meet demand. We believe an application like The Nourish Network could serve as a valuable tool to help boost food donations and reduce operational costs, allowing food banks to allocate more funds directly to hunger relief efforts.

Additionally, we reviewed the work of the Capital Area Food Bank in Washington, D.C., a direct partner of Feeding America. In 2023, this food bank distributed 60.9 million meals, of which 31.6 million were purchased while 32.3 million came from government programs or donations from retail sources, wholesalers, and manufacturers. This significant dependence on purchased meals resulted in $95,943,433 in food costs. By improving access to surplus donations, The Nourish Network could potentially reduce these expenses, allowing food banks to redirect resources toward other critical needs and expand their reach.

Example Use Case: "As a food bank administrator at zip code 11208, I am looking to stock up on frozen food by October 31, 2024. Provide me with a list of potential facilities that could assist in fulfilling my request." 

**Detailed Objectives**:
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





