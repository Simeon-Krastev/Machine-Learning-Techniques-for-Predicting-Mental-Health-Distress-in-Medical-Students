# An Exploration on Medical Students’ Program Load and Mental Health Based on Mother Tongue, Employment, and Relationship Status
Simeon Krastev Master’s in Data Science, Harika Koduri Master’s in Data Science

## Section 1. Introduction
### Motivational Background
The first step in addressing issues of mental health is to understand the factors that might lead to an increased susceptibility to developing certain psychological conditions. The effect of medical study programs on their students’ mental health has been well-researched and well-documented, and stress from the medical curriculum has been shown to contribute to the risk of developing symptoms of depression, anxiety, and burnout in its students. To be able to predict, prevent, and counteract these risks, individual factors that contribute to students’ stress levels must be explored so as to design solutions that alleviate students’ workload and preoccupations and allow them to focus more freely on their chosen program of study.

In the qualitative study by Bergmann et al. (2019), medical students' experiences of academic stress and its impact on various domains of their lives were explored. The participants reported physical and mental health issues due to academic stress, such as headaches and tense necks. Balancing academic workload with extracurricular activities and part-time jobs was also a concern for some participants. Participants were motivated to pursue medical studies for personal interest, career goals, and a desire to help others. However, external pressures, such as family expectations and societal norms, were also reported. Notably, the study did not investigate certain aspects of empathy or the burnout experienced by medical students.

Bexelius et al. (2019) investigated the mental health of medical students using statistical analyses. The study found that self-reported health status, job satisfaction, and academic motivation significantly decreased during clinical courses. Female students reported significantly higher levels of depressive symptoms compared to their male counterparts. The study also found that state anxiety significantly increased during clinical courses, while trait anxiety remained unchanged. Emotional exhaustion and cynicism increased, while professional efficacy decreased during clinical courses. Patient-related activities were the most stressful, and the study involved 68 medical students who participated in the contextual activity sampling system for 1,825 assessments.

Chia et al. (2020) reported on the mental health of medical students during anatomy dissection. The study found that a majority of students experienced physical symptoms, such as fatigue, backache, and headache, during the dissection. The mean score for state anxiety was 51.01, and for trait anxiety was 46.93, indicating moderate levels of anxiety among the students.

A. Duncan's study, "The Potential Protective Effect of Hope on Students’ Experience of Perceived Stress and Burnout during Medical School," found that 18.5% of the participants reported symptoms of depression at least once during medical school, based on the CES-Depression scale. The mean score for state anxiety was 41.8, and for trait anxiety was 42.2, indicating moderate levels of anxiety. Notably, the study did not investigate certain aspects of empathy or burnout.

Halperin et al. (2021) investigated the mental health of medical students during the COVID-19 pandemic. The study found a mean score of 21.9 (SD = 9.5) on the CES-Depression scale, indicating moderate depression symptoms. The mean score on the State-Trait Anxiety Inventory scale was 43.2 (SD = 11.2), indicating moderate anxiety symptoms among medical students during the pandemic.

In a study conducted by Iorga et al. (2020), it was found that international medical students displayed mild to moderate depressive symptoms, with a mean score of 15.8 on the CES-Depression scale, and moderate anxiety levels, with a mean score of 42.1 on the State-Trait Anxiety Inventory scale. The study also highlighted the high levels of intrinsic academic motivation and empathy rating among the students. However, the study failed to report statistics related to job satisfaction, cognitive empathy or affective empathy.

Wickramasinghe et al. (2019) reported that 52% of medical students showed symptoms of depression on the CES-Depression scale, and 85% of them experienced at least one stressful life event during their undergraduate medical education. The study also found that medical students studying in English as a second language reported higher levels of depression compared to those studying in their first language.

Pokhrel et al. (2020) conducted a cross-sectional study on medical students and residents in Nepal, using various measures to assess mental health. The CES-Depression scale was used to determine depression prevalence, with results showing that 44.1% of medical students and 35.9% of medical residents experienced depression. Additionally, the State-Trait Anxiety Inventory scale was used to measure anxiety prevalence, revealing that 53.1% of medical students and 40.9% of medical residents experienced anxiety. The study also used the Maslach Burnout Inventory (MBI) to measure burnout, which found that 45.1% of medical students and 38.6% of medical residents experienced emotional exhaustion, and 30.9% of medical students and 20.5% of medical residents reported cynicism. It should be noted that the study was conducted in Nepal and used the English language.

Proietti Ergün and Ersöz Demirdağ's (2022) study focused on investigating the relationship between foreign language enjoyment, subjective well-being, and perceived stress in multilingual students. The study comprised 427 multilingual students and found a positive correlation between foreign language enjoyment and subjective well-being (r = .33, p < .001) and a negative correlation between foreign language enjoyment and perceived stress (r = -.16, p = .002).

Puranachaikere et al. (2021) conducted a study on mental health among medical students in Thailand during the COVID-19 pandemic. The study reported alarming statistics, with 40.9% of medical students rating their health as fair or poor, and 28.4% experiencing physical symptoms associated with stress. The study also used the CES-Depression scale, which revealed that 27.3% of medical students experienced mild to severe depressive symptoms. Additionally, the State-Trait Anxiety Inventory scale was used to measure anxiety symptoms, and the results showed that 37.8% of medical students experienced mild to severe anxiety symptoms. Furthermore, the Maslach Burnout Inventory (MBI) was used to measure burnout, and the findings showed that 37.4% of medical students experienced high emotional exhaustion, 37.3% experienced high cynicism, and 38.6% had low professional efficacy. Although the study did not report statistics related to job satisfaction, cognitive empathy, affective empathy, academic motivation, or empathy rating, the findings provide valuable insight into the mental health challenges faced by medical students during the pandemic.

The paper by Carrard et al. (2022) explores the relationship between medical students' empathy, mental health, and burnout. Specifically, the authors investigate whether medical students' levels of empathy are related to their levels of burnout and mental health distress. To obtain the statistical results presented in the paper, Carrard et al. conducted a cross-sectional study in which they recruited medical students from a Swiss university. The study included a total of 497 participants, and data was collected using various questionnaires, including the Jefferson Scale of Empathy, the Maslach Burnout Inventory, and the Brief Symptom Inventory.

To analyze the data, Carrard et al. used correlation and regression analyses. Correlation analyses were used to examine the relationships between empathy, burnout, and mental health distress, while regression analyses were used to determine whether empathy was a significant predictor of burnout and mental health distress, after controlling for other variables. It is important to note that the paper by Carrard et al. focuses more on the relationship between empathy, burnout, and mental health distress, rather than the relationship between other predictors and these metrics. However, the paper does report some descriptive statistics for other variables, such as age, gender, and academic performance, which may be relevant in future studies.

The findings of these studies are highly concerning and highlight the need for effective support systems and resources to help medical students cope with the stressors they face in their education and training. It is essential to recognize the mental health challenges faced by medical students and take measures to address them to ensure the well-being of future healthcare providers. By taking steps to support the mental health of medical students, we can help them develop into successful healthcare providers who can provide high-quality care to their patients.

### Current Methods
Multiple studies have explored the relationship between medical students’ mental health and their programs of study, certain aspects of the medical curriculum, personal lifestyle factors that could affect their performance in the program, and even the effect on worldwide events such as the COVID-19 pandemic on students’ mental health. These are significant factors that influence stress levels and even challenge medical students’ resilience. While extensive efforts have been made to address the increased risk of developing mental health conditions, there are multiple factors and aspects of the medical study curriculum that have yet to be explored in order to further address the possible risks to students’ mental health that these might entail. In particular, few studies have addressed the effect of pursuing a medical degree on the mental health of international students and non-native speakers of the program's language, or the students employment and relationship status.

This project means to use the data from “Medical Student Mental Health” (Sayadi, 2023), which presents information on the mental health, empathy and burnout of 886 medical students in Switzerland, collected as a data set for the paper “The relationship between medical students' empathy, mental health, and burnout: A cross-sectional study” by Carrard et al. This paper explores “[...] the relationship between the empathy dimensions, depressive symptoms, anxiety, and burnout as well as the influence of curriculum year and gender [...] to investigate how medical students' empathy is related to their mental health and burnout.” (Carrard et al., 2023); however, the data set also includes information on job and relationship status as well as the mother tongue of the students, which is not addressed in the paper by Carrard et al. These factors could be significant contributors to the increased risk of developing symptoms of stress, anxiety, and burnout, which is why it is imperative to explore their effect on students’ mental health.

### Novel Approaches
This project means to use the “Medical Student Mental Health” to explore relationships between medical students’ self-reported study hours, levels of mental health, empathy, and burnout, and sociological aspects such as their employment and relationship status, as well as the influence of their mother tongue on their stress levels. To this end, a multivariate regression model will be used to represent any connection between these factors, exploring relationships different from those analyzed in the paper by Carrard et al. In addition to mapping study hours to the prevalence of mental health conditions, whether a particular student has any sort of employment, a relationship, or a mother tongue other than French (the language of instruction in the medical program) will be incorporated as dummy variables into the regression. The multiple measures for mental health symptoms will be condensed into three separate indicators for each aspect of mental health outlined above in addition to a general indicator of mental health concern. Logistic Regression will then be used to predict the risk of developing the symptoms mentioned above given these factors, and decision tree classifiers in addition to an SVM model will finally generate a supporting measure to calculate the likelihood of a medical student developing mental health concerns.

By obtaining a better assessment on the extent to which these sociological characteristics affect the risk of developing mental health conditions during medical study programs, it will be possible to design support programs targeted at those students that present higher such risk. Furthermore, after a potential future consultation with experts in mental health, it would be possible to outline methods that cope with and improve on the symptoms and conditions attributable to the above-mentioned factors. By further examining the characteristics that increase the risk of stress, anxiety, and other mental health conditions in medical students as well as the methods to lessen their negative effect, it will be increasingly possible to provide students with the help and support they need to get relief from their stress and be able to focus better on their studies.

### Evaluating Effectiveness
This paper aims to generate models that will predict the likelihood of a medical student developing mental health concerns. This model will be evaluated by using SMOTE to balance the data, bootstrapping the observations for cross validation, and splitting data into training and testing sets to calculate statistical measures of classification effectiveness such as accuracy, precision, and recall.

To explore the relationships outlined above, this report will begin by outlining related work as well as exploring the work by Carrard et al. in the original paper at greater depth. The subsequent section will define the methodology for further analysis, including cleaning and preprocessing tasks, reducing the outcome variables to single measures of mental health concerns, presenting descriptive statistics on the data, and generating models that will predict the risk of mental health concern prevalence among the medical students that participated in the story. The results of the analysis will then be presented, alongside conclusions from the findings.

## Section 2. Related Work
The data set in question makes use of existing metrics for quantifying the prevalence of mental health symptoms in the general population. These metrics are outlined and explained in the sections below.

### Self-reported Health Status
This is a self-reported metric in which the participants rate the assessment of their own health status on a scale ranging from 1 (“Very dissatisfied”) to 5 (“Dissatisfied”).

### Psychological Distress Score
A boolean value that indicates whether the participant has sought a psychotherapist’s or a psychiatrist’s help for their health in the past.

### Job Satisfaction Score
The Job Satisfaction Psychological Scale (JSPE) is a widely used psychometric tool for measuring job satisfaction. It consists of 18 items that assess various aspects of job satisfaction, including pay, work conditions, supervision, promotion opportunities, and the overall sense of achievement. Scores on the JSPE range from 18 to 126, with higher scores indicating greater job satisfaction. The JSPE has been shown to have good reliability and validity in various studies and can be used to measure job satisfaction in different occupations and industries. It can be a valuable tool for employers and managers to assess the job satisfaction levels of their employees and develop strategies to increase job satisfaction and ultimately enhance employee engagement and retention (Ironson et al., 1989).

### Cognitive and Affective Empathy Scores
The QCAE is a self-report questionnaire that measures cognitive and affective empathy. It was developed by Reniers, Corcoran, Drake, Shryane, and Völlm (2011) and consists of 25 items that assess four different dimensions of empathy: cognitive empathy, emotional reactivity, emotional concern, and social skills. The questionnaire uses a 5-point Likert scale to rate each item, with responses ranging from "strongly disagree" to "strongly agree." The scores for each dimension of empathy are calculated by summing the relevant items and dividing by the number of items in that dimension. The range of the QCAE scale varies for each dimension, but the overall range of scores is from 25 to 125. Higher scores indicate greater levels of cognitive and affective empathy.

### Academic Motivation Scale
The Academic Motivation Scale (AMS) is a self-reported questionnaire used to measure academic motivation. It was developed by Richard Ryan and Edward Deci in the 1980s, and has since been revised. The questionnaire contains 28 items, which measure six different subscales: intrinsic motivation to know, intrinsic motivation to accomplish, intrinsic motivation to experience stimulation, identified regulation, introjected regulation, and external regulation. The subscales are typically scored on a 7-point Likert scale, ranging from 1 (not at all true) to 7 (very true) (Ryan & Deci, 2000). For this study, a 1 to 7 rating was assigned to each of the subscales, for an effective range of 6 to 42.

### JSE Empathy Rating Score
The Jefferson Scale of Empathy (JSE) has the purpose of evaluating empathy in healthcare providers who interact with patients in a clinical environment, including medical students and other individuals studying healthcare to prepare for a clinical career (Chen et al., 2019). The JSE uses a 7-point Likert scale to rate 20 items. The scale ranges from "strongly disagree" to "strongly agree", and the total score can vary from 20 to 140. A higher score reflects a greater level of empathy.

### Geneva Emotion Recognition Test
The Geneva Emotion Recognition Test (GERT) is a computerized test that measures the ability to recognize emotions in facial expressions. It was developed by Scherer and colleagues (2012) and consists of 96 color photographs of faces expressing six basic emotions (anger, disgust, fear, happiness, sadness, and surprise) and six compound emotions (e.g., happy and surprised). Participants are presented with each photograph and asked to choose the emotion that best describes the expression. The range of the GERT scale is from 0 to 96, with higher scores indicating better performance in recognizing facial expressions of emotions. For this analysis, this metric is condensed to a mean score of correct recognitions onto a range between 0 and 1.

### Center for Epidemiologic Studies Depression Scale
The CES-D scale is a self-reported questionnaire that calculates an overall score based on how often participants experienced feelings such as loneliness, sadness, hopelessness, and other similar symptoms of depression in the past seven days. This scale ranges from 0 to 60, with a higher score indicating a more significant prevalence of depression symptoms (Radloff, 1977).

### State-Trait Anxiety Inventory Scale
The State-Trait Anxiety Inventory (STAI) is a prevalent tool for evaluating both trait and state anxiety levels (Spielberger, Gorsuch, Lushene, Vagg, & Jacobs, 1983). Its applications extend to clinical settings where it is utilized for diagnosing anxiety and differentiating it from depressive disorders. It consists of a self-evaluation questionnaire aimed at assessing the extent to which participants experience various feelings and mental states. This scale ranges from 20 to 80, with higher numbers indicating a more significant prevalence of anxiety symptoms.

### Maslach Burnout Inventory
The Maslach Burnout Inventory (MBI) is a widely used psychological assessment tool that measures burnout, which is a state of emotional, mental, and physical exhaustion caused by prolonged exposure to stressors at work. The MBI consists of 22 items that assess three aspects of burnout: emotional exhaustion, depersonalization, and personal accomplishment. Respondents rate each item on a seven-point scale, ranging from 0 (never) to 6 (every day). Scores for each dimension range from 0 to 54 for emotional exhaustion, 0 to 30 for depersonalization, and 0 to 48 for personal accomplishment, with higher scores indicating greater levels of each dimension. The MBI has been widely used in research and clinical settings to identify individuals at risk of burnout and to evaluate the effectiveness of interventions aimed at reducing burnout and promoting well-being (Maslach, Jackson, & Leiter, 1996).

### Carrard et al.: The relationship between medical students’ empathy, mental health, and burnout: A cross-sectional study
This paper aims to expand the work done by Carrad et al. (2019) on the relationship between medical students’ empathy, mental health, and burnout. This study found that 13.1% of medical students reported poor or fair health status, suggesting that a small percentage of medical students are struggling with physical health during their studies. Furthermore, the study showed that 49.2% of medical students had high cognitive empathy, while 27.4% had low cognitive empathy, suggesting that almost half of the medical students in the study had a strong ability to understand and relate to the emotions of others. Additionally, the study discovered that 31.8% of medical students had high affective empathy, while 41.5% had low affective empathy. This suggests that a significant proportion of medical students may struggle with experiencing emotions related to the suffering of others. The study found that 54.5% of medical students had high academic motivation, while 21.5% had low academic motivation. This suggests that the majority of medical students are highly motivated in their academic pursuits.

Moreover, the study found that the median empathy rating for medical students was 4.2 out of 5, indicating a high level of empathy among the study participants. The prevalence of depression among medical students in the study was 44.9%. This suggests that almost half of the medical students in the study experienced symptoms of depression. The prevalence of anxiety among medical students in the study was 55.6%. This suggests that over half of the medical students in the study experienced symptoms of anxiety. The prevalence of burnout due to emotional exhaustion among medical students in the study was 37.4%. This suggests that a significant proportion of medical students in the study were experiencing burnout related to emotional exhaustion. The prevalence of burnout due to cynicism among medical students in the study was 23.3%. This suggests that a smaller proportion of medical students in the study were experiencing burnout related to cynicism. The study found that 33.1% of medical students had low professional efficacy, while 43.2% had high professional efficacy. This suggests that over a third of the medical students in the study may be struggling with feelings of competence and confidence in their professional abilities.

While the original work looks mostly at how empathy, mental health, and burnout are related in medical students, this paper aims to further explore the relationships between the individual predictors and an overall measure of mental health.

## Section 3. Methodology
### Data Cleaning and Preprocessing
The first step in this analysis is to clean and preprocess the data. This includes removing any null, empty, and duplicate values, identifying outliers and inconsistent data, as well as adjusting or modifying certain columns to make them easier to work with and interpret.

Aside from cleaning the data, the following changes were made on the original data set:

1. The “language spoken by the participant” column was modified so that the actual name of the language is displayed instead of a code for easier interpretability.
2. The columns indicating mental health symptoms were normalized to obtain a similar score between variables of varying scales.
3. Several columns indicating mental health symptoms were evaluated on a scale in which a higher value indicates lower prevalence of mental health distress. In order to reduce these outcomes to a singular measure of mental health to a single principal component as outlined below, the values in these columns were replaced with their complement (i.e., “1-value”) so that for all columns, a higher value would represent a stronger indicator of mental distress. The following columns were affected:
   - JSE Empathy Score
   - Health status
   - Cognitive empathy
   - Affective empathy
   - Academic motivation
   - Empathy rating
   - MBI - Professional Efficacy

#### Reducing Mental Health Symptoms Columns
Due to the multiple assessments of mental health conditions, column averaging was used to reduce the columns indicating the prevalence of symptoms. Four reductions were applied, aiming to obtain four different models:

1. In the first model, the following assessment columns were averaged to one single measure of mental health symptom prevalence:
   - Self-reported health status [Complement]
   - Job satisfaction [Complement]
   - Cognitive empathy [Complement]
   - Affective empathy [Complement]
   - Academic motivation [Complement]
   - Empathy rating [Complement]
   - CES-Depression scale
   - State-Trait Anxiety Inventory scale
   - MBI - Exhaustion
   - MBI - Cynicism
   - MBI - Professional Efficacy [Complement]

   It will then be assessed whether or not the data set is balanced by counting the number of students that show a higher indicator of mental health concerns as opposed to those that do not. Should one count prove to be much greater than the other, the SMOTE technique will be used to balance the data set before continuing.

2. In the second model, the following assessment columns were averaged to one single measure of empathy:
   - Cognitive empathy
   - Affective empathy
   - Empathy rating

3. In the third model, the following assessment columns were averaged to a measure of mental health distress:
   - CES-Depression scale
   - State-Trait Anxiety Inventory scale

4. In the fourth model, the following assessment columns were averaged to one single measure of burnout:
   - Maslach Burnout Inventory - Exhaustion
   - Maslach Burnout Inventory - Cynicism
   - Maslach Burnout Inventory - Professional Efficacy [Complement]
   - Academic motivation [Complement]

### Descriptive Analysis
For each of the four models outlined above, their respective data frames were summarized to explore the distribution of variables and the range of the averaged metrics. Furthermore, a correlation matrix was created for each data frame to examine any significant relationships among the variables.

### Linear Regression Models
Multivariate linear regression models were generated for each of the four indicators as outlined above to obtain a preliminary idea of how the predictors affect the outcome and explore whether a linear relationship exists between the dependent and independent variables.

### Logistic Regression Classifiers
Logistic regression models were generated by categorizing the indicator outcome variables in two classes, below and above a threshold of 0.50, that could predict a low or high risk of developing mental health concerns during the participants’ medical studies.

### Decision Tree Classifiers
Additional Decision Tree models were generated for each of the four models to supplement the logistic regression classifiers and to compare classification performance, in addition to identifying critical splits.

### SVM Model
Grid searches were used to find out the best hyperparameters for a Support Vector Machine model that will classify students based on their risk to develop mental health concerns during their medical studies, evidenced by an averaged indicator value of mental health above 0.50.

### Model Evaluation
For the logistic regression models, SMOTE was used to balance the data, and cross-validation through bootstrapping was applied to increase the number of samples for each model. Furthermore, each set of data was split into training (80%) and testing (20%) sets. The models generated thereafter were then evaluated by examining the accuracy, precision, recall, and F1-score statistics based on model prediction of the test data. The same was done for the Decision Tree Classifiers and SVM models, generating a classification report showing statistics on prediction precision, recall, and accuracy.

## Section 4. Preliminary Project Results and Discussions
### Overall Mental Health Symptom Prevalence
#### Descriptive Analysis
The reduced indicator of overall mental health symptom prevalence produced a normalized variable with a range of 0.09 to 0.72 among the observations, with higher values indicating higher levels of mental health distress. This indicator seems to have the highest correlation of 0.22 to the “psyt” predictor indicating whether or not the participant has sought professional help for mental health concerns in the past. This shows a moderate relationship between the two characteristics. The indicator also showed a moderate negative correlation of -0.21 with the year of study, supporting the findings of Carrard et al. that there is a lower prevalence of mental health concerns among students in later years of study (2019).

#### Regression Model
A low R-squared value of 0.105 and high P-values indicates that a linear model is not an appropriate fit for the data.

#### Logistic Regression Classifier
A logistic regression model was generated with the following coefficients:

```text
age : 0.052540623615196395
year : -0.18215763894997672
part : -0.026031709739531214
job : 0.08771790518656292
stud_h : 0.025537936674024483
psyt : 1.340122735633607
foreignlang : 0.41554759822661225
sex_Man : 2.2298730486648255
sex_Non-binary : 1.0176296681316104
sex_Woman : 1.7894274386558955
```
This model classifies the outcome of the predictors above based on the probability that the
‘ov_mhs_preval’ metric will result in a value of 0.50 or more. This would indicate a moderate to strong risk of
mental health distress. Gender and year of study are shown to be a significant predictor of overall mental health, as
well as the mother tongue; employment and relationship status do not seem to have so great an effect on the risk of
developing mental health concerns. As expected, the ‘psyt’ variable is a significant indicator of overall mental health
symptom prevalence.
The model produced the following measures of accuracy:
```text
Accuracy: 0.6123595505617978
Precision: 0.6470588235294118
Recall: 0.5851063829787234
F1-score: 0.6145251396648045
```
And the following confusion matrix:
| precision | recall | f1-score | support |
|-----------|--------|----------|---------|
| 0         | 0.58   | 0.64     | 0.61    | 84      |
| 1         | 0.65   | 0.59     | 0.61    | 94      |
| accuracy  |        |          | 0.61    | 178     |
| macro avg | 0.61   | 0.61     | 0.61    | 178     |
| weighted avg | 0.62 | 0.61   | 0.61    | 178     |

#### Decision Tree Classifier
The decision tree classifier produced a model that returned the following measures of accuracy,
outperforming the logistic regression classifier:
Accuracy: 0.8033707865168539
| precision | recall | f1-score | support |
|-----------|--------|----------|---------|
| 0         | 0.76   | 0.86     | 0.80    | 84      |
| 1         | 0.86   | 0.76     | 0.80    | 94      |
| accuracy  |        |          | 0.80    | 178     |
| macro avg | 0.81   | 0.81     | 0.80    | 178     |
| weighted avg | 0.81 | 0.80   | 0.80    | 178     |

SVM Classifier
Using a grid search to find the best hyperparameters for the SVM model resulted in the following
parameters:
```text
Best hyperparameters: {'C': 100, 'gamma': 0.1, 'kernel': 'rbf'}
C: 100
break_ties: False
cache_size: 200
class_weight: None
coef0: 0.0
decision_function_shape: ovr
degree: 3
gamma: 0.1
kernel: rbf
max_iter: -1
probability: False
random_state: None
shrinking: True
tol: 0.001
verbose: False
```
Using these parameters, a SVM model was generated. This model was used to predict the outcome of
overall mental health symptom prevalence based on the predictors, resulting in the following evaluation:
Accuracy: 0.8314606741573034
| precision | recall | f1-score | support |
|-----------|--------|----------|---------|
| 0         | 0.81   | 0.85     | 0.83    | 84      |
| 1         | 0.86   | 0.82     | 0.84    | 94      |
| accuracy  |        |          | 0.83    | 178     |
| macro avg | 0.83   | 0.83     | 0.83    | 178     |
| weighted avg | 0.83 | 0.83   | 0.83    | 178     |

The model predicts an overall mental health concerns indicator with an accuracy greater than the decision
tree classifier.
### Empathy Indicator
#### Descriptive Analysis
The reduced empathy indicator produced a normalized variable with a range of 0.28 to 0.89 among the
observations, with higher values indicating higher levels of empathy among the participants. This indicator seems to
have the highest correlation of -0.12 to the “foreignlang” predictor, indicating whether or not the participant speaks a
mother tongue other than French, the language of instruction of the medical program in which the participants study.
This shows a weak relationship between the two characteristics. The indicator also showed a positive correlation of
0.11 with the year of study, supporting the findings of Carrard et al. that more advanced students in the medical
curriculum report slightly higher cognitive and affective empathy than first-year students (2019).
#### Regression Model
The following OLS regression model was generated:
A low R-squared value of 0.154 and high P-values indicates that a linear model is not an appropriate fit for
the data.
#### Logistic Regression Classifier
A logistic regression model was generated with the following coefficients:
```text
age : -0.0610902221687773
year : 0.3460577000292258
stud_h : 0.018150976814688878
foreignlang : 0.3623696240291945
part : 0.7573655960184604
job : 0.3675862597274941
sex_Man : 1.5814328922973937
sex_Non-binary : 1.530364398449996
sex_Woman : 3.3157515365601204
```
This model classifies the outcome of the predictors above based on the probability that the ‘emp_ind’
metric will result in a value of 0.50 or more. This would indicate a moderate to strong levels of empathy among the
participants. The predictor “year” seems to have a significant positive influence on empathy levels. Male medical
students show lower levels of empathy than female or non-binary students. Employment status, relationship status,
and age show lower levels of influence on empathy.
The model produced the following measures of accuracy:
```text
Accuracy: 0.7808988764044944
Precision: 0.7473684210526316
Recall: 0.8255813953488372
F1-score: 0.7845303867403315
```
#### Decision Tree Classifier
The decision tree classifier produced a model that returned the following measures of accuracy,
outperforming the logistic regression classifier:
Best parameters: {'max_depth': 21}
Accuracy: 0.9213483146067416
| precision | recall | f1-score | support |
|-----------|--------|----------|---------|
| 0         | 0.94   | 0.90     | 0.92    | 92      |
| 1         | 0.90   | 0.94     | 0.92    | 86      |
| accuracy  |        |          | 0.92    | 178     |
| macro avg | 0.92   | 0.92     | 0.92    | 178     |
| weighted avg | 0.92 | 0.92   | 0.92    | 178     |

#### SVM Classifier
Using a grid search to find the best hyperparameters for the SVM model resulted in the following
parameters:
```text
Best hyperparameters: {'C': 100, 'gamma': 0.1, 'kernel': 'rbf'}
C: 100
break_ties: False
cache_size: 200
class_weight: None
coef0: 0.0
decision_function_shape: ovr
degree: 3
gamma: 0.1
kernel: rbf
max_iter: -1
probability: False
random_state: None
shrinking: True
tol: 0.001
verbose: False
```
Using these parameters, a SVM model was generated. This model was used to predict the outcome of
empathy based on the predictors, resulting in the following evaluation:
Accuracy: 0.9269662921348315
| precision | recall | f1-score | support |
|-----------|--------|----------|---------|
| 0         | 0.93   | 0.92     | 0.93    | 92      |
| 1         | 0.92   | 0.93     | 0.92    | 86      |
| accuracy  |        |          | 0.93    | 178     |
| macro avg | 0.93   | 0.93     | 0.93    | 178     |
| weighted avg | 0.93 | 0.93   | 0.93    | 178     |

The model predicts an empathy indicator with an accuracy greater than the decision tree classifier.
### Mental Health Distress Indicator
#### Descriptive Analysis
The reduced mental health distress indicator produced a normalized variable with a range of 0.00 to 0.99
among the observations, with higher levels indicating a higher prevalence of anxiety and depression symptoms
among the participants. This indicator seems to have the highest correlation of -0.36 to the “health” predictor,
indicating a self-reported measure of health ranging from 1 (weakest) to 5 (strongest). This shows a moderate
negative correlation between the self-reported measure of health and the prevalence of anxiety and depression
symptoms as represented by the principal component. The indicator also showed a positive correlation of 0.30 with
the variable ‘psyt’, indicating whether or not the student has sought professional help for mental health concerns in
the past. A negative correlation of -0.22 with the year of study supports the findings of Carrard et al. (2019) in which
first-year students show higher levels of anxiety and depression as opposed to more advanced students.
#### Regression Model
The following OLS regression model was generated:
A low R-squared value of 0.285 and high P-values indicates that a linear model is not an appropriate fit for
the data.
Logistic Regression Classifier
A logistic regression model was generated with the following coefficients:
```text
age : -0.00975821829735036
year : -0.16714969089841794
stud_h : -0.0023646225781372805
psyt : 0.41773688396936304
foreignlang : -0.3716607687103845
part : -0.7131640323133914
job : -0.8106859757323814
health : -0.8110263864730923
sex_Man : -3.113139360256602
sex_Non-binary : -1.3846822151698122
sex_Woman : -1.7489527518939434
```
This model classifies the outcome of the predictors above based on the probability that the ‘mh_ind’ metric
will result in a value of 50 or more. This would indicate a moderate to strong levels of mental health distress among
the participants. As expected, the predictors ‘psyt’ and ‘health’ seem to have a large effect on the prevalence of
anxiety or depression among the participants. In this model, relationship and employment status seem to also have a
moderate influence on mental health distress. Male medical students show lower levels of mental health distress than
female students, but it is the non-binary students that seem to show the lowest prevalence of depression and anxiety.
The model produced the following measures of accuracy:
```text
Accuracy: 0.7415730337078652
Precision: 0.75
Recall: 0.6976744186046512
F1-score: 0.7228915662650603
```
#### Decision Tree Classifier
The decision tree classifier produced a model that returned the following measures of accuracy,
outperforming the logistic regression classifier:
Accuracy: 0.8539325842696629
| precision | recall | f1-score | support |
|-----------|--------|----------|---------|
| 0         | 0.86   | 0.86     | 0.86    | 92      |
| 1         | 0.85   | 0.85     | 0.85    | 86      |
| accuracy  |        |          | 0.85    | 178     |
| macro avg | 0.85   | 0.85     | 0.85    | 178     |
| weighted avg | 0.85 | 0.85   | 0.85    | 178     |

#### SVM Classifier
Using a grid search to find the best hyperparameters for the SVM model resulted in the following
parameters:
```text
Best hyperparameters: {'C': 100, 'gamma': 0.1, 'kernel': 'rbf'}
C: 100
break_ties: False
cache_size: 200
class_weight: None
coef0: 0.0
decision_function_shape: ovr
degree: 3
gamma: 0.1
kernel: rbf
max_iter: -1
probability: False
random_state: None
shrinking: True
tol: 0.001
verbose: False
```
Using these parameters, a SVM model was generated. This model was used to predict the outcome of
empathy based on the predictors, resulting in the following evaluation:
Accuracy: 0.8146067415730337
| precision | recall | f1-score | support |
|-----------|--------|----------|---------|
| 0         | 0.82   | 0.83     | 0.82    | 92      |
| 1         | 0.81   | 0.80     | 0.81    | 86      |
| accuracy  |        |          | 0.81    | 178     |
| macro avg | 0.81   | 0.81     | 0.81    | 178     |
| weighted avg | 0.81 | 0.81   | 0.81    | 178     |

The model predicts a mental health distress indicator with an accuracy lower than the decision tree
classifier.
### Burnout Indicator
#### Descriptive Analysis
The reduced mental health indicator produced a normalized variable with a range of 0.05 to 0.86 among the
observations, with higher levels indicating a higher prevalence of burnout symptoms among the participants. This
indicator seems to have the highest correlation of -0.05 to the “year” predictor. This shows a weak negative
correlation between year of study and the burnout indicator as represented by the averaged metric. The indicator did
not show any further significant correlations to the remaining predictors.
#### Regression Model
The following OLS regression model was generated:
A very low R-squared value of 0.023 and high P-values indicates that a linear model is not an appropriate
fit for the data.
#### Logistic Regression Classifier
A logistic regression model was generated with the following coefficients:
```text
age : -0.09645618178939863
year : 0.08837194880934997
stud_h : -0.002525163757227461
foreignlang : -0.9833850274044306
part : -0.8555976918111883
job : -0.3810041866562519
sex_Man : -3.045981169230055
sex_Non-binary : -1.2222956272853072
sex_Woman : -2.1517369060133578
```
This model classifies the outcome of the predictors above based on the probability that the ‘burn_ind’
metric will result in a value of 0.50 or more. This would indicate moderate levels of burnout. In this model, the
biggest influence on burnout seems to be gender. Mother tongue is also a significant factor for burnout.
The model produced the following measures of accuracy:
```text
Accuracy: 0.6910112359550562
Precision: 0.6891891891891891
Recall: 0.6144578313253012
F1-score: 0.6496815286624203
```
#### Decision Tree Classifier
The decision tree classifier produced a model that returned the following measures of accuracy, outperforming the
logistic regression classifier:
Accuracy: 0.8651685393258427
| precision | recall | f1-score | support |
|-----------|--------|----------|---------|
| 0         | 0.87   | 0.87     | 0.87    | 95      |
| 1         | 0.86   | 0.86     | 0.86    | 83      |
| accuracy  |        |          | 0.87    | 178     |
| macro avg | 0.86   | 0.86     | 0.86    | 178     |
| weighted avg | 0.87 | 0.87   | 0.87    | 178     |

#### SVM Classifier
Using a grid search to find the best hyperparameters for the SVM model resulted in the following
parameters:
```text
Best hyperparameters: {'C': 100, 'gamma': 0.1, 'kernel': 'rbf'}
C: 100
break_ties: False
cache_size: 200
class_weight: None
coef0: 0.0
decision_function_shape: ovr
degree: 3
gamma: 0.1
kernel: rbf
max_iter: -1
probability: False
random_state: None
shrinking: True
tol: 0.001
verbose: False
```
Using these parameters, a SVM model was generated. This model was used to predict the outcome of
empathy based on the predictors, resulting in the following evaluation:
Accuracy: 0.8539325842696629
| precision | recall | f1-score | support |
|-----------|--------|----------|---------|
| 0         | 0.88   | 0.84     | 0.86    | 95      |
| 1         | 0.83   | 0.87     | 0.85    | 83      |
| accuracy  |        |          | 0.85    | 178     |
| macro avg | 0.85   | 0.85     | 0.85    | 178     |
| weighted avg | 0.86 | 0.85   | 0.85    | 178     |

The model predicts a burnout indicator, albeit with lesser accuracy than the decision tree classifier.
## Section 5. Conclusions
The findings of the study suggest that gender plays a role in the likelihood of developing
mental health concerns among university students, with female students being less likely to experience such issues
than male students. The year of study emerged as a significant predictor of empathy levels, indicating that as
students progress through their academic journey, they may become more attuned to the emotions and needs of
others. On the other hand, the year of study was also found to be a negative predictor of mental health distress,
suggesting that as students advance through their program, they may be at a higher risk of experiencing mental
health challenges. Age was found to be a significant negative predictor of burnout, indicating that older students
may be less likely to experience burnout compared to their younger counterparts. Interestingly, factors such as
relationship status, language spoken, and employment status were not found to be significant predictors of mental
health outcomes among medical students.
## Reference List
Bergmann, C., Muth, T., & Loerbroks, A. (2019). Medical students’ perceptions of stress due to academic studies
and its interrelationships with other domains of life: a qualitative study. Medical Education Online, 24(1),
1603526. https://doi.org/10.1080/10872981.2019.1603526

Bexelius, T., Lachmann, H., Järnbert-Pettersson, H., Kalén, S., Möller, R., & Ponzer, S. (2019). Stress among
medical students during clinical courses: a longitudinal study using contextual activity sampling system.
International Journal of Medical Education, 10, 68–74. https://doi.org/10.5116/ijme.5c94.9391
Carrard, V., Bourquin, C., Berney, S., Schlegel, K., Gaume, J., Bart, P.-A., Preisig, M., Schmid Mast, M., & Berney,

A. (2022). The relationship between medical students’ empathy, mental health, and burnout: A
cross-sectional study. Medical Teacher, 44(12), 1392–1399.
https://doi.org/10.1080/0142159x.2022.2098708

Chen, Y., Yang, K., Jing, T., Huang, Y., & Li, L. (2019). Effects of team-based learning on perceived teamwork and
empathy among nursing students. Advances in Health Sciences Education, 24(1), 155-164.
https://doi.org/10.1007/s10459-018-9839-9

Chia, T. I., Oyeniran, O. I., Ajagbe, A. O., Onigbinde, O. A., & Oraebosi, M. I. (2020). The symptoms and stress
experienced by medical students in anatomy dissection halls. Journal of Taibah University Medical
Sciences, 15(1), 8–13. https://doi.org/10.1016/j.jtumed.2020.01.001

Duncan, A. (2020). The Potential Protective Effect of Hope on Students’ Experience of Perceived Stress and
Burnout during Medical School. The Permanente Journal, 24(5). https://doi.org/10.7812/tpp/19.240
Dyrbye, L. N., Sciolla, A. F., Dekhtyar, M., Rajasekaran, S., Allgood, J. A., Rea, M., Knight, A. P., Haywood, A.,

Smith, S., & Stephens, M. B. (2019). Medical School Strategies to Address Student Well-Being. Academic
Medicine, 94(6), 861–868. https://doi.org/10.1097/acm.0000000000002611

Halperin, S. J., Henderson, M. N., Prenner, S., & Grauer, J. N. (2021). Prevalence of Anxiety and Depression
Among Medical Students During the Covid-19 Pandemic: A Cross-Sectional Study. Journal of Medical
Education and Curricular Development, 8, 238212052199115. https://doi.org/10.1177/2382120521991150

Iorga, M., Soponaru, C., Muraru, I.-D., Socolov, S., & Petrariu, F.-D. (2020, June 22). Factors Associated with
Acculturative Stress among International Medical Students. BioMed Research International.
https://www.hindawi.com/journals/bmri/2020/2564725/

Ironson, G. H., Smith, P. C., Brannick, M. T., Gibson, W. M., & Paul, K. B. (1989). Construction of a job in general
scale: A comparison of global, composite, and specific measures. Journal of Applied Psychology, 74(2),
193-200. doi:10.1037/0021-9010.74.2.193

Jordan, R. K., Shah, S. S., Desai, H., Tripi, J., Mitchell, A., & Worth, R. G. (2020). Variation of stress levels,
burnout, and resilience throughout the academic year in first-year medical students. PLOS ONE, 15(10),
e0240667. https://doi.org/10.1371/journal.pone.0240667

Maslach, C., Jackson, S. E., & Leiter, M. P. (1981). Maslach Burnout Inventory. Journal of Occupational
Psychology, 52(2), 131-136. https://doi.org/10.1002/job.4030020205

Neufeld, A., & Malin, G. (2021). How medical students cope with stress: a cross-sectional look at strategies and
their sociodemographic antecedents. BMC Medical Education, 21(1).
https://doi.org/10.1186/s12909-021-02734-4

Pokhrel, N. B., Khadayat, R., & Tulachan, P. (2020). Depression, anxiety, and burnout among medical students and
residents of a medical school in Nepal: a cross-sectional study. BMC Psychiatry, 20(1).
https://doi.org/10.1186/s12888-020-02645-6

Proietti Ergün, A. L., & Ersöz Demirdağ, H. (2022). The relation between foreign language enjoyment, subjective
well-being, and perceived stress in multilingual students. Journal of Multilingual and Multicultural
Development, 1–13. https://doi.org/10.1080/01434632.2022.2057504

Puranachaikere, T., Hataiyusuk, S., Anupansupsai, R., In-iw, S., Saisavoey, N., Techapanuwat, T., Arunrodpanya, F.,
Charonpongsuntorn, C., Wiwattanaworaset, P., Siripongpan, A., Pruttithavorn, W., Wonglertwisawakorn,
C., Pojanapotha, P., Rueangrong, B., Pattrakornkul, N., Piyawattanametha, N., Piyawattanametha, S., &
Ratanapichayachai, D. (2021). Stress and associated factors with received and needed support in medical
students during COVID-19 pandemic: a multicenter study. Korean Journal of Medical Education, 33(3),
203–213. https://doi.org/10.3946/kjme.2021.200

Reniers, R. L., Corcoran, R., Drake, R., Shryane, N. M., & Völlm, B. A. (2011). The QCAE: A questionnaire of
cognitive and affective empathy. Journal of personality assessment, 93(1), 84-95. doi:
10.1080/00223891.2010.528485

Radloff, L. S. (1977). The CES-D scale: A self report depression scale for research in the general population.
Applied Psychological Measurements, 1, 385-401.

Ryan, R. M., & Deci, E. L. (2000). Self-determination theory and the facilitation of intrinsic motivation, social
development, and well-being. American Psychologist, 55(1), 68-78.

Sayadi, F. (2023, January 25). Medical Student Mental Health. Kaggle. Retrieved February 10, 2023, from
https://www.kaggle.com/datasets/thedevastator/medical-student-mental-health

Scherer, K. R., Clark-Polner, E., & Mortillaro, M. (2012). In the eye of the beholder? Universality and cultural
specificity in the expression and perception of emotion. International Journal of Psychology, 47(6),
469-480. doi: 10.1080/00207594.2012.676864

Spielberger, C. D., Gorsuch, R. L., Lushene, R., Vagg, P. R., & Jacobs, G. A. (1983). Manual for the State-Trait
Anxiety Inventory. Palo Alto, CA: Consulting Psychologists Press.

Steiner-Hofbauer, V., & Holzinger, A. (2020). How to Cope with the Challenges of Medical Education? Stress,

Depression, and Coping in Undergraduate Medical Students. Academic Psychiatry, 44(4), 380–387.
https://doi.org/10.1007/s40596-020-01193-1

Wickramasinghe, D. P., Almeida, I. S., & Samarasekera, D. N. (2019). Depression and stressful life events among
medical students during undergraduate career: Findings from a medical school in South Asia. The Asia

Pacific Scholar, 4(1), 42–47. https://doi.org/10.29060/taps.2019-4-1/oa2025
