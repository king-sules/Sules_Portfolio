# Welcome To My Portfolio! I have listed projects I have done in the past. 
### Categories are organized by: Machine Learning, Data Analysis, and Mechanical Engineering


## Machine Learning
### [Project 1: Covid-19 Effects on Yellow Taxi in NYC](https://github.com/king-sules/Covid_Taxi/blob/main/Covid-19%20Taxi.ipynb)
The basis of this project is to review if Covid-19 had an effect on the popularity of taxi in NYC. We take into consideration the year 2018 and 2020. We also take into consideration the months during the lockdown, April and May, and the months when NYC had less restriction, August and September (2020). We compare them with the same months in 2018 when there were no Covid-19 restrictions.

We used ML models such as 1D Gaussian Mixture Model, Random Forest Regression, and also Clustering. We determined accuracy by using MSE and MAE. More information is available in detail with the link.

<img width="650" alt="Boroughs" src="https://user-images.githubusercontent.com/54907087/142779263-b1ac2b05-a04d-4aea-a0d0-13323740f9e1.png">

### [Project 2: Housing Prices vs. Nuclear Power Plants](https://github.com/king-sules/Nuclear_Matrix_Data)
The following is my python and R codes I used for my undergraduate thesis paper. The basis of my paper was to capture house price variation with distance from a nearby nuclear power plant. I used the town of Plymouth, Massachussets for my house data. 

I continued to clean, and later find correlations in my data. Prices were originally listed in my dataset, but distance was obtained using geopy and geopandas library. By using these libraries, I obtained distance from each individual house listed to the power plant.

My paper essentially looked at how the Fukushima Daiichi event effected house prices. I created a new column in my dataset, a Fukushima dummy, where a value of 1 was assigned if the indivial house sold after 2011 and 0 before 2011. I also categorically grouped my distance column, in incriments of 4 miles, to control price variation in rural areas.

Lastly I used R to run multiple regressions.


<img width="300" img height="300" alt="plymouth" src="https://user-images.githubusercontent.com/54907087/140659135-7cc55f6b-087c-4d19-9b3c-298bfdbbee41.png">




All of my codes are listed in this repository and I also included an original sample of data I recieved for the year 2007, which can be ran through each file.

[Here is the full thesis paper](https://github.com/king-sules/Nuclear_Matrix_Data/blob/master/Final%20Thesis.pdf)

## Data Analysis

### [Project 3: Covid-19 Breakout Analysis](https://github.com/king-sules/Covid) 
This project focused on the Covid-19 outbreak. We simply follow the cases from the original covid outbreak from December 2019 to May 2020. We try to analyze which countries are most effected by the virus and try to visualize it through Rstudios.

The data comes from John Hopkins.

### [Project 4: Taxi vs. Uber](https://github.com/king-sules/Taxi)
An analysis of taxi popularity in NYC after tlc new policy implemented in August 2018

In August 2018 the taxi & limousine commision passed a new policy which restricted the rides given to for hire vehicles, such as Uber and Lyft. This was to allow the yellow cab to compete with these rising companies

Through this project, we analysed how many rides taxi cabs give out every day, and month. We then compare this to rides that fhv vehicles give out. We use Postgres SQL to essentially gather our information.

We use python to visualize our results. Afterwards, we use facebooks fbprophet to predict the future trends in rides given in both fhv and taxi.

## Mechanical Engineering 
### [Project 5: Airplane Wing Vibration Analysis](https://github.com/king-sules/Vibrations/blob/main/Multi_DOF_Response.m)
In this project I analyze a sample airplane wing to determine the effects of vibration towards the whole airplane. 

The wing was experimentally divided into many degrees of freedom, and furthermore vibration modes were determined with the help of a Matlab code I created. 

Results were also visualized with ANSYS software 

Full report was created with LaTeX and can be found [here](https://github.com/king-sules/Vibrations/blob/main/Vibration_Project%20(2).pdf)


<img width="451" alt="Screen Shot 2021-11-28 at 8 17 27 PM" src="https://user-images.githubusercontent.com/54907087/143794858-40ba1d3a-aab5-4643-87a4-627a041bd47f.png">


### [Project 6: Design for Manufacturability (Tire)](https://github.com/king-sules/Vibrations/blob/main/Taguchi%20Project%20Tire%20Wear.pdf)
For this project I Created a design of a sample tire, using the Taguchi method, to ensure the best manufacturability of the tire and reduce tire wear by selecting specific parameters. These parameters included slip angle, tension strength and the friction of the tire. The results were calculated using Minitab.

The report is linked [here](https://github.com/king-sules/Vibrations/blob/main/Taguchi%20Project%20Tire%20Wear.pdf)



