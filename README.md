# final_project_nlp

Мы взяли датасет с текстами и вопросами по ним DaNetQA. Это датасет с бинарными ответами на вопросы.

Провели эксперименты по применению:

- rule-based подхода

- ML

  3 модели построения эмбеддингов + logreg

  bert-classifier
  
- DL

  Нейросетка с 1-2 слоями LSTM и лемматизированными/не лемматизированными текстами
  
- LLM:

  Попробовали использовать промпты без и с chain of thoughts

  mistral
  gigachat
