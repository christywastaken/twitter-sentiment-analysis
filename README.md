# Tweet Sentiment Analysis: Exploring Temporal Patterns

This project is a short exploratory data analysis (EDA) that investigates how the sentiment of tweets changes over different periods of time, such as days, weeks, and months. The goal of this project is to gain insights into how tweet sentiment varies over time and potentially identify any interesting patterns or trends.



### Prerequisites

To run this project, you will need the following Python packages:

- transformers
- scipy
- torch torchvision 
- matplotlib
- tdqm
- seaborn
- scikit-posthocs
- twitscrape



### Conclusions 

Our analysis found a significant shift in sentiment between tweets created between 4am and 6am, with an increase in positivity and a decrease in negativity. This was evidenced by the statistically significant differences in p-values for both positive and negative sentiments during these hours.



### Further Work

To build on this analysis, we recommend investigating the following areas:

<b>Temporal Analysis</b>: Explore whether the increase in positive sentiment between 3am and 5am is consistent across different years, especially considering the unusual circumstances of 2020 due to COVID and lockdown restrictions.

<b>Geographical Analysis</b>: Examine if the observed change in sentiment occurs in other locations outside of Newcastle-Upon-Tyne.

<b>Tweet Content Analysis</b>: Delve into the content of the tweets themselves to gain insights into the factors driving the significant shift in sentiment between 3am and 5am. Consider the possibility that a small number of highly active positive users may be influencing the data.

<b>Lockdown Impact</b>: Assess the impact of COVID-related lockdown restrictions on tweet sentiment by comparing data from different weeks/months and years.

<b>Daily and Weekly Patterns</b>: Investigate the subtle, gradual changes in sentiment throughout the day and week, and explore potential links to events or timings such as lunchtime, dinnertime, and weekends. This may be more evident in non-COVID years when people have more consistent routines.
By addressing these areas, we can gain a deeper understanding of the factors influencing tweet sentiment and how it changes over time and across different contexts.



### Acknowledgements

This project uses TimeLMs for sentiment analysis. The original work can be found here:

Loureiro, D., Barbieri, F., Neves, L., Espinosa Anke, L., & Camacho-collados, J. (2022). TimeLMs: Diachronic Language Models from Twitter. In Proceedings of the 60th Annual Meeting of the Association for Computational Linguistics: System Demonstrations (pp. 251-260). Association for Computational Linguistics. https://aclanthology.org/2022.acl-demo.25



