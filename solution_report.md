**## Task 1: Choose a Business Domain**



Selected Domain: Healthcare



I selected the healthcare domain because hospitals and healthcare centers manage a large amount of patient information on a daily basis. In many situations, identifying diseases at an early stage can make treatment easier and reduce serious health risks. Heart disease is one of the major health concerns, and timely prediction can help both doctors and patients take preventive action.



Artificial Intelligence can support healthcare professionals by analyzing medical information more quickly and identifying possible risks at an earlier stage. Instead of depending only on manual observation, AI can assist doctors by providing additional insights from patient data, which may improve the overall quality of healthcare services.





**## Task 2: Define the Business Problem**



* What problem is being solved?



The main problem being solved is the early prediction of heart disease risk in patients. In many cases, heart-related problems are identified at a later stage, which can increase health complications and make treatment more expensive. By using AI, hospitals can identify patients who may have a higher risk of heart disease earlier and take preventive action before the condition becomes serious.



* Who are the users or stakeholders?



The main stakeholders in this system are doctors, hospitals, healthcare staff, and patients. Doctors can use the system to support medical decisions, while hospitals can improve patient care and treatment planning. Patients may benefit from early warnings and faster diagnosis, which can improve their overall health outcomes.



* What is the current manual or traditional process?



At present, doctors mainly depend on patient medical reports, blood pressure levels, cholesterol reports, sugar levels, and personal medical history to assess disease risk. This process is done manually and usually depends on medical experience and physical examination.



* What are the limitations of the current process?



The traditional process can sometimes take more time, especially when hospitals handle many patients. Since decisions are mostly based on manual review, there is a chance that some warning signs may be overlooked. In addition, large amounts of patient data can become difficult to analyze quickly without technological support.





**## Task 3: Identify the AI Task Type**



AI Task Type: Classification



This problem can be considered a classification task because the model predicts whether a patient belongs to a specific category of disease risk, such as high risk or low risk. The output is not a numerical value but a category, which makes classification the most suitable approach.



Classification is appropriate here because the main goal is to identify patients who may require early medical attention. It can help doctors quickly separate high-risk patients from lower-risk patients and improve treatment planning.





**## Task 4: Data Requirement Plan**



* Type of data needed



To solve this problem, patient health and medical information would be required. This may include details such as age, blood pressure, cholesterol levels, heart rate, diabetes history, smoking habits, body weight, and medical background.



* Structured or unstructured data



The majority of data used in this system would be structured data because patient information is usually stored in tables, rows, and columns in hospital databases.



* &#x20;Input features



The important input features may include:



\- Age

\- Blood pressure

\- Cholesterol level

\- Blood sugar level

\- Smoking history

\- Heart rate

\- Body Mass Index (BMI)

\- Family medical history



These features can help the AI system understand patterns related to heart disease risk.



* Target variable or labels



The target variable would represent the disease risk level of a patient. For example:



\- High Risk

\- Low Risk



This label helps the system learn and predict future patient risk.



* &#x20;Data collection method



The required data can be collected from hospital records, regular health checkups, laboratory reports, wearable health devices, and patient medical history files.



* Data quality risks



Some possible data quality risks may include missing records, incorrect patient information, duplicate entries, and biased datasets that represent only a small group of people. Poor quality data may reduce prediction accuracy and affect the reliability of the system.





**## Task 5: Model Recommendation**



Recommended Model: Feed-Forward Neural Network



A feed-forward neural network is a suitable model for this problem because the healthcare data used is mainly structured and numerical. The model can learn relationships between different patient health features and identify patterns that may indicate heart disease risk.



This model is appropriate because it can handle multiple health factors at the same time and provide faster predictions. Compared to manual analysis, a neural network can process large amounts of patient data more efficiently and support doctors in making better decisions.





**## Task 6: Evaluation Plan**



* Technical metrics



The performance of the model can be evaluated using technical metrics such as Accuracy, Precision, Recall, and F1 Score. Accuracy measures how many predictions are correct overall, while Precision and Recall help understand how well the model identifies patients with actual disease risk. F1 Score helps balance both precision and recall.



* Business metrics



The success of the solution can also be measured through business outcomes such as improved diagnosis speed, reduced treatment costs, early disease detection, and better patient care. Hospitals may also benefit from improved efficiency in handling patient cases.



* Possible failure cases



The model may sometimes produce incorrect predictions if the patient data is incomplete, inaccurate, or outdated. It may also struggle when dealing with patients who have unusual medical conditions that are not well represented in the training data.



* Human review or validation process



Doctors and healthcare professionals should always review the predictions made by the AI system before making final medical decisions. Human supervision is necessary because AI should support medical judgment rather than completely replace it.





**## Task 7: Responsible AI Considerations**



* Bias in data



If the dataset mainly contains information from one type of patient group, the predictions may become unfair for other groups. For example, age, gender, or regional differences may affect prediction quality.



* Incorrect predictions



Wrong predictions can create serious problems in healthcare because they may lead to delayed treatment or unnecessary concern for patients. This is why accuracy and human review are important.



* Privacy concerns



Patient health information is highly sensitive and should be stored securely. Hospitals must ensure that patient data is protected and used responsibly.



* Over-reliance on AI



Doctors should avoid depending completely on AI systems. Medical knowledge and human experience are still important in making final healthcare decisions.



* Impact on users



Incorrect results may affect patient confidence and emotional well-being. Patients may become worried if predictions are inaccurate.



* Need for human oversight



Human supervision is very important in healthcare systems. Doctors should always validate AI recommendations before using them in treatment planning.





**## Task 8: Final Solution Summary**



* Problem



The main problem focuses on identifying patients who may have a high risk of heart disease at an early stage.



* Proposed AI solution



An AI-based disease prediction system can be developed to analyze patient health records and identify individuals who may require medical attention earlier.



* Required data



The system would require structured patient information such as age, blood pressure, cholesterol levels, sugar levels, heart rate, smoking history, and medical background.



* Model recommendation



A feed-forward neural network is recommended because it can work effectively with structured healthcare data and identify important patterns between different health factors.



* Expected business impact



The proposed solution can help hospitals improve diagnosis speed, support doctors in medical decision-making, reduce healthcare costs, and improve patient care through early disease detection.



* Risks and mitigation plan



Risks such as biased data, incorrect predictions, and privacy concerns can be reduced through proper data monitoring, secure storage systems, and human supervision from healthcare professionals.

