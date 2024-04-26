# 👨‍💻 Análise de risco e crédito com IA.👩‍💻

> Utilização de deep analytics e machine learning para solução de um problema

## 📌 Descrição
Este projeto é um estudo de caso realizado por uma empresa de consultoria especializada em tecnologia contratada para fornecer suporte à ABX Tecnologia. A ABX Tecnologia atua no segmento de importação e revenda de produtos, atendendo a uma variedade de clientes que inclui desde pequenas lojas até grandes redes de supermercados e armarinhos.

## 📄 Explicação do problema

A empresa precisa de uma estratégia para melhorar a análise de crédito de seus clientes. Atualmente, a análise de crédito não é uniforme e varia de acordo com o segmento do cliente. Além disso, a empresa deseja automatizar o processo de recomendação de crédito para que os analistas possam basear suas decisões em modelos preditivos.

## 🎲 Conjunto de Dados
O conjunto de dados fornecido consiste em 8974 solicitações de crédito de diversos clientes da ABX Tecnologia. Cada cliente pode ter várias solicitações de crédito com valores distintos. Os dados incluem informações como razão social, nome fantasia, CNPJ, histórico de pagamento, indicadores financeiros, status da solicitação, entre outros.

## 🗂️ Estrutura do Projeto

O projeto está organizado da seguinte forma:

### 📂 Pasta `dataset`
Esta pasta contém o arquivo CSV fornecido pela ABX Tecnologia, que contém os dados necessários para a análise de crédito.

### 📂 Pasta `analise`
Esta pasta contém o arquivo Jupyter Notebook (arquivo .ipynb) onde é realizada a análise exploratória dos dados, pré-processamento, criação do modelo de machine learning e métricas de performance. O notebook está organizado da seguinte maneira:

- **Análise exploratória dos dados**: Análise exploratória dos dados (graficos, visualização etc).
- **pré-processamento de dados**: Limpeza e normalização dos dados.
- **Criação do modelo ML** Definição do tipo do problema(classificação ou regressão), definição do algoritmo a ser utilizado, separação de dados testes e de treinamento.
- **Métricas de perfomance**: Para testar a performance de algoritmos de classificação(acuracia). Para testar a performance de algoritmos de regressão(MSE, RMSE e R²).

## 💻 Tecnologias

As seguintes ferramentas foram usadas neste projeto:

### 🖥️ Ambientes de Desenvolvimento Integrado (IDEs):
![Visual Studio Code](https://img.shields.io/badge/Visual%20Studio%20Code-0078d7.svg?style=for-the-badge&logo=visual-studio-code&logoColor=white)
![Jupyter Notebook](https://img.shields.io/badge/jupyter-%23FA0F00.svg?style=for-the-badge&logo=jupyter&logoColor=white)

### 🐍 Linguagem de Programação:
![Python](https://img.shields.io/badge/Python-3776AB?style=for-the-badge&logo=python&logoColor=white)

A linguagem Python é amplamente utilizada neste projeto para desenvolvimento de código, manipulação de dados, criação de modelos de machine learning e muito mais. Sua sintaxe simples e poderosas bibliotecas tornam Python uma escolha popular para projetos de ciência de dados e machine learning.

#### 📚 Bibliotecas Python Utilizadas:
![Pandas](https://img.shields.io/badge/pandas-%23150458.svg?style=for-the-badge&logo=pandas&logoColor=white)
![Matplotlib](https://img.shields.io/badge/Matplotlib-%23ffffff.svg?style=for-the-badge&logo=Matplotlib&logoColor=black)
![NumPy](https://img.shields.io/badge/numpy-%23013243.svg?style=for-the-badge&logo=numpy&logoColor=white)
![scikit-learn](https://img.shields.io/badge/scikit--learn-%23F7931E.svg?style=for-the-badge&logo=scikit-learn&logoColor=white)
![TensorFlow](https://img.shields.io/badge/TensorFlow-%23FF6F00.svg?style=for-the-badge&logo=TensorFlow&logoColor=white)
![Keras](https://img.shields.io/badge/Keras-%23D00000.svg?style=for-the-badge&logo=Keras&logoColor=white)

### 🧭 Controle de Versão:
![Git](https://img.shields.io/badge/Git-F05032?style=for-the-badge&logo=git&logoColor=white)

## 🧾 Requisitos

Antes de começar, verifique se você tem os seguintes requisitos instalados em seu computador:

- [Git](https://git-scm.com)
- [VSCode](https://code.visualstudio.com/)
- [python](https://www.python.org/downloads/)

Certifique-se de ter essas ferramentas instaladas para poder clonar o projeto e executar as etapas seguintes.

## :checkered_flag: Getting Started

Siga estas etapas para começar:

- Clone o projeto :
```bash
$ git clone https://github.com/laiscrz/CP2-IA
```
- Acesse o projeto :
```bash
$ cd CP2-IA
```
- Antes de executar o projeto, Instale as dependências:
```bash
$ pip install -r requirements.txt
```
Isso garantirá que todas as bibliotecas Python necessárias estejam instaladas e prontas para uso no seu ambiente.

Agora você está pronto para começar a trabalhar no projeto!

> Essas etapas claras e concisas guiarão os usuários para iniciar o projeto sem problemas.

### 🤝 Colaboradores

Queremos agradecer às seguintes pessoas que contribuíram para este projeto:

<table>
  <tr>
        <td align="center">
      <a href="https://github.com/biancaroman">
        <img src="https://avatars.githubusercontent.com/u/128830935?v=4" width="100px;" border-radius='50%' alt="Bianca Román's photo on GitHub"/><br>
        <sub>
          <b>Bianca Román</b>
        </sub>
      </a>
    </td>
    <td align="center">
      <a href="https://github.com/charlenefialho">
        <img src="https://avatars.githubusercontent.com/u/94643076?v=4" width="100px;" border-radius='50%' alt="Charlene Aparecida's photo on GitHub"/><br>
        <sub>
          <b>Charlene Aparecida</b>
        </sub>
      </a>
    </td>
    <td align="center">
      <a href="https://github.com/laiscrz">
        <img src="https://avatars.githubusercontent.com/u/133046134?v=4" width="100px;" alt="Lais Alves's photo on GitHub"/><br>
        <sub>
          <b>Lais Alves</b>
        </sub>
      </a>
    </td>
    <td align="center">
      <a href="https://github.com/LuccaRaphael">
        <img src="https://avatars.githubusercontent.com/u/127765063?v=4" width="100px;" border-radius='50%' alt="Lucca Raphael's photo on GitHub"/><br>
        <sub>
          <b>Lucca Raphael</b>
        </sub>
      </a>
    </td>
     <td align="center">
      <a href="https://github.com/Fabs0602">
        <img src="https://avatars.githubusercontent.com/u/111320639?v=4" width="100px;" border-radius='50%' alt="Fabricio Torres's photo on GitHub"/><br>
        <sub>
          <b>Fabricio Torres</b>
        </sub>
      </a>
    </td>
  </tr>
</table>

<a href="#top">Voltar para o topo</a>
