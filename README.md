# Desafio Cientista de Dados 

## Introdução

Este projeto foi desenvolvido como parte do desafio de Cientista de Dados da Indicium. O objetivo é realizar uma análise de dados para auxiliar um cliente na criação de uma plataforma de aluguéis temporários na cidade de Nova York..

## Estrutura do Projeto

- `EDA.pdf/`: Contém o PDF com a análise exploratória de dados (EDA).
- `previsão de preço.pdf/`: Contém o PDF do Jupyter Notebook com o modelo preditivo e a previsão do preço de um determinado apartamento.
- `modelo.pkl/`: Contém o modelo salvo em formato `.pkl`.
- `Perguntas.pdf/`: Contém a respostas as perguntas dos passos 2 e 3 do desafio em formato PDF.
- `requirements.txt`: Lista de pacotes Python necessários.
- `README.md`: Instruções sobre como instalar e executar o projeto.

## Instalação

1. **Clone o repositório:**

   ```bash
   git clone https://github.com/seuusuario/desafio-cientista-dados.git
   cd desafio-cientista-dados

2. **Crie um ambiente virtual:**

   ```bash
   python -m venv venv
   source venv/bin/activate  # Para Windows: venv\Scripts\activate

3. **Instale os pacotes necessários:**

   ```bash
   pip install -r requirements.txt

## Bibliotecas Utilizadas 

| Biblioteca          | Versão   | Descrição                                                                 |
|---------------------|----------|---------------------------------------------------------------------------|
| `pandas`            | 2.1.4    | Manipulação e análise de dados tabulares.                                 |
| `numpy`             | 1.26.3   | Cálculos numéricos e operações matemáticas eficientes.                    |
| `scikit-learn`      | 1.4.0    | Machine Learning: modelos, pré-processamento e avaliação de métricas.     |
| `matplotlib`        | 3.8.2    | Visualização de gráficos estáticos e interativos.                         |
| `seaborn`           | 0.13.1   | Visualização estatística com gráficos mais atrativos.                     |
| `Jupyter`           | 1.0.0    | Ambiente interativo para desenvolvimento e análise de dados.              |
| `cartopy`           | 0.22.0   | Visualização de mapas e dados geográficos.                                |

## Execução
- `Análise Exploratória de Dados (EDA):/`: Abra o pdf EDA.pdf para visualizar a análise exploratória dos dados.
- `Modelagem Preditiva:/`: O PDF previsão de preço.pdf contém a modelagem preditiva, incluindo a previsão do preço e as variáveis mais importantes.
- `respostas:/`: As respostas das análises estão disponíveis em Perguntas.pdf.
- `Modelo Salvo:/`: O modelo preditivo treinado está salvo em modelo.pkl. Você pode carregá-lo em Python para fazer previsões.
  
  ## Carregando o Modelo

Para carregar o modelo salvo e fazer previsões, utilize o seguinte código em Python:

```python
import pickle

with open('models/modelo.pkl', 'rb') as file:
    model = pickle.load(file)
````

## Contato
Para dúvidas ou sugestões, entre em contato:

-`Nome:`   Gustavo Silva

-`Email:`  gustavo616.silva@gmail.com

-`Github:` GustavoSSSSilva
