# Definição do Problema de Negócio

## Contexto

A crescente disponibilidade de dados meteorológicos possibilita que organizações utilizem informações climáticas como apoio ao planejamento operacional e à tomada de decisão. Entretanto, esses dados normalmente são disponibilizados em arquivos independentes, dificultando análises consolidadas e a extração de informações estratégicas.

Considerando esse cenário, este projeto simula a atuação de uma equipe de Business Intelligence responsável por desenvolver uma solução analítica para uma empresa fictícia do setor logístico, cuja operação é diretamente influenciada pelas condições meteorológicas observadas em diferentes regiões do país.

Para esse estudo foram utilizados dados oficiais disponibilizados pelo Instituto Nacional de Meteorologia (INMET), contemplando registros provenientes de estações meteorológicas automáticas distribuídas pelo território nacional.

---

# Problema de Negócio

A empresa necessita compreender como as condições climáticas variam entre regiões, estados e períodos do ano para subsidiar decisões relacionadas ao planejamento operacional.

Embora os dados estejam disponíveis publicamente, sua organização em diversos arquivos dificulta análises históricas, comparações geográficas e a identificação de padrões relevantes.

Dessa forma, o principal desafio consiste em transformar dados meteorológicos brutos em informações estruturadas que possam ser utilizadas como apoio à tomada de decisão.

A solução proposta consiste na construção de um ambiente de Business Intelligence capaz de consolidar os dados, disponibilizar indicadores estratégicos e permitir análises interativas por meio do Microsoft Power BI.

---

# Stakeholders

A solução foi desenvolvida considerando três perfis principais de usuários.

| Perfil                 | Responsabilidade                                                                         |
| ---------------------- | ---------------------------------------------------------------------------------------- |
| Diretoria              | Acompanhamento dos indicadores estratégicos e visão consolidada do ambiente operacional. |
| Gerência Operacional   | Monitoramento das condições climáticas e apoio ao planejamento das operações.            |
| Equipe de Planejamento | Análise histórica dos dados e identificação de padrões climáticos relevantes.            |

---

# Hipóteses Iniciais

Antes do desenvolvimento da solução foram estabelecidas as seguintes hipóteses:

* Existem diferenças significativas entre as condições meteorológicas observadas nas diferentes regiões brasileiras.
* Determinadas localidades apresentam maior frequência de precipitação ao longo do período analisado.
* A consolidação das informações em um ambiente analítico reduz significativamente o esforço necessário para obtenção de indicadores.
* A utilização de dashboards interativos facilita a identificação de tendências e padrões climáticos.

---

# Critérios de Sucesso

O projeto será considerado bem-sucedido caso os seguintes objetivos sejam alcançados:

* Consolidar todos os arquivos meteorológicos em um único modelo analítico;
* Disponibilizar indicadores confiáveis por meio de medidas desenvolvidas em DAX;
* Permitir análises por período, região, unidade federativa e estação meteorológica;
* Disponibilizar dashboards interativos que apoiem o processo de tomada de decisão;
* Demonstrar a aplicação dos principais conceitos estudados na disciplina de Business Intelligence II.

---

# Valor Entregue

A solução desenvolvida centraliza informações meteorológicas anteriormente distribuídas em diversos arquivos, permitindo consultas rápidas, análises comparativas e acompanhamento histórico das principais variáveis climáticas.

Além de atender aos requisitos acadêmicos da disciplina, o projeto demonstra a aplicação prática de conceitos de Engenharia de Dados e Business Intelligence, contemplando todas as etapas de construção de um ambiente analítico moderno, desde o processo de ETL até a disponibilização de dashboards interativos para apoio à decisão.
