# Conjunto de Dados

## Origem

Os dados utilizados neste projeto foram obtidos junto ao **Instituto Nacional de Meteorologia (INMET)**, órgão oficial do Governo Federal responsável pela coleta, armazenamento e divulgação de informações meteorológicas no território brasileiro.

As bases disponibilizadas pelo INMET são compostas por medições realizadas em estações meteorológicas automáticas distribuídas por todas as regiões do Brasil.

---

## Fonte Oficial

Instituto Nacional de Meteorologia (INMET)

Portal de Dados Meteorológicos:

https://portal.inmet.gov.br/

Download dos dados:

https://portal.inmet.gov.br/dadoshistoricos

---

## Período Utilizado

O projeto utiliza registros referentes ao ano de **2026**, contemplando dados meteorológicos horários provenientes das estações automáticas do INMET.

Os arquivos foram importados diretamente para o Microsoft Power BI utilizando o recurso de conexão com pasta (Folder), permitindo a consolidação automática dos arquivos em uma única tabela fato.

---

## Principais Variáveis

A base contém diversas variáveis meteorológicas, entre as quais destacam-se:

- Temperatura do ar;
- Temperatura máxima;
- Temperatura mínima;
- Temperatura do ponto de orvalho;
- Umidade relativa do ar;
- Pressão atmosférica;
- Precipitação horária;
- Radiação global;
- Velocidade do vento;
- Direção do vento.

Além dessas variáveis, cada registro contém informações sobre a estação meteorológica, data e horário da observação.

---

## Tratamento dos Dados

Durante o processo de preparação foram realizadas as seguintes etapas:

- remoção das linhas de cabeçalho presentes nos arquivos originais;
- padronização dos tipos de dados;
- criação das dimensões Calendário, Horário e Estação;
- consolidação dos arquivos em uma única tabela fato;
- criação das medidas analíticas utilizando DAX.

Todas as transformações foram implementadas no Power Query, garantindo reprodutibilidade e facilidade de atualização do modelo.

---

## Licença

Os dados são disponibilizados publicamente pelo Instituto Nacional de Meteorologia (INMET), observando as políticas de acesso e reutilização estabelecidas pelo Governo Federal.

Este projeto possui finalidade exclusivamente acadêmica e não realiza qualquer modificação na autoria ou propriedade intelectual dos dados utilizados.

---

## Observações

Devido ao volume do conjunto de dados, os arquivos originais podem não estar integralmente presentes neste repositório.

Para reproduzir o projeto, recomenda-se realizar o download diretamente no portal oficial do INMET e atualizar a conexão da pasta utilizada pelo Microsoft Power BI.