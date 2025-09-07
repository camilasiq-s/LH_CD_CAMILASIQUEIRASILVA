# Desafio de Ciência de Dados - Indicium Lighthouse

**Candidata:** Camila Siqueira Silva

## Nota Importante

Para uma visualização completa e interativa do notebook, incluindo os gráficos feitos com Plotly, por favor, utilize o seguinte link para abrir o projeto diretamente no Google Colab:  
[Abrir Notebook Interativo no Google Colab](https://colab.research.google.com/drive/1V0-7tbU68EDZi1Yj_-iu0mHR_c5qRIwl?usp=drive_link)

## Objetivo do Projeto

O objetivo deste projeto é explorar um dataset de filmes do **IMDb** para identificar os principais fatores que levam ao sucesso cinematográfico.  

A análise é voltada para fornecer recomendações estratégicas a um estúdio fictício de Hollywood, a **PProductions**, sobre quais tipos de filmes desenvolver para maximizar tanto o retorno financeiro quanto a aclamação do público.  

Além da análise exploratória para extrair insights de negócio, o projeto inclui o desenvolvimento de um modelo de **Machine Learning** capaz de prever a nota do IMDb de um filme com base em suas características.  

## Estrutura do Repositório

O projeto está organizado da seguinte forma:
- `/data`: Contém o dataset original `desafio_indicium_imdb.csv`.
- `/images`: Contém as imagens estáticas dos gráficos interativos para visualização no GitHub.
- `/notebooks`: Contém o notebook principal `LH_CD_CAMILASIQUEIRASILVA.ipynb` com toda a análise de dados e o desenvolvimento do modelo.
- `modelo_nota_imdb.pkl`: O modelo de Machine Learning treinado.
- `requirements.txt`: O arquivo com todas as dependências (pacotes utilizados e suas versões).

## Como Executar o Projeto

### Pré-requisitos

Para executar este notebook, é necessário ter o **Python 3.8+** instalado, além das bibliotecas listadas no arquivo `requirements.txt`.

### Instalação

**1. Clone o Repositório:**
```bash
git clone https://github.com/camilasiq-s/LH_CD_CAMILASIQUEIRASILVA.git
```

**2. Crie um Ambiente Virtual (Opcional, mas Recomendado):**

```bash
python -m venv venv
source venv/bin/activate  # No Windows: venv\Scripts\activate
```

**3. Instale as Dependências:**

```bash
pip install -r requirements.txt
```

**4. Abra o Notebook:**

```bash
jupyter notebook notebooks/LH_CD_CAMILASIQUEIRASILVA.ipynb
```

(ou abra diretamente no VS Code pelo caminho `notebooks/LH_CD_CAMILASIQUEIRASILVA.ipynb`)

## Principais Ferramentas Utilizadas

- **Linguagem:** Python
- **Bibliotecas:** Pandas, Seaborn, Matplotlib, Plotly, Scikit-learn, WordCloud, Joblib