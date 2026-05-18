## Introducing the transformer
Transformers are part of pre-training and enhance the techniques we have already learned about

Transformer architecture emphasizes long-range relationship between words in a sentence to generate accurate and coherent text

* **Components:** Pre-processing, Positional Encoding, Encoders, and Decoders
  
### Inside the transformer
* **Input:** Jane, who lives in New York and works as a software

<img width="1201" height="127" alt="image" src="https://github.com/user-attachments/assets/9c827257-81c4-4f4d-b758-62912d87c921" />

The transformer pre-processes input text converting it to numbers and incorporating position references, the encoder uses this information to encode the sentences, which the decoder then uses to predict subsequent words

The predicted word is added to the input and the proccess continues until the final output completes the input sentence

* **Output:** engineer, loves exploring new restaurants in the city

### Imagine the transformers are like an orchestra
#### First component: Text pre-processing and representation (Musical notes)
* Text preprocessing: tokenization, stop word removal, lemmatization
* Text representation: word embedding

#### Second component: Positional encoding (sheet music)
* Provides information on the position of each word
* Understand distant words

#### Third component: Encoders (Volume in specific sections)
* **Attention mechanism:** directs attention to specific words and relationships
* **Neural network:** process specific features, complex patterns

#### Fourth component: Decoders (individual musicians combine their knowledge as an orchesta to create a cohesive and meaningful performance)
* Also includes attention and neural networks
* Generates the output

<img width="1197" height="306" alt="image" src="https://github.com/user-attachments/assets/c0aa5511-fbf8-4044-b61d-4986ab5d4d29" />

### Transformers and long-range dependencies
* **Initial challenge:** long-range dependency
* **Attention:** focus on different parts of the input

* **Example:** "Jane, who lives in New York and works as a software engineer, loves exploring new restaurants in the city"
* "Jane" --- "loves exploring new restaurants"

### Processes multiple parts simultaneously
* **Limitation of traditional language models:** sequential - one word at a tiem
* **Transformers:** Process multiple parts simultaneously, faster processing

* **Ex:** "The cat sat on the mat"
* Processes "cat", "sat", "on", "the", and "mat" at the same time




