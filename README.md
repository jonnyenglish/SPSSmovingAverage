# SPSS Moving Average
custom node for SPSS Modeler to calculate the simple moving average over last n periods (unweighted mean of the previous n data)

![Screenshot](./Screenshot.png)

To create a moving average:
  1. select any continous field in the '*Values*' selector on which you want to calculate the moving average
  2. In the Field '*Moving average over periods*' select a period over which the moving average should be calculated
  3. The result is a field that contains the average of the last n periods for each row.

#### Output
The result is a new column '*ma*' wich is filled with $null$ the first n-1 periods and then with the mean over the last n periods:

![outputScreenshot](./outputScreenshot.png)

Future updates may contain different moving averages as well as the possibility to derive multiple periods. Feel free to contribute.
