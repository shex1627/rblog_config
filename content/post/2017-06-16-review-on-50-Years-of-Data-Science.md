---
layout: post
title: review on 50 Years of Data Science
category: Review
tags: 
keywords: 
---

1.I am happy to read about some history of statistics and the development of data analysis(at least in the academia setting). 
And I learn that sometimes old papers(decades ago) could be an important insight for solving some contemporary problems or giving new directions, such as John Turkey’s paper which proposes the idea of “data analysis” as an extension to traditional statistics.
 
2.Seeing the effectiveness of the “Common Task Framework” in the development of various research, I think a potential direction of 
my Education research could be finding a “good tutoring/teaching practice/research” framework. 
 
Common Task Framework Definition(from the article)

>(a) A publicly available training dataset involving, for each observation, a list of (possibly many) feature measurements, and a 
class label for that observation.   
(b) A set of enrolled competitors whose common task is to infer a class prediction rule from the training data.   
(c) A scoring referee, to which competitors can submit their prediction rule. The referee runs the prediction rule against a testing dataset 
which is sequestered behind a Chinese wall. The referee objectively and automatically reports the score (prediction accuracy) achieved 
by the submitted rule.
 
3.cross-study analysis + cross-workflow analysis
Cross-study analysis: congregate data and model pertaining to a similar/same problem, then use the model on the aggregated data and 
compare model effectiveness.
 
Cross-workflow analysis: use the same dataset but changes the procedures used in the analysis process such as sampling methods, cleaning methodology, dimension reduction and etc.
 
 
4.simple yet powerful algorithm development(not marginal progress), this insight could be helpful when I am doing real data analysis. 
#even though sometimes marginal progress could produce massive result
 
5.Reading different reviews, I see different perspectives. More or less people want to include their line of work into this category, 
also provides their own take on some of Dohono’s arguments.  

1. Donoho’s more ideal/academic research:  
The science of data science(like the research department of a school that I proposed)
 
2. Sean Owen’s emphasis on data engineering:  

>However, a team with only these skills would struggle to create a real live production anything. It’s one thing to create an excellent fraud detection model in R, and quite another to build:
Fault-tolerant ingest of live data at scale that could represent fraudulent actions
Real-time computation of features based on the data stream
Serialization, versioning and management of a fraud detection model
Real-time prediction of fraud based on computed features at scale
Learning over all historical data
Incremental update of the production model in near-real-time
Monitoring, testing, productionization of all of the above
And in the end, in industry, any predictive model of actual value is going to be productionized, and need to accomplish one or more of the above. Far from a mere detail, it’s 80+% of the work I see people whose job title contains the string “Data Scientist” actually doing.”
 
>I would argue that Software Engineering remains as big a part, and can’t be written out of the Data Science story.”
 
3. Norm Matloff’s small adding in parallel computing 
“Donoho doesn’t cover this point about computation (nor, it seems, do most data science curricula), limiting himself to programming languages and libraries.” 
 
4. William brigg’s philosophy of dealing with uncertainty  
>They are all branches of probability, which is to say the understanding and sometime quantification of uncertainty. Probability itself is an extension of logic.
