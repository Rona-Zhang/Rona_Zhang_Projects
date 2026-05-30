# 👋 Welcome to Rona's Project Portfolio!

### Business & Data Analytics | Data Visualization | Quantitative Research | Machine Learning

---

## 👩🏻 About Me

I'm passionate about harnessing the power of data to solve real-world challenges. Grounded in quantitative research and analytics, I thrive in dynamic settings where innovation, strategy, and collaboration come together.  

🎒 MS in Business Analytics @ USC Marshall  
🎓 BA in Data Science (Minor in Mathematics & Business Studies) @ NYU  

---

## 🛠️ Skills
- Python, SQL, Java, R, Excel, Data Visualization (Tableau, Power BI, Streamlit), Statistical Analysis (Quantitative Analysis),
Machine Learning, Predictive Modeling, Data Transformation, Data Cleaning & Validation, Exploratory Data Analysis, Data Integration & Reporting

---

## 🌟 Projects
### Kickstarter Campaign Success Drivers & Platform Insights Analytics
This project analyzes Kickstarter campaign data to understand the key factors driving campaign success under the platform’s all-or-nothing funding model. Using Python and visualization techniques, the analysis explores how funding goals, campaign duration, category differences, and backer engagement relate to funding outcomes. Through distributional, comparative, and time-based analysis, the project uncovers key patterns in campaign performance, including the importance of realistic goal-setting, significant variation in success rates across categories, and the strong relationship between user engagement and funding results. It also highlights how increasing platform activity may intensify competition and impact success probability over time. These findings provide actionable insights for optimizing campaign design and funding goal-setting strategies, offering a data-driven perspective on improving campaign success probability.
- [Notebook](Kickstarter_Data_Analysis_notebook.pdf)
  
### Income Inequality in Los Angeles Building Permit Activity
The project examines how income levels shape building permit activity across Los Angeles neighborhoods, using permit data linked to census-tract income classifications. Leveraging Python-based analysis on Snowflake-hosted data accessed via SQL, the analysis compares permit volume, total valuation, and improvement types between low-income and high-income areas. Through statistical analysis and visualization, the project reveals that while overall permit counts are similar across income groups, meaningful disparities emerge in investment scale and the types of improvements prioritized. Findings are presented through an interactive Streamlit dashboard and narrative report, enabling intuitive exploration of structural inequality in urban development and supporting data-informed planning and policy evaluation.
- [Report](Income_Inequality/Income_Inequality_in_Los_angeles_Building_Permit_Activity.pdf)
- [Notebook](Income_Inequality/Income_Inequality_in_Los_angeles_Building_Permit_Activity_notebook.pdf)
  
### Amazon Product Ratings & Purchase Behavior Analytics
This project investigates whether higher product ratings on Amazon are associated with increased purchasing behavior, using a dataset of 30,000+ products. We conducted end-to-end data preparation and exploratory analysis to examine the relationship between star ratings and purchases, while accounting for confounding factors such as review volume, pricing, badges, and product categories. Through descriptive statistics, correlation analysis, visualization, and regression modeling, we identified meaningful patterns and quantified how ratings relate to demand variability across categories. The project emphasizes translating complex analytical results into clear, presentation-ready insights, highlighting both the explanatory power and limitations of the models to support data-driven decision-making for non-technical stakeholders.
- [Slides](Amazon/Amazon_Product_Ratings_&_Purchase_Behavior_Analysis.pdf)
- [Notebook](Amazon/Amazon_Product_Ratings_&_Purchase_Behavior_Analysis_notebook.pdf)

### TuneWorks Entertainment Agency Data Pipeline Analytics
As a group of seven, we began by building an end-to-end SQL data preparation workflow across 10+ relational tables, validating primary and foreign keys, cleaning missing values, and detecting outliers to ensure reliable revenue and performance analysis. We then conducted exploratory data analysis (EDA) using multi-table joins, window functions, and common table expressions (CTEs) to uncover booking trends, rank agent performance, and evaluate entertainer demand patterns. Throughout the project, we iterated on insights and translated technical results into a clear, client-ready presentation that communicated actionable recommendations for operational optimization and long-term growth.
- [Slides](TuneWorks/TuneWorks_Presentation_Deck.pdf)
- [Report](TuneWorks/TuneWorks_Report.pdf)
- [Notebook](TuneWorks/TuneWorks_Visualizations_notebook.pdf)

### Spotify Music Popularity Analytics & Predictive Modeling
Examined Spotify audio features to predict and explain song popularity. The dataset was cleaned, standardized with z-score normalization, and reduced with PCA to uncover structure. Statistical tests (Mann-Whitney U), correlation analysis, and regression models identified significant differences across song attributes and revealed instrumentalness as the strongest predictor of popularity, with multiple regression improving accuracy. Logistic regression and classification trees were also applied for predicting mode and genre.
- [Report](Spotify_Analysis/Spotify%20Music%20Popularity%20Analysis%20%26%20Predictive%20Modeling.pdf)
- [Notebook](Spotify_Analysis/Spotify_Music_Popularity_Analysis%20_Predictive_Modeling_code_notebook.pdf)

### Multimodal Emotion Recognition with Deep Learning
Developed a multimodal emotion recognition system that fuses text embeddings from fine-tuned BERT with audio features extracted using Mel-Frequency Cepstral Coefficients (MFCC). By constructing preprocessing workflows for both modalities and training multilayer perceptron classifiers, the approach demonstrated that integrating text and audio provides richer emotional context than unimodal baselines. The results highlight the potential of multimodal AI to improve applications such as customer support, mental health monitoring, and human-computer interaction.
- [Slides](Multimodel/Investigating%20Multimodal%20Fusion%20for%20Emotion%20Recognition%20Using%20Deep%20Learning.pdf)
- [Notebook 1](Multimodel/Multimodelcode1_notebook.pdf)
- [Notebook 2](Multimodel/Multimodelcode2_notebook.pdf)
  
*(Notebook links open PDF versions for easier viewing on GitHub; original .ipynb files remain in the project folders.)*

### Spotify Music Genre Classification with Machine Learning
This project built a machine learning pipeline to classify Spotify songs into genres using a combination of preprocessing, dimensionality reduction, and ensemble modeling. PCA and KMeans revealed meaningful structure in the audio features, while a tuned Random Forest classifier delivered strong predictive performance and generalization across genres. Feature importance analysis identified popularity, loudness, and instrumentalness as the most influential predictors, providing both accuracy and interpretability. The project demonstrated how audio attributes can effectively capture genre distinctions and support multi-class classification at scale.
- [Report](Spotify_ML/Spotify_Music_Genre_Classification_%20with_Machine_Learning.pdf)
- [Notebook](Spotify_ML/Spotify_Music_Genre_Classification_with_Machine_Learning_code_notebook.pdf)

### PMI LA Project Management Case Challenge
As part of the PMI Los Angeles Project Management Case Challenge, our team Trojanalytics addressed a critical production bottleneck by designing a project plan for installing and certifying an industrial-grade paint booth system within a strict three-month timeline. We instituted a project charter, stakeholder register, and work breakdown structure, then formulated cost and risk baselines using Monte Carlo simulations and timeline modeling to quantify uncertainties and guide decision-making. When unexpected obstacles emerged, we collaborated on change management analysis, updating scope, schedule, and budget to maintain project feasibility. The final solution demonstrated both regulatory compliance and operational efficiency, while emphasizing structured planning and data-driven risk mitigation.
- [Slides](PMI_LA_Case_Challenge.pdf)
- [Other Project Materials](https://drive.google.com/drive/folders/1DuHW8aUNd0tU44S_42EXBCkLauxIdWsn?usp=sharing)

### Time Series Modeling with Applications in Economics
Applied advanced time-series methods, ARIMA (Autoregressive Integrated Moving Average) and ETS (Exponential Smoothing), to forecast U.S. stock indices (S&P500, NASDAQ, and DJIA). Using two decades of historical data, our team performed preprocessing steps such as logarithmic transformations and differencing to achieve stationarity, then compared the predictive accuracy of ARIMA and ETS under conditions of market volatility. The analysis highlighted ARIMA's relative strength in capturing volatility and long-term patterns. Then culminated in a group presentation, technical report, and a peer-reviewed individual publication paper at EMFRM 2023, offering insights valuable to investors, researchers, and policymakers for understanding stock market behavior and improving forecasting strategies.
- [Report](TimeSeries/TimeSeriesProjectReport.pdf)
- [Notebook](TimeSeries/Time-Series-code.html)
- [Publication Paper](TimeSeries/Time-Series%20paper.pdf)

### Singapore Economy Analysis
This project analyzed Singapore's economic development from 2001 to 2020 using indicators such as GDP, FDI, employment, and consumer prices. Data was processed and visualized in Excel to generate graphs showing growth patterns and the impacts of events like the 2008 financial crisis and COVID-19. The study highlighted Singapore's resilience, policy-driven growth, and transformation into a global financial hub, while noting volatility and sustainability challenges.
- [Report](Singapore%20Economy%20Analysis.pdf)

### SWS Healthcare Stock Pitch – Reata Pharmaceuticals
Evaluated Reata Pharmaceuticals as an investment opportunity using SWOT, PESTLE, and Porter's Five Forces analyses, supported by revenue forecasting and peer benchmarking. The research incorporated clinical trial outcomes, FDA approvals, and industry growth drivers to assess the company's pipeline and strategic position. A discounted cash flow model and valuation multiples reinforced the investment thesis, which projected over 100% upside potential.
- [Slides](Reata%20Pharmaceuticals.pdf)
  
### Home Credit Default Risk ADS Audit
Audited a credit scoring system built on 300,000+ loan applications to assess accuracy, fairness, and interpretability. While feature engineering and LightGBM models delivered strong performance, subgroup analysis revealed fairness concerns for older applicants. The audit recommended fairness-aware modeling, SHAP explanations, and continuous monitoring to ensure responsible deployment in lending.
- [Report](ADS/Home%20Credit%20Default%20Risk%20ADS%20Audit.pdf)
- [model_evaluation_analysis](ADS/ADSmodel_evaluation_analysis_notebook.pdf)
- [model_training_validation](ADS/ADSmodel_training_validation_notebook.pdf)
- [profiling&analysis](ADS/ADSprofiling%26analysis_notebook.pdf)
- [var_importance](ADS/ADSvar_importance.pdf)

### Immigration and Labor Market: Mariel Boatlift Analysis
This project reviewed David Card's classic study on the 1980 Mariel Boatlift, where a sudden influx of Cuban immigrants increased Miami's labor force by about 7%. Using a Difference-in-Differences framework with comparable U.S. cities, the study estimated the causal effect of immigration on wages and unemployment, particularly for low-skilled and minority workers. The analysis found no significant negative impacts, showing that Miami’s labor market absorbed the new workers effectively. The review highlighted the study’s influential role in immigration policy debates, its strong causal design, and limitations in statistical inference that invite further research.
- [Report](mariel-impact-review.pdf)
---

## 📫 Contact Me
- Email: hairong.rona.zhang@gmail.com
- LinkedIn: https://www.linkedin.com/in/rrona
- Phone Number: 551-344-7269

---

### 😃 Always open to connecting, collaborating, and exploring new opportunities!
