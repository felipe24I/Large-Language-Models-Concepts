## Building blocks to train LLMs
### 1. Generative pre-training
* Input data of text tokens
* Trained to predict the tokens within the dataset

**Types**

* Next word prediction
* Masked language modeling

### 1.1 Next word prediction
* Supervised leaarning technique: Model trained on input-output pairs
* Predicts next word and generates coherent text
* Captures the dependencies between words
* Training data: pairs of input and output examples

#### Example: Training data for next word prediction
Ex: The quick brown fox jumps over the lazy dog

Create input output pairs for the model to learn from, during training, each generated output is added to the input for the next pair, allow to the model to predict the next output

Ex: 

<img width="721" height="522" alt="image" src="https://github.com/user-attachments/assets/ca672cf3-ca3e-4361-b438-079e5c489f5f" />

#### Which word realtes more with pizza?
* More examples = better prediction

Ex: I love to eat pizza with ____

<img width="525" height="502" alt="image" src="https://github.com/user-attachments/assets/92061144-e8fe-44de-a01a-8285ddfc1ca2" />

* Cheese is more related with pizza than anything else

### 1.2 Masked language modeling
* Hides a selective word
* Trained model predicts the masked word

Ex:

* **Original text:** "The quick brown fox jumps over the lazy dog"
* **Masked Text:** "The quick [MASK] fox jumps over the lazy dog"

During training, the model receives both original and mask text as input

* **models objective:** predict the missing word
* The model has learned that it's "brown" based on the training data
