# 🚛 Dashboard de Análise Logística

<p align="center">
  <img src="https://github.com/pedrolucas-gr/Dashboard-Desempenho-Logistico/blob/main/Images/Capa.png" alt="Dashboard de Análise Logística" width="100%">
</p>

---

# 📖 Sobre o Projeto

O **Dashboard de Análise Logística** foi desenvolvido em **Power BI** com o objetivo de transformar dados operacionais em informações estratégicas, permitindo acompanhar o desempenho logístico da empresa por meio de indicadores visuais e interativos.

O projeto consolida informações de fretes e da frota de veículos para analisar faturamento, pedidos, atrasos, devoluções e desempenho operacional, auxiliando na tomada de decisão baseada em dados.

---

# 🎯 Objetivos

- Monitorar indicadores logísticos.
- Acompanhar o faturamento ao longo do tempo.
- Identificar atrasos nas entregas.
- Analisar os principais motivos das devoluções.
- Avaliar o desempenho da frota.
- Apoiar decisões estratégicas através de dashboards.

---

# 📊 Dashboard

<p align="center">
<img src="https://github.com/pedrolucas-gr/Dashboard-Desempenho-Logistico/blob/main/Images/Dahboard.png" width="100%">
</p>

O dashboard permite explorar os dados através de filtros e visualizações dinâmicas, facilitando a análise dos principais indicadores logísticos.

### KPIs monitorados

- 💰 Receita Bruta
- 📦 Total de Pedidos
- ⏰ Entregas Atrasadas
- 🔄 Total de Devoluções

### Análises disponíveis

- Receita por Ano
- Status dos Pedidos
- Motivos das Devoluções
- Devoluções por Tipo de Baú
- Ranking de Veículos
- Distribuição Geográfica das Devoluções

---

# 🛠 Tecnologias Utilizadas

| Tecnologia | Aplicação |
|------------|-----------|
| Power BI | Desenvolvimento do Dashboard |
| Power Query | ETL e transformação dos dados |
| DAX | Construção das medidas |
| Microsoft Excel | Base de dados |
| Modelagem de Dados | Relacionamento entre tabelas |

---

# 🗂 Modelagem de Dados

<p align="center">
<img src="https://github.com/pedrolucas-gr/Dashboard-Desempenho-Logistico/blob/main/Images/Modelagem.png" width="85%">
</p>

O modelo foi desenvolvido utilizando uma estrutura composta por **Tabela Fato** e **Tabela Dimensão**, permitindo análises mais organizadas e eficientes.

## 📄 Base Fretes.xlsx

Tabela responsável pelos registros das operações logísticas.

Principais informações:

- Documento Fiscal
- Cliente
- Data do Pedido
- Data de Entrega
- Valor da Mercadoria
- Status
- Devolução
- Código do Veículo
- Peso

---

## 🚚 Base CadastroVeiculos.xlsx

Tabela contendo os dados da frota.

Principais informações:

- Código do Veículo
- Marca
- Tipo de Veículo
- Tipo de Baú
- Ano
- Placa

---

## 🔗 Relacionamento

As tabelas são relacionadas através do **Código do Veículo**, permitindo enriquecer as análises operacionais com informações da frota.

---

# 📈 Principais Indicadores

| Indicador | Descrição |
|------------|-----------|
| Receita Bruta | Valor total faturado |
| Pedidos | Quantidade de pedidos registrados |
| Entregas Atrasadas | Total de entregas fora do prazo |
| Devoluções | Total de pedidos devolvidos |

---

# 💡 Insights Gerados

Com o dashboard é possível identificar:

- Evolução do faturamento ao longo dos anos.
- Veículos com maior participação nas operações.
- Principais motivos das devoluções.
- Tipo de baú com maior incidência de devoluções.
- Distribuição geográfica das devoluções.
- Percentual de entregas realizadas dentro e fora do prazo.

---

# 📂 Estrutura do Projeto

```text
📦 Dashboard-Desempenho-Logistico
│
├── 📁 BaseDados
│   ├── Fretes.xlsx
│   └── CadastroVeiculos.xlsx
│
├── 📁 Images
│   ├── capa.png
│   ├── dashboard.png
│   └── modelagem.png
│
├── Dashboard.pbix
└── README.md
```

---

# 🚀 Como Executar

1. Clone o repositório.

```bash
git clone https://github.com/pedrolucas-gr/Dashboard-Desempenho-Logistico.git
```

2. Abra o arquivo **Dashboard.pbix** utilizando o **Power BI Desktop**.

3. Caso necessário, atualize o caminho das bases de dados.

4. Atualize o modelo para visualizar todas as informações.

---

# 📚 Aprendizados

Durante o desenvolvimento deste projeto foram aplicados conhecimentos em:

- Modelagem de Dados
- ETL com Power Query
- Criação de Medidas em DAX
- Desenvolvimento de KPIs
- Storytelling com Dados
- Visualização de Dados
- Dashboards Executivos

---

# 👨‍💻 Autor

Desenvolvido por **Pedro Lucas**

- 💼 LinkedIn: https://www.linkedin.com/in/pedrolucasrodriguesdata/
- 📧 E-mail: pedrolucaspbi@gmail.com

---
