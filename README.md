# Sleep_disorder_prediction
In this study, we delve into the critical realm of sleep disorder prediction, harnessing a dataset 
from Kaggle comprising 374 observations spanning 13 variables. 
Our endeavour aims to unravel the intricate interplay between lifestyle factors and sleep 
disorders. Central to our pursuit is the pressing need to underscore the importance of early 
detection, given the often overlooked yet profound ramifications of sleep disorders on overall 
well-being and productivity.
The genesis of this project stems from an intriguing query posed by an insurance company 
regarding the potential influence of sleep disorders on policy premiums. Amidst the quest for 
suitable datasets across various platforms, the discovery of this Kaggle dataset seized my 
attention, prompting a deep dive into this pertinent subject matter. Thus, our study not only 
sheds light on the nexus between sleep disorders and insurance policies but also underscores 
their broader societal implications.
We begin by pre-processing the data and conducting exploratory data analysis (EDA) to 
elucidate the relationships between various variables and sleep disorders. Based on our 
findings, we opt for logistic regression as it aligns with our goal of predicting the presence of 
sleep disorders. Employing stepwise AIC technique for model selection and addressing 
multicollinearity using VIF, we derive our final model. Notably, variable selection is rigorously 
addressed throughout our analysis to ensure the model's robustness and interpretability using 
Pearson's chi-square and Goodman-Kruskal gamma.
With a threshold probability of 0.5 to classify individuals as having a sleep disorder, our 
confusion matrix validation on testing data demonstrates an approximate 94% accuracy. 
Moreover, cross-validation on a randomly selected sample of 10 individuals achieves a perfect 
100% accuracy. Following this, we've developed an HTML form for straightforward input of 
individual data, providing both probabilities of sleep disorder affliction and a diagnosis of sleep 
disorder.
Our conclusion emphasizes the criticality of early detection and highlights the practical value 
of our predictive model in enabling timely intervention. This model not only assists the medical 
industry in delivering personalized treatment but also offers various other benefits.
