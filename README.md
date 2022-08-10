# BERT Model Projects

## Sentence list Reordering using BERT model for next sentence prediction (STAT 946 Deep Learning Data Challenge)

In the BERT training process, the model receives pairs of sentences as input and learns to predict if the second sentence in the pair is the subsequent sentence in the original document. In this competition, we will tackle a more complex task. Each sample in the dataset contains 6 consecutive sentences from a document where they shuffled randomly. The task is predicting the correct order of the sentences. In the train dataset, you have access to the correct order of the sentences and for the test dataset, you must predict this order for each sample.

link to dataset: https://www.kaggle.com/c/stat946winter2021dc2

- Task 1: Download all parts of the dataset from the data section.
- Task 2: Design/Train model using the train dataset
- Task 3: Predict the correct order of sentences in the test data

Result: Mean column wise Spearman's rank correlation of 0.77237.






## Fine Tune BERT for Text Classification with TensorFlow

- Task 1: Load the Quora Insincere Questions Dataset
- Task 2: Create `tf.data.Datasets` for Training and Evaluation
- Task 3: Download a Pre-trained BERT Model from TensorFlow Hub
- Task 4: Tokenize and Preprocess Text for BERT
- Task 5: Wrap a Python Function into a TensorFlow op for Eager Execution
- Task 6: Create a TensorFlow Input Pipeline with `tf.data`
- Task 7: Add a Classification Head to the BERT `hub.KerasLayer`
- Task 8: Fine-Tune BERT for Text Classification
- Task 9: Evaluate the BERT Text Classification Model
