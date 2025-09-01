# Análise de Salários em Data Science - Imersão Python Alura

![Status](https://img.shields.io/badge/Status-Concluído-brightgreen)

<p align="center">
  <img src="[LINK PARA UMA IMAGEM/GRÁFICO IMPACTANTE DO SEU PROJETO]" width="700">
</p>

*Uma análise completa sobre a remuneração no mercado de Dados, explorando fatores como nível de experiência, tipo de contrato, trabalho remoto e muito mais. Este projeto foi desenvolvido como parte da Imersão Python da Alura.*

---

## 🎯 Visão Geral do Projeto


O mercado de trabalho em ciência de dados e áreas afins é dinâmico e altamente influenciado por diversos fatores. Compreender a estrutura salarial nesse cenário é fundamental tanto para profissionais que buscam crescimento quanto para empresas que desejam se manter competitivas na atração e retenção de talentos. O objetivo deste projeto foi realizar uma análise exploratória aprofundada de um conjunto de dados de salários para desvendar os principais elementos que moldam a remuneração na área de dados.

Através desta análise, buscamos responder a perguntas cruciais como: Qual a distribuição geral dos salários? Como o nível de experiência impacta os ganhos? Quais cargos oferecem as maiores remunerações? A localização geográfica e o tamanho da empresa são fatores relevantes? Qual a influência do modelo de trabalho (remoto, presencial, híbrido) nos salários? Além disso, investigamos as tendências salariais ao longo do tempo para identificar a evolução do mercado.

Os resultados desta análise fornecem insights valiosos para profissionais e empresas, ajudando a orientar decisões de carreira, negociações salariais e estratégias de remuneração, contribuindo para uma compreensão mais clara do panorama salarial no campo da ciência de dados.

---

## 🗂️ Fonte de Dados


* **Dataset:** [https://raw.githubusercontent.com/guilhermeonrails/data-jobs/refs/heads/main/salaries.csv]
* **Origem:** [Imersao de Dados Python Alura 2025]
* **Descrição:** O conjunto de dados contém 133349 linhas e 11 colunas, incluindo informações sobre o cargo, salário em USD, nível de experiência, localização da empresa, entre outros.

---

## 🛠️ Ferramentas e Bibliotecas



* **Python 3.10**
* **Pandas:** para manipulação e limpeza dos dados.
* **Matplotlib & Seaborn:** para visualização de dados e criação de gráficos.
* **Jupyter Notebook:** como ambiente de desenvolvimento.
* **Git & GitHub:** para versionamento de código e hospedagem do projeto.

---

## 📈 Metodologia

*   **Limpeza e Preparação dos Dados**: O processo incluiu a verificação e tratamento de valores ausentes, a padronização de categorias (renomeamento de colunas e mapeamento de valores categóricos para termos mais descritivos) e a conversão de tipos de dados (como 'work_year' para inteiro) para garantir a qualidade da análise.
    
*   **Análise Exploratória de Dados (EDA)**: Foram geradas estatísticas descritivas e visualizações (histogramas, box plots) para entender a distribuição dos salários e as relações entre as diferentes variáveis (nível de experiência, cargo, localização, tamanho da empresa, status remoto, ano).
    
*   **Visualização de Insights**: Foram criados gráficos de barras, box plots, histogramas e um mapa para comunicar os principais achados de forma clara e objetiva.

---

## 🚀 Resultados e Principais Insights

*   **Insight 1**: O nível de experiência é um fator determinante para o salário. Com base em nossa análise, a média salarial aumenta significativamente com o nível de senioridade. (Podemos calcular a porcentagem exata se desejar, mas a visualização do box plot já demonstra claramente essa tendência).
  
*   **Insight 2**: Profissionais em regime de trabalho totalmente remoto (`remoto`) e presencial (`presencial`) apresentaram médias salariais mais elevadas em comparação com os que trabalham em regime híbrido (`hibrido`), com médias de aproximadamente \$151.077,66 e \$159.571,46, respectivamente, enquanto o regime híbrido teve uma média de aproximadamente \$80.706,48.
  
*   **Insight 3**: O cargo de **Research Team Lead** demonstrou ser o mais bem remunerado em nossa base de dados, com uma média salarial de \$450.000,00.
  
*   **Insight 4**: Países como **Estados Unidos (US)**, **Canadá (CA)** e **Austrália (AU)**, com um número significativo de vagas de Data Scientist, apresentaram as maiores médias salariais para cargos de ciência de dados.

*   **Insight 5**: Empresas de **grande porte (`Grande`)** e **médio porte (`Médio`)** oferecem salários médios consideravelmente mais altos (\$158.157,58 e \$157.717,34, respectivamente) em comparação com empresas de **pequeno porte (`Pequeno`)** (\$88.012,52).

*   **Insight 6**: A média salarial em USD tem mostrado uma **tendência geral de aumento** ao longo dos anos na base de dados, com um crescimento notável observado entre 2021 e 2024.

## 📂 Como Executar o Projeto

*Instruções simples para que outra pessoa possa rodar sua análise.*

```bash
# 1. Clone o repositório
git clone [https://github.com/andrelsrn/imersao-python-alura-2025.git](https://github.com/andrelsrn/imersao-python-alura-2025.git)

# 2. Navegue até o diretório
cd imersao-python-alura-2025

# 3. Abra o notebook no seu ambiente preferido (Jupyter, VSCode, etc.)
# O arquivo principal é o [COLOQUE O NOME DO SEU NOTEBOOK .ipynb AQUI]
