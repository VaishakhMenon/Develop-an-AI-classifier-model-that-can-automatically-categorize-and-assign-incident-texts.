**Context**
In the IT industry, Incident Management is a crucial component in providing high-quality support to customers. An incident refers to an unexpected disruption to an IT service or a decrease in its quality that impacts users and the business. The primary aim of the Incident Management process is to swiftly address and resolve the disruption, restoring the service to its optimal state to minimize any negative effects on the business.  
The service desk team conducts a preliminary analysis of users' needs, identify reported issues, and allocate them to the relevant teams. Assigning incidents to the appropriate IT teams is often done manually in many organizations, which is a time-consuming process that relies on human effort. Manual assignment can lead to errors and inefficient resource allocation, resulting in delays in response and resolution times, ultimately affecting customer satisfaction.  
The goal is to develop an AI classifier model that can automatically categorize and assign incident texts.  

**DataSet Link:**
https://github.com/Premalatha-success/Datasets/blob/main/input_data.xlsx Links to an external site. Links to an external site.

**Action Plan:**
- Create a word vocabulary from the corpus of report text data 
- Identify NaN values and replace them 
- Convert all text to lowercase 
- Remove punctuations, digits and special characters 
- Build the following classifier models from the dataset provided 
  -  KNN 
  - SVM 
  - Random Forest
- Evaluation of model performance
