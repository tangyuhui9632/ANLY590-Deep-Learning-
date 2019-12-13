# ANLY 590 Final Project
##### By Yao Huang, Yuhui Tang, Xuechun Wang, Xinyu Zhang

## Introduction

Essay is used to convey a limited or personal point of view with regard to a domain specific topic. It is a common and important form of communication for the purpose of education to evaluate the perspectives and learning outcomes of students. However, it is not only time-consuming but also subjective. This leads to long time waiting for feedbacks for students and potential unfair assessment based on graders’ preference of word choice, perspective and values.  For the difficulty of being objective in grading an essay, Automated Essay Scoring has been an active area of research in recent years. The application of the research is very likely to be extended beyond 
education As the prosperous development of machine learning and neural networks in natural language processing, there are diverse ways to approach this problem. In this project, we use Deep Learning to solve the problem and provide advanced solutions based on previous work. The modeling procedure is divided into four stages. 

## Data Description 
The graded essays are from Kaggle and are selected according to the specific data characteristics. On average, each essay is approximately 150 to 550 words in length. There are eight essay sets in total, all essays were written by students ranging in grade levels from Grade 7 to Grade 10. All essays were hand graded and were double scored. Each of the eight data sets has its own unique characteristics, distinct marking criteria and score range. The variability is intended to test the limits of scoring engine's capabilities. Each data point has essay ID, essay set ID, ascii text of essay, score of different raters on different domains

## Result
In our stage 2, 3 and 4, our advanced model outperforms the baseline model of 0.573. In the final stage, we apply LSTM with Glove embedding to grade handwritten essays and achieved a final accuracy (evaluated by average Kappa score) of 0.9765.
