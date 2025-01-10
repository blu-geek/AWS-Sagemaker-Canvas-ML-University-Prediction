# AWS-Sagemaker-Canvas-ML-University-Prediction

Predicting University Admission Qualification using Amazon Sagemaker Canvas

Univesities usually filter through tons of documents and applications painstakingly using benchmarks/applicant features like GPA, test scores, extracurricular activities, and recommendation letters. A university seeks to streamline its admissions process by predicting the likelihood of applicants being accepted based on historical data. Using Amazon SageMaker Canvas (Autopilot), the university can automatically generate machine-learning models that predict admission outcomes.This enables the Admissions board to prioritize high-potential candidates more efficiently.

This is a project walk-through using Amzaon Sagemaker Canvas (Auto-Pilot) to Build, Train, Predict and Deploy a Machine Learning Model for this purpose.

<img width="694" alt="Screenshot 2025-01-10 at 16 25 40" src="https://github.com/user-attachments/assets/be875c10-7f07-44f6-90e5-1a7fa296ae27" />

<img width="734" alt="Screenshot 2025-01-10 at 16 25 21" src="https://github.com/user-attachments/assets/9f8dec6c-b088-4592-a501-32b021c23590" />


Activity Guide: Predicting University Admissions Using Amazon SageMaker Canvas

# 1. Set Up the SageMaker Environment (Amazon SageMaker)
Provision SageMaker Domain:
- Launch an Amazon SageMaker domain via the AWS Management Console.
- Configure user profiles and permissions for accessing SageMaker Canvas.
Access SageMaker Canvas:
- Open the SageMaker Canvas environment from the SageMaker domain.
  
# 2. Prepare the Dataset (Amazon S3)
Upload Historical Data:
- Prepare a dataset containing historical student admission data (e.g., GPA, test scores, extracurricular activities).
- Upload the dataset to an S3 bucket and ensure SageMaker Canvas has access to it.
Verify Data Quality:
- Check for missing values, inconsistencies, or anomalies in the data.
- Use SageMaker Canvas’s built-in data exploration tools to validate the dataset.
  
# 3. Build the Predictive Model (Amazon SageMaker Canvas - Autopilot)
Launch Autopilot Experiment:
- Import the dataset into SageMaker Canvas and define the target column (e.g., Chance of Admission).
- Use the Autopilot feature to automatically build a machine-learning pipeline.
Train the Model:
- Allow Autopilot to train multiple models and identify the best-performing one.
- Review performance metrics such as RMSE.
  
# 4. Deploy the Model (Amazon SageMaker)
Create a Deployment Endpoint:
- Deploy the selected model to an Amazon SageMaker endpoint for real-time predictions.
Generate Predictions:
- Use SageMaker Canvas to test predictions by uploading new student profiles.
- Verify the prediction accuracy using additional validation datasets.
  
# 5. Test and Validate the Model (Amazon SageMaker Canvas)
Simulate Use Cases:
- Test the model with a variety of scenarios to ensure robustness.
Analyze Results:
- Compare predicted admission outcomes with actual historical outcomes.
- Refine the model as needed by retraining with updated data.
  
# 6. Automate the Workflow (Amazon SageMaker, CloudWatch)
Schedule Batch Predictions:
- Use SageMaker Canvas or SageMaker Pipelines to automate periodic predictions for new datasets.
Monitor Model Performance:
- Set up CloudWatch to monitor endpoint performance and prediction latency.
  
# 7. Clean Up Resources (Amazon SageMaker, S3)
Delete Unused Resources:
- Remove the SageMaker endpoint, domain, and Canvas models when no longer needed.
Archive Data:
- Archive the dataset in S3 for future use, or delete it to save costs.
Track Costs:
- Use AWS Budgets to monitor SageMaker usage and prevent unexpected charges.

