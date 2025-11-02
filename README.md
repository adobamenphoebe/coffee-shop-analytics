## ☕ Coffee Shop Analytics  
**Sales, Survey, and Sentiment Analysis + Seasonal Drink Recommender**

### 📘 Overview  
This project explores coffee shop performance using sales, survey, and Yelp review data to uncover insights on customer preferences, store trends, and drink performance. The goal is to help cafés make data-driven menu decisions instead of relying on intuition.  

### 📂 Datasets  
• **Coffee Shop Sales:** Transactions by product, outlet, and date  
• **Coffee Tasting Survey:** Preferences, habits, and tasting ratings for Coffees A–D  
• **Yelp Reviews:** Customer sentiments and ratings for each store location  
All cleaned datasets are stored in the `data` folder.  

### 🔍 Exploratory Data Analysis (EDA)  
**Tools:** Python (pandas, seaborn, matplotlib)  

**Sales Analysis**  
• Identified top-performing drinks by revenue and volume  
• Found daily and hourly sales peaks, with highest activity on Fridays between 8–10 AM  
• Compared store performance and found one outlet outperformed others by **32%**  
• Visualized key metrics with bar charts, heatmaps, and time-series plots  

**Survey Analysis**  
• Analyzed taste preference ratings for bitterness, acidity, and overall score  
• Compared preferences across age and consumption habits  
• Found younger respondents (18–25) preferred **medium roast and sweetened drinks**  
• Mapped survey preferences to product categories from the sales dataset  

**Sentiment Analysis**  
• Processed Yelp reviews with natural language processing to extract polarity scores  
• Calculated sentiment averages per shop and correlated with revenue (**r = 0.61**)  
• Found higher sentiment stores showed **15% higher repeat purchase rates**  

**Combined Insights**  
• Connected what sells best, what customers prefer, and how they feel online  

### 🤖 Seasonal Drink Recommender  
Built a simple recommender that ranks drinks by a combined feature score using:  
• Recent sales trend  
• Average survey preference rating  
• Yelp sentiment score  
Top-scoring drinks are recommended as next-season menu features.  

### 🛠 Tools and Libraries  
• Python (pandas, numpy, matplotlib, seaborn, scikit-learn)  
• Tableau (interactive dashboards for revenue and survey insights)  
• Jupyter Notebook (`notebooks/coffee_shop_eda_and_model.ipynb`)  

### 📈 Repository Structure  
```
coffee-shop-analytics/
│
├── data/                 cleaned datasets
├── notebooks/            notebooks for EDA and modeling
├── outputs/              generated visualizations
└── README.md
```


**Phoebe Adobamen**  
B.S. Economics & Data Science, Drexel University  
[LinkedIn](https://www.linkedin.com/in/phoebeadobamen) | [GitHub](https://github.com/adobamenphoebe)
