# Udacity Blog Post - COVID-19 vs USA

## Libraries Used
- Pandas - Used for wrangling data
- Numpy - Used for wrangling data
- Matplotlib - Used to create charts
- sklearn - Used for prediction model

## Functions Created
**prep_data**
Function used to clean up data in preparation for plotting (can be used for infection and death data)
Input: Dataset with the Province/State, Lat, Long columns removed, string name of 3 countries
Output: A list of dates, a list of infections or deaths for 3 countries (4 lists total)
Example: prep_data(data, "Italy", "Iran", "US")


**line_plot_deaths**
Function to plot death data as line graph
Note: data_prep function will return all necessary variables for input (see below)
Input: List of dates, list of deaths for 3 countries
Output: Comparison line chart of 3 countries deaths per date


**line_plot_infections**
Function to plot infection data as line graph
Note: data_prep function will return all necessary variables for input (see below)
Input: List of dates, list of infections for 3 countries
Output: Comparison line chart of 3 countries infections per date


**plot_infections_vs_death**
Function to plot Infections vs Deaths of a provided country
Input: List of dates, list of infections for a country, list of deaths for same country, string of country name
Output: Graph of Infections vs Deaths for a particular date and country
Example: plot_infections_vs_death(dates, infections, deaths, "USA")


**last_30_days**
Subset data to last 30 days 
Input: list of dates, list of deaths/infections for 3 countries (4 lists total)
Output: A subset of these lists of the last 30 days

## Project Motivation
With COVID-19 being the topic on everyone's minds lately, I wanted to see what analysis I could do with the publicly available data from JHU. I was also curious to see if there was enough data for a basic prediction model to predict the next day's infection reports.

## Files in Project
Everything can be accessed via the Jupyter Notebook file entitled "COVID-19 Investigation for Iran, Italy, USA.ipynb"
