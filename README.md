# predicting-opioid-misuse
Predicting opioid misuse using the National Survey on Drug Use and Health. 

Objective. To study the correlation between opioid dependence and marijuana use and identify actionable improvements to opioid risk assessment.

Data & Methods. Labeled data sets were created from the 2016 National Survey on Drug Use and Health (NSDUH) and the eICU Collaborative Research Database (eICU). Multilayer perceptron (MLP) networks were trained and tested with the two data sets to compare the merit of the survey and medical data.

Results. While the prevalence of opioid dependence is only roughly 1%, the classifiers trained with survey data can accurately predict the subjects at risk for opioid dependence (sensitivity = .71, specificity = .80, AUC = .81) with marijuana use history.

Conclusion. The results indicate that supervised machine learning can be used to predict opioid dependence through demographic, socioeconomic, and behavioral features. The output indicates that having ever used marijuana (ever-use), a variable absent from eICU data and the Opioid Risk Tool, is important for predicting opioid dependence, highlighting gaps in medical data currently collected. The researchers propose several courses of action for the improvement of opioid risk assessment.
