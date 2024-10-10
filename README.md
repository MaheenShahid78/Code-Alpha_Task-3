# A/B Testing Analysis

This project demonstrates the process of conducting an A/B test to analyze the impact of a new experimental change on key performance metrics: Gross Conversion (GC) and Net Conversion (NC). The analysis leverages statistical methods to determine if the differences observed between the control and experiment groups are statistically and practically significant.

## Contents

-	Data Scaling: Adjusting the dataset to a smaller scale of 5,000 visitors.
-	Standard Deviations Calculation: Computing standard deviations for each metric using binomial distribution.
-	Sample Size Estimation: Determining the minimum sample size for valid statistical results.
-	Confidence Interval Calculation: Calculating confidence intervals for GC and NC.
-	Statistical Significance Testing: Evaluating if the differences between control and experiment groups are statistically significant.
  
## Getting Started

Follow these instructions to set up and run the project on your local machine.
Getting Started Follow these instructions to set up and run the project on your local machine.

### Prerequisites
Ensure you have the following installed:
Python 3.x Jupyter Notebook Required Python libraries (listed in requirements.txt)

## Installation

1.	Clone the repository:
    bash
  	git clone https://github.com/MaheenShahid78/Code-Alpha_Task-3

   
2.Create a virtual environment and activate it:
bash
python -m venv venv source venv/bin/activate # On Windows, use venv\Scripts\activate


3.Install the required libraries: bash pip install -r requirements.txt

### Usage

1.Place the experiment_data.csv and control_data.csv files in the project directory.
2.Start the Jupyter Notebook:
bash
jupyter notebook

3.Open the A/B Testing Analysis.ipynb notebook and run the cells step-by-step to execute the code.

## Project Structure

1.A/B Testing Analysis.ipynb: The main Jupyter Notebook containing the code and explanations.
2.data/: Directory containing the CSV datasets. 
3.requirements.txt: List of required Python libraries.

## Dataset

The datasets used in this project represent daily records of user interactions and conversions for both the control and experiment groups. They include the following metrics:
•	Pageviews: Total page views.
•	Clicks: Total clicks on the sign-up page.
•	Enrollments: Total enrollments after clicking.
•	Payments: Total payments after enrollment.

## Analysis Methodology

The A/B test evaluates two key metrics:

1.Gross Conversion (GC): Ratio of enrollments to clicks.
2.Net Conversion (NC): Ratio of payments to clicks.

## Key Steps in the Analysis:

•	Scaling Baseline Estimates: Adjusting the dataset for smaller pageview counts.
•	Standard Deviations: Calculating standard deviations for both GC and NC using binomial distributions.
•	Confidence Intervals: Computing confidence intervals for the metrics in both groups.
•	Statistical Testing: Performing two-sided p-value tests to assess the statistical significance of changes.

## Results

1.Gross Conversion (GC): The experimental change had a statistically significant effect, with a -2.06% difference compared to the control group.
2.Net Conversion (NC): No statistically significant change was observed in this metric.

## Contributing

Contributions are welcome! Please feel free to submit a Pull Request.

## License

This project is licensed under the MIT License. See the LICENSE file for more details.

##Contact

Feel free to reach out if you have any questions or suggestions:
•	Email: maheenshahid0302@gmail.com

