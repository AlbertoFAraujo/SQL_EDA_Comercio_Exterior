![image](https://github.com/AlbertoFAraujo/SQL_EDA_Comercio_Exterior/assets/105552990/8d7f287c-4b8a-4ad5-ba45-30c5298eb8f4)

### Tecnologias utilizadas: 
| [<img align="center" alt="sql" height="60" width="60" src="https://github.com/AlbertoFAraujo/SQL_EDA_exercito2022/assets/105552990/805dfaf3-4725-47f9-86d5-241953a018ab">](https://learn.microsoft.com/en-us/sql/sql-server/?view=sql-server-ver16) | [<img align="center" alt="azure" height="60" width="60" src="https://github.com/AlbertoFAraujo/SQL_People_analytics/assets/105552990/a0848293-4573-431a-b7e4-2f79bc9cc32e">](https://azure.microsoft.com/pt-br/products/data-studio/) |
|:---:|:---:|
| SQL | Azure Data |

- **SQL**: Linguagem padrão para consulta e manipulação de bancos de dados relacionais, permitindo operações como consulta, inserção, atualização e exclusão de dados.
- **Azure Data Studio**: Ferramenta de gerenciamento de banco de dados desenvolvida pela Microsoft, permitindo desenvolvimento, administração e operações de bancos de dados relacionais e não relacionais, com suporte a múltiplos sistemas operacionais e extensões para funcionalidades adicionais.
<hr>

### Sobre a base de Dados e Objetivo

A área de comércio exterior de uma empresa automotiva, busca melhorar o monitoramento dos embarques de importação, implementando uma torre de controle eficiente. A empresa enfrenta desafios críticos, como paralisações na linha de produção devido a atrasos nas entregas, e precisa de uma visão completa das operações logísticas para tomar decisões mais inteligentes, encontrar oportunidades de melhoria e garantir o cumprimento dos prazos, minimizando o impacto em toda a cadeia de suprimentos.

O objetivo desta análise exploratória é responder as perguntas de negócios para posteriomente servir como base para o painel de visualização (Dashboard).

1. **Monitoramento de Operações:** Acompanhar as operações de importação, separadas por modal aéreo e marítimo;
2. **Indicadores de Entrega:** Avaliar o desempenho de entrega no prazo(*On Time Delivery*, também conhecido como OTD) para cada modal, comparando com metas pré-estabelecidas;
3. **Desempenho de Operadores:** Avaliar a performance de cada operador logístico (companhias de transporte) envolvidos nas entregas;
4. **Exceções:** Identificar e categorizar desvios e exceções (tipos de problemas) no processo logístico que afetam a entrega pontual;
5. **Quantidade de Embarque:** Número total de embarques realizados, separados por modal;
6. **OTD(*On Time Delivery*):** Percentual de entregas realizadas dentro do prazo para cada modal, comparado com a meta estabelecida;
7. **Ranking de Exceções:** Classificação dos principais tipos de exceções que causam desvio nas operações, como atrasos do fornecedor, avarias, problemas de documentação, etc;
8. **Desempenho por Operador:** Performance dos operadores logísticos(companhias de transporte), considerando a porcentagem de OTD e total de embarques;
9. **Tendência Mensal OTD:** Visualização de tendência mensal para identificar padrões de entregas ao longo do tempo.

> **Créditos da base de dados:** Dados sintéticos disponibilizados no Power Bi Discovery (Karine Lago e Letícia S.)

<hr>
