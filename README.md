# HR prediction at Salifort

**Overview**
The goal of this project was to determine the likelihood of an employee leaving Salifort Motors. The project used a decision tree and random forest models to determine the factors that may affect an employee's duration at the company or the employee's desire to leave. Two random forest models were employed and the final random forest model was performed with a precision of 94% and an accuracy of 97% determining what features were most important in separating an employee who would stay in the company and one who would leave. Based on the model, the number of hours worked and the number of projects worked on were the most deciding factors whether employees would stay or leave.

**Business Understanding**
Employee retention rate is a major problem for companies. Companies budget so much money on training new staff and having to budget frequently on hiring and training new staff might not be financially healthy for the company. Also, businesses need to retain their best staff and not lose them to close competitors. 

**Data Understanding**
The dataset consists of 10 columns with 14999 entries/rows. The data set has columns that can help us predict employee retention. These columns include satisfaction level, evaluation score, number of projects, average monthly hours, time spent at the company, work accident, details of promotion, department, and salary. The predicted column is the left column which determines if staff is still at the company or not. 83.4% of the staff stayed and 16.4% left.
![left or stayed](https://github.com/osasanalyst01/Salifort-motors/assets/145936122/37cd2a67-aa80-4532-8cd6-d79408b7e992)

**Modelling and Evaluation**
Below are the most important predictors according to our final random forest evaluation. 
![image](https://github.com/osasanalyst01/Salifort-motors/assets/145936122/e1de8ef4-33fc-4148-a3a7-fa97ab415723)

**Conclusion**
This model can predict if staff will leave the company or not. Reducing the workload on the employees, compensating staff who work overtime, and promoting old employees are possible measures to improve employee retention.
