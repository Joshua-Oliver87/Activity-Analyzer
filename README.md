**Overview**

The Activity Analyzer with Wearable Sensors is a data analysis and visualization tool that leverages the Sussex-Huawei Locomotion Dataset to monitor, analyze, and predict user activities using data collected from wearable sensors (e.g., accelerometers, gyroscopes, magnetometers). The project focuses on providing interactive insights into sensor data and predicting activities based on sensor readings.

**Features**

**1. Sensor Statistics**

Monitor key statistics for various sensors, including:
- Minimum and maximum values
- Average value
- Standard deviation
- Frequency of data points
- Filter statistics based on:
- User ID
- Recording session
- Timestamp range
- Specific sensor types (e.g., acceleration, gyroscope, pressure).
  
**2. Interactive Data Visualization**

Visualize sensor data using Plotly for:
- Time-series plots of sensor readings.
- Frequency spectrum or wavelet transforms (planned feature).
- Display data and statistics in an easy-to-understand table or graph format.
  
**3. Activity Recognition (In Progress)**

Integration of machine learning models for:
- Activity classification: Recognize user activities like walking, sitting, and running.
- Activity prediction: Predict upcoming activities based on historical sensor data.
- Technology Stack
  
**Currently Implemented**
- Python: Core programming language for data processing.
- PyMongo: Integration with MongoDB for querying and managing sensor data.
- Pandas library: For data manipulation and statistical analysis.
- Plotly: Interactive visualizations and front-end GUI.
  
**User process**
- Select the user ID, recording session, and timestamp range using the GUI.
- View sensor statistics in the table and visualize them in time-series plots.
- Analyze activity data and monitor patterns in sensor readings.
  
**Future Improvements**
Big Data Processing:
- Integrate Apache Spark to handle dataset more efficiently.
- Use Hadoop MapReduce for distributed processing and aggregation.


**Contributors**
Joshua Oliver
Aryan Dabiri
Ninad Gaikwad


**Acknowledgments**
- Dataset: Sussex-Huawei Locomotion Dataset
- Tools: MongoDB, Python, Plotly, and Pandas.
