# 📊 Análise de Emissões de Títulos - Debêntures, CRIs e CRAs (2017-2024)

Este projeto realiza uma análise exploratória de dados sobre emissões de **Debêntures**, **CRIs** e **CRAs** no mercado de capitais brasileiro desde 2017. O objetivo principal é identificar padrões e tendências ao longo do tempo, explorar a sazonalidade e analisar a atuação dos coordenadores financeiros, setores e segmentos envolvidos.

---

## 📋 Objetivo do Projeto

Este projeto foi desenvolvido para:  

1. **Analisar a Atuação dos Coordenadores** - Avaliar a frequência, impacto e estratégias dos coordenadores financeiros nas emissões.  
2. **Explorar Sazonalidade e Evolução Temporal** - Estudar padrões mensais, sazonais e anuais na captação.  
3. **Avaliar Contribuições por Setor e Segmento** - Identificar setores com maior relevância e impacto financeiro.  
4. **Fornecer Insights Estratégicos** - Apoiar investidores e instituições financeiras na tomada de decisão.  

---

## 📚 Conteúdo do Projeto

- **Coordenadores**: Informações detalhadas sobre as instituições financeiras responsáveis pela organização das ofertas.  
- **Emissões e Valores**: Dados sobre valores emitidos, cronologia das ofertas e tipos de títulos.  
- **Análise Temporal e Sazonalidade**: Evolução das ofertas ao longo do tempo e sazonalidade por mês e estação.  
- **Setores e Segmentos**: Impacto financeiro e número de ofertas por setor e segmento econômico.  

---

## 🗂️ Descrição dos Dados

Os dados foram extraídos diretamente do site oficial da [ANBIMA Data](https://data.anbima.com.br/) e incluem informações detalhadas sobre ofertas públicas de **Debêntures**, **CRIs** e **CRAs**.  

### Principais Colunas:
- **Código da Oferta:** Identificador único para cada oferta pública.  
- **Coordenador e Coordenador Líder:** Instituições financeiras responsáveis pela organização e condução das emissões.  
- **Emissor:** Empresa ou entidade que realizou a emissão dos títulos.  
- **Tipo de Título (TVM):** Classificação do título como **Debêntures**, **CRI** ou **CRA**.  
- **Valor Total Emitido:** Valor total captado por meio da emissão, em reais.  
- **Quantidade de Coordenadores:** Número de instituições envolvidas na condução da oferta.  
- **Datas:** Informações sobre as datas de início, registro e encerramento das ofertas.  
- **Setor e Segmento:** Classificação ANBIMA do setor e segmento do emissor ou devedor.  

---

## 🔍 Principais Conclusões

### 📈 Evolução Temporal
- **2021:** Crescimento significativo, impulsionado pela recuperação econômica pós-pandemia.  
- **2024:** Queda nas emissões de **CRI** e **CRA**, atribuída a mudanças regulatórias.  

### 📅 Sazonalidade
- **Mensal:**  
  - **Dezembro** tem o maior número de ofertas.  
  - **Junho** registra o maior valor total emitido.  
- **Estacional:**  
  - **Verão (Dezembro-Fevereiro):** Mais ofertas.  
  - **Inverno (Junho-Agosto):** Maior valor captado.  
- **Por Tipo de Título:**  
  - Diferenças sazonais para **Debêntures**, **CRI** e **CRA**.  
- **Por Coordenador:**  
  - Estratégias diferenciadas entre coordenadores, com picos de atividade em períodos específicos.  

### 🏢 Setores e Segmentos
- **Setores Líderes:**  
  - **Energia Elétrica, Transporte e Logística e Saneamento** lideram em valor emitido.  
- **Emissões Recorrentes:**  
  - Estratégias contínuas de captação indicam flexibilidade e planejamento financeiro.  
- **Segmentos Relevantes:**  
  - **Infraestrutura, Serviços Financeiros e Indústria** se destacam no valor captado.  

---

## 🛠️ Tecnologias Utilizadas

- **Linguagem:** Python  
- **Bibliotecas:** Pandas, NumPy, Matplotlib, Seaborn, SciPy  
- **Análise Estatística:** Testes t de Student e Correlação de Spearman  
- **Visualização de Dados:** Gráficos dinâmicos e comparativos  
- **Manipulação de Dados:** Tratamento de datas, strings e categorização  


