# Problem Statement 
Animal agriculture is responsible for 16.5% of all global greenhouse emissions and 77% of the world’s agricultural land is used for animal agriculture and growing. The United States discards 120 billion pounds of food — every year. At the same time nearly 35 million people across America — including 10 million children — suffer from food insecurity. Animal farming puts a strain on our soil further reducing our planet’s ability to recuperate from climate disasters, making food access increasingly insecure fueling a vicious cycle.

(@Michelle to find sources for statistics and fact check numbers in our problem statment.)

# Welcome to The Nourish Network 
The Nourish Network is a simple application that assists organizations tackling food waste by using AI to connect food banks and mutual aid organizations with food retailers, wholesalers, and farmers; to resolve some of the logistical and administrative barriers. Our goal is to create and train a model that can predict food availability, optimize logistics, and identify food surplus Ensure that food banks can easily access information about available food. To do present the data we will create a simple web API interface for organizations to use that exposes the following data: 

    - Areas of food availblity and surplus 
    - Areas of predicted food insecurity and need
    - food types, availability, shelf life, and demand patterns

Our project will not handle to logistics of transportation, consumer outreach, or public data disclosure, our proposed goal with the Nourish Network is to streamline connections between organizatitons that handle food excess with food retailers, farmers, and wholesalers. 

## Project Name???

    A short description
    The Executive Challenge: Hack For a Sustainable Planet
    Link to a video featuring a demo of your project, including a presentation describing your project goals, your solution components and architecture, how you thought through your approach, and any key learnings
    The PowerPoint presentation from your video
    A link to your code repository on GitHub

## Table of Contents

## Data Sources
https://insights-engine.refed.org/solution-database?dataView=total&indicator=us-dollars-profit
https://www.fao.org/platform-food-loss-waste/flw-data/en/
https://thefoodwasteatlas.org/records

## Next Steps 
Project Steps

- Data Collection: Gather data from various sources, including food retailers, wholesalers, farmers, and food banks. This could include information on food types, availability, shelf life, and demand patterns.

-Data Preparation: Clean and preprocess the data using Azure Data Factory, Document Intelligence or within AzureML to ensure it is ready for modeling.

-Model Development: Use Azure ML to create and train models. Focus on models that can predict food availability, optimize logistics, and identify food surplus.

-Integration: Use Azure Functions and Logic Apps to integrate various components of your system. Ensure that food banks can easily access information about available food.

-Deployment
Deploy your model and system using Azure Kubernetes Service (AKS) or Azure App Service, ensuring scalability and reliability.

-Monitoring and Improvement
Set up monitoring to track the performance of your models and workflows. Use Azure Monitor and Application Insights for this purpose. Iterate on your models based on real-world data and feedback.

   

