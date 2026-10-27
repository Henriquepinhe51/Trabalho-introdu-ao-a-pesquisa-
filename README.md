# Análise de Sentimento de Tweets com Naive Bayes

Este repositório contém o código e os recursos necessários para reproduzir uma análise de sentimento em tweets utilizando o algoritmo **Naive Bayes** em Python.

---

## 📁 Estruturação do Repositório

### 1. Arquivos de Dados
* **`tweets.csv`**: Arquivo contendo os tweets utilizados na análise, estruturado com as colunas `texto` e `sentimento`.
* **`stop_words.txt`**: Lista de *stop words* em português para serem removidas durante o pré-processamento dos textos.

### 2. Código Python
* **`main.py`**: Script principal que executa o fluxo completo da análise de sentimento.
* **`pre_processing.py`**: Funções de pré-processamento (remoção de caracteres especiais, conversão para minúsculas, remoção de *stop words* e *stemming*).
* **`naive_bayes_model.py`**: Implementação do modelo Naive Bayes e classificação dos tweets.
* **`evaluation.py`**: Funções para avaliação do desempenho do modelo utilizando métricas padrão.

### 3. Documentação
* **`README.md`**: Instruções e detalhes sobre o projeto.

---

## 🛠️ Tecnologias e Bibliotecas Utilizadas

O projeto foi desenvolvido em **Python**, utilizando as seguintes bibliotecas:
* **[pandas](https://pandas.pydata.org/)**: Manipulação e análise de dados tabulares (arquivos CSV).
* **[NLTK](https://www.nltk.org/)**: Processamento de Linguagem Natural (PLN), remoção de *stop words* e *stemming*.
* **[scikit-learn](https://scikit-learn.org/)**: Implementação do modelo Naive Bayes e métricas de avaliação.

---

## 🚀 Como Reproduzir a Análise

Siga as etapas abaixo para executar o projeto em sua máquina local:

1. **Clone o repositório:**
   ```bash
   git clone [https://github.com/seu-usuario/seu-repositorio.git](https://github.com/seu-usuario/seu-repositorio.git)
   cd seu-repositorio
   
