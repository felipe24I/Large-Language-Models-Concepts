## Advanced fine-tuning
### Reinforcement Learning through Human Feedback (RLHF)
* **Pre-training:** Learns general language patterns, grammar and facts. Model learns to predict next word using Next-word prediction or Masked language modeling
* **Fine-tuning:** using N-shot training or small labeled dataset for related task

### Why RLHF?
* General-purpose training data lacks quality: Nosie, Errors, Inconsistencies, Reduced accuracy
* Example of reduced accuracy: Trained on data from online discussion forums. Unvalidated opinions and facts.

Needs external expert validation

* Pre-training: Learns underlying language patterns, doesn't capture context-specific complexities
* Fine-tuning: quality labeled data improves performance
* Enter RLHF: Human feedback

### Simplifying RLHF
* Model output reviewed by human
* Updates model based on the feedback

#### Step 1:
* Receives a prompt
* LLM generates multiple responses

<img width="575" height="231" alt="image" src="https://github.com/user-attachments/assets/9de10057-d1e3-4890-ac84-fc59a453a239" />

#### Step 2:
* Human expert checks these responses
* Ranks the responses based on quality such as Accuracy, Relevance and Coherence

<img width="341" height="452" alt="image" src="https://github.com/user-attachments/assets/75fa6d0a-52a0-4102-b8a2-b8133c1b4c0c" />

#### Step 3:
* Learns from expert's ranking
* To align its response in future with their preferences
* And it goes on: Continues to generate responses, Receives expert's rankings, Adjusts the learning
  
<img width="597" height="272" alt="image" src="https://github.com/user-attachments/assets/9bfda1d6-c173-4467-8d07-af5a2b1ffd66" />

<img width="893" height="482" alt="image" src="https://github.com/user-attachments/assets/9f2dbab6-efaf-4d2f-b8f8-433866ab1ca7" />

<img width="1093" height="528" alt="image" src="https://github.com/user-attachments/assets/df242397-25f9-49a3-b506-54240f2dd513" />

