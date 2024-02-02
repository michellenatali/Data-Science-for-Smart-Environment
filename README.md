**Individual Learning Goal: Energy Behavior Prediction of Prosumers in Estonia**

**Background:**
This project, commissioned by Eesti Energy Company, aims to address the challenge of energy imbalance in Estonia—an issue where the anticipated energy usage doesn't align with the actual energy consumed or generated. Prosumers, individuals who both consume and generate energy, significantly contribute to this energy imbalance. The primary objective is to develop an energy prediction model for prosumers, ultimately reducing energy imbalance costs.

As a novice in data science, this project aligns well with my learning objectives. It involves data wrangling, data visualization, and machine learning—providing a comprehensive learning experience. Through this project, my goal is to gain a thorough understanding of the fundamentals of data science, enabling me to apply this knowledge to future projects.

**Methodology and Data Source Used**

To achieve my learning goal, I adopted a data-driven approach, utilizing historical energy consumption and production data from prosumers in Estonia (2021-2023). Employing Python, I performed data preprocessing, visualization, and implemented regression models for energy behavior prediction. The evaluation involved utilizing the Mean Absolute Error (MAE) metric to assess model accuracy. 

The dataset used for this analysis can be accessed in the 'data' folder.

**Implementation Details**

The implementation involved several crucial steps:

1. Data Wrangling:
-Compiled a dataset incorporating relevant features, including county name, consumption pattern, production pattern, and installed capacity of solar panels.
-Addressed missing or anomalous data points to ensure the quality of the dataset.

2. Data Visualization:
-Explored and visualized consumption and production patterns along with installed capacity.
- Utilized Seaborn and Matplotlib to create visualizations representing consumption and production installed capacity data across all years, per year, and per county.

3. Feature Engineering:
Extracted crucial features from time series data, including county name, consumption, production patterns, and solar panel capacity, enhancing model input with real-time data for 24-hour predictions.

4. Model Selection:
Using LightGBM and scikit-learn's algorithms chosen for their strength in capturing intricate relationships in energy behavior data.

5. Model Training:

Trained selected models, especially LightGBMRegressor, using historical data on energy consumption and production patterns.

6. Evaluation:

Assessed model effectiveness using the Mean Absolute Error (MAE) metric, providing key insights into predictive accuracy and generalization performance.

(Code snippets and detailed algorithms can be accessed in the attached Jupyter notebook.)

**Results, conclusions, and reflections are documented separately for further detail.**
