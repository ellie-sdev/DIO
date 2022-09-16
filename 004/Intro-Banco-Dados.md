# Introdução a Banco de Dados :file_folder:



### A diferença entre Dados e Informação

- **Dados** podem ser meros números, fatos não processados, não são específicos. Elementos "brutos".

- **Informação** é o que dá sentido ao que foi processado. Possui um significado detalhado a partir do trabalho com elementos mais brutos.

### A diferença entre BD e SGBD

- **Banco de dados** (BD ou Database) é uma coleção organizada de dados estruturados, normalmente armazenados eletronicamente em um sistema de computador. É o agrupamento de dados que tratam do mesmo assunto, e que precisam ser armazenados para segurança ou conferência futura. 

- **Sistema Gerenciador de Banco de Dados** (SGBD) serve para conseguir manipular as informações e tornar as rotinas de trabalho muito mais simples.

### Tipos de SGBS's

Oracle, MySQL, SQL Server, PostgreSQL, Mongo DB, Redis, ElasticSearch, Access, MariaDB, Cassandra, DB2.

Fatores que influenciam na escolha do SGBD: popularidade, tempo de mercado, documentação, robustez, confiabilidade, segurança, multiplataforma.

### Etapas de um SGBD de propósito geral MINI-MUNDO

- Definição: conceitualização, quais tipos de dados que vou utilizar, o que quero representar dentro do SGBD?, qual estrutura irei utilizar? etc.
- Construção: inserção dos dados, mapeamento, implementação da estrutura escolhidas, criação de comandos, determinação de um índice para auxílio, etc.
- Manipulação: em sua utilização, a recuperação e geração de relatórios. As informações coletadas são compiladas (transformadas em ling. de máq.), para serem retornadas. _Query_
- Compartilhamento: Simultaneidade, acesso. Há a necessidade de gerenciamento de acessos simultâneos. O BD bloqueia e libera temporariamente tabelas para modificações.

*QUERY = uma consulta (Query) é **qualquer comando usado para recuperar dados de uma tabela, realizado em Structured Query Language (SQL)**. Assim, a 'Query' é o requerimento ou a consulta enviada para o sistema em troca de informações.

- Proteção: réplicas, log, acesso, etc.

METADADOS= informações que fornecem uma descrição concisa dos dados contidos no BD.

### Breve histórico

- 1960 Criação do Conceito de BD 
- 1970 Modelo de BD Relacional 
- 1980 Uso de PC e Internet, aprimoração do MBDR
- 1990 POO - Orientação a objetos
- 2000 - Novas necessidades, SQL
- ISO/IEC 9075 SQL

### Tipos de Modelos de BD's

- Modelo de Banco de Dados Hierárquico: 
  - Pai/Filho; 
  - Estrutura em árvore/raiz;
  - Menos performance;
  - COBOL, FoxPro, Clipper.
- Modelo de Banco de Dados em Rede: 
  - Links - Ponteiros entre nós;
  - Estrutura em gráfico;
  - Complexo, mas menos rico;
  - CODASYL.
- Modelo de Banco de Dados Relacional:
  - Baseado na Teoria de Conjuntos - Álgebra relacional;
  - Relações entre as entidades, união de diferentes tipos de dados;
  - Tipos de usuários: 
    - Adm BD + Staff: LDD e a tradução = comandos específicos para definição dos dados. A linguagem.
    - Usuário: recuperação da informação.
  - Storage/ Buffer.
  - Integração de SGBD's

### Cenário da carreira de dados

- Carreira Tech em Data
  - Engenheiro de Dados: Desenho/ Construção/ Sustentação das Soluções de Dados;
  - Cientista de Dados: Modelagem/ Reconhecimento de Padrões/ Predição (previsão);
  - Analista de Dados: Representação das Informações/ Criação de Dashboards/ Apresentação visual dos dados/ Busca entender o comportamento do negócio a partir dos dados. Diagnóstico/ Identifica possiveis motivos para comportamentos e verifica métricas.
- Data-driven: abordagem, análise e Interpretação dos dados (analisar, entender, decidir); Área estratégia, gerenciamento, marketing; Customer Center (focado no consumidor), 3 V's;
- Novos modelos NoSQL (Not Only SQL) orientados à: documentos (Mongo), wide-columns (Cassandra), key-value/dicionário (Redis), grafos (Neo4j), orientação à objetos. Alto poder computacional. Utilizado sob demandas pontuais e comportamentos anormais (ex: Black Friday);
- DB & Cloud: BD como serviços - paga o que se usa. (Azure BD, Amazon Redshift, Amazon Aurora, DynamoDB, Amazon RDS).

### O contexto de uso dos SGBD's

- Papel Central - Sistemas Corporativos: uso de MIN/MÁX, COUNT/ MÉDIA/ SOMA; Negócios, vendas, etc.;
- Researching - Pesquisa Científica. Mapeamento de DNA/ Simulação de Farmácos/ Astronomia/ Meteorologia/ etc.; Pensa-se no poder computacional, o nº de tarefas computacionais, a quantidade de dados, heterogeneidade, computação paralela e distribuída.
- 4 º Paradigma: Científico. Uso de AI, Machine Learning, Detecção de padrões e anomalias dentro de redes e sistema de dados. 3V's: Volume, velocidade e variedade.
  - Modelos de paradigma anteriores: Empírico (experimental, tentativa-erro), Teórico (teoria) e computacional (sistemas simulados analisados computacionalmente).
  - Composição do problema, execução de teoria, análise, reutilização, reprodutividade, abstração e escalabilidade (larga escala). 
    - Experimentos realizados em larga escala: Paralelismo (múltiplos processadores operando concomitantemente); Big Data (Processamento paralelo de dados persistentes e particionados); Cloud (Recursos de terceiros. Soluções de tecnologia como serviço.

**HPC** = High Performance Computing. HPC ajuda a quebrar as barreiras enfrentadas por computadores convencionais, principalmente em relação à velocidade de processamento, flexibilidade, tolerância a falhas e custos de processamento. 

**Big Data** = dados com maior variedade que chegam em volumes crescentes e com velocidade cada vez maior. Isso também é conhecido como os três V's. Conjunto de dados maior e mais complexo, especialmente de novas fontes de dados.

​		
