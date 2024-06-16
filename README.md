# Thai-TableQA using LLM 
Objective
to create LLM model that capable of doing questions-answering from tabular data in Thai language.
Method
training data were generated from english-based dataset 
- using valhalla/t5-base-e2e-qg for generate questions from text
- using gaussalgo/T5-LM-Large-text2sql-spider for generate SQL quert from questions.
Base model : scb10x/typhoon-7b
