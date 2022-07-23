# Change of Point Model
Implementation and comparison of different 'offline' unsupervised methods of change-point detection, based in real data.
The mission : detecting the CPD of the Israeli's summer temperatures distribution.
# Methods 
### 1 - Detection CPD by three different packeges.
An attempet to detemrined 0,1 0r 2 change points with MCP , NP.ChangePoint , BCP. 
### 2 - Computation of performance
In this project, the performance is understood as how likely it is that the temperatures rate has actually gone up, as opposed to it being random chance.
The higher the likelihood of the temperatures mean increasing to have actually gone up, the hotter it gets. The performance is calculated by using multiple method and diagnostics such as - Cross Validation ('Leave Onu Out') to asses the number of points and the model's accuracy. 

# Files 
- CPD_R - Main  Rmarkdown file which containes the paper itself. 
- Data4R - Raw data of the average temperatures from 1800 to 2013 divided to country or state. 
- Simple_Ex.py - For those of you how want to generate simple example of CPD with python. 
