# AIF-C01 Study Notes

## Useful Links
- [Official Exam Guide](https://d1.awsstatic.com/training-and-certification/docs-ai-practitioner/AWS-Certified-AI-Practitioner_Exam-Guide.pdf)
- [Official Exam Prep - Amazon Skill Builder](https://explore.skillbuilder.aws/learn/course/internal/view/elearning/19554/exam-prep-standard-course-aws-certified-ai-practitioner-aif-c01)

## Types of Training Data for Machine Learning/AI

| Data Type       | AWS Data Source Example                | Actual Example                           |
|-----------------|----------------------------------------|------------------------------------------|
| **Structured**  | SQL data stored in RDS then moved to S3| Customer information in relational tables|
| **Semi-Structured** | Data in DynamoDB or DocumentDB then moved to S3 | JSON logs of user activity           |
| **Unstructured**| Objects and files stored directly in S3| Images, videos, and PDF documents        |
| **Time-Series** | Time-stamped data stored in S3         | IoT device data, stock market data       |


## Confusion Matrix Evaluation Metrics

| Metric Name              | Formula                                                        | Use Case                                                                                      |
|--------------------------|----------------------------------------------------------------|-----------------------------------------------------------------------------------------------|
| **Accuracy**             | (True Positives + True Negatives) / Total                       | General correctness; e.g., evaluating overall performance of a transaction system.            |
| **Precision**            | True Positives / (True Positives + False Positives)             | Minimizing false positives; e.g., in spam detection to avoid marking legitimate emails as spam.|
| **Recall (TPR)**         | True Positives / (True Positives + False Negatives)             | Minimizing false negatives; e.g., in disease screening to avoid missing actual cases.         |
| **F1 Score**             | (2 * Precision * Recall) / (Precision + Recall)                 | Balancing precision and recall; useful in document classification where both metrics matter.  |
| **False Positive Rate (FPR)** | False Positives / (True Negatives + False Positives)        | Minimizing incorrect positive predictions; e.g., in security alarms to reduce false alerts.   |
| **Specificity (TNR)**    | True Negatives / (True Negatives + False Positives)             | Maximizing true negatives; e.g., in medical tests to correctly identify non-diseased patients.|
