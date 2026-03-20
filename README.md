# Dashboard - Hospitais de Alta Complexidade em Oncologia (SUS)

## 📊 Objetivo do Projeto

Este projeto tem como objetivo **analisar e visualizar a distribuição de hospitais habilitados em alta complexidade em oncologia no Sistema Único de Saúde (SUS)**, permitindo a exploração interativa dos dados por:

* Estado (UF)
* Município
* Região do Brasil

O dashboard foi desenvolvido para apoiar:

* Análises exploratórias de dados em saúde pública
* Estudos acadêmicos e científicos
* Demonstrações de uso de dados abertos governamentais
* Construção de soluções analíticas com R e Shiny
* Transparência e visualização de políticas públicas em oncologia

A aplicação permite identificar rapidamente:

* Quantidade de hospitais habilitados no Brasil
* Distribuição por estado e município
* Concentração regional de serviços oncológicos
* Ranking dos municípios com maior número de hospitais habilitados

---

## 🌐 Aplicação em Produção

A aplicação está publicada e acessível em:

**APP online:**
https://webmatte.shinyapps.io/dashboard/

---

## 📁 Repositório do Projeto

Código-fonte disponível em:

**GitHub:**
https://github.com/andersonmatte/dashboard-oncologia-alta-complexidade

---

## 🗂️ Fonte de Dados (Insumos)

Os dados utilizados neste projeto são provenientes do portal oficial de dados abertos do Ministério da Saúde.

**Base de dados:**

Prevenção do Câncer de Colo e Mama — Hospitais habilitados em alta complexidade em oncologia.

Acesso ao dataset:

https://dadosabertos.saude.gov.br/dataset/mgdi-prevencao-do-cancer-de-colo-e-mama/resource/ccmhhcac_csv

Formato:

CSV (Comma-Separated Values)

Tipo de dados:

Dados administrativos de serviços habilitados no SUS.

---

## 📦 Tecnologias Utilizadas

Este projeto foi desenvolvido utilizando as seguintes tecnologias:

### Linguagem

* R

### Frameworks e Bibliotecas

* flexdashboard
* shiny
* tidyverse
* plotly
* DT
* scales

### Ferramentas de Desenvolvimento

* RStudio
* Git
* GitHub
* ShinyApps.io

---

## 🏗️ Arquitetura da Aplicação

A aplicação segue o modelo:

R + Shiny + Flexdashboard

Fluxo:

```text
CSV (Dados Abertos do SUS)
        ↓
Tratamento com tidyverse
        ↓
Renderização com flexdashboard
        ↓
Interatividade com Shiny
        ↓
Visualização com plotly
        ↓
Deploy em shinyapps.io
```

---

## 📊 Funcionalidades do Dashboard

O sistema apresenta:

### Filtros Interativos

* Seleção por Estado (UF)
* Seleção por Município

### Indicadores (KPIs)

* Total de hospitais no Brasil
* Total de hospitais no Estado
* Total de hospitais no Município

### Visualizações

* Gráfico de barras: Hospitais por Estado
* Ranking: Top Municípios com maior número de hospitais
* Gráfico de pizza: Distribuição por Região

---

## 🎯 Possíveis Aplicações

Este dashboard pode ser utilizado em:

* Análises epidemiológicas
* Planejamento em saúde pública
* Avaliação de cobertura assistencial
* Estudos acadêmicos
* Portfólios de ciência de dados
* Demonstração de uso de dados abertos governamentais
* Prototipação de sistemas de monitoramento em saúde

---

## 🚀 Como Executar o Projeto Localmente

### 1) Clonar o repositório

```bash
git clone https://github.com/andersonmatte/dashboard-oncologia-alta-complexidade
cd dashboard-oncologia-alta-complexidade
```

### 2) Abrir no RStudio

Abrir o arquivo:

```text
dashboard.Rmd
```

### 3) Executar o projeto

Clique em:

Run Document

ou:

```r
rmarkdown::run("dashboard.Rmd")
```

---

## ☁️ Deploy da Aplicação

O deploy foi realizado utilizando:

ShinyApps.io

Comando utilizado:

```r
rsconnect::deployApp()
```

---

## 📈 Evoluções Futuras

Possíveis melhorias:

* Inclusão de mapa geográfico interativo
* Séries temporais por competência
* Exportação de dados filtrados
* Integração com API do DataSUS
* Layout responsivo para dispositivos móveis
* Tema institucional do SUS
* Dashboard comparativo entre regiões

---

## 👨‍💻 Autor

Anderson Matte
Especialista em Arquitetura de Software e Soluções
Experiência em desenvolvimento, dados e sistemas para saúde

GitHub:
https://github.com/andersonmatte

LinkedIn:
https://www.linkedin.com/in/andersonmatte

---

## 📄 Licença

Este projeto utiliza dados públicos disponibilizados pelo Ministério da Saúde.

Uso livre para fins:

* Educacionais
* Científicos
* Demonstrativos
* Institucionais

Respeitando as políticas de dados abertos do governo federal.

---
