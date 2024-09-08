Walmart Sales Prediction
Project Overview:
The Walmart Sales Prediction project aims to forecast weekly sales using machine learning. It leverages multiple factors such as store number, department, store size, temperature, and holiday status to predict sales.
The project provides an easy-to-use web interface where users can input data, submit, and view the prediction results along with visualizations like bar graphs and pie charts.

Key Features:
Sales Prediction: Predicts weekly sales based on input data.
User-Friendly Interface: A clean, intuitive form to input store and environmental details.
Visualizations: After predictions, displays a bar graph and pie chart to show sales trends.

Technologies Used:
Frontend: HTML, CSS
Backend: Flask (Python)
Machine Learning: Random Forest Regressor
Data Visualization: Matplotlib, Plotly

Project Structure:
Web Interface: Users can input the store number, size, department, temperature, and holiday status.
Prediction Model: Uses a Random Forest Regressor to predict weekly sales.
Visualization: Displays a bar graph and pie chart to visualize the prediction results.

How It Works:
The user enters details such as the store number, size, department, temperature, and holiday status in the form.
Upon submission, the system predicts the weekly sales based on the input data.
The prediction is then displayed along with visualizations, including a bar graph and pie chart, for better insights into the predicted sales trends.

Prediction Model:
The project uses a Random Forest Regressor machine learning model that predicts weekly sales based on the input variables like store size, department number, temperature, and holiday status. This model is trained on historical sales data.

Visualizations
Once the prediction is made, two visualizations are generated:

Bar Graph: Illustrates the sales predictions in comparison to previous or expected data.
Pie Chart: Visualizes the distribution of sales across different departments or stores.

Future Enhancements:
Explore more advanced machine learning techniques to improve prediction accuracy.
Enhance data visualizations for deeper insights.
Add additional factors like promotional events or regional differences to the prediction model.
