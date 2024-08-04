# Property Management Analysis

### Problem Statement

The client, a real estate and property management company, requires a comprehensive analysis of their property portfolio to understand the distribution of properties based on various attributes such as location, number of bedrooms, floor status, renovation status, and waterfront status. The analysis will help identify patterns, trends, and potential areas for improvement in property management, maintenance, and market positioning.

The goal is to identify trends and factors contributing to employee turnover, such as age, education, salary, and tenure. By analyzing these metrics, the company aims to develop strategies to reduce attrition, improve employee satisfaction, and optimize workforce management.

### Task

As a Data Analyst, I developed a comprehensive real estate and property management report in Power BI. This report was designed to provide insights into various aspects of the property portfolio, including location, condition, renovation status, and other key metrics, with the goal of aiding decision-making for property management and strategy.

### Steps Followed

**Step 1: Data  Gathering and Import**

- The initial step was to collect and understand the real estate data provided in Excel format. This involved reviewing the business requirements to ensure the data aligned with the project's objectives.
- After setting up Power BI Desktop, I imported the Excel data by selecting the appropriate file and loading the necessary tables. This established a connected and structured dataset within Power BI, ready for analysis.

**Step 2: Data Transformation**

- **Removing Irrelevant Columns:** Streamlined the dataset by eliminating columns that were not necessary for the analysis, ensuring a focus on relevant data.
- **Removing Duplicate Values:** Ensured data integrity by identifying and removing duplicate entries to maintain accuracy in reporting.
- **Using Find and Replace:** Standardized data entries to correct inconsistencies across the dataset.
- **Changing Data Types:** Adjusted data types, such as converting text fields to numerical values where applicable, to facilitate accurate analysis.
- **Inserting New Conditional Columns:** Created new columns based on specific conditions (e.g., categorizing properties by condition status) to enrich the dataset and provide deeper insights.

**Step 3: Wireframe Creation using Power Point**

- **Define Structure**: Start by outlining the structure of each report page on PowerPoint slides. Use rectangles and text boxes to represent different visual elements like charts, maps, and filters.
- **Layout Design**: Position the elements according to their importance and logical flow. For instance, place key metrics at the top and more detailed visuals below.
- **Navigation Buttons**: Add shapes or buttons on the slides to simulate page navigation. Label these buttons according to the page or section they will navigate to in the final Power BI report.

[Real Estate Background Layouts.pptx](https://prod-files-secure.s3.us-west-2.amazonaws.com/0391df94-4734-4849-a107-fd90a40b7b76/23570d81-a69f-4ac6-85bc-295eab67d345/Real_Estate_Background_Layouts.pptx)

**Step 4: Visualization**

- **Dashboard Design**: Plan the layout of the dashboard, considering what information needs to be prominently displayed and how users will interact with it.
- **Create Visuals**:
    - Use bar charts for comparing property counts by bedroom and floor status.
    - Use cards to show the distribution of property condition status.
    - Incorporate maps for geographical distribution of properties.
    - Use line charts for time-series analysis of properties built by year.
- **Apply Filters and Slicers**: Add slicers and filters to the dashboard to enable users to interact with the data and explore different dimensions, such as location, condition, or property type.

**Step 5: Report Creation and Page Navigation**

- **Create Multiple Report Pages**: Design different pages within the Power BI report to present various aspects of the data, such as "Property Overview," "Location Analysis," and "Property Condition."
- **Implement Page Navigation**:
    - Use buttons or images as navigation elements. These can be configured to navigate to specific report pages when clicked.
    - In Power BI, use the “Action” feature under button or image settings. Set the “Type” to “Page Navigation” and select the target page.
    - Ensure that the navigation is intuitive, allowing users to easily move between different sections of the report.
- **Styling and Formatting**: Customize the theme, colors, and fonts to maintain consistency and visual appeal across the report.

![image](https://github.com/user-attachments/assets/e8590249-4a9c-4c60-bdb0-beb6457008c8)
![image](https://github.com/user-attachments/assets/28e2c2cd-9dfe-4737-9a62-166f73896633)


**Insights and Recommendations**

- **Waterfront Properties**: Only 1% of the properties have waterfront views, indicating a potential premium market segment. Consider focusing marketing efforts on these properties for higher returns.
- **Condition Status**: A significant number of properties (15K) are in "Good" condition, but 3,485 properties are classified as "Bad." Prioritize maintenance or renovation for properties in poor condition to increase their market value.
- **Renovation Insights**: A near-equal distribution between renovated and non-renovated properties suggests potential for value addition through targeted renovations. Consider identifying properties that would benefit most from renovation to increase their appeal and market price.
- **Geographical Distribution**: The map visualization shows the spread of properties across various states, with noticeable clusters. This can guide strategic decisions regarding where to focus expansion or divestment efforts.
- **Year Built Analysis**: Properties built between 2000 and 2010 show higher numbers. Understanding the condition and market value of these older properties could inform decisions about potential upgrades or sales.
- **Floor and Bedroom Insights**: Properties with more bedrooms or higher floors are fewer and should be considered for targeted marketing to families or investors looking for premium offerings.

These insights will help the property management team make data-driven decisions, improve property value, and enhance overall portfolio performance.
