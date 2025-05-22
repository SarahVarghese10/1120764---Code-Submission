# 1120764--TSA-Software-Development-Code-Submission
**TSA Software Development Code Submission (1120764).**
This software was developed for the 2025 TSA Events National Conference under the Software Development Category.

This project aims to utilize a customized Machine Learning Model with extremely high accuracy to create an application that can be used to detect weeds and other harmful plants among essential crops, such as wheat. This project is intended to be used by farmers that grow these crops to help them identify the presence of weeds, locate them, and treat them if needed. MIT App Inventor and Teachable Machine were utilized to create the app.

**Approach**
- The app uses a camera (to simulate the camera on a drone) to analyze the live video camera feed and it uses the real time Machine Learning Model backend to identify the objects in the screen.
- In order to maintain the accuracy of the program, a confidence level of 90% confidence has been implemented.
- Next, an in-build Location Sensor was used to obtain the latitude and longitude where the weed was identified.
- To store this data, a TinyDB component was used and shared among different screens. Data was extracted from this array and a marker was programmed to be placed on respective latitude and longitude. Color and image variations were used for visual appealment in order to classify the areas on the map as infested with which corresponding weed type.
- The user would be able to access a map with precise markers on each location of where a weed has been detected. Next steps include spot treating areas where crops could be in danger. Compared to other products that are already in the market, this is a no cost alternative with a higher accuracy rate that allows users to easily gain insights on their crops.
This app can be easily trained and customized to identify any weed with less than 5 minutes of training. There is no geographic barriers for this software, it can be used all around the world. 


