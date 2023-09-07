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

These SQL queries and data manipulations provide valuable insights into COVID-19 statistics, helping users understand the pandemic's impact at various levels, from individual states to global trends. The data can be used for further analysis and visualization in various data visualization tools or platforms.
