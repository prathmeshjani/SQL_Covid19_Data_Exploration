# SQL Covid - Data Exploration


The SQL queries provided in this script are used to analyze COVID-19 data from the PortfolioProject database. Here is a brief description of each section of the script:

  - **Total Cases vs Total Deaths** : This query calculates the percentage of deaths relative to total COVID-19 cases for each state, helping to show the likelihood of dying if contracting COVID-19 in each state.

  - **Total Cases vs Population** : This query computes the percentage of the population infected with COVID-19 for each state over time.

  - **Countries with Highest Infection Rate compared to Population** : This query identifies countries with the highest infection rates relative to their populations.

  - **Countries with Highest Death Count per Population** : This query lists countries with the highest COVID-19 death counts per population.

  - **Showing Continents with the Highest Death Count per Population** : This query presents continents with the highest COVID-19 death counts per population.

  - **Global Numbers** : This section provides global COVID-19 statistics, including total cases, total deaths, and the death percentage on a global scale.

  - **Total Population vs Vaccinations** : This query shows the percentage of a population that has received at least one COVID-19 vaccine dose over time for each location and continent.

  - **Using CTE to Perform Calculation on Partition By** : This section introduces a Common Table Expression (CTE) to calculate the rolling number of people vaccinated per location and date. It also calculates the percentage of the population vaccinated.

  - **Using Temp Table to Perform Calculation on Partition By** : This section uses a temporary table to achieve the same calculations as the previous section.

  - **Creating View to Store Data for Later Visualizations** : This section creates a view that combines COVID-19 and vaccination data, making it easier to retrieve and use this data for future visualizations and analyses.

  **Objective: Total Cases vs Total Deaths**
  - Calculate death percentages relative to COVID-19 cases for each state.
  - Assess the likelihood of mortality if contracting COVID-19 in different states.

  **Objective: Total Cases vs Population**
  - Determine the percentage of COVID-19 cases relative to the population for each state over time.
  - Understand the scale of COVID-19 infection within different states.

  **Objective: Countries with Highest Infection Rate compared to Population**
  - Identify countries with the highest infection rates relative to their populations.
  - Highlight regions with severe COVID-19 outbreaks in relation to their population size.

  **Objective: Countries with Highest Death Count per Population**
  - List countries with the highest COVID-19 death counts per population.
  - Identify areas with the most significant impact of COVID-19 in terms of mortality.

  **Objective: Showing Continents with the Highest Death Count per Population**
  - Present continents with the highest COVID-19 death counts per population.
  - Gain insights into the impact of COVID-19 at a continental level in terms of mortality.

  **Objective: Global Numbers**
  - Provide comprehensive global COVID-19 statistics, including total cases, total deaths, and the death percentage.
  - Offer an overview of the COVID-19 pandemic's global impact.

  **Objective: Total Population vs Vaccinations**
  - Calculate the percentage of the population that has received at least one COVID-19 vaccine dose over time.
  - Monitor vaccination progress in different locations and continents.

  **Objective: Using CTE to Perform Calculation on Partition By**
  - Utilize a Common Table Expression (CTE) to simplify rolling vaccination statistics calculation.
  - Calculate rolling vaccination numbers and the percentage of the population vaccinated.

  **Objective: Using Temp Table to Perform Calculation on Partition By**
  - Employ a temporary table as an alternative method for calculating rolling vaccination statistics.
  - Demonstrate an alternative approach to performing the same calculations.

  **Objective: Creating View to Store Data for Later Visualizations**
  - Create a view that integrates COVID-19 and vaccination data for future use.
  - Facilitate data retrieval and visualization for future analyses.

These SQL queries and data manipulations provide valuable insights into COVID-19 statistics, helping users understand the pandemic's impact at various levels, from individual states to global trends. The data can be used for further analysis and visualization in various data visualization tools or platforms.
