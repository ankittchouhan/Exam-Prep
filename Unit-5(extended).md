### **Comparison of Different Computer Vision Tasks**

| **Task**                  | **Definition**                                                                 | **Example Applications**                               |
|---------------------------|--------------------------------------------------------------------------------|-------------------------------------------------------|
| **Image Classification**  | Identifies the main content of an image and assigns a single label to it.      | - Determining if an image contains a cat or dog. <br> - Handwritten digit recognition for postal automation. |
| **Object Localization**   | Detects the presence of an object and specifies its location using bounding boxes. | - Identifying where a car is located in a traffic image. |
| **Object Detection**      | Identifies multiple objects in an image along with their locations.             | - Self-driving cars identifying nearby vehicles, pedestrians, and road signs. <br> - Security cameras spotting intruders. |
| **Image Segmentation**    | Divides an image into segments, assigning a label to each pixel for detailed analysis. | - Tumor detection in medical imaging. <br> - Lane detection in autonomous vehicles. |
| **Pose Estimation**       | Detects key points (e.g., joints) of humans or objects to estimate movement or posture. | - Sports performance analysis. <br> - Gesture recognition for gaming. |
| **Image Generation**      | Creates new images based on learned patterns using algorithms like GANs.        | - Creating virtual artwork. <br> - Augmenting datasets with synthetic images for training. |

### **Can Data Science Be Used in Stock Market Analysis? Justify**

#### **Yes, Data Science Is Widely Used in Stock Market Analysis.**

**Reasons**:  
1. **Predictive Analytics**:
   - Algorithms like ARIMA, LSTM, and linear regression can predict future stock prices using historical data.
2. **Sentiment Analysis**:
   - Analyzing news, reports, and social media to evaluate public sentiment toward stocks.
3. **Portfolio Optimization**:
   - Data science tools analyze risk-reward ratios, helping investors make data-driven decisions.
4. **Market Pattern Recognition**:
   - Machine learning identifies recurring patterns that human traders may miss.
5. **Real-Time Monitoring**:
   - Automated systems analyze real-time data streams to alert investors about trends.

#### **Example**:
Consider Tesla stocks:
- By analyzing news about Tesla’s production output and historical data, one can predict the stock price trends and decide whether to buy or sell.

---

### **Satellite Imagery and Sensor Data in Weather Forecasting**

#### **Satellite Imagery**:
1. **Definition**:
   - Images captured by satellites showing real-time atmospheric and environmental conditions.
2. **Applications**:
   - Tracking cyclones, cloud movements, and temperature changes.
3. **Advantages**:
   - Large-scale data collection and real-time monitoring.
4. **Example**:
   - Using NOAA satellites to predict hurricanes.

#### **Sensor Data**:
1. **Definition**:
   - Data from ground sensors measuring environmental parameters like temperature, humidity, and wind speed.
2. **Applications**:
   - Hyperlocal weather predictions, climate research.
3. **Example**:
   - IoT weather sensors placed in urban areas predicting localized rainfall.

#### **Integration of Satellite Imagery and Sensor Data**:
- Combining both data types enhances the accuracy of forecasts by validating large-scale satellite observations with localized sensor measurements.

---

### **Explaining the Stock Market with Suitable Example**

#### **Definition**:
The stock market is a platform for buying and selling shares of publicly traded companies.

#### **Example**:
- **Scenario**: A company announces a breakthrough in technology.
  - Investors perceive this as valuable, increasing the demand for the stock.
  - The stock price rises due to the high demand.

#### **Use of Data Science in the Stock Market**:
1. **Sentiment Analysis**:
   - Analyze social media sentiment to predict public interest in a company.
2. **Time-Series Forecasting**:
   - Predict price movements using historical data.
3. **Risk Management**:
   - Measure volatility to guide investments.

---

### **Case Study: Google Stock Price Prediction Using LSTM**

#### **Objective**:
Predict Google stock prices using Long Short-Term Memory (LSTM).

#### **Steps**:
1. **Data Collection**:
   - Download historical data, including opening and closing prices.
2. **Data Preprocessing**:
   - Normalize data for better model performance.
3. **Feature Selection**:
   - Select features like closing price, volume, and market trends.
4. **Model Building**:
   - Build an LSTM neural network that retains long-term dependencies in time-series data.
5. **Evaluation**:
   - Test the model on unseen data and calculate RMSE (Root Mean Square Error).

#### **Outcome**:
LSTM provides better long-term price trend predictions compared to traditional models like ARIMA.

---

### **Case Study: Weather Forecasting**

#### **Objective**:
Predict weather conditions using satellite data and machine learning.

#### **Steps**:
1. **Data Sources**:
   - Combine satellite data, sensor readings, and historical weather records.
2. **Feature Engineering**:
   - Extract features like temperature, pressure, humidity, and wind speed.
3. **Model Development**:
   - Use Random Forest for short-term predictions or LSTMs for time-series predictions.
4. **Evaluation**:
   - Compare predicted weather conditions with actual outcomes.

#### **Outcome**:
Accurate weather predictions improve disaster preparedness and resource planning.

---

### **Case Study: Real-Time Sentiment Analysis**

#### **Objective**:
Analyze real-time user sentiment using social media data.

#### **Steps**:
1. **Data Collection**:
   - Scrape tweets or posts using APIs like Twitter API.
2. **Preprocessing**:
   - Clean text data by removing special characters, stop words, and punctuation.
3. **Sentiment Analysis**:
   - Use a machine learning model (e.g., Naïve Bayes or Transformer-based models like BERT).
4. **Visualization**:
   - Display real-time sentiment trends on a dashboard.

#### **Example**:
Analyze public sentiment about a new product launch and predict its impact on sales.

---

### **Descriptions of Specific Computer Vision Tasks**

#### **i. Image Classification**:
- **Definition**:
   Assigns a single label to an entire image, identifying its primary content.
- **Example**:
   Classifying whether an image contains a cat or a dog.
- **Techniques**:
   - Convolutional Neural Networks (CNNs).
   - Data augmentation for improved generalization.

#### **ii. Object Localization**:
- **Definition**:
   Locates specific objects in an image and marks their positions with bounding boxes.
- **Example**:
   Identifying the location of a car in a traffic image.
- **Applications**:
   - Autonomous vehicles detecting objects on the road.
   - Security systems identifying intruders.
