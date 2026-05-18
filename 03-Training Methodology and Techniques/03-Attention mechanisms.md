## Attention mechanisms
Help language models understand complex structures and represent text more effectively focus on important words and the relationships

### Book reading analogy:
* Clues in a mystery book
* Focus on relevant content
* Concentrate on crucial input data

### Self-attention and multi-head attention
**Self-attention:** Weighs the importance of each word in a sentence baed on the context to capture long-range dependencies

**Multi-head attention:** takes self-attetion to the next level by splitting the input into multiple "heads" with each head focusing on different aspects of the relationships between words, allowing the model to learn a richer representation of the text

#### Example
* Group conversation at a party it is common to selective attention to the most relevant speaker to understand the topic being discuss, by filtering out background noise, individuals can focus on key points of the conversation and understand what is being discussed

#### self-attention
Can be compared to foucs on each person's words in the group conversation and evaluating the relevance in relation to other people's words

This technique enables the model to weigh each speaker's input and combine them to from a more comprehensive understanding of the conversation

#### Multi-head attention
involves split attetion into "multiple" channels that simultaneously focus on different aspects of the conversation, for instance, one channel may concentrate on the speaker's emotion, another on the primary topic, and a third on related side topics, each aspect is processed independently, and the resulting understandings are merged to gain a holistic perspective of the conversation  

#### Multi-head attention advantages
* "The boy went to the store to buy some groceries, adn he found a discount on his favorite cereal"
* **Attention:** "boy", "store", "gorceries", and "discount"
* **self-attention:** "boy" and "he" -> same person
* **Multi-head attention:** multiple channels
* channel 1: character ("boy")
* channel 2: action ("went to the store", "found a discount")
* channel 3: Things involved ("gorceries", "cereal")



