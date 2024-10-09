# Multi-Label-Emotion-Classification-using-NLP

## Emotional Dataset README

### Overview
This dataset contains text samples labeled with various emotions. It is designed for use in Natural Language Processing (NLP) tasks, specifically for emotion detection and sentiment analysis.

### Dataset Details
- Total Samples: 43,410
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
| id | text                         | emotion  |
|----|------------------------------|----------|
| 1  | "I just got a promotion!"    | Happiness |
| 2  | "I feel so lonely today."    | Sadness   |
| 3  | "This is absolutely unfair!" | Anger     |

### Usage
This dataset can be used to train machine learning models for emotion classification. It is suitable for both supervised learning tasks and for fine-tuning pre-trained models.

### License
This dataset is released under the MIT License. Please ensure to credit the source when using the data.

### Acknowledgments
We would like to thank all of our group members & contributors who helped in collecting and labeling the data and making this a success.

---

© Miriam Mumbua, Martin Kandie, Gilead Gad, Robinson Karasha & Graffin Kiprotich 2024
