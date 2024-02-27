### Salsa Tecnology
# Teste Prático para a Vaga de Analista de Dados:
Descrição do Teste:
Você está encarregado de criar uma solução de gerenciamento de dados e relatórios para uma
empresa fictícia de apostas esportivas. Siga as etapas abaixo e apresente seus resultados em
um dashboard no Apache Superset:

# 1. Banco de Dados Relacional:
Crie uma base de dados relacional em um sistema de gerenciamento de banco de
dados de sua escolha (por exemplo, MySQL, PostgreSQL, SQL Server).
Defina as seguintes tabelas com campos relevantes:
    ○ Tabela "Jogadores" para armazenar informações sobre os jogadores.
    ○ Tabela "Eventos" para registrar eventos relacionados a apostas ou jogos.
    ○ Tabela "Depósitos" para rastrear depósitos de dinheiro dos jogadores.
    ○ Tabela "Apostas" para registrar as apostas feitas pelos jogadores.
Popular essas tabelas com valores fictícios, criando um conjunto de dados de tamanho
suficiente para gerar indicadores significativos. Certifique-se de que os dados sejam
realistas e variados.

# 2. ETL (Extract, Transform, Load):
Utilize uma ferramenta de ETL de sua escolha (por exemplo, Apache NiFi, Talend,
Azure Data Factory) para realizar as seguintes tarefas:
    ○ Extrair dados das tabelas de origem no banco de dados relacional.
    ○ Realizar transformações de dados, como agregações, filtragens ou cálculos,
para criar dados agregados significativos.
    ○ Carregar os dados transformados em uma nova base de dados, que pode ser no
mesmo servidor ou em outro local.

# 3. Desenvolvimento de Dashboards:
Utilize, preferencialmente, o Apache Superset para criar um ou mais dashboards que
apresentem indicadores e gráficos relevantes com base nos dados agregados. Caso
não consiga desenvolver no Superset você pode utilizar qualquer outra ferramenta do
seu conhecimento.
Os indicadores e gráficos podem incluir métricas como receita total, número de
jogadores ativos, eventos mais populares, depósitos e apostas por jogador, entre
outros. Sinta-se à vontade para usar sua criatividade para escolher os indicadores mais
relevantes.
Organize o dashboard de maneira intuitiva, com gráficos claros e legíveis, filtros, e, se
possível, painéis de controle interativos.
Critérios de Avaliação:

## Os candidatos serão avaliados com base nos seguintes critérios:
# Estrutura e Organização dos Dados: A qualidade da estrutura das tabelas de banco de
dados e a quantidade de dados fictícios gerados.
Qualidade do Fluxo ETL: A eficácia das etapas de extração, transformação e carga,
bem como a clareza e organização do processo ETL.
Qualidade do Dashboard: A clareza, a usabilidade e a relevância dos indicadores e
gráficos no dashboard.
Adaptação ao Apache Superset: A capacidade do candidato de utilizar o Apache
Superset para criar dashboards atraentes e informativos.

# Entrega do teste
O candidato deve fornecer um link para acesso ao dashboard, e, se possível, disponibilizar
acesso às bases de dados e ao fluxo ETL. Se não for possível fornecer acesso direto, essa
parte pode ser entregue por meio de uma breve documentação que explique o processo. A
documentação pode incluir capturas de tela, descrições, scripts e outros recursos utilizados no
desenvolvimento.