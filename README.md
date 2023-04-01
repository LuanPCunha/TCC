# Introduction

This repository contains the routines used in the conclusion research of Thalessa Hungerbühler Daroz and Luan Pereira Cunha, students guided by Professor Leila Weitzel from the Federal Fluminense University (UFF) campus Rio das Ostras.

Topic: **HATE SPEECH DETECTION A DEEP LEARNING BASED APPROACH.**

# Database

We used the social network Twitter to assemble the database used in this research. The data consists of public tweets in the Portuguese-BR language.

- Unprocessed database [data/base80k.csv]

# Dictionaries

During the research, some dictionaries were generated to assist in data preprocessing tasks and in the classification of the data into **hate** (presence of hate speech), **not_hate** (free of hate speech), **badword** (presence of offensive language) and **not_badword** (free of offensive language).

- data/dicionarios/vogais_duplicadas.csv (List of Portuguese words with consecutive vowels)
- data/dicionarios/internetes_list.csv (Pairs of "internetês", a contracted version of the word, and the correct version of the word)
- data/dicionarios/stop_word_list.csv (List of stopwords)
- data/dicionarios/badword_list.csv (List of offensive words and expressions)
- data/dicionarios/odio_list.csv (List of hate words and expressions)
- data/dicionarios/estados_list.csv (Pairs of state acronyms and the written out name of the state)

# Methodology

Deep learning networks used in this research

- Long Short-Term Memory (LSTM) [Treinamento_LSTM.ipynb]
- Convolutional Neural Network (CNN) [Treinamento_CNN.ipynb]
- Bidirectional LSTM (Bi-LSTM) [Treinamento_BiLSTM.ipynb]

Research baselines

- Multinomial Naive Bayes [Treinamento_NaiveBayes.ipynb]
- Shallow Neural Networks (SNN) [Treinamento_ShallowNet.ipynb]

-------------------
**VERSÃO EM PORTUGUÊS**

# Introdução
O presente repositório contém as rotinas utilizadas na pesquisa de conclusão de curso dos alunos Thalessa Hungerbühler Daroz e Luan Pereira Cunha orientados pela professora Leila Weitzel da Universidade Federal Fluminense (UFF) campus Rio das Ostras.

Tema: **DETECÇÃO DE DISCURSO DE ÓDIO UMA ABORDAGEM BASEADA EM APRENDIZADO PROFUNDO**

# Base de dados
Utilizamos a rede social Twitter para montar a base de dados utilizada nessa pesquisa. Os dados são tuítes públicos no idioma Português-BR.

- Base de dados não-processada [data/base80k.csv]

# Dicionários
Durante a pesquisa foram gerados alguns dicionários que auxiliaram nas tarefas de pré-processamento dos dados e na classificação desses em **hate** (presença de discurso de ódio), **not_hate** (livre de discurso de ódio), **badword** (presença de linguagem ofensiva) e **not_badword** (livre de linguagem ofensiva).

- data/dicionarios/vogais_duplicadas.csv (Lista de palavras do Português onde se tem vogais consecutivas)
- data/dicionarios/internetes_list.csv (Pares de "internetês", versão contraída da palavra, e a versão correta da palavra)
- data/dicionarios/stop_word_list.csv (Lista de stopwords)
- data/dicionarios/badword_list.csv (Lista de palavras e expressões ofensivas)
- data/dicionarios/odio_list.csv (Lista de palavras e expressões de ódio)
- data/dicionarios/estados_list.csv (Pares de siglas de alguns estados e o nome escrito por extenso)

# Metodologia

Redes de aprendizado profundo utilizadas nessa pesquisa
- Long Short-Term Memory (LSTM) [Treinamento_LSTM.ipynb]
- Convolutional Neural Network (CNN) [Treinamento_CNN.ipynb]
- Bidirectional LSTM (Bi-LSTM) [Treinamento_BiLSTM.ipynb]

Baselines da pesquisa
- Multinomial Naive Bayes [Treinamento_NaiveBayes.ipynb]
- Shallow Neural Networks (SNN) [Treinamento_ShallowNet.ipynb]
