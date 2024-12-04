# Monitoring_unstructured_data_for_LLM_and_NLP_with_text_descriptors

![image](https://github.com/user-attachments/assets/28a80064-183a-4bf0-a8c5-c949fe4eb0ee)

# Text Description : 
Text descriptor is any feature or property that describes objects in the text dataset. For example, the length of texts or the number of symbols in them.You might already have helpful metadata to accompany your texts that will serve as descriptors. For example, e-commerce user reviews might come with user-assigned ratings or topic labels. Otherwise, you can generate your own descriptors! You do this by adding “virtual features” to your text data. Each helps describe or classify your texts using some meaningful criteria.

![image](https://github.com/user-attachments/assets/f3eca3c0-33bd-4210-b31c-9ba1e9e30da6)

# We can leverage this text descriptors for : 
  ## a.  monitor production NLP models or LLM applications. You can track the properties of your data in time and detect when they change. For example, descriptors help detect text length spikes or drift in sentiment. 
  ## b.  test models during updates. When you iterate on models, you can compare the properties of the evaluation datasets and model responses. For example, you can check that the lengths of the LLM-generated answers 
  ##     remain similar, and they consistently include words you expect to see. 
  ## c. Debug data drift or model decay. If you detect embedding drift or directly observe a drop in the model quality, you can use text descriptors to explore where it comes from.

# Steps of Implementation : 

## Step 1 : Import necessary libraries

## Step 2 : Import necessary dataset and perform baseline EDA

## Step 3 : Generate the text overview report and save it in .html format
         Text length
         OOV %
         Non letter characters
         Text sentiments
         Trigger words

Some chart visualizations , for the complete report download text_overview_report.html and open in browser of your choice

![image](https://github.com/user-attachments/assets/74224731-d789-455a-81c2-e1513505380e)

![image](https://github.com/user-attachments/assets/ad555956-3c3c-434d-bb32-38688c5e8197)

![image](https://github.com/user-attachments/assets/924d45d4-a293-4bc2-9cd6-b15208714c3f)

![image](https://github.com/user-attachments/assets/986935a4-0605-4188-b641-6819f7d33ce9)

![image](https://github.com/user-attachments/assets/a72ba03d-a363-43b0-a0bd-71932c4dc734)

![image](https://github.com/user-attachments/assets/32108eb4-076e-4e2e-aa82-bad30e10d618)

![image](https://github.com/user-attachments/assets/6681acbb-37ac-4940-9aef-2918babf2059)

## Step 4 : Customize the report

## Step 5 : How to add new text property ? 
we leveraged a BERT model from huggingface to perform multiclass classification on "Review_Text" column in reference and current datasets and compare the distribution drift
Some chart visualizations , for the complete report download descriptors_report_with_emotion.html and open in browser of your choice

![image](https://github.com/user-attachments/assets/6ed0d111-b535-4154-8e30-23c426ecfbfa)

## Step 6 : Run pipeline tests 

![image](https://github.com/user-attachments/assets/7f18c2ff-165f-4125-b704-6e4445deb93e)

Happy coding :)





