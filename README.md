SpaceX Falcon 9 First Stage Landing Prediction

Project Overview

This project aims to predict the landing success of the Falcon 9 first stage, enabling cost-efficient space missions for SpaceX by reusing the rocket's first stage. With a significant cost reduction compared to other providers, understanding the factors influencing the landing outcome is crucial for future mission planning and cost optimization.

In this project, a variety of Exploratory Data Analysis (EDA) methods and machine learning models were employed to explore relationships between mission parameters, such as launch site, payload mass, orbit type, and success rate. We used Python tools, including Folium for geographical analysis and Plotly Dash for creating interactive visualizations.

Objectives

Conduct EDA to understand trends and insights regarding Falcon 9 launches.

Utilize multiple machine learning models (Logistic Regression, SVM, Decision Tree, and KNN) to predict the success of first-stage landings.

Visualize the results using a dashboard to provide meaningful insights.

Tools & Technologies

Python (Pandas, NumPy, Scikit-Learn, Matplotlib, Seaborn, Plotly, Folium)

SQL for data querying and exploration

Plotly Dash for building interactive dashboards

Jupyter Notebook for analysis and development

Key Insights

Launch Site Analysis: The CCAFS LC-40 and KSC LC-39A launch sites demonstrated the highest success counts, highlighting certain favorable launch conditions.

Orbit Type & Payload: Success rates varied significantly across different orbit types, with orbits like SSO and GEO showing consistently high success rates.

Yearly Trends: The success rate has shown steady improvements over the years, showcasing the advancements and learning curve of SpaceX's technology.

Machine Learning Models

Logistic Regression, SVM, Decision Tree, and KNN models were trained and evaluated using GridSearchCV to determine the best hyperparameters.

The Decision Tree model achieved the highest accuracy (86.3%), showcasing its strength in predicting binary outcomes with complex conditions.

Dashboard Overview

A dashboard was built using Plotly Dash to visualize insights such as the launch success count per site, payload impact on success rate, and other key metrics. The interactive components allow users to filter results by launch site, payload mass, and booster version, providing a comprehensive view of SpaceX's mission data.

Conclusion

This project successfully demonstrated the utility of data analysis and machine learning in predicting the success of Falcon 9 first-stage landings, providing valuable insights into the conditions and factors that influence mission outcomes. The findings can aid in optimizing future launches and enhancing reusability.
