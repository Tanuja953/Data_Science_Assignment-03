🌍 Global Terrorism Analysis
📌 Project Overview
This project analyzes the Global Terrorism dataset to study patterns in terrorist incidents around the world. The dataset contains event details such as year, country, region, attack type, target type, weapon type, casualties, and other related attributes.

The goal of this project is to clean the data, explore important trends, and create meaningful visualizations that help understand terrorism patterns over time and across regions.

🎯 Objectives
📂 Load and inspect the dataset
🧹 Handle missing values and duplicate rows
🔄 Clean incorrect data types
➕ Create new useful columns such as casualties
📊 Perform exploratory data analysis
📈 Visualize key trends using charts
💡 Generate insights that are useful for stakeholders
🛠️ Tools Used
🐍 Python
🐼 Pandas
🔢 NumPy
📉 Matplotlib
🎨 Seaborn
🧼 Data Cleaning Steps
The following cleaning steps were performed:

🗑️ Removed duplicate rows
⚠️ Handled missing values in important columns
🔧 Converted incorrect data types into proper numeric or text formats
➕ Created a new column called casualties using nkill + nwound
📅 Created additional helpful columns such as year, decade, and month_name
📌 Key Columns Used
📅 iyear
📆 imonth
📍 iday
🌎 country_txt
🗺️ region_txt
🏙️ city
💣 attacktype1_txt
🎯 targtype1_txt
👥 gname
🔫 weaptype1_txt
☠️ nkill
🤕 nwound
✅ success
⚔️ suicide
📊 casualties
📊 Exploratory Data Analysis
The analysis focuses on:

📈 Terrorist attacks by year
🌍 Countries with the highest number of attacks
💣 Most common attack types
🎯 Most affected target types
☠️ Casualty distribution
📦 Outliers in attack impact
🔗 Correlation between numerical variables
📉 Visualizations
The project includes the following visualizations:

📈 Line chart for attacks by year
📊 Bar chart for top affected countries
💣 Bar chart for attack type frequency
🥧 Pie chart for target type distribution
📉 Histogram for casualties
📦 Box plot for outliers in casualties
🔥 Heatmap for numerical correlations
💡 Key Insights
🌍 Terrorist attacks are not evenly distributed across time or geography
📍 Some countries and regions experience significantly more attacks than others
💣 Bombing and explosive attacks are often common
🎯 Civilian and public targets are frequently affected
📊 Casualty values are highly skewed, showing that a small number of events cause large losses
🧠 The dataset can help identify high-risk areas and support security planning
👥 Stakeholder Usefulness
This project is useful for:

🏛️ Governments planning counter-terrorism strategies
🛡️ Security agencies monitoring risk patterns
🎓 Researchers studying terrorism trends
📜 Policy makers allocating resources
🌐 International organizations evaluating regional threats
📁 Project Structure
project-folder/
├── Global_Terrorism_Data.csv
├── notebook.ipynb
├── README.md
└── images/
🚀 How to Run
📥 Clone this repository
💻 Open the notebook in Google Colab or Jupyter Notebook
📦 Install required libraries if needed
▶️ Run the notebook cells step by step
👀 View the cleaned dataset, charts, and insights
🏁 Conclusion
This project provides a structured analysis of global terrorism data. It shows how data cleaning, exploratory analysis, and visualization can uncover useful patterns and support better decision-making.

✍️ Author
Anshika Thapliyal
