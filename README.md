**Algorithm Description**
----------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------
**Algorithm Name:** Helios-LSTM

**Objective:** To monitor solar wind activity using NASA data and predict solar wind patterns with high accuracy.

**Solar Wind Data:** [solar_wind.csv](https://drive.google.com/file/d/1A1KiawBjZuL9JUOFrq_l9ihm5X5HnJ-P/view?usp=sharing)

**App Source Code**: [Helios_Explorer.zip](https://drive.google.com/file/d/1pFz0P5rLq6BSr3rLWrIohW79U7XwY1Iu/view?usp=sharing) 

**Methodology:**

1. **Data Collection and Integration**
   - Retrieve data from three NASA APIs: Solar Wind, Solar Radiation (CME), and Geomagnetic Storm.
   - Integrate the data to create a comprehensive dataset for model training.

2. **Data Preprocessing**
   - Aggregate hourly features from the "solar_wind" data provided by NASA.
   - Impute missing values using the most frequent strategy.
   
3. **Model Architecture**
   - Construct a novel model consisting of the following components:
     - Bidirectional LSTM layer to capture temporal dependencies in the data.
     - Three dense layers for feature transformation.
     - GRU (Gated Recurrent Unit) layer to further analyze and monitor solar wind activity.
   
4. **Training Data Split**
   - Use 29 features from the dataset.
   - Split the data into 10,000 samples for validation and 6,000 samples for testing.

5. **Model Training**
   - Train the Helios-LSTM model on the training dataset to recognize patterns based on historical examples.
   
6. **Prediction**
   - Utilize the trained model to make predictions for solar wind patterns for different time intervals:
     - Last one day
     - Last seven days
     - Last three days
     - Last two hours
     
7. **Performance Evaluation**
   - Calculate prediction accuracy.
   - Assess the model's performance against existing methods.
   - Achieve an impressive accuracy rate of 94%.
   
**Results:**
The Helios-LSTM model demonstrates outstanding performance in monitoring solar wind activity and predicting patterns with a 94% accuracy rate. This achievement surpasses existing methods and provides a reliable tool for solar wind analysis.


**App Description**
----------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------
**App Name:** HELIOS EXPLORER

**Objective:** To provide real-time forecasts of geomagnetic storms, solar winds, and solar radiation, along with their impact angle and intensity on Earth, using data from NASA APIs. Additionally, the app offers a global overview of potential catastrophic events and K-index measurements. It serves as an environmental conservation tool by sending government alerts days before solar flares impact Earth.

**Key Features:**

1. **Real-time Space Weather Forecasts**
   - Forecast geomagnetic storms, solar winds, and solar radiation.
   - Predict the angle and intensity of these space weather phenomena based on user-selected time and location.

2. **Integration with NASA APIs**
   - Utilize data from three NASA APIs:
     - NASA Solar Wind API
     - NASA CME (Coronal Mass Ejection) API
     - NASA FLR (Solar Flare) API
     - NASA GST (Geomagnetic Storm) API

3. **Global Overview of Catastrophic Events**
   - Provide users with a global view of potentially catastrophic events occurring anywhere on Earth.

4. **K-Index Measurements**
   - Include K-index measurements for space weather assessment.

5. **Rich Multimedia Content**
   - Offer a variety of engaging content such as 4K videos and podcasts related to space and solar phenomena.

6. **Augmented Reality (AR)**
   - Enhance user experience with augmented reality features.

7. **Environmental Conservation**
   - Proactively conserve the environment by sending government alerts 3-4 days in advance of solar flares or space weather events impacting Earth.

**Platform Compatibility:**
   - Available on both Android and iOS platforms for widespread accessibility.

**User-Friendly Interface:**
   - Simple and intuitive user interface for easy navigation.

**HELIOS EXPLORER** empowers users with real-time space weather forecasts, providing crucial information about geomagnetic storms, solar winds, and solar radiation, including their potential impact on Earth. The app integrates seamlessly with NASA APIs, ensuring accurate and up-to-date data for informed decision-making. Users can also stay informed about global events and space weather conditions while enjoying a rich multimedia experience and AR features. Moreover, the app actively contributes to environmental conservation by delivering timely government alerts before solar flares affect our planet.
