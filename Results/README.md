# **i. NOTEBOOK 1: (Covid19-CORD-NER)**

# **1. Filtered required article:**
**Among 10000 articles, found only 606 articles related to covid19 containing required keywords.**

**keywords_cov = ["sars-cov-2","sars","cov-2","2019-ncov","ncov","cov","covid19","covid","corona",
             "coronavirus"]**

# **2. Word Cloud: Articles Related to SAR-Cov-2:**

![image](https://user-images.githubusercontent.com/80167074/209726867-c4c29eef-b75f-406f-9781-60a1cd8f9020.png)

**Words or phrases like  'patient', 'infection', 'disease', 'outbreak', 'virus', 'case, 'epidemic' occur frequently in this corpus.**

# **3. c_v Coherence Score w.r.t. Topic Number:**
![image](https://user-images.githubusercontent.com/80167074/209726987-186366f8-e4b7-4a14-89ce-d62c3f82bee5.png)

**The higher the c_v coherence score is, the more suitable the topic number should be. Hence, I choose 8 as the topic number for analysis.**

# **4. Word per Topic:**

![image](https://user-images.githubusercontent.com/80167074/209727120-26a38b1f-7232-40d7-8ef1-703a6129d020.png)

**1. First topic is talking about the hospital practices to ensure the public health by adopting public treatment strategies and infection prevention control measures. We can see words like 'infection', 'hospital', 'disease', 'prevention_control','public health','treatment strategies'.**

**2. Second topic is probably talking about evolution of virus inside human host. We can see words like  'virus', 'human', 'cell','host','protein','infection'.**

**3. Third topic talks about Scientists testion western drugs in lab for atypical pneumonia and myocardial. We can see words like 'Scientist', 'lab', 'test', 'ventilator', 'drug','western','atypical pneumonia','myocardial'.**

**4. Fourth topic probably talks about most of the patient cases orignated from distribution of lesions in lungs that were infected. We can see words like 'patient', 'case', 'lesion', 'infection', 'lung', 'distribuion'.**

**5. Fifth topic talks about observation on hospitalised COVID19 confirmed patients for syndrome, treatment, effect and precaution in isolation. We can see words like 'patient', 'treatment', 'syndrome', 'confirm', 'hospitalize_observation','effect','precaution'.**

**6. Sixth topic talks about rise in cases of COVID19 in the country. We can see words like 'country', 'case', 'transmission', 'outbreak', 'report', 'virus'.**

**7. Seventh topic probably talks about symptoms of COVID19 in a patient. We can see words like 'patient','case','fever','high'.**

**8. Eighth topic probably talks about psychological impact and research on vaccine by scientists in medical world and also about COVID19 cases in wild animals. We can see words like 'vaccine','scientist','research',medical','journal','wild_animal'.**

# **5. LDA Visualization:**
![image](https://user-images.githubusercontent.com/80167074/209727434-41bd143d-9385-4f0b-99b6-2980b5df1506.png)

**As we can see from the interactive figure above, topic 1 and 2 are very close as well as 7 and 8 (5 is also similar to 7). The other topics are separated appropriately.**


# **6. Topic per Document:**
![image](https://user-images.githubusercontent.com/80167074/209799505-129990b0-cb12-49a9-8efe-8a5de96c8c41.png)

**1.The left figure shows that there are very few articles who covered all the topics. 3rd and 4th topic are mostly present in many articles.**

**2.The right figure shows that occurence frequencies of topics are not very close as we can see many articles covered 1st and 6th topic.**

# **7. T-SNE clustering of LDA topics:**

![image](https://user-images.githubusercontent.com/80167074/209727614-05222930-f330-4dcb-849f-71b7de61ce3b.png)

![image](https://user-images.githubusercontent.com/80167074/209727582-37ee6d7d-9085-49e6-ac34-3e19d459c686.png)

# **8. Semantic-Based Search:**

![image](https://user-images.githubusercontent.com/80167074/210631294-9f6fd19e-8d4e-4270-9be1-fe606d6f3b67.png)

# **ii. NOTEBOOK 2: (COVID-19-CORD-NER-information-extraction-Q&A)**

# **1. NER Extraction:**
![image](https://user-images.githubusercontent.com/80167074/210633033-0836a7bd-9f8a-4961-9ecc-25ed03324547.png)

# **2. Dependency parses:**

![image](https://user-images.githubusercontent.com/80167074/210633259-caba35a3-4c20-4a24-bc87-317b96d02a82.png)

![image](https://user-images.githubusercontent.com/80167074/210633274-730ee4af-2227-47ef-8ad3-647d54e69a4f.png)

![image](https://user-images.githubusercontent.com/80167074/210633293-bdd819ad-63f3-4754-95ae-301927efd425.png)

![image](https://user-images.githubusercontent.com/80167074/210633324-81feed2f-f3f0-4cf5-90c2-4d9d1c6ccc07.png)


# **3. Question-Answering:**
![image](https://user-images.githubusercontent.com/80167074/210631516-888cd902-86e2-4d11-b532-f3fe45483131.png)

![image](https://user-images.githubusercontent.com/80167074/210631535-cd97217e-14f6-488d-bf09-d7bb799634c5.png)

![image](https://user-images.githubusercontent.com/80167074/210631550-88a87ad6-77a0-4e07-844a-0f39a7492312.png)

![image](https://user-images.githubusercontent.com/80167074/210631583-244d6d42-63bb-4614-ad75-2bc4d7adbe81.png)

![image](https://user-images.githubusercontent.com/80167074/210631605-5ff55ed7-9906-45b3-9e23-c5e51902a2a0.png)

![image](https://user-images.githubusercontent.com/80167074/210631623-50a42cfb-e50b-4cf7-a9f7-8a96c11fee53.png)


# Notebook available in 'Task' folder.

