# Description
A script that visualizes the number of COVID-19 cases in a specified state (Massachusetts, MA in this project.) The script extracts data from nytimes dataset and visualizes cases from 02/20 to the present day.

## Modifications
Some modifications that can be made: 
- You can change the state for which you'd like to see the daily cases for: just enter the name of a state you'd like to see the cases for. For example to see cases for California: 
```
data = data[data['state'] == 'California']
```
- You can also see the daily death rate by modifying:
```
y = data['cases']` to `y = data['deaths']
``` 
and 
```
DF['cases'] = y` to `DF['deaths'] = y
```  


### Example Plot
COVID-19 Cases for Massachusetts:

![Mass](https://github.com/rrafay/COVID19-tracker/blob/master/plot.png)

### Run executable file on your machine:
To run the python script on your local machine, clone the repo and run the script.py file by typing this in the terminal:
```
python -i script.py

```
This will output an interactive python graph.

To stop the script simply type
```
exit()

```
in the terminal.
