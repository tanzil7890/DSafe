# What is the Problem?

Road accidents killed 13.5 lakh people globally in 2018. They are the single largest cause of death for those in the age group of 15-45. Reckless driving is responsible for 90% of road deaths. In order to make our roads safer, a cost-effective and accessible method is needed to monitor and track reckless driving.

## My solutions?

I have developed an Android smartphone application, DriveSafe, which detects reckless driving behaviors in real-time.

## Steps for development:

I identified the major reckless driving behaviors. These are:
a. Overspeeding
b. Sudden braking
c. Sudden acceleration
d. Sharp turning


I developed an app that detects the above behaviors. In this app:

a. Accelerometer sensor is used to measure acceleration in 3D space. The haversine formula is applied to calculate distances and speed from GPS coordinates.

b. The data collected is stored in a csv file for later analysis.

c. The user interface was integrated with Google Maps API to provide the user with an interactive experience.

> The app was run on Bangalore roads for over 2 months. The acceleration in all 3 axes, the speed, the time, and the location of the vehicle were recorded every second. Using the data, I set appropriate thresholds for the rash driving behaviors.

> DriveSafe can be used to monitor reckless driving behaviors with high accuracy and improve road safety by individuals, fleet operators, insurance companies, and traffic police.




