# README

# Projeto Final — Business Intelligence II

## Análise de Dados Meteorológicos utilizando Microsoft Power BI

### Visão Geral

Este projeto foi desenvolvido como requisito parcial para aprovação na disciplina **Business Intelligence II**, ministrada pelo **MsC Pedro H. Mello**, no Centro Universitário de Brasília (CEUB).

O objetivo consiste no desenvolvimento de uma solução completa de Business Intelligence, contemplando todas as etapas de um projeto analítico: definição do problema de negócio, construção do processo de ETL, modelagem dimensional, implementação de indicadores em DAX, aplicação de Segurança em Nível de Linha (RLS) e desenvolvimento de dashboards interativos.

A solução foi construída utilizando dados meteorológicos oficiais disponibilizados pelo **Instituto Nacional de Meteorologia (INMET)**.

---

# Problema de Negócio

Empresas que dependem diretamente das condições climáticas, como organizações dos setores de logística, transporte, agricultura e infraestrutura, necessitam monitorar continuamente variáveis meteorológicas para subsidiar decisões operacionais.

Embora os dados do INMET sejam públicos, encontram-se distribuídos em diversos arquivos, dificultando consultas consolidadas, análises históricas e comparações entre regiões.

Este projeto propõe a construção de um ambiente analítico capaz de transformar dados meteorológicos brutos em informações estratégicas por meio de um Data Warehouse e de painéis desenvolvidos no Microsoft Power BI.

---

# Fonte dos Dados

**Instituto Nacional de Meteorologia (INMET)**

Portal Oficial:

https://portal.inmet.gov.br/

Período utilizado no projeto:

**Janeiro a Maio de 2026**

Formato original dos dados:

* CSV

---

# Tecnologias Utilizadas

| Tecnologia                 | Finalidade                        |
| -------------------------- | --------------------------------- |
| Microsoft Power BI Desktop | Desenvolvimento dos dashboards    |
| Power Query                | Processo de ETL                   |
| DAX                        | Construção das medidas analíticas |
| Power BI Project (.pbip)   | Versionamento do projeto          |
| Git e GitHub               | Controle de versão                |

---

# Arquitetura da Solução

```text
Arquivos CSV (INMET)
          │
          ▼
Processo ETL (Power Query)
          │
          ▼
Modelo Dimensional (Star Schema)
          │
          ▼
Medidas Analíticas (DAX)
          │
          ▼
Dashboards Interativos
```

---

# Modelo Dimensional

O modelo foi desenvolvido seguindo o padrão **Star Schema**, composto por uma tabela fato e três tabelas dimensão.

### Tabela Fato

* Fato_Clima

### Tabelas Dimensão

* DimCalendario
* DimHorario
* DimEstacao

A modelagem adotada permite análises temporais, geográficas e operacionais de forma eficiente, reduzindo redundâncias e facilitando a criação de indicadores analíticos.

---

# Principais Indicadores

Os principais indicadores implementados são:

* Temperatura Média;
* Temperatura Máxima;
* Temperatura Mínima;
* Precipitação Total;
* Umidade Média;
* Pressão Média;
* Velocidade Média do Vento;
* Dias com Chuva;
* Amplitude Térmica;
* Ranking das Estações.

---

# Dashboards

O relatório foi organizado em três páginas analíticas.

## Visão Executiva

Apresenta os principais indicadores climáticos consolidados, permitindo uma visão geral do comportamento das variáveis meteorológicas.

## Análise Comparativa

Permite comparar regiões, unidades federativas e estações meteorológicas por meio de gráficos interativos.

## Evolução Temporal

Apresenta a evolução histórica dos indicadores ao longo do período analisado, permitindo identificar tendências e padrões climáticos.

---

# Segurança em Nível de Linha (RLS)

Foram implementados dois papéis distintos para demonstrar o funcionamento da Segurança em Nível de Linha.

| Papel            | Acesso                                      |
| ---------------- | ------------------------------------------- |
| Diretoria        | Acesso completo ao modelo                   |
| Gerente Regional | Visualização restrita à Região Centro-Oeste |

---

# Estrutura do Repositório

```text
.
├── README.md
├── docs/
├── data/
├── apresentacao/
├── imagens/
└── pbip/
```

---

# Como Executar

1. Clonar o repositório.
2. Abrir a pasta **pbip**.
3. Abrir o arquivo **Projeto_Final.pbip** utilizando o Microsoft Power BI Desktop.
4. Atualizar o caminho da pasta contendo os arquivos CSV, caso necessário.
5. Atualizar o modelo para carregar os dados.

---

# Autores

**Artur Nemer Xavier Costa**

**João Marcelo Campos Fafá**

Centro Universitário de Brasília – CEUB

Disciplina: **Business Intelligence II**

Professor: **MsC Pedro H. Mello**

---

# Licença

Este projeto foi desenvolvido exclusivamente para fins acadêmicos.

Os dados utilizados pertencem ao Instituto Nacional de Meteorologia (INMET) e foram empregados apenas para demonstração dos conceitos estudados na disciplina.
# Analise-de-dados-INMET
