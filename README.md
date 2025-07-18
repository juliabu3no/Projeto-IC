# 📍 Localização de Unidades para Atendimento Soroterápico no Estado de São Paulo

## 📘 Sobre o Projeto

Este repositório reúne as análises, visualizações e modelos desenvolvidos no âmbito do projeto de Iniciação Científica da aluna **Júlia Campos Bueno Paz Perez**, do curso de **Bacharelado em Matemática Aplicada e Computação Científica** do **Instituto de Ciências Matemáticas e de Computação da Universidade de São Paulo (ICMC-USP)**, sob orientação da professora **Maristela Oliveira dos Santos (SME/ICMC/USP)**.

O projeto tem como foco a otimização da resposta do sistema de saúde público frente a **acidentes com animais peçonhentos**, com ênfase na análise e reestruturação da rede de **postos de atendimento com soros antiveneno** no estado de São Paulo. A investigação é conduzida a partir de modelos de **programação matemática**, métodos de **acessibilidade espacial** e **visualização interativa de dados**.

## 🎯 Objetivos

- Analisar a distribuição espacial dos acidentes com animais peçonhentos no estado de São Paulo (2007–2023).
- Avaliar o tempo de atendimento e a acessibilidade aos postos com soros disponíveis.
- Aplicar modelos de otimização para propor uma redistribuição mais eficiente dos recursos soroterápicos.
- Desenvolver uma plataforma interativa e acessível para apoiar a população e gestores públicos.

## 📊 Dados Utilizados

Os dados utilizados foram extraídos do **Sistema de Informação de Agravos de Notificação (SINAN)** por meio da plataforma **DATASUS**, e referem-se aos registros de acidentes com animais peçonhentos no estado de São Paulo entre os anos de **2007 e 2023**.  
Informações sobre a localização de postos com soro foram obtidas a partir do CVE/CIEVS:  
🔗 https://cievs.saude.sp.gov.br/soro/

## 📂 Acesso aos Dados

Os arquivos de dados utilizados neste projeto estão disponíveis no Google Drive:

🔗 [Clique aqui para acessar a pasta](https://drive.google.com/drive/folders/1hA8wW6yj9IABLPeNaE56vwUecN_v8xxz?usp=sharing)

> ⚠️ **Observação:** arquivos CSV com mais de 100 MB não são versionados diretamente neste repositório devido às limitações do GitHub.

## 🧑‍💻 Equipe do Projeto

- **Júlia Campos Bueno Paz Perez** — Aluna de Iniciação Científica (ICMC-USP)  
- **Profa. Maristela Oliveira dos Santos** — Orientadora (ICMC-USP)  

**Colaboradores:**

- **Docentes e Pesquisadores:**  
  - Cibele Maria Russo Novelli (ICMC-USP)  
  - Oilson Alberto Gonzatto Júnior (ICMC-USP)  
  - Hellen Geremias Gatica Santos (Fiocruz)  

- **Alunos:**  
  - Emanuel Victor da Silva Favorato (ICMC-USP)  
  - Karine Cerqueira Nascimento (ICMC-USP)  

## 🛠️ Tecnologias Utilizadas

- Python (Pandas, NumPy, Matplotlib, Seaborn, Plotly, Shiny, GeoPandas, NetworkX)
- OpenRouteService API
- GeoJSON + dados do OpenStreetMap

## 📦 Como Executar o Projeto

Siga os passos abaixo para instalar as dependências e executar os notebooks localmente:

```bash
# 1. Clone o repositório
git clone https://github.com/juliabu3no/Projeto-IC.git
cd seu-repositorio

# 2. (Opcional) Crie um ambiente virtual
python -m venv venv

# Ative o ambiente virtual:
# No Windows:
venv\Scripts\activate
# No macOS/Linux:
source venv/bin/activate

# 3. Instale as dependências
pip install -r requirements.txt
