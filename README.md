# AI to combat Pneumonia COVID-19
## Proposed Working Solution
Identifying Medical Diagnoses and Treatable Diseases(Pneumonia from Chest X-Rays) by Image-Based Deep Learning using Neural Networks

## Summary
The implementation of clinical-decision support algorithms for medical imaging faces challenges with reliability and interpretability. Here, I demonstrate the general applicability of our AI system for diagnosis of pneumonia using chest X-ray images. This tool may ultimately aid in expediting the diagnosis and referral of these treatable conditions, thereby facilitating earlier treatment, resulting in improved clinical outcomes.

Although currently, deep learning still cannot replace doctors/clinicians in medical diagnosis, it can provide support for experts in the medical domain in performing time-consuming works, such as examining chest radiographs for the signs of pneumonia.

## Introduction
Artificial intelligence (AI) has the potential to revolutionize disease diagnosis and management by performing classification difficult for human experts and by rapidly reviewing immense amounts of images. Despite its potential, clinical interpretability and feasible preparation of AI remains challenging.

In the world of healthcare, one of the major issues that medical professionals face is the correct diagnosis of conditions and diseases of patients. Not being able to correctly diagnose a condition is a problem for both the patient and the doctor. The doctor is not benefitting the patient in the appropriate way if the doctor misdiagnoses the patient. This could lead to malpractice lawsuits and overall hurt the doctor's business. The patient suffers by not receiving the proper treatment and risking greater harm to health by the condition that goes undetected; further, the patient undergoes unnecessary treatment and takes unnecessary medications, costing the patient time and money.

If we can correctly diagnose a patient's condition, we have the potential to solve the above-mentioned problems. If we can produce deep learning models that can classify whether a patient has a condition or not, that can determine which particular condition the patient has, and that can determine the severity of the condition, then medical professionals will be able to use these models to better diagnose their patients. Accurate diagnosis can also be useful by allowing for timely treatment of a patient; being misdiagnosed can cause a delay in receiving the proper treatment.

* Radiology is a branch of medicine where the disease diagnosed by examining X-ray Images.

* To reduce the human eye error in diagnosing the disease computer aided system has evolve for better diagnosis.

* Machine learning techniques has shown remarkable results in the recent years.

* In this project we are trying to diagnose the Pneumonia from chest X-ray using Machine Learning techniques.

I would like to apply a convolutional neural network (CNN) and try to classify a patient as either having pneumonia or not having pneumonia. This is a binary classification problem. I would also like to apply CNN's to classify a patient as either having bacterial pneumonia, viral pneumonia, or no pneumonia. This is a 3-class classification problem.
