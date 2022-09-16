# Introdução a Banco de Dados :file_folder:



### A diferença entre Dados e Informação

**Dados** podem ser meros números, fatos não processados, não são específicos. Elementos "brutos".

**Informação** é o que dá sentido ao que foi processado. Possui um significado detalhado a partir do trabalho com elementos mais brutos.

### A diferença entre BD e SGBD

Um **Banco de dados** (BD ou Database) é uma coleção organizada de dados estruturados, normalmente armazenados eletronicamente em um sistema de computador. É o agrupamento de dados que tratam do mesmo assunto, e que precisam ser armazenados para segurança ou conferência futura. 

Um **Sistema Gerenciador de Banco de Dados** (SGBD) serve para conseguir manipular as informações e tornar as rotinas de trabalho muito mais simples.

### Tipos de SGBS's

Oracle, DB2, MySQL, SQL Server, PostgreSQL.

### Etapas de um SGBD de propósito geral

- Definição: conceitualização, quais tipos de dados que vou utilizar, o que quero representar dentro do SGBD?, qual estrutura irei utilizar? etc.
- Construção: inserção dos dados, mapeamento, criação da estrutura escolhidas, criação de comandos, determinação de um índice para auxílio, etc.
- Manipulação: em sua utilização, a recuperação e geração de relatórios. As informações coletadas são compiladas (transformadas em ling. de máq.), para serem retornadas. _Query_
- Compartilhamento: Simultaneidade, acesso. Há a necessidade de gerenciamento de acessos simultâneos. O BD bloqueia e libera temporariamente tabelas para modificações.

*QUERY = uma consulta (Query) é **qualquer comando usado para recuperar dados de uma tabela, realizado em Structured Query Language (SQL)**. Assim, a 'Query' é o requerimento ou a consulta enviada para o sistema em troca de informações.

- Proteção: réplicas, log, acesso, etc.

METADADOS= informações que fornecem uma descrição concisa dos dados contidos no BD.

