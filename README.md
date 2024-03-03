# AI-for-Space-for-Environmental-Justice-Policy_Egypt-Nile-Case-Study
AI for Space for Environmental Justice Policy_Egypt-Nile Case Study

## From: Team EcoEquity (Isabelle Haddad, Genevive Mckeown-Green, Yassine Elhallaoui, Maryam Ghashghaie, Precious Nneka Elendu)
Earth observation and satellite data are valuable tools for analyzing water availability issues, but further policies are necessary to ensure proper evaluation and increase water resiliency for vulnerable communities.

# Problem Statement:

Water pollution, scarcity, and accessibility have become significant global humanitarian issues, especially with exacerbating crises such as climate change and the COVID-19 pandemic. https://www.apha.org/-/media/files/pdf/topics/equity/water_health_equity_factsheet.ashx 
Even with growing technological options and our increasing understanding of climate change impacts, more than 2.2 billion people continued to lack access to safe drinking water in 2022, with many others facing sanitation and basic service issues, https://www.un.org/sustainabledevelopment/water-and-sanitation/
The United Nations' Sustainable Development Goal 6: Clean Water and Sanitation focuses on the necessity to improve clean and safe water accessibility through improved water resource management around the globe to not only provide benefits to human health but also have prosperous food and energy systems. It has also been shown in the U.S. that those facing water scarcity are unequal in exposure, with socially vulnerable groups being disproportionately impacted. 
https://iopscience.iop.org/article/10.1088/1748-9326/acb06d/pdf 
Globally, the most disadvantaged groups are burdened with water accessibility issues. Therefore, policies are necessary to prioritize these groups when it comes to future water management.
Earth observation, satellite data, and remote sensing technology are extremely useful tools for sustainable water management and policy formation. 
https://docs.sentinel-hub.com/api/latest/data/sentinel-2-l2a/
https://www.esa.int/Applications/Observing_the_Earth/Satellites_and_machine_learning_for_water_management 
Providing accessible data to communities facing water management issues will help inform stakeholders on the ground to develop innovative techniques for addressing the crisis and providing this basic human right to their vulnerable populations. In order to make meaningful progress in addressing water scarcity and ensuring that this vital human right is accessible to all, we must use a combination of technical data, equitable policies, and community-supported action.

# Recommended Solution

We propose the following technological and policy recommendations from our analysis:

## Technology:

We recommend utilizing our user-friendly automated framework (AQUA) that processes satellite images and provides details on water quantity and quality. This tool can be easily accessed as it only requires freely available satellite images, which are available for locations all across the globe. By determining the type and level of water scarcity threat, leaders can tailor their action plans to address the highest priorities in their communities. Additionally, by identifying the areas with the highest levels of scarcity and contamination,  the most vulnerable communities can be determined through proximity.
To help ensure equity in accessibility, we suggest creating a free app for easy access that outlines current risk levels based on location and provides suggested actions. We recommend implementing an alert system to let municipal planners know when water levels are changing, when pollution is present, and when to plan for different strategies. Keeping the community informed through this free, easily accessible data will hold water management authorities accountable for planning for water resource changes. 
In order to ensure the most vulnerable water-scarce communities  have access to this tool and are able to address threats, we suggest working with community leaders to design workshops and help them learn to work with the AQUA framework and/or proposed app so that they can share it within their communities and help troubleshoot locally. By working directly with community leaders, we will ensure that there is ready access to all threat-related data and recommended solutions.

## Policy:

Require and fund municipalities in water-stressed zones to implement the app proposed for disseminating water quality data. Include monthly check-ins with communities lacking access to early warning technologies or predictive data. 
Develop an identifiable partnership between community groups and water management stakeholders to ensure that marginalized communities facing low water access are involved in the decision-making process.
Incorporate results from the data to initiate and gather funding for water management strategies, such as nature-based solutions to improve water resilience and adaptation in identified water-stressed and vulnerable areas.
 

# Implementation:

Using DevSeed as an exemplar model, earth observation techniques were utilized in our new framework in order to show changes in the water quality and quantity data over time and provide this information in an accessible format to communities.

### AQUA (Aqua Quality Unity Assessment) Framework:
An automated framework for water resource assessment that utilizes vector data representing specific areas of interest. This framework will incorporate analyses such as NDWI, NDSI, Turbidity Index, Chlorophyll Concentration, and Evapotranspiration Index to evaluate the quality and availability of water resources. The primary goal is to enable organizations monitoring water resources to make informed decisions and provide a foundation for case studies in specific regions by facilitating report generation and updating management dashboards.
Key Features of AQUA:

#### Versatility: 
The framework accommodates vector data from different organizations and sectors, allowing for a versatile application across diverse domains.
Comprehensive Analysis: Integrating NDWI, NDSI, Turbidity Index, Chlorophyll Concentration, and Evapotranspiration Index provides a thorough assessment of water quality.
API Functionality: The framework can be used as an API, enabling organizations to seamlessly incorporate water quality data into their existing systems.
Modularity: The modular design allows organizations to plug the framework into their datasets, facilitating easy integration and customization.
Predictive Modeling: By combining water quality analysis with existing datasets, the framework supports the development of predictive models for informed decision-making.

#### Implementation Plan for Various Municipalities:
Conduct a thorough assessment of the organization's water resource management needs.
Customize the framework to align with specific goals and requirements.
Provide training for relevant personnel on the utilization of the framework.
Integrate the framework into existing systems and workflows.
Conduct comprehensive testing to ensure the accuracy and reliability of water quality assessments.
Evaluate the framework's performance against predefined metrics.
Implement the framework gradually, starting with pilot projects if necessary.
Establish a feedback loop for continuous improvement based on user experiences and evolving data needs.

## Case Study:
We have provided a selective case study to show how geospatial data gained through our framework can identify locations of high water vulnerability. Our framework identifies water quality and the amount of water in the area, both presently and over time.  These results and similar ones can be used to identify specific solutions that will increase resilience for the identified communities.
 
Geo-spatial Analysis Results: 'Historical evolution of water sanity'
 
The water quality analysis of the Nile river for 2021, 2022, and 2023 respectively reveals a nuanced situation, The NDWI shows a slight decrease (-0.470 to -0.484), hinting at reduced water content, simultaneously, Chlorophyll Concentration increases (from 4.38 to 4.56), signaling higher nutrient levels. The Turbidity Index remains steady, indicating consistent water clarity. There's a marginal rise in the Evapotranspiration Index (from 0.438 to 0.456), pointing to increased water loss. 
Water coverage expands (from 4.99 to 5.47), suggesting potential growth. In general, the water quality appears relatively stable, emphasizing the need for ongoing monitoring to support informed
Decision-making and sustainable management can be extracted by understanding the indexes from : https://www.earthdata.nasa.gov/learn/pathfinders/water-quality-data-pathfinder 
Framework Components:
The automated framework will function as both an API and a modular tool that can seamlessly be integrated with diverse datasets from organizations in fields such as healthcare, marine life, humanitarian aid, risk assessment, and outbreak prevention. By adding water quality analysis to existing datasets, organizations can enhance their predictive modeling capabilities and improve decision-making processes
 

## Limitations of Study and Future Improvements:
* Due to the scope of this study, there are some limitations, including real-time data accessibility hindrances due to cloud coverage because water satellite data needs a clear sky.
* Currently, the case studies show yearly data comparisons; if we want more real-time data, we would have to use past data for future projections or invest in heavy computing software.
* To be able to access this data on software like an app, there would need to be sufficient storage or employees working on transferring the data from satellite imagery maps to dashboard statistics.
* Both data projections and application usage require network access and associated technologies (phone, laptop/computer, etc.) for handling the data.
