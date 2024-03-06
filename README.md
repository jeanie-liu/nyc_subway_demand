# NYC Subway Demand Prediction

## About the Project
Our project revolves around addressing the multifaceted concerns of the New York City Metropolitan Transportation Authority (MTA) regarding the subway system. The three key areas of inquiry include:
* **Understanding Current Subway Traffic Patterns and Demographics**: We embarked on an analysis of subway turnstile data spanning several years to discern the prevailing traffic patterns across New York City, both holistically and at the neighborhood level. Moreover, we explored the interplay between subway demand and demographic factors, particularly assessing the impact of COVID-19 on ridership trends.

* **Predicting Future Subway Demand**: Anticipating future demand for the subway system is crucial for informed decision-making regarding infrastructure investments and repairs. Leveraging our analytical insights, we aimed to forecast subway demand and identify the stations deserving of prioritized attention from the city.

* **Informing Strategic Investments**: In alignment with the city's broader goals, we explored the potential for revenue generation through the establishment of city-owned convenience stores adjacent to subway stations. Our analysis sought to determine the optimal types of stores to build and their strategic placement based on neighborhood characteristics and consumer preferences.

## Installation and Setup
### Prerequisites
* **R** 4.1.2 or higher.
* **RStudio** to run the .Rmd file. [Download RStudio](https://posit.co/downloads/).

* **Required R Libraries/Packages**:
  * tidyverse: for data manipulation, analysis, and visualization.
  * lubridate: for parsing, manipulation, and arithmetic with date-time objects.
  * purrr: for applying map functions to elements of lists, vectors, or data frames.
  * sf:  for working with spatial data structures, such as reading and writing shapefiles.
  * glmnet: for implementing regularized regression methods, including ridge and lasso regression, for high-dimensional data
  * glue: for embedding R code within strings.
  * data.table: provides an enhanced version of data frames with additional functionality. 

### Cloning the Repository
To get started with the project, you first need to clone the repository to your local machine. Follow these steps:
1. **Open Your Terminal or Command Line:** This can be the Terminal app on macOS or Linux, Command Prompt or PowerShell on Windows, or any other terminal application you prefer.
2. **Clone the Repository:** Run the following command.
   ```bash
   git clone https://github.com/jeanie-liu/nyc_subway_demand
   ```
3. **Navigate to the Project Directory:** After cloning, move into the project directory with this command:
   ```bash
   cd nyc_subway_demand
   ```
Once the repository is cloned, follow the instructions in the prerequisites section to install the necessary project dependencies.

## Usage
This project consists of one main R Markdown file and a final report pdf file:
1. **Code for Analysis and Reporting (`nyc_subway_demand.Rmd`):**
   - Download the csv file `NYC_subway_traffic_2017-2021.csv` on [Kaggle](https://www.kaggle.com/datasets/eddeng/nyc-subway-traffic-data-20172021?resource=download&select=NYC_subway_traffic_2017-2021.csv). Log in or create an account if you don't have one since Kaggle requires an account for downloading data.
   - Place the downloaded dataset in the `data` folder. All other csv files and shapefiles used are included in the `data` folder in the repository.
   - To view or run the R Markdown file, open `nyc_subway_demand.Rmd` in RStudio.
3. **Final Report (`nyc_subway_demand_final_report.pdf`):**
   - This is the knitted pdf output from running the R Markdown file.

To work with the files:
   - You can either simply review the content and findings from the final report or run the cells to execute the code in the Markdown file.

## Credits and Contact
This project was developed by Jeanie Liu, Kazuma Parkinson, and Jonathan Gotian. For any queries regarding this project, please contact Jeanie Liu at hjeanieliu@gmail.com.

This project is no longer actively maintained. The repository serves as an archive of the work done and the findings of the analysis.

