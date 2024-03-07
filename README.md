# # Analysis of Historical Mortality Data and Impact of Handwashing

This repository contains Python code for analyzing historical mortality data from two clinics and investigating the impact of handwashing on mortality rates. The analysis is based on two datasets: yearly deaths by clinic and monthly deaths.

## Datasets

1. **Yearly Deaths Dataset**: This dataset contains yearly data on births, deaths, and clinics for the years 1841 to 1846. It includes information about the number of births and deaths recorded in each clinic for each year.

2. **Monthly Deaths Dataset**: This dataset includes monthly data on births and deaths from the same time period. It provides a more granular view of mortality trends over time.

## Analysis Steps

The Python code in this repository performs the following steps:

1. **Import Necessary Libraries**: Import pandas, numpy, and matplotlib libraries for data manipulation, numerical operations, and data visualization, respectively.

2. **Read and Explore Yearly Deaths Dataset**: Read the yearly deaths dataset into a pandas DataFrame and explore its structure. Calculate the total number of deaths for each clinic and the proportion of deaths.

3. **Read and Explore Monthly Deaths Dataset**: Read the monthly deaths dataset into a pandas DataFrame and explore its structure. Calculate the proportion of deaths for each month.

4. **Investigate Mortality Trends from 1841 to 1846**: Separate the yearly dataset into two datasets for each clinic and visualize the number of deaths per year for both clinics. Plot the proportion of deaths over the years for each clinic.

5. **Visualize the Proportion of Deaths in Clinic 1 and 2**: Plot the proportion of deaths over the years for both clinics using line plots.

6. **Investigate the Impact of Handwashing**: Label the date when handwashing started and split the monthly dataset into periods before and after handwashing started. Visualize the proportion of deaths before and after handwashing.

7. **Calculate the Effect of Handwashing on Mortality**: Calculate the average proportion of deaths before and after handwashing and determine the difference, indicating the impact of handwashing on reducing mortality rates.

## Results

The analysis demonstrates that handwashing had a significant impact on reducing mortality rates, with the proportion of deaths decreasing from approximately 10% to 2%, representing an approximate 8% reduction in mortality rates.

## Instructions for Running the Code

To run the code:

1. Clone this repository to your local machine.
2. Ensure you have Python installed along with the necessary libraries: pandas, numpy, and matplotlib.
3. Run the Python script (`analysis.py`) in your preferred Python environment.

## Contributors

- Afeefa kauser
- afeefakauser_407@outlook 

## License

This project is licensed under the [MIT License](LICENSE).
