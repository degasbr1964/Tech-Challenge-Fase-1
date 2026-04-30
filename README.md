## 🎯 Objetivo do Projeto

O objetivo deste projeto é compreender os fatores que influenciam o NPS (Net Promoter Score) de um e‑commerce e avaliar como dados operacionais podem antecipar a satisfação do cliente antes da aplicação da pesquisa.

O trabalho envolve:

- Entendimento do problema de negócio  
- Análise exploratória dos dados (EDA)  
- Identificação dos fatores críticos que impactam o NPS  
- Construção de um modelo preditivo  
- Geração de insights acionáveis para logística, atendimento e produto  

O foco é transformar dados brutos em informações úteis para tomada de decisão.

---

## 📊 Descrição da Base de Dados

A base utilizada contém informações completas sobre clientes, pedidos, logística e atendimento. Entre as variáveis disponíveis:

- **Cliente:** idade, região, tempo de relacionamento  
- **Pedido:** valor, quantidade de itens, descontos, parcelas  
- **Logística:** tempo de entrega, atraso, tentativas, valor do frete  
- **Atendimento:** número de contatos, reclamações, tempo de resolução  
- **Indicadores internos:** CSAT interno, recompra em 30 dias  
- **Variável alvo:** `nps_score` (0 a 10)

Esses dados permitem analisar a jornada completa do cliente e identificar pontos críticos que afetam sua percepção.

---

## 🧠 Metodologia Utilizada

A metodologia aplicada no notebook segue quatro etapas principais:

### 1. Entendimento do Negócio
- Papel do NPS no e‑commerce  
- Áreas impactadas  
- Relação entre NPS, recompra, boca a boca e market share  

### 2. Preparação dos Dados
- Leitura e inspeção da base  
- Tratamento de valores ausentes  
- Conversão de tipos  
- Criação de variáveis derivadas  

### 3. Análise Exploratória (EDA)
- Distribuição do NPS  
- Correlações entre variáveis  
- Identificação de fatores críticos (atraso, contatos, reclamações etc.)  
- Comparação entre perfis de clientes  

### 4. Modelo Preditivo
- Definição da variável alvo (classificação: detrator, neutro, promotor)  
- Separação entre treino e teste  
- Treinamento de modelos (ex.: Random Forest)  
- Avaliação por acurácia e matriz de confusão  
- Interpretação das features mais importantes  

---

## 🔁 Como Reproduzir os Resultados

### 1. Clonar o repositório
```bash
git clone https://github.com/degasbr1964/Certicard.git
```

### 2. Acessar o diretório
```bash
cd Certicard
```

### 3. Abrir o notebook
Use Jupyter Notebook, JupyterLab ou VS Code:

```bash
jupyter notebook
```

Abra o arquivo:

```
Tech_Challenge_Fase_1_Edgar.ipynb
```

### 4. Instalar dependências
Certifique‑se de ter instalado:

- Python 3.8+  
- pandas  
- numpy  
- matplotlib  
- seaborn  
- scikit-learn  

Instalação rápida:

```bash
pip install -r requirements.txt
```

*(Caso não exista um requirements.txt, instale manualmente os pacotes acima.)*

### 5. Executar as células em ordem
O notebook foi estruturado para execução sequencial. Basta rodar célula por célula.
