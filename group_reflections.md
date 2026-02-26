# Group3 Project1 Reflections
## Jing Chen

Our team had clear division,smooth collaboration and communication,making this a very pleasant group project.Everyone took responsibility and actively joined in topic selection,material searching and coding,and we finished this complete project report.  
The innovation of this project is that we fully considered the seasonal climate characteristics.By comparing differences across four seasons,we revealed the main climatic factors driving extreme temperatures in different seasons,supporting more accurate judgments of regional climate differences.  
However, the project still has some limitations:  

1.**The definition of extreme temperature is still not rigorous enough.** When screening extreme temperatures in data preprocessing,we only roughly selected outliers beyond the 95% confidence interval,without considering that some of these values may lie within the human thermal comfort range.  

2.**The core objective was described too generally.** In the future, we should better target existing research gaps and further explore the value of our results for social decision-making — for example,how crops respond to the combined effects of extreme temperatures and key climatic factors in agriculture.  

3.**The final result is not clear in initial planning.** The full research path should be planned more carefully at the initial stage for a clearer overall design.

##Yuqing Liu

In the three weeks of completing the project, I think everyone in our team has a team spirit, does their own duties, actively participates in every discussion, has a good division of labour and time conditioning, and distributes the whole work process evenly during this period. I think it is a very pleasant project cooperation experience. 

At the beginning of the project, after getting the data set, we confirmed the continuation of exploration with the theme of extreme temperature through data reading. Then, we defined the extreme temperature in the confidence interval and divided the data into four seasons based on time. Through EDA and visualisation, we explored the main driving factors of extreme temperature in each season. It was found that the driving factors of temperature in different seasons showed structural changes, and the temperature change mechanisms were different. Therefore, the periodic model in years cannot be used to analyse the temperature. 

However, at the same time, the project is still lacking. First of all, I think the results and conclusions of our project are not compact enough. Because the data is divided by season, the characteristics of each data set cannot be summarised in a general way. If there is a chance, I think we can analyse the temperature in detail for a certain season, or compare two seasons with opposite trends (for example, in spring and winter, the correlation of solar radiation is reversed). 

Moreover, I don't think the definition of extreme temperature is rigourous enough. In the project, we use the confidence interval to define extreme temperature, but do not fully take into account the differences in the characteristics of each season. Therefore, when doing autumn analysis, it is found that the large temperature difference affects the amount of extreme temperature data. In the future, we should consult more literature and methods when making definitions, and make a more rigourous analysis of different situations.

##Haoran Lin
Overall, the project tackles a relevant and well-defined question. Using the CESM LENS ensemble to study seasonal drivers of extreme temperatures is an appropriate choice because it reduces single-year noise and gives enough samples to examine seasonal patterns. Focusing on seasonality rather than a single annual model is also practically useful, for example, when designing seasonal forecasting or risk management strategies.
Methodologically, the workflow is straightforward and effective. Grouping by season, flagging seasonal extremes, computing correlation matrices, and validating with boxplots provides clear descriptive evidence about which variables are associated with extremes in each season. These visual and statistical summaries help us identify promising candidate mechanisms for further study.
That said, there are clear limitations to be addressed. First, correlation does not imply causation. We should be careful to frame our findings as associations and, where possible, support them with causal arguments or external evidence. Second, multicollinearity can distort interpretation; while obvious redundancies were removed, a more systematic presentation of collinearity diagnostics and how they affect results would strengthen the analysis.
The winter result — that circulation matters more than local radiation — aligns with literature, but it would be more convincing if supplemented with direct circulation indices (for example, NAO, blocking frequency, or composite maps of wind anomalies). Also, the choice of extreme threshold (seasonal 95%) affects sample size and composition; performing sensitivity checks with alternative thresholds would test how robust our conclusions are.
From a presentation standpoint, add sample sizes and significance markers to the key plots so the audience can quickly assess robustness. In short, this project is solid and well-motivated. With a few focused additions — causal framing, collinearity diagnostics, sensitivity analyses, and direct circulation metrics — the work will move from a strong descriptive study toward a more explanatory and policy-relevant contribution.
