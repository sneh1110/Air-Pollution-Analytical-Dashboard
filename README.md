# Air Pollution Monitoring and PM2.5 Prediction Dashboard
The Air Pollution Monitoring and PM2.5 Prediction Dashboard is an essential tool in the proactive management of air quality and public health. By effectivelyintegrating real-time data collection from various monitoring sources withadvanced predictive modeling techniques, the dashboard provides a robustframework for forecasting PM2.5 concentrations. This predictive capability iscrucial, as PM2.5 particles are known for their adverse health impacts,penetrating deep into the respiratory tract and potentially leading to severerespiratory disorders, cardiovascular diseases, and premature death.

Usage:
The utility of this dashboard extends beyond simple monitoring; it acts as adecision-support tool enabling policymakers, environmental agencies, and thepublic to take timely and informed actions. For instance, it can guide theimplementation of emergency measures during high pollution episodes, assist inurban planning, and help in the evaluation of long-term policies aimed atemission reduction. Moreover, it increases public awareness and engagement byproviding accessible and understandable pollution data.
## Visual Representation
### Heat Map
### Distribution plot
### 2D TSNE
### 2D UMAP
### 3D TSNE
### 3D UMAP

## Methodology
Storing the  data in SQL databases like PostgreSQL or MySQL.
NoSQL databases like MongoDB, especially if dealing with large volumes of unstructured data. Time-series databases like InfluxDB, which are optimized for timestamped data.
Training the model for linear regression the accuracy score provided by this is not good . 
Proceeding with hyperparameter tuning which focuses on precision and enhancement in accuracy score using grid cross-validation this approach helps to find the optimal set of hyperparameters that maximize the model's accuracy and generalization ability while accounting for variations in the data. It's particularly useful in airpollution models where the relationships between variables can be complex and nonlinear.
After hyperparameter tuning we use random forest and we get the overall accuracy and accuracy is good to proceed.

After model selection we move to model training, we train our model on parameters longitude and latitude, temperature, year, and country code.

To the creation of the dashboard  a web framework and visualization libraries for the creation of Front-end using HTML, CSS,JavaScript, and streamlit with frameworks like React.js . Backend using Flask and Django in Python, which serves the data and handles requests.
Visualization libraries: D3.js, Chart.js, the libraries specific to Python which arePlotly and Matplotib.



