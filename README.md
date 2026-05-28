# 📊 Generation Brasil | Análise de Dados

Aplicações práticas, automações e pipelines de dados desenvolvidos durante o Bootcamp de Análise de Dados da **Generation Brasil**. O objetivo deste repositório é consolidar o domínio técnico em engenharia de dados (ingestão e ETL), análise exploratória (EDA), modelagem e visualização de dados voltados para tomadas de decisão de negócio.

---

## 🚀 Arquitetura Técnica e Stack de Ferramentas

Para a resolução dos desafios de negócios e exercícios propostos, foram utilizadas boas práticas de engenharia de software e análise de dados:

*   **Linguagem Core:** Python 3.x
*   **Manipulação e Engenharia de Dados:** `pandas`, `numpy`
*   **Ingestão e Conexão de APIs:** `kagglehub`, `requests` (Integrações GET/POST)
*   **Visualização de Dados:** `matplotlib`, `seaborn`
*   **Ambientes de Desenvolvimento:** Google Colab, Jupyter Notebooks
*   **Gestão de Projetos & Versionamento:** Git/GitHub sob metodologia ágil

---

## 📁 Estrutura de Módulos e Projetos

O repositório está estruturado de forma incremental, refletindo a evolução das competências em dados:

### 1. Ingestão e Automação de Dados (`/importar_dados_kaggle.ipynb`)
*   **Foco:** Construção de pipelines automatizados para extração de bases de dados.
*   **Solução:** Integração direta com a API do Kaggle através da biblioteca `kagglehub` para download automatizado de datasets estruturados (como o histórico de avaliações da Netflix).
*   **Conceitos Aplicados:** Gerenciamento de variáveis de ambiente, manipulação de caminhos de arquivos do sistema (`os`), persistência de arquivos CSV e reprodutibilidade de pipelines de ingestão.

### 2. Manipulação, Limpeza e Tratamento (ETL)
*   Tratamento de dados ausentes, duplicados e conversão de tipos primitivos.
*   Manipulação de séries temporais com Pandas (ex: transformação de strings em objetos `datetime` e agregação por períodos mensais/anuais).
*   Estruturação de dados para Data Warehouses ou ferramentas de BI.

### 3. Análise Exploratória de Dados (EDA) & Data Viz
*   Agrupamento de dados (`groupby`), tabelas dinâmicas (`pivot_table`) e técnicas de decupagem de dados (`unstack`).
*   Construção de gráficos de distribuição, tendência temporal (gráficos de área/linha) e volumetria de dados para identificação de padrões de comportamento.

---

## 🛠️ Como Executar os Projetos

### Pré-requisitos
Certifique-se de ter o Python 3.8+ instalado e as chaves de API necessárias (caso utilize os scripts do Kaggle).

1. Clone o repositório:
```bash
   git clone [https://github.com/iThaysCambi/Generation-Exercicios.git](https://github.com/iThaysCambi/Generation-Exercicios.git)

2. Instale as dependências necessárias: 

   pip install pandas numpy matplotlib seaborn kagglehub

3. Caso prefira rodar no ecossistema cloud, os notebooks contêm suporte nativo para execução direta via Google Colab.
