# BDDA — Banco de Dados

**Curso:** Técnico em Redes de Computadores Integrado ao Ensino Médio — IFSP Boituva
**Carga horária:** 60h (60h em laboratório) — 2 aulas/semana — 40 semanas (80 aulas)
**Professores:** Rogerio dos Santos · Ricardo Pasquati Pontarolli

Cronograma com **72 aulas de conteúdo** (18 por bimestre) e **8 avaliações** (2 por bimestre),
em formato **GIFT** para importação no Moodle (10 questões cada).

> As aulas são apresentações **Beamer (PDF)** geradas a partir das fontes `.qmd`.
> As avaliações ficam na pasta `avaliacoes/` em `.gift`.

---

## 1º Bimestre — Fundamentos e Modelagem Conceitual

| # | Aula | Arquivo |
|---|------|---------|
| 01 | Apresentação da disciplina e metodologia | `aula-01-apresentacao-disciplina.qmd` |
| 02 | Introdução ao conceito de dados | `aula-02-introducao-conceito-de-dados.qmd` |
| 03 | De sistemas de arquivos a banco de dados | `aula-03-sistemas-de-arquivos-a-bd.qmd` |
| 04 | Organização de dados e normalização: conceitos | `aula-04-organizacao-dados-normalizacao.qmd` |
| 05 | Exercícios de normalização | `aula-05-exercicios-normalizacao.qmd` |
| 06 | Tabelas e relacionamentos: abordagem lúdica | `aula-06-tabelas-relacionamentos-ludico.qmd` |
| 07 | Estudo de caso comercial: o vendedor de pipoca | `aula-07-estudo-de-caso-pipoca.qmd` |
| 08 | Análise de requisitos para banco de dados | `aula-08-analise-de-requisitos.qmd` |
| 09 | Redação descritiva dos requisitos (minimundo) | `aula-09-minimundo-requisitos.qmd` |
| 10 | Modelo Entidade-Relacionamento: visão geral | `aula-10-modelo-er-visao-geral.qmd` |
| 11 | Entidades e tipos formais de representação | `aula-11-entidades.qmd` |
| 12 | Atributos no modelo ER | `aula-12-atributos.qmd` |
| 13 | Relacionamentos no modelo ER | `aula-13-relacionamentos.qmd` |
| 14 | Cardinalidades e participação | `aula-14-cardinalidades.qmd` |
| 15 | Chave primária: conceito | `aula-15-chave-primaria-conceito.qmd` |
| 16 | Chave estrangeira: conceito | `aula-16-chave-estrangeira-conceito.qmd` |
| 17 | Exercícios de fixação da modelagem | `aula-17-exercicios-modelagem.qmd` |
| 18 | Síntese e revisão do 1º bimestre | `aula-18-revisao-bimestre-1.qmd` |
| — | **Avaliação 1 (GIFT, 10 questões)** | `avaliacoes/bimestre-1-avaliacao-1.gift` |
| — | **Avaliação 2 (GIFT, 10 questões)** | `avaliacoes/bimestre-1-avaliacao-2.gift` |

## 2º Bimestre — SGBD e Criação de Tabelas com SQL

| # | Aula | Arquivo |
|---|------|---------|
| 19 | Introdução aos Sistemas Gerenciadores de Banco de Dados | `aula-19-introducao-sgbd.qmd` |
| 20 | Componentes e arquitetura de um SGBD | `aula-20-arquitetura-sgbd.qmd` |
| 21 | Introdução à linguagem DML | `aula-21-introducao-dml.qmd` |
| 22 | Apresentando o SGBD MySQL | `aula-22-apresentando-mysql.qmd` |
| 23 | Instalação e configuração do MySQL | `aula-23-instalacao-mysql.qmd` |
| 24 | Primeiros passos: cliente modo texto | `aula-24-cliente-modo-texto.qmd` |
| 25 | Clientes modo gráfico: MySQL Workbench | `aula-25-cliente-modo-grafico.qmd` |
| 26 | Criando um banco de dados no MySQL | `aula-26-criando-banco-de-dados.qmd` |
| 27 | Tipos de dados e campos | `aula-27-tipos-de-dados.qmd` |
| 28 | Criando tabelas de dados no SGBD | `aula-28-criando-tabelas.qmd` |
| 29 | Criando tabelas: o papel das chaves primárias | `aula-29-tabelas-chave-primaria.qmd` |
| 30 | Criando tabelas: o papel das chaves estrangeiras | `aula-30-tabelas-chave-estrangeira.qmd` |
| 31 | Criando tabelas e estabelecendo relacionamentos | `aula-31-tabelas-relacionamentos.qmd` |
| 32 | Integridade referencial na prática | `aula-32-integridade-referencial.qmd` |
| 33 | Preenchendo tabelas com dados | `aula-33-preenchendo-tabelas.qmd` |
| 34 | Acessando o banco por outros programas | `aula-34-acesso-outros-programas.qmd` |
| 35 | Prática: banco de dados completo | `aula-35-pratica-banco-completo.qmd` |
| 36 | Síntese e revisão do 2º bimestre | `aula-36-revisao-bimestre-2.qmd` |
| — | **Avaliação 1 (GIFT, 10 questões)** | `avaliacoes/bimestre-2-avaliacao-1.gift` |
| — | **Avaliação 2 (GIFT, 10 questões)** | `avaliacoes/bimestre-2-avaliacao-2.gift` |

## 3º Bimestre — Linguagem SQL: Consultas e Manipulação

| # | Aula | Arquivo |
|---|------|---------|
| 37 | Revisão e introdução à linguagem SQL | `aula-37-introducao-sql.qmd` |
| 38 | O comando SELECT: estrutura geral | `aula-38-comando-select.qmd` |
| 39 | SELECT: colunas, alias e DISTINCT | `aula-39-select-colunas-alias.qmd` |
| 40 | SELECT ... WHERE: filtros básicos | `aula-40-select-where.qmd` |
| 41 | WHERE: operadores de comparação e lógicos | `aula-41-where-operadores.qmd` |
| 42 | WHERE: BETWEEN, IN, LIKE, IS NULL | `aula-42-where-avancado.qmd` |
| 43 | SELECT: ordenação com ORDER BY | `aula-43-order-by.qmd` |
| 44 | SELECT: funções de agregação | `aula-44-funcoes-agregacao.qmd` |
| 45 | SELECT: agrupamento com GROUP BY | `aula-45-group-by.qmd` |
| 46 | SELECT: filtrando grupos com HAVING | `aula-46-having.qmd` |
| 47 | Funções de string e de data | `aula-47-funcoes-string-data.qmd` |
| 48 | INSERT: inserindo dados | `aula-48-insert.qmd` |
| 49 | INSERT: múltiplas linhas e valores padrão | `aula-49-insert-multiplas-linhas.qmd` |
| 50 | UPDATE: atualizando dados | `aula-50-update.qmd` |
| 51 | UPDATE ... WHERE: cuidados | `aula-51-update-where-cuidados.qmd` |
| 52 | DELETE: excluindo dados | `aula-52-delete.qmd` |
| 53 | Exercícios de fixação de SELECT | `aula-53-exercicios-select.qmd` |
| 54 | Síntese e revisão do 3º bimestre | `aula-54-revisao-bimestre-3.qmd` |
| — | **Avaliação 1 (GIFT, 10 questões)** | `avaliacoes/bimestre-3-avaliacao-1.gift` |
| — | **Avaliação 2 (GIFT, 10 questões)** | `avaliacoes/bimestre-3-avaliacao-2.gift` |

## 4º Bimestre — SQL Avançado, DDL e Integração com Aplicação

| # | Aula | Arquivo |
|---|------|---------|
| 55 | Mapeamento do modelo ER para o relacional | `aula-55-mapeamento-er-relacional.qmd` |
| 56 | DDL: linguagem de definição de dados | `aula-56-ddl-visao-geral.qmd` |
| 57 | DDL: CREATE TABLE | `aula-57-create-table.qmd` |
| 58 | DDL: ALTER TABLE e DROP | `aula-58-alter-table-drop.qmd` |
| 59 | Restrições: PRIMARY KEY e FOREIGN KEY | `aula-59-constraints-pk-fk.qmd` |
| 60 | Restrições: NOT NULL, UNIQUE, CHECK e DEFAULT | `aula-60-constraints-outras.qmd` |
| 61 | JOIN: juntando dados de tabelas | `aula-61-join-conceitos.qmd` |
| 62 | INNER JOIN na prática | `aula-62-inner-join.qmd` |
| 63 | LEFT e RIGHT JOIN | `aula-63-left-right-join.qmd` |
| 64 | Subconsultas (subqueries) | `aula-64-subconsultas.qmd` |
| 65 | Views e índices | `aula-65-views-indices.qmd` |
| 66 | Transações e integridade | `aula-66-transacoes-integridade.qmd` |
| 67 | Acesso ao banco de dados por uma aplicação | `aula-67-acesso-por-aplicacao.qmd` |
| 68 | Conectando a aplicação ao banco: visão geral | `aula-68-conectando-aplicacao.qmd` |
| 69 | Projeto final: modelagem de um negócio | `aula-69-projeto-modelagem.qmd` |
| 70 | Projeto final: implementação no banco | `aula-70-projeto-implementacao.qmd` |
| 71 | Recuperação e reavaliação | `aula-71-recuperacao-e-reavaliacao.qmd` |
| 72 | Encerramento do ano letivo | `aula-72-encerramento-ano-letivo.qmd` |
| — | **Avaliação 1 (GIFT, 10 questões)** | `avaliacoes/bimestre-4-avaliacao-1.gift` |
| — | **Avaliação 2 (GIFT, 10 questões)** | `avaliacoes/bimestre-4-avaliacao-2.gift` |
