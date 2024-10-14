# Multi-Label-Emotion-Classification-using-NLP

## Emotional Dataset README
![Local Image](./emotionimage.png)
### Overview
This dataset contains text samples labeled with various emotions. It is designed for use in Natural Language Processing (NLP) tasks, specifically for emotion detection and sentiment analysis.

### Business Understanding<br>
Companies can categorise consumer emotions from text data (such as social media postings, customer reviews, or support tickets) by using the GoEmotions dataset. Through comprehending the feelings conveyed in client feedback, businesses can:
* Enhance consumer Experience: 
Recognise and address consumer annoyance or discontent (such as rage or grief) as soon as possible.
* Improved Client Assistance :
Assign complaints and enquiries to the appropriate support staff automatically based on the emotional tone of the communication (e.g., furious clients can be prioritised for resolution).
* Customise Marketing:
 Create more effective and individualised outreach by incorporating client emotions into communication methods or adverts.Companies can categorise consumer emotions from text data (such as social media postings, customer reviews, or support tickets) by using the GoEmotions dataset. By comprehending the feelings conveyed in customer feedback

### Dataset Details
The GoEmotions dataset was sourced from Reddit, a popular social media platform where users post comments on various topics. Specifically, the dataset consists of over 58,000 Reddit comments that were manually annotated by human labelers into 27 distinct emotion categories (such as joy, anger, sadness, curiosity, and more).The dataset was created by Google Research as part of their efforts to advance Natural Language Processing (NLP) research. The comments were collected from publicly available Reddit posts, ensuring a wide variety of topics and emotional expressions. The comments were then labeled with one or more emotions, making it a multi-label classification problem.

- Languages: English
- Emotion Labels: 
  - Joy
  - Neutral
  - Anger
  - Fear
  - Surprise
  - Sadness
  - Disgust

### Data Format
The dataset is provided in CSV format with the following columns:
- `id`: Unique identifier for each sample
- `text`: The text sample (e.g., tweets, reviews)
- `emotion`: The label indicating the primary emotion expressed in the text
- `label`:This typically refers to the specific emotion assigned to each text sample. For example, if a text expresses happiness, the label for that sample would be "happiness."
- `list of classes`:This is a comprehensive list of all possible emotions or categories that the dataset can include. For instance, it might list classes like ["happiness", "sadness", "anger", "fear", "surprise", "disgust"].
- `len of classes`:This indicates the number of unique emotion classes present in the dataset. For example, if the list of classes contains six emotions, the `len of classes` would be 6.

#### Example Entry
|    | text                         |label |    Id   | List of classes |Len of classes| emotions  |
|----|------------------------------|------|---------|-----------------|--------------|-----------|
| 1  | "I just got a promotion!"    |  27  | eebbqej |      [27]       |       1      |  Happiness|
| 2  | "I feel so lonely today."    |  08  | eebb08y |      [08]       |       1      |  Sadness  |
| 3  | "This is absolutely unfair!" |  13  | wsbbqej |      [13]       |       1      |  Anger    |

### Usage
This dataset can be used to train machine learning models for emotion classification. It is suitable for both supervised learning tasks and for fine-tuning pre-trained models.

## Recommendations

* Align with Business Objectives: <br>
   Make sure the precision satisfies the requirements of the company. Establish appropriate cutoff points depending on the particular use case, such as fraud detection or product suggestions.

* Concentrate on accuracy or Recall:<br>
 Depending on the business environment, maximise recall (to minimise damaging false negatives) or accuracy (to decrease expensive false positives).

* Test on Real-World Data:<br>
 Conduct A/B testing to determine how the model affects actual business performance and validate the model using current business data.
 Weigh the trade-offs between increasing accuracy and the expense of more computer power or complexity using a cost-benefit analysis.

* Model Explainability:<br>
Especially in regulated sectors, make CNN outputs interpretable by using tools like Grad-CAM or LIME.

* Update and Monitor:<br>
 After deployment, periodically assess the model's performance and retrain it to adapt to evolving business needs.
 the Model which can be used make a chatbot Assistant

*Constant Maintenance

### Conclusion
This project demonstrates a basic approach to multi-class classification using a neural network in Keras. The model is designed to classify text into seven categories, and one-hot encoding is applied to prepare the labels for training. Further improvements can be made by experimenting with different architectures, regularization techniques, and hyperparameter tuning.
We Decided to use CNN , In a business scenario, the objective is to guarantee that the CNN contributes quantifiable benefit to company outcomes in addition to attaining high accuracy. Prioritise guaranteeing scalability, cost-effectiveness, explainability for stakeholders, and matching model performance to business objectives. You can optimise the model's effect on the company by keeping an eye on it and making improvements all the time.
  

### License
This dataset is released under the MIT License. Please ensure to credit the source when using the data.

### Acknowledgments
We would like to thank all of our group members & contributors who helped in collecting and labeling the data and making this a success.

# GROUP 7 DSFT09 HYBRID PHASE 4
1.Mirriam Mumbua<br>
2.Martin Kandie<br>
3.Gilead Gad <br>
4.Robinson Karasha<br>
5.Graffin Kiprotich<br>


---

© Miriam Mumbua, Martin Kandie, Gilead Gad, Robinson Karasha & Graffin Kiprotich 2024
