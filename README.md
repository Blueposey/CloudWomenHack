**Project Overview**:
The Nourish Network is an AzureML based application designed to support food banks, mutual aid groups, and related organizations in reducing food waste and addressing food insecurity. Created for the Hack for a Sustainable Planet executive challenge, this solution analyzes historical data on food surplus and scarcity to predict potential excess, facilitating timely upcycling and donations. By redirecting surplus food to communities in need, the application aims to reduce waste and free up resources for other essential programs. The project was inspired by the vast 120 billion pounds of food wasted annually in the U.S., where nearly 35 million Americans, including 10 million children, face food insecurity.

Our research explored large-scale hunger relief models like Feeding America, the largest in the U.S., which connects individuals in need with local food banks. However, a gap exists in coordinating resources among food banks, leaving some under-supplied. A tool like Nourish Network could streamline this, boosting donations and reducing operational costs. For instance, let's take the work of the Capital Area Food Bank in Washington, D.C., a direct partner of Feeding America. In 2023, this organization distributed 60.9 million meals, of which 31.6 million were purchased while 32.3 million came from government programs or donations from retail sources, wholesalers, and manufacturers. This significant dependence on purchased meals resulted in $95,943,433 in food costs. By improving access to surplus donations, The Nourish Network could potentially reduce these expenses, allowing food banks to redirect resources toward other critical needs and expand their reach.

**Detailed Objectives**:
Existing technology is donor-initiated, which match doners and food banks focus on reducing food waste in real time, meaning food banks cannot effectively plan for future supply due to limited visibility into potential donations, leaving food banks to rely on purchasing food with cash donations, this current process aids in food waste since so many meals end up in the landfill. The Nourish Network will use AI/ML to forecast food surplus, shifting to a consumer-initiated model where food banks request resources based on their needs. This model not only matches food banks with donor facilities but can also support recurring donation setups outside the app. Our discussions with Feeding America and Capital Area Food Bank confirm this approach could fill a critical gap. Even a modest 5% increase in donations could yield 1 million additional meals and save $40 million annually in D.C. alone.

Use Case Example:
“As a food bank administrator in ZIP code 11208, I want to secure frozen food stock by October 31, 2024. Provide a list of facilities that could assist with this request.”

**Data Sources**:
   - https://hunger-report.capitalareafoodbank.org/report-2024/ [Capital Food Bank Hunger Report]
   - 

**Architecture and Workflow**:
  
**Technologies and Tools**:
Front End - 
Reporting - Power BI
UI for food bank administrator to search for potential doners - Web app utilizing Azure maps. The app calls REST API endpoint for the model to get the matches. 

**Implementation Details**:
Data Flow
    Data Collection 
    Data Preparation: 
    Data Ingestion: 
    Storage:
    Processing: Azure Machine Learning standardizes the data and can also apply linear regression and clustering techniques.
    Intermediate Storage: 
    Advanced Analysis: 
    Search: 
    Visualization: 
    Interaction: 
    Data Validation: 

**Model Training and Evaluation**:
   - Information on how the AI model is trained and evaluated, including the algorithms used and performance metrics.

**Usage Instructions**:
   - How to use the web API or interface to get recommendations for food banks.

**Future Work and Improvements**:
   - Provide a dashboard for food bank admnistrator to help them plan better.
   - analyze past donations and inform administrators about new possible doner matches. This can be monthly email/in app notification based on the underlying data updates.  
     

**Contributors**:
    - 





