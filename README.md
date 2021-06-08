# 09_DataProducts_Proj
Repository for my final project for Course 9 in Coursera Data Science Specialization

Due to limited time for this project, I made a fairly simple app. 

# ui.R
The general idea behind this is pretty simple. The user is presented with two sliders, one named bins and one named number of samples. There are also 3 radio buttons available to allow the user the opportunity to change the color of the histogram. 

The user selects both of these values with a slider. 

Bins controls how many divisions are present in the histogram for the output.

Number of samples controls how many values are generated in the normal distribution. 

The output graph demonstrates two key things:
1) More values in the distribution will make it more closely resemble a proper normal distribution
2) Too many bins will ruin the effect, but smaller amounts will more closely resemble a normal distribution. 

Point 2 is due to over specifying your sample discritization. 

# server.R
This simple calculation creates a normal distribution from the number of values specified by the user, and plots it in a histogram with the bumber of breaks controlled by the number chosen by the user. The color of this histogram is set by the radio buttons from the user. 
