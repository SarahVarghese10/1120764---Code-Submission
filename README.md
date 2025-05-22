# 1120764--TSA-Software-Development-Code-Submission
**TSA Software Development Code Submission (1120764).**
This software was developed for the 2025 TSA Events National Conference under the Software Developement Category.

This project aims to utilize a customized Machine Learning Model to create an application that can be used to detect weeds and other harmful plants amoung essential crops, such as wheat. This project is intened to be used by farmers that grow these crops to help them have more concentrated treatments such as pesticides. MIT App Inventor and Teachable Machine were utilized to create the app.

**Approach**
- The app uses a camera (from a drone) to analyze the live video camera feed and it uses the Machine Learning Model backend to identify the objects in the screen and place bounding boxes around them.
- In order to maintain the accuracy of the program, a confidence level of 90% confidence has been implemented.
- Next, an in-build Location Sensor was used to obtain the latitude and longitude as well as the classification of the weed type.
- To store this data, a TinyDB component was used and shared amoung different screens. Data was extracted from this array and a marker was programmed to be placed on respective latitude and longitude. Color and image variations were used for visual appealment in order to classify the areas on the map as infested with which corresponding weed type.
- The user would be able to access a map with precise markers on each location of where a weed has been detected. Next steps include spot treating areas where crops could be in danger. Compared to other products that are already in the market, this is a no cost alternative with a higher accuracy rate that allows users to easily gain insights on their crops.

