\documentclass{article}
\usepackage{graphicx}
\usepackage{amsmath}
\usepackage{booktabs}
\usepackage{hyperref}

\title{Statistical Analysis of Customer Churn in the Iranian Telecom Market}
\author{Nitharshan Coimbatore Venkatesan}
\date{\today}

\begin{document}

\maketitle

\section{Introduction / Background}
In the highly competitive telecommunications sector, maintaining customers is crucial for companies' economic viability. When a major Iranian telecom company experienced a significant increase in customers switching to competitors, it highlighted the importance of retaining subscribers. Faced with the prospect of losing a large portion of their customer base, the company's leaders understood the need to analyze the reasons for customer churn.

As my interest in performing data analysis on marketing and customer service aligns with this scenario, I decided to perform a statistical analysis on this topic. While numerous research papers employ advanced machine learning models and big data implementations to predict customer churn rates, this project leverages statistical techniques to extract deeper insights.

Prior research such as \textit{Customer Churn Prediction in Telecommunications} by Huang et al. analyzed usage patterns, billing behaviors, demographics, and location data to improve prediction models. Similarly, \textit{Telco Churn Prediction with Big Data} by Huang et al. demonstrated how scalable analytical techniques helped predict customer attrition with high accuracy.

This study adopts a more interpretative statistical approach by applying hypothesis testing, ANOVA, bootstrapping, and regression modeling to understand the underlying factors influencing customer churn in the Iranian telecom market.

\section{Research Questions}
\begin{enumerate}
    \item Are there discernible patterns in usage duration among customers enrolled in different tariff plans? (Hypothesis Test: T-Test)
    \item Do customers with longer subscription lengths exhibit different calling and messaging behaviors? (Exploratory Data Analysis - EDA)
    \item How do customer perceptions of service quality and satisfaction interact with their level of activity to influence churn likelihood? (Chi-Squared Test)
    \item Can demographic segmentation based on age help identify high-value customer segments for targeted marketing? (ANOVA, EDA)
    \item How do predictor variables influence the accuracy and reliability of Customer Lifetime Value (CLV) predictions? (Regression Modeling: AIC, BIC, $R^2$ diagnostics)
    \item What plan changes can help reduce the churn ratio? (Bootstrapping and Confidence Intervals)
\end{enumerate}

\section{Methods and Data Collection}
\subsection{Dataset Source}
The dataset, sourced from the UCI Machine Learning repository, comprises real customer data from an Iranian telecom company collected over 12 months. It includes 3,150 customer records with 13 features such as call failures, SMS frequency, complaints, subscription length, and a "churn" label indicating retention. The dataset is anonymized, with a "Customer Value" metric reflecting each customer's significance.

\subsection{Statistical Analyses}
To address the research questions, the following statistical techniques were employed:
\begin{itemize}
    \item \textbf{T-tests}: Used to compare the mean usage duration between different tariff plans.
    \item \textbf{ANOVA}: Examined differences in customer behavior across age groups.
    \item \textbf{Regression Modeling}: Evaluated predictor variables' impact on CLV.
    \item \textbf{Chi-Squared Test}: Assessed the association between customer activity levels and churn likelihood.
    \item \textbf{Bootstrapping}: Estimated confidence intervals to determine the impact of plan modifications on churn reduction.
\end{itemize}

\section{Results and Insights}
\subsection{Exploratory Data Analysis (EDA)}
\begin{itemize}
    \item \textbf{EDA1}: Only 15\% of customers churned, highlighting an imbalance requiring further investigation.
    \item \textbf{EDA2}: Customers aged 30-39 had low churn rates, whereas younger (10-19) and older (50-59) groups exhibited higher churn rates, indicating unmet needs in those demographics.
    \item \textbf{EDA3}: Right-skewed distributions suggest that customers prefer calls over texts.
    \item \textbf{EDA4}: Customers who filed complaints used services less frequently, linking dissatisfaction to lower service usage.
    \item \textbf{EDA5}: Higher churn rates among pay-as-you-go users compared to contractual plans suggest increased loyalty in structured plans.
    \item \textbf{EDA6}: Communication preferences shift with subscription length—longer terms see more SMS usage, while shorter terms favor voice calls.
\end{itemize}

\subsection{Connecting Statistical Findings to Research Questions}
\textbf{Research Question 1:} T-test results ($t = -7.4271$, $p = 1.295 \times 10^{-12}$) indicated significant differences in usage between tariff plans, suggesting enhancements in the pay-as-you-go plan, such as bonus minutes or data rollover, could improve retention.

\textbf{Research Question 2:} EDA revealed longer-term subscribers preferred SMS over calls, emphasizing the need for customized offerings.

\textbf{Research Question 3:} Chi-squared test ($\chi^2 = 781.11$, $p < 0.05$) confirmed that active customers were less likely to churn, highlighting the importance of engagement initiatives.

\textbf{Research Question 4:} ANOVA results indicated significant variance in churn rates across age groups, suggesting demographic-driven marketing strategies.

\textbf{Research Question 5:} Regression analysis showed that dynamic changes in predictor variables significantly impacted CLV accuracy.

\textbf{Research Question 6:} Bootstrapping confirmed that optimizing plans with new features could statistically reduce churn rates.

\section{Conclusion}
This study provided a statistical perspective on customer churn in the Iranian telecom sector. The findings emphasized the importance of targeted retention strategies, customer engagement, and demographic segmentation to reduce churn and enhance profitability.

\end{document}
