### Project Title: Comprehensive Power BI Dashboard for Survey Data Analysis

#### Overview
This project involves the creation of a detailed Power BI dashboard to analyse survey data collected from data professionals. The goal is to extract actionable insights from the data, such as average salary, job satisfaction, and preferred programming languages, and to present these insights in an interactive and visually appealing format. The project showcases the use of Power BI's data extraction, transformation, and visualisation capabilities, along with advanced calculations using DAX (Data Analysis Expressions).

#### Data Source
The dataset used for this project is sourced from a survey of data professionals, provided by Alex The Analyst. The data is initially in Excel format and contains various columns, such as job titles, programming languages, salaries, and job satisfaction metrics.

#### Project Steps

1. **Data Extraction:**
   - The data is extracted from an Excel file and loaded into Power BI for further processing.

2. **Data Transformation (Power Query):**
   - Unnecessary columns are removed to streamline the dataset.
   - The data is standardised across various columns, including 'Current Role,' 'Favourite Programming Language,' 'Industry,' and 'Domicile Country,' using the Split Column function and appropriate delimiters.
   - Salary data, provided as a range (e.g., 105-125k), is split into two columns and averaged to create a new 'Average Salary' column.
   - Data types are adjusted, and new custom columns are created where necessary to ensure data consistency and accuracy.

3. **Data Loading:**
   - The transformed data is loaded into Power BI, ready for visualisation.

4. **Data Visualisation:**
   - **Title and Design:** The dashboard title is set, and the design elements such as font size, background colour, and accessible themes are configured to enhance readability and user experience.
   - **Cards:** Used to display summary metrics like the number of survey entries and the average age of participants.
   - **Stacked Bar Chart:** Visualises average salary by job title.
   - **Stacked Column Chart:** Represents the favourite programming languages by job title and the number of votes each language received.
   - **TreeMap:** Displays the domicile country of participants.
   - **Gauges:** Two gauges are used to display the average satisfaction with work-life balance and salary, respectively.
   - **Donut Chart:** Illustrates the average salary distribution by gender.

5. **DAX Calculations:**
   - DAX is utilised to perform other calculations, such as calculating the average salary based on split salary ranges. This step highlights the analytical depth and flexibility of Power BI in handling complex data scenarios.

#### Key Features
- **Interactive Dashboard:** Users can interact with various visual elements to filter and drill down into specific insights.
- **Data Standardisation:** Ensures consistency across the dataset, making the analysis more reliable.
- **Advanced Analytics with DAX:** Enhances the dashboard's capability to provide precise and insightful metrics.

#### Conclusion
This Power BI project demonstrates a comprehensive approach to data analysis, from initial data extraction to the creation of an interactive dashboard. It highlights the importance of data transformation and the power of visual storytelling through carefully designed charts and graphs. The inclusion of DAX for advanced calculations adds an extra layer of analytical depth, making this project a valuable asset for understanding key trends in data professional roles.

#### How to Use
- Download the `.pbix` file and open it in Power BI Desktop.
- Explore the dashboard by interacting with various visual elements to filter data and gain insights.
- Review the DAX formulas used in the report for advanced calculations and analysis.

This project is a robust example of how Power BI can be used to transform raw survey data into meaningful business intelligence.
