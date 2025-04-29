### **Remake-GPT2-mini**

I remake GPT-2 model with reference to 'Let's reproduce GPT-2 (124M)' by Andrej Kaparthy to learn how to *think like a OpenAI co-founder' and boost the training process. This is a really cool video that he mentioned a variety of concepts. I have notes on my code file to explain some concepts he mentioned. In the near future, I'll attach a docx file to explain them clearly.

As WebText mentioned in [GPT-2 paper](https://cdn.openai.com/better-language-models/language_models_are_unsupervised_multitask_learners.pdf) is not publicly available, dataset used in this model is Fineweb with 10B tokens. Because tokens of this dataset are randomly sampled from the whole dataset, the result achieved may vary. As can be seen in the graph below, the model loss is stuck at around 3.9 from nearly the last one third of the whole process (~6000 last steps). The reason can be due to the dataset which is different from WebText dataset. Additionally, it can also due to the training process the training process was done in Google Colab Pro+, running time was interrupted several time, I have to upload the last checkpoint file and keep running (Anyway I don't think because of this reason).

Addition information: This model can be nicely trained on Google Colab with about ~150 computing unit and 100GB storage in Drive.

![image](https://github.com/user-attachments/assets/100596d4-72ce-4239-841a-8ed77726bfbb)





