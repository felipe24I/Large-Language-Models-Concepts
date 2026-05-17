## Generalized overview of NLP
### 1. Text Pre-processing
Transforms raw text data into a standardized format

1. tokenization
2. Stop-word reomoval
3. Lemmatization

Can be done in a different order as they are independent

#### Tokenization
Splits text into individual words, or tokens

* Text: "Working with natural language processing techniques is tricky."
* Tokenization: ["Working", "with", "natural", "language", "processing", "techniques", "is", "tricky", "."]

#### Stop word removal
Stop words do not add meaning

Eliminated through stop word removal

* **Before** stop word removal: ["Working", "with", "natural", "language", "processing", "techniques", "is", "challenging", "."]
* **After** stop word removal: ["Working", "natural", "language", "processing", "techniques", "challenging", "."]

#### Lemmatization
* Group slightly different words with similar meaning
* Reduces words to their base form
* Mapped to root word

Example:

* Talking -> Talk
* Talked -> Talk
* Talk -> Talk

### 2. Text representation
Text data into numerical form

#### Bag-of-words
Text into a matrix of word counts

<img width="1196" height="195" alt="image" src="https://github.com/user-attachments/assets/9bf51ba2-7a88-45a6-9f7f-ce83f7177298" />

0 represents the absence of a word

#### Limitations of bag-of-words
* Does not capture the order or context: can lead to incorrect interpretations

example: 

* "The cat chased the mouse swiftly"
* "The mouse chased the cat"

similar sentece but opposite meaning

* Does not capture semantic between the words: treats related words as independent like "cat" and "mouse"

#### Word embeddings
Capture the semantic meanings as numbers

<img width="380" height="356" alt="image" src="https://github.com/user-attachments/assets/b90e86fe-9240-45d7-8580-03adbdf524a4" />

cat [-0.9, 0.9, 0.9]

<img width="583" height="526" alt="image" src="https://github.com/user-attachments/assets/629c18e6-4bde-421f-8e12-80ca46f5e1e6" />

### To recap

<img width="1080" height="257" alt="image" src="https://github.com/user-attachments/assets/47b4cf68-a654-4718-84ba-c2f387a80574" />

### 3. Pre-training
* Leraned from general-purpose datasets
* Not optimized for specific-tasks
* Can be fine-tuned for a specific problem
  
### 4. Fine-tuning
* Addresses some of these challenges
* Adapts a pre-trained model

#### Challenges of building a LLM
#### 1. powerful computers
* Memory
* Processing power
* Infrastructure
* Expensive

* **LLM:** 100000's central processing Units (CPUs) and 10000's Graphic Processing Units (GPUs)

* **A personal computer:** 4-8 CPU and 1-2 GPUs

#### 2. Efficient model training
* Training time is huge
* May take weeks or even months
* Efficient model training = faster training time
* 355 years of processing tiem on a single GPU

#### 3. Data availability
* Need of high-quality data
* To learn the complexities and subtleties of language
* A few hundred gigabytes (GBs) of text data: more than a million books
* Massive amount of data

<img width="1067" height="525" alt="image" src="https://github.com/user-attachments/assets/df21de12-a2fe-49a1-ba43-3ada179d4025" />
