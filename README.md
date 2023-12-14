# Bengali-Ekman-s-Six-Basic-Emotions-Corpus-NLP

## Accuracy for XLM-Roberta

|  *XLM-Roberta*    | *Accuracy*             |
| :--------           | :------------------------- |
|  `Without Any Technique`       |  `86%`|
|  `Without Stop Words`       | `84%` |
|  `Custom Stop Words Removal`       | `87%` |
|  `Stemming`       | `85%` |
|  `Lemmatization`       | `85%` |
|  `Custom StopWords Removal+TF-IDF`       |  |
|  `Custom StopWords Removal+Lemmatization+TF-IDF`       |  |


                    
## Accuracy for BangaBert

|  *BanglaBert*    | *Accuracy*             |
| :--------           | :------------------------- |
|  `Without Any Technique`       |  `87%`|
|  `Without Stop Words`       | `87%` |
|  `Custom Stop Words Removal-SagorSarkerBanglaBert`       | `87%` |
|  `Custom Stop Words Removal-BUETBanglaBert`       | +`89%` |
|  `Stemming`       | `86%` |
|  `Lemmatization`       | `87%` |
|  `Custom StopWords Removal+TF-IDF`       |  |
|  `Custom StopWords Removal+Lemmatization+TF-IDF`       |  |


## Dataset Details
### The dataset comprises 6 distinct classes, each corresponding to a specific emotion. With 6000 rows allocated to each class, the dataset as a whole consists of a total of 36,000 rows.

|  *Emotion*    | *Rows*             |
| :--------           | :------------------------- |
|  `Disgust`       |  `6000`|
|  `Angry`       | `6000` |
|  `Happy`       | `6000` |
|  `Surprise`       | `6000` |
|  `Fear`       | `6000` |
|  `Sad`       | `6000` |
