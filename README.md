A script that visualizes the number of COVID-19 cases in a specified state (Massachusetts, MA in this project.) The script extracts data from nytimes dataset and visualizes cases from 02/20 to the present day. Some modifications that canbe made: You can change the state for which you'd like to see the daily cases: just enter the name of a state you'd like to see the cases for. You can also see the daily death rate by modifying `y = data['cases']` to `y = data['deaths']` and `DF['cases'] = y` to `DF['deaths'] = y`.  