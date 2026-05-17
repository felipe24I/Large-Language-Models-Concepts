## Challenges of language modeling
### 1. Sequence matters
* I only follow a healthy lifestyle
* Only I follow a healthy lifestyle
* Different positions = different meanings

### 2. Context modeling
 For example, run has different meanings
* To jog: I run a marathon every year
* To manage: I run a non-profit organization
* To operate: Do you know how to run this machine?

### 3. Long-range dependency
Recognize and connect distant words in a sentence

For example: The **book** that the young girl, who had just returned from her vacation, carefully placed on the shelf **was quite heavy**

## Traditional models are trained for each specific task (single-task learning)
Traning separate models for each task

* Task-specific
* Less flexible
* Traditional models and early LLMs
  
<img width="1082" height="351" alt="image" src="https://github.com/user-attachments/assets/2587a126-885d-4132-a768-b2bba593113c" />

* Time and resource expensive
* Less flexible compare to modern LLMs

## Multi-task learning for LLMs
training a model to perform multiple related tasks simultaneously

* Versatile
* Multiple tasks
* More developed LLMs
  
<img width="981" height="363" alt="image" src="https://github.com/user-attachments/assets/0db99902-5561-4649-a3df-42049f502c49" />

* Improved performance on each individual task (using new and acient data)
* Might impact accuracy and efficiency
* Less training data needed because data is shared
