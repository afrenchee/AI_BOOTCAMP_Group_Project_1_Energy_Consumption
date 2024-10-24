
# U.S. Energy Consumption Analysis: Trends, Types, and Future Costs

## Project Overview
This project focuses on analyzing U.S. energy consumption across regions and industries, with an emphasis on energy types (coal, nuclear, renewables) and predicting future energy costs for the largest consumers. The project leverages national, regional, and industry-level data to provide insights into energy trends and forecast consumption and costs up to the year 2030.

### Key Objectives:
1. **National and Regional Energy Consumption**: Analyze U.S. energy consumption at both the national and regional levels.
2. **Industry-Specific Consumption**: Evaluate energy consumption by major industries, and assess efficiency (kWh per dollar of output).
4. **Predictive Modeling**: Forecast future energy consumption and costs, particularly for the largest energy consumers.
5. **Insights and Recommendations**: Identify trends, future risks, and offer recommendations based on the analysis.

---

## Data Structure:

### 1) **Regional Energy Consumption**:
   - **Measurement/Data**: kWh consumption by state.
   - **Data Source**: CSV file - Total Energy Consumption by State.
   - Analyze the total energy consumption per state to identify the highest and lowest energy-consuming regions.

### 2) **Industry Energy Consumption**:
   - **Measurement/Data**: kWh/$ consumption for various industries (Residential, Commercial, Industrial, Transportation).
   - **Data Source**: CSV files - Consumption and Expenditures for Residential, Commercial, Industrial, Transportation by State.
   - Examine how energy consumption and expenditures vary across industries in each state, and calculate energy efficiency (kWh/$).

### 4) **Predictive Analysis**:
   - **Measurement/Data**: Future prediction of energy consumption and cost per kWh for the largest energy-consuming states and industries.
   - **Data Source**: Combined data from the previous analyses (state, type, and industry-level data).
   - Use time series forecasting models to predict the future cost of energy and identify potential risks for the highest consumers.

---

## Project Members:
- Austin French
- Eric Wang
- Scott Horvath
- Arshiya Mohammed
- Johnathan Marsh
---

## Project Structure:
The project is organized into the following sections:

1. **Data Collection**:
   - U.S. national energy consumption data.
   - Regional breakdown of energy usage by state.
   - Industry-specific energy consumption and expenditures data.

2. **Data Analysis**:
   - Energy consumption by region and type.
   - Industry-specific energy efficiency (kWh/$).
   - Visualization of trends in energy consumption across sectors.

3. **Predictive Modeling**:
   - Time series forecasting to predict future energy consumption and price per kWh using methods like ARIMA and Prophet.
   - Analysis of how energy demand and costs may evolve up to 2030.

4. **Reporting & Visualization**:
   - Dashboards and visualizations showing key insights, including geographic heatmaps and industry-specific trends.
   - Final report summarizing findings and offering recommendations.

---

## How to Use This Repository

### Prerequisites:
- Python 3.8 or higher
- Key libraries: `pandas`, `matplotlib`, `seaborn`, `scikit-learn`, `statsmodels`, `fbprophet`
- Access to EIA API: To access energy consumption data, register for an API key at [EIA API](https://www.eia.gov/opendata/register.php).

### Installation:
1. Clone the repository:
   ```bash
   git clone https://github.com/<your-repo>/energy-consumption-analysis.git
   ```
2. Navigate to the project directory:
   ```bash
   cd energy-consumption-analysis
   ```
3. Install dependencies:
   ```bash
   pip install -r requirements.txt
   ```

### Usage:
- To run the analysis, first set up your EIA API key by adding it to a `.env` file in the root directory:
   ```
   EIA_API_KEY=your_api_key_here
   ```
- Use Jupyter notebooks in the `/notebooks` directory to explore the data and run specific analyses.
- Visualizations and final reports can be found in the `/reports` and `/visualizations` directories.

---

## Contributing:
1. Each team member works on their feature branch and submits pull requests for review before merging into the main branch.
2. Follow the standard Git workflow:
   - Pull from the main branch before starting any new work.
   - Push your changes to your feature branch.
   - Create a pull request for code review.
3. Ensure that all code is well-commented and includes relevant documentation for clarity.

Toatal_Energy_consuption_State.ipynb
Written by Eric Wang, this program cleans and organizes the “Total Energy Consumption By State.csv” file, giving us graphs representing:
Energy Consumption by Region (1970 - 2022)
Top Ten Energy Consuming States for 2022
Bottom 10 Energy Consuming States (2022)
Forecast Energy Consumption (1970 - 2035)

Industry Data.ipynb
Written By Scott Horvath, this program cleans and organizes both the “Total Energy Consumption By State.csv" and “Total Energy Consumption By Sector.csv” files, giving us graphs showing:
Energy Consumption By Sector from 1970 - 2022
Average Energy Consumption By State (2008 - 2022)

Data Centers.ipynb
Written By Johnathan Marsh, this program gives us a graph showing the energy usage by three large companies, Citadel, Google, Microsoft, compared to three low population states, Vermont, Wyoming, and Rhode Island, and how close the consumption between the industries and states is.

Generation -> New_Total_Energy_Generation_Graph.ipynb
Written by Johnathan Marsh with help from Eric Wang, this program uses an giving us a graph representing Total Electric Energy Generation Forecast (1970 - 2035)

Github management and organization by Austin French

---

## Data Sources:
- **U.S. Energy Information Administration (EIA)**: [EIA API](https://www.eia.gov/opendata/)
- **International Energy Agency (IEA)**: [IEA Data](https://www.iea.org/data-and-statistics)
- **Additional industry-specific data**: Collected from publicly available industry reports and data sources.

---

## License:
This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

---

## Contact:
For questions or collaboration, please reach out to any of the team members.
