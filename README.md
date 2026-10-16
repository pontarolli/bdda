# Banco de Dados — Aulas

Material didático da disciplina **Banco de Dados (BDDA)**
do **Curso Técnico em Redes de Computadores** do **IFSP — Câmpus Boituva**.

- **Professores:** Rogerio dos Santos · Ricardo Pasquati Pontarolli
- **Contato:** pasquati@ifsp.edu.br
- **Carga horária:** 60 h (60 h em laboratório) — 2 aulas por semana
- **Formato das aulas:** slides em PDF (Beamer) gerados a partir de fontes Quarto/Markdown

---

## Como usar este repositório

As aulas estão na pasta [`aulas/`](aulas/), numeradas de **01 a 80**.

- Para **estudar**, abra o arquivo **`.pdf`** da aula (ex.: [`aulas/aula-01.pdf`](aulas/aula-01.pdf)).
- Cada aula também tem a **fonte editável** `.qmd` (mesmo nome), para quem quiser adaptar o conteúdo.
- As **avaliações** (`.gift`, com gabarito) ficam na pasta `aulas/` junto das aulas e **não** são publicadas.

> Dica: no GitHub, clique no arquivo `.pdf` e depois em **Download** para abrir os slides.

---

## Conteúdo por Bimestre

Cronograma com **72 aulas de conteúdo** (18 por bimestre) e **8 avaliações** (2 por bimestre), em formato **GIFT** para importação no Moodle (10 questões cada).

> As aulas são apresentações **Beamer (PDF)** geradas a partir das fontes `.qmd`.
> As avaliações (`.gift`) ficam na pasta `aulas/` e **não** são publicadas.

### 1º Bimestre — Fundamentos e Modelagem Conceitual

| # | Aula | PDF | Fonte (.qmd) |
|---|---|-----|-----|
| 01 | Apresentação da disciplina e metodologia | [aula-01](aulas/aula-01.pdf) | [.qmd](aulas/aula-01-apresentacao-disciplina.qmd) |
| 02 | Introdução ao conceito de dados | [aula-02](aulas/aula-02.pdf) | [.qmd](aulas/aula-02-introducao-conceito-de-dados.qmd) |
| 03 | De sistemas de arquivos a banco de dados | [aula-03](aulas/aula-03.pdf) | [.qmd](aulas/aula-03-sistemas-de-arquivos-a-bd.qmd) |
| 04 | Organização de dados e normalização: conceitos | [aula-04](aulas/aula-04.pdf) | [.qmd](aulas/aula-04-organizacao-dados-normalizacao.qmd) |
| 05 | Exercícios de normalização | [aula-05](aulas/aula-05.pdf) | [.qmd](aulas/aula-05-exercicios-normalizacao.qmd) |
| 06 | Tabelas e relacionamentos: abordagem lúdica | [aula-06](aulas/aula-06.pdf) | [.qmd](aulas/aula-06-tabelas-relacionamentos-ludico.qmd) |
| 07 | Estudo de caso comercial: o vendedor de pipoca | [aula-07](aulas/aula-07.pdf) | [.qmd](aulas/aula-07-estudo-de-caso-pipoca.qmd) |
| 08 | Análise de requisitos para banco de dados | [aula-08](aulas/aula-08.pdf) | [.qmd](aulas/aula-08-analise-de-requisitos.qmd) |
| 09 | Redação descritiva dos requisitos (minimundo) | [aula-09](aulas/aula-09.pdf) | [.qmd](aulas/aula-09-minimundo-requisitos.qmd) |
| 10 | Modelo Entidade-Relacionamento: visão geral | [aula-10](aulas/aula-10.pdf) | [.qmd](aulas/aula-10-modelo-er-visao-geral.qmd) |
| 11 | Entidades e tipos formais de representação | [aula-11](aulas/aula-11.pdf) | [.qmd](aulas/aula-11-entidades.qmd) |
| 12 | Atributos no modelo ER | [aula-12](aulas/aula-12.pdf) | [.qmd](aulas/aula-12-atributos.qmd) |
| 13 | Relacionamentos no modelo ER | [aula-13](aulas/aula-13.pdf) | [.qmd](aulas/aula-13-relacionamentos.qmd) |
| 14 | Cardinalidades e participação | [aula-14](aulas/aula-14.pdf) | [.qmd](aulas/aula-14-cardinalidades.qmd) |
| 15 | Chave primária: conceito | [aula-15](aulas/aula-15.pdf) | [.qmd](aulas/aula-15-chave-primaria-conceito.qmd) |
| 16 | Chave estrangeira: conceito | [aula-16](aulas/aula-16.pdf) | [.qmd](aulas/aula-16-chave-estrangeira-conceito.qmd) |
| 17 | Exercícios de fixação da modelagem | [aula-17](aulas/aula-17.pdf) | [.qmd](aulas/aula-17-exercicios-modelagem.qmd) |
| 18 | Síntese e revisão do 1º bimestre | [aula-18](aulas/aula-18.pdf) | [.qmd](aulas/aula-18-revisao-bimestre-1.qmd) |
| 19 | **Avaliação 1 (GIFT, 10 questões)** | — | `aula-19-avaliacao-b1-av1.gift` |
| 20 | **Avaliação 2 (GIFT, 10 questões)** | — | `aula-20-avaliacao-b1-av2.gift` |

### 2º Bimestre — SGBD e Criação de Tabelas com SQL

| # | Aula | PDF | Fonte (.qmd) |
|---|---|-----|-----|
| 21 | Introdução aos Sistemas Gerenciadores de Banco de Dados | [aula-21](aulas/aula-21.pdf) | [.qmd](aulas/aula-21-introducao-sgbd.qmd) |
| 22 | Componentes e arquitetura de um SGBD | [aula-22](aulas/aula-22.pdf) | [.qmd](aulas/aula-22-arquitetura-sgbd.qmd) |
| 23 | Introdução à linguagem DML | [aula-23](aulas/aula-23.pdf) | [.qmd](aulas/aula-23-introducao-dml.qmd) |
| 24 | Apresentando o SGBD MySQL | [aula-24](aulas/aula-24.pdf) | [.qmd](aulas/aula-24-apresentando-mysql.qmd) |
| 25 | Instalação e configuração do MySQL | [aula-25](aulas/aula-25.pdf) | [.qmd](aulas/aula-25-instalacao-mysql.qmd) |
| 26 | Primeiros passos: cliente modo texto | [aula-26](aulas/aula-26.pdf) | [.qmd](aulas/aula-26-cliente-modo-texto.qmd) |
| 27 | Clientes modo gráfico: MySQL Workbench | [aula-27](aulas/aula-27.pdf) | [.qmd](aulas/aula-27-cliente-modo-grafico.qmd) |
| 28 | Criando um banco de dados no MySQL | [aula-28](aulas/aula-28.pdf) | [.qmd](aulas/aula-28-criando-banco-de-dados.qmd) |
| 29 | Tipos de dados e campos | [aula-29](aulas/aula-29.pdf) | [.qmd](aulas/aula-29-tipos-de-dados.qmd) |
| 30 | Criando tabelas de dados no SGBD | [aula-30](aulas/aula-30.pdf) | [.qmd](aulas/aula-30-criando-tabelas.qmd) |
| 31 | Criando tabelas: o papel das chaves primárias | [aula-31](aulas/aula-31.pdf) | [.qmd](aulas/aula-31-tabelas-chave-primaria.qmd) |
| 32 | Criando tabelas: o papel das chaves estrangeiras | [aula-32](aulas/aula-32.pdf) | [.qmd](aulas/aula-32-tabelas-chave-estrangeira.qmd) |
| 33 | Criando tabelas e estabelecendo relacionamentos | [aula-33](aulas/aula-33.pdf) | [.qmd](aulas/aula-33-tabelas-relacionamentos.qmd) |
| 34 | Integridade referencial na prática | [aula-34](aulas/aula-34.pdf) | [.qmd](aulas/aula-34-integridade-referencial.qmd) |
| 35 | Preenchendo tabelas com dados | [aula-35](aulas/aula-35.pdf) | [.qmd](aulas/aula-35-preenchendo-tabelas.qmd) |
| 36 | Acessando o banco por outros programas | [aula-36](aulas/aula-36.pdf) | [.qmd](aulas/aula-36-acesso-outros-programas.qmd) |
| 37 | Prática: banco de dados completo | [aula-37](aulas/aula-37.pdf) | [.qmd](aulas/aula-37-pratica-banco-completo.qmd) |
| 38 | Síntese e revisão do 2º bimestre | [aula-38](aulas/aula-38.pdf) | [.qmd](aulas/aula-38-revisao-bimestre-2.qmd) |
| 39 | **Avaliação 1 (GIFT, 10 questões)** | — | `aula-39-avaliacao-b2-av1.gift` |
| 40 | **Avaliação 2 (GIFT, 10 questões)** | — | `aula-40-avaliacao-b2-av2.gift` |

### 3º Bimestre — Linguagem SQL: Consultas e Manipulação

| # | Aula | PDF | Fonte (.qmd) |
|---|---|-----|-----|
| 41 | Revisão e introdução à linguagem SQL | [aula-41](aulas/aula-41.pdf) | [.qmd](aulas/aula-41-introducao-sql.qmd) |
| 42 | O comando SELECT: estrutura geral | [aula-42](aulas/aula-42.pdf) | [.qmd](aulas/aula-42-comando-select.qmd) |
| 43 | SELECT: colunas, alias e DISTINCT | [aula-43](aulas/aula-43.pdf) | [.qmd](aulas/aula-43-select-colunas-alias.qmd) |
| 44 | SELECT ... WHERE: filtros básicos | [aula-44](aulas/aula-44.pdf) | [.qmd](aulas/aula-44-select-where.qmd) |
| 45 | WHERE: operadores de comparação e lógicos | [aula-45](aulas/aula-45.pdf) | [.qmd](aulas/aula-45-where-operadores.qmd) |
| 46 | WHERE: BETWEEN, IN, LIKE, IS NULL | [aula-46](aulas/aula-46.pdf) | [.qmd](aulas/aula-46-where-avancado.qmd) |
| 47 | SELECT: ordenação com ORDER BY | [aula-47](aulas/aula-47.pdf) | [.qmd](aulas/aula-47-order-by.qmd) |
| 48 | SELECT: funções de agregação | [aula-48](aulas/aula-48.pdf) | [.qmd](aulas/aula-48-funcoes-agregacao.qmd) |
| 49 | SELECT: agrupamento com GROUP BY | [aula-49](aulas/aula-49.pdf) | [.qmd](aulas/aula-49-group-by.qmd) |
| 50 | SELECT: filtrando grupos com HAVING | [aula-50](aulas/aula-50.pdf) | [.qmd](aulas/aula-50-having.qmd) |
| 51 | Funções de string e de data | [aula-51](aulas/aula-51.pdf) | [.qmd](aulas/aula-51-funcoes-string-data.qmd) |
| 52 | INSERT: inserindo dados | [aula-52](aulas/aula-52.pdf) | [.qmd](aulas/aula-52-insert.qmd) |
| 53 | INSERT: múltiplas linhas e valores padrão | [aula-53](aulas/aula-53.pdf) | [.qmd](aulas/aula-53-insert-multiplas-linhas.qmd) |
| 54 | UPDATE: atualizando dados | [aula-54](aulas/aula-54.pdf) | [.qmd](aulas/aula-54-update.qmd) |
| 55 | UPDATE ... WHERE: cuidados | [aula-55](aulas/aula-55.pdf) | [.qmd](aulas/aula-55-update-where-cuidados.qmd) |
| 56 | DELETE: excluindo dados | [aula-56](aulas/aula-56.pdf) | [.qmd](aulas/aula-56-delete.qmd) |
| 57 | Exercícios de fixação de SELECT | [aula-57](aulas/aula-57.pdf) | [.qmd](aulas/aula-57-exercicios-select.qmd) |
| 58 | Síntese e revisão do 3º bimestre | [aula-58](aulas/aula-58.pdf) | [.qmd](aulas/aula-58-revisao-bimestre-3.qmd) |
| 59 | **Avaliação 1 (GIFT, 10 questões)** | — | `aula-59-avaliacao-b3-av1.gift` |
| 60 | **Avaliação 2 (GIFT, 10 questões)** | — | `aula-60-avaliacao-b3-av2.gift` |

### 4º Bimestre — SQL Avançado, DDL e Integração com Aplicação

| # | Aula | PDF | Fonte (.qmd) |
|---|---|-----|-----|
| 61 | Mapeamento do modelo ER para o relacional | [aula-61](aulas/aula-61.pdf) | [.qmd](aulas/aula-61-mapeamento-er-relacional.qmd) |
| 62 | DDL: linguagem de definição de dados | [aula-62](aulas/aula-62.pdf) | [.qmd](aulas/aula-62-ddl-visao-geral.qmd) |
| 63 | DDL: CREATE TABLE | [aula-63](aulas/aula-63.pdf) | [.qmd](aulas/aula-63-create-table.qmd) |
| 64 | DDL: ALTER TABLE e DROP | [aula-64](aulas/aula-64.pdf) | [.qmd](aulas/aula-64-alter-table-drop.qmd) |
| 65 | Restrições: PRIMARY KEY e FOREIGN KEY | [aula-65](aulas/aula-65.pdf) | [.qmd](aulas/aula-65-constraints-pk-fk.qmd) |
| 66 | Restrições: NOT NULL, UNIQUE, CHECK e DEFAULT | [aula-66](aulas/aula-66.pdf) | [.qmd](aulas/aula-66-constraints-outras.qmd) |
| 67 | JOIN: juntando dados de tabelas | [aula-67](aulas/aula-67.pdf) | [.qmd](aulas/aula-67-join-conceitos.qmd) |
| 68 | INNER JOIN na prática | [aula-68](aulas/aula-68.pdf) | [.qmd](aulas/aula-68-inner-join.qmd) |
| 69 | LEFT e RIGHT JOIN | [aula-69](aulas/aula-69.pdf) | [.qmd](aulas/aula-69-left-right-join.qmd) |
| 70 | Subconsultas (subqueries) | [aula-70](aulas/aula-70.pdf) | [.qmd](aulas/aula-70-subconsultas.qmd) |
| 71 | Views e índices | [aula-71](aulas/aula-71.pdf) | [.qmd](aulas/aula-71-views-indices.qmd) |
| 72 | Transações e integridade | [aula-72](aulas/aula-72.pdf) | [.qmd](aulas/aula-72-transacoes-integridade.qmd) |
| 73 | Acesso ao banco de dados por uma aplicação | [aula-73](aulas/aula-73.pdf) | [.qmd](aulas/aula-73-acesso-por-aplicacao.qmd) |
| 74 | Conectando a aplicação ao banco: visão geral | [aula-74](aulas/aula-74.pdf) | [.qmd](aulas/aula-74-conectando-aplicacao.qmd) |
| 75 | Projeto final: modelagem de um negócio | [aula-75](aulas/aula-75.pdf) | [.qmd](aulas/aula-75-projeto-modelagem.qmd) |
| 76 | Projeto final: implementação no banco | [aula-76](aulas/aula-76.pdf) | [.qmd](aulas/aula-76-projeto-implementacao.qmd) |
| 77 | Recuperação e reavaliação | [aula-77](aulas/aula-77.pdf) | [.qmd](aulas/aula-77-recuperacao-e-reavaliacao.qmd) |
| 78 | Encerramento do ano letivo | [aula-78](aulas/aula-78.pdf) | [.qmd](aulas/aula-78-encerramento-ano-letivo.qmd) |
| 79 | **Avaliação 1 (GIFT, 10 questões)** | — | `aula-79-avaliacao-b4-av1.gift` |
| 80 | **Avaliação 2 (GIFT, 10 questões)** | — | `aula-80-avaliacao-b4-av2.gift` |

---

## Estrutura do repositório

```
.
├── README.md            # este arquivo (inclui o cronograma)
└── aulas/
    ├── aula-01.pdf      # slides (para estudar)
    ├── aula-01-*.qmd     # fonte editável (Quarto/Markdown)
    ├── aula-NN-avaliacao-*.gift  # avaliações (não publicadas)
    ├── images/          # ilustrações e diagramas
    └── ...
```

## Observações

- As **fontes** `.qmd` permitem editar o conteúdo e gerar novamente os PDFs com o Quarto.
- As aulas são apresentadas em **PDF (Beamer)** para leitura simples e impressão.
- Dúvidas e sugestões: fale com o professor.

## Licença

Material didático do IFSP. Uso educacional.
