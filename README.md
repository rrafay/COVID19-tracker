# Description
A script that visualizes the number of COVID-19 cases in a specified state (Massachusetts, MA in this project.) The script extracts data from nytimes dataset and visualizes cases from 02/20 to the present day.

### Example Plot
COVID-19 Cases for Massachusetts:

![Mass](https://github.com/rrafay/COVID19-tracker/blob/master/plot.png)

### Run an executable file on your machine:
To run the python script on your local machine, clone the repo and run the script.py file by typing this in the terminal:
```

python -i script.py --state California --y_axis deaths

```
This will output an interactive python graph.

To stop the script simply type
```
exit()

```
in the terminal.

You can visualize the cases and deaths for your preferred state. Simply type either `cases` or `deaths` after `y_axis` and the name of the desired state after `--state`


For example to see deaths in Delaware: 
```

python -i script.py --state Delaware --y_axis deaths

```

