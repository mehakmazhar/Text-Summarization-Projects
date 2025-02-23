#**Text Summarization using Facebook BART (CNN/DailyMail)**
This project applies Facebook BART (base) fine-tuned on CNN/DailyMail for abstractive text summarization. Additionally, we evaluate the generated summaries using benchmark metrics like ROUGE, BLEU, and BERTScore to measure the quality of the summaries.

####**📌 Dataset Details**
**Source:** News articles published by CNN and DailyMail.
**Task:** Abstractive text summarization (though it can also be used for extractive summarization).
**Total Articles:** ~300,000
**Average Article Length:** ~800 words
**Average Summary Length**: ~56 words

#### **Dataset Split:**
**Training Set:** ~287,000 articles
**Validation Set**: ~13,000 articles
**Test Set:** ~11,000 articles

#### **📌 Dataset Structure**
Each entry in the dataset contains:

| Column      | Description                                      |
|------------|--------------------------------------------------|
| **article**   | Full news article text                        |
| **highlights** | Extracted bullet-point summary (ground truth) |
| **id**       | Unique identifier for each article             |

### **🚀 Project Overview**
**Model Used:** facebook/bart-base (fine-tuned on CNN/DailyMail)
**Dataset:** CNN/DailyMail (news articles + highlights)
**Summarization Type**: Abstractive
**Evaluation Metrics:** ROUGE, BLEU, BERTScore

#### **🔗 References**
Hugging Face BART Model
CNN/DailyMail Dataset
ROUGE Metric
BLEU Metric
BERTScore Metric




