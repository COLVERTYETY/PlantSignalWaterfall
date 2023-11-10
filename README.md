# Plant Signal Waterfall

![Plant Signal Waterfall](./edmo.gif)

## About

This is a simple waterfall plotter for the Plant Signal.
This project uses PyQt5 and PyQtGraph to plot the waterfall.

## usage 

- ```app.py``` is the PyQt5 application that plots the waterfall and sends the data to Pure Data over socket
- ```receiveTCP.pd``` is the Pure Data patch that generates sound from the waterfall socket
- 