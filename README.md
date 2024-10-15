## VeloCityX Fan Engagement Analysis
This repository contains the data analysis and predictive modeling for the VeloCityX app, which focuses on improving fan engagement and monetization strategies in autonomous racing. The analysis explores user interactions with the app during racing events and aims to provide insights for optimizing fan challenges, virtual merchandise sales, and sponsorship integration.

### Table of Contents
Project Overview
Dataset
Analysis Approach
Methodology
Key Findings
Proposed Fan Challenge
Installation
Usage
Visualizations
Contributing
License

### Project Overview
The VeloCityX app offers an immersive spectator experience for autonomous racing events, featuring live 360-degree coverage, fan challenges, and virtual merchandise. The goal of this project is to analyze user interaction data to:

### Identify trends in fan behavior.
Propose new challenges that will enhance engagement.
Drive monetization strategies for virtual merchandise and sponsorships.

### Dataset
The dataset used in this project includes the following fields:

#### User ID: Unique identifier for each user.
#### Fan Challenges Completed: Number of fan challenges completed by a user.
#### Predictive Accuracy: Percentage accuracy of user predictions in fan challenges.
#### Virtual Merchandise Purchases: Number of virtual merchandise items purchased by a user.
#### Sponsorship Interactions: Count of ad clicks or sponsorship interactions.
#### Time on Live 360: Total time (in minutes) spent on live 360-degree coverage.
#### Real-Time Chat Activity: Number of messages sent by the user in the real-time chat.

### Analysis Approach
The project is broken down into several stages:

#### Data Cleaning: Handling missing values, ensuring data types are appropriate, and filtering out irrelevant columns.
#### Exploratory Data Analysis (EDA): Investigating trends in fan behavior, including correlations between user activities such as challenge completions and virtual merchandise purchases.
#### Clustering and Predictive Modeling: Using K-Means clustering and logistic regression to segment users and predict merchandise purchases.
#### Visualization: Creating clear, insightful visualizations to communicate key findings.
#### Fan Challenge Proposal: Based on the trends, proposing a new fan challenge aimed at boosting engagement and monetization.

### Methodology
#### Data Cleaning:

Removed missing or invalid entries and ensured numerical columns were formatted correctly.
Filtered out irrelevant columns such as specific user IDs for general analysis.

#### Exploratory Data Analysis (EDA):

Analyzed trends between fan challenges, merchandise purchases, and sponsorship interactions.
Calculated correlations to understand the relationships between different user behaviors.

#### Clustering & Predictive Modeling:

#### Clustering: Used K-Means clustering to group users based on their engagement levels.

#### Predictive Modeling: Implemented logistic regression to predict the likelihood of users purchasing virtual merchandise based on their behavior in the app.

### Visualization:

Created bar plots, correlation heatmaps, and other visualizations to clearly communicate insights.

### Key Findings
#### Challenges and Purchases: Users who complete more fan challenges are more likely to purchase virtual merchandise, suggesting that fan engagement directly impacts monetization.
#### Sponsorship Interactions: Users who spend more time on Live 360 coverage are more likely to interact with sponsorship ads, offering key insights for optimizing ad placement.
#### Clustering: High-engagement users (those who complete many challenges and make purchases) can be segmented into distinct groups for targeted marketing and promotions.

### Proposed Fan Challenge
#### Challenge Name: "Charge Master Prediction"
#### Description: 
Fans will predict which vehicle will manage its battery life the most effectively and complete the race with the fewest recharges. This challenge focuses on battery consumption and vehicle efficiency, with real-time updates provided to the fans.

### Predicted Outcomes:

#### Engagement: Increased engagement through strategic thinking and real-time data monitoring during key moments in the race.
#### Monetization: Higher chances of virtual merchandise purchases, as engaged users are more likely to buy exclusive in-game rewards. Sponsorship opportunities increase during crucial race events (e.g., when vehicles approach recharge).

### Installation
To run the code locally, ensure you have the following tools and libraries installed:

Python 3.x
Jupyter Notebook or Google Colab
Pandas: For data manipulation and analysis.
Matplotlib/Seaborn: For data visualization.
Scikit-learn: For clustering and predictive modeling.
You can install the required libraries using:

bash
Copy code
pip install pandas matplotlib seaborn scikit-learn
Usage
Clone the repository:

bash
Copy code
git clone https://github.com/your-username/velocityx-fan-engagement-analysis.git
Open the Jupyter Notebook or Google Colab and run the cells step-by-step to perform the analysis.

Ensure you have the dataset in the correct directory, or update the file path accordingly in the notebook.

Review the visualizations and insights generated.

### Visualizations
#### Clustering Bar Plot: Segments users based on engagement level and shows which clusters are more likely to purchase virtual merchandise.
#### Correlation Heatmap: Displays the relationship between various user behaviors, highlighting key factors in driving merchandise purchases and sponsorship interactions.
#### Challenge Completion vs. Purchases: A bar plot visualizing how completing fan challenges correlates with virtual merchandise purchases.

### Contributing
If you'd like to contribute to this project:

Fork the repository.
Create a new branch (git checkout -b feature-branch-name).
Commit your changes (git commit -m 'Add some feature').
Push to the branch (git push origin feature-branch-name).
Create a Pull Request.

### License
This project is licensed under the MIT License. See the LICENSE file for more details.
