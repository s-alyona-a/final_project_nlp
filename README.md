# final_project_nlp

Мы взяли датасет с текстами и вопросами по ним DaNetQA. Это датасет с бинарными ответами на вопросы.

![{5CA86A3A-F835-453E-A76E-FDCEDC4022FF}](https://github.com/user-attachments/assets/a5243939-0f0a-4abe-9769-ce2119bb0f3d)

![{7E2C9D98-12AF-447A-824F-90D4161F5D19}](https://github.com/user-attachments/assets/266e080b-f70f-4226-afe3-7cfc14a06ae2)


Провели эксперименты по применению:

- rule-based подхода

![{29FEF8C3-7015-4876-A64F-B27497C2E73F}](https://github.com/user-attachments/assets/c6795b9c-8041-4943-b8a9-79b03b4db6ca)


- ML

  3 модели построения эмбеддингов + logreg

  ![{4950B758-6296-439F-8D05-DBBFA52A0E42}](https://github.com/user-attachments/assets/4def01bf-856b-4765-8e44-3fd68286f18a)

  
- DL

  Нейросетка с 1-2 слоями LSTM и лемматизированными/не лемматизированными текстами

  ![{D5EC7D84-4A49-47CA-AFF9-D1F2E86430AB}](https://github.com/user-attachments/assets/4863d757-bdce-4c8f-a2f8-aa079c817b32)


  DeepPavlov/rubert-base-cased
  
- LLM:

  Попробовали использовать промпты без и с chain of thoughts

  mistral

  ![{45E1F39A-CE4B-4049-8ECB-6131CB0D57B9}](https://github.com/user-attachments/assets/54f64dc3-96e5-485c-bc31-73c51765b286)


  gigachat
  
![{1E70388A-0ED7-4D5D-86D1-3AC0F97659E7}](https://github.com/user-attachments/assets/ce0327bb-4082-42ee-b41b-16515e50395a)
