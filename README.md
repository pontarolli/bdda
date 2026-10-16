# Banco de Dados — Aulas

Material didático da disciplina **Banco de Dados (BDDA)**
do **Curso Técnico em Redes de Computadores** do **IFSP — Câmpus Boituva**.

- **Professores:** Rogerio dos Santos · Ricardo Pasquati Pontarolli
- **Contato:** pasquati@ifsp.edu.br
- **Carga horária:** 60 h (60 h em laboratório) — 2 aulas por semana
- **Formato das aulas:** slides em PDF (Beamer) gerados a partir de fontes Quarto/Markdown

---

## Como usar este repositório

As aulas estão na pasta [`aulas/`](aulas/), numeradas de **01 a 72**.

- Para **estudar**, abra o arquivo **`.pdf`** da aula (ex.: [`aulas/aula-01.pdf`](aulas/aula-01.pdf)).
- Cada aula também tem a **fonte editável** `.qmd` (mesmo nome), para quem quiser adaptar o conteúdo.
- As **avaliações** ficam em `avaliacoes/` em formato **GIFT** (10 questões cada) e **não são publicadas** neste repositório (uso do professor no Moodle).

> Dica: no GitHub, clique no arquivo `.pdf` e depois em **Download** para abrir os slides.

---

## Conteúdo por Bimestre

### 1º Bimestre — Fundamentos e Modelagem Conceitual

| # | Aula | PDF |
|---|------|-----|
| 01 | Apresentação da disciplina e metodologia | [aula-01](aulas/aula-01.pdf) |
| 02 | Introdução ao conceito de dados | [aula-02](aulas/aula-02.pdf) |
| 03 | De sistemas de arquivos a banco de dados | [aula-03](aulas/aula-03.pdf) |
| 04 | Organização de dados e normalização: conceitos | [aula-04](aulas/aula-04.pdf) |
| 05 | Exercícios de normalização | [aula-05](aulas/aula-05.pdf) |
| 06 | Tabelas e relacionamentos: abordagem lúdica | [aula-06](aulas/aula-06.pdf) |
| 07 | Estudo de caso comercial: o vendedor de pipoca | [aula-07](aulas/aula-07.pdf) |
| 08 | Análise de requisitos para banco de dados | [aula-08](aulas/aula-08.pdf) |
| 09 | Redação descritiva dos requisitos (minimundo) | [aula-09](aulas/aula-09.pdf) |
| 10 | Modelo Entidade-Relacionamento: visão geral | [aula-10](aulas/aula-10.pdf) |
| 11 | Entidades e tipos formais de representação | [aula-11](aulas/aula-11.pdf) |
| 12 | Atributos no modelo ER | [aula-12](aulas/aula-12.pdf) |
| 13 | Relacionamentos no modelo ER | [aula-13](aulas/aula-13.pdf) |
| 14 | Cardinalidades e participação | [aula-14](aulas/aula-14.pdf) |
| 15 | Chave primária: conceito | [aula-15](aulas/aula-15.pdf) |
| 16 | Chave estrangeira: conceito | [aula-16](aulas/aula-16.pdf) |
| 17 | Exercícios de fixação da modelagem | [aula-17](aulas/aula-17.pdf) |
| 18 | Síntese e revisão do 1º bimestre | [aula-18](aulas/aula-18.pdf) |

### 2º Bimestre — SGBD e Criação de Tabelas com SQL

| # | Aula | PDF |
|---|------|-----|
| 19 | Introdução aos Sistemas Gerenciadores de Banco de Dados | [aula-19](aulas/aula-19.pdf) |
| 20 | Componentes e arquitetura de um SGBD | [aula-20](aulas/aula-20.pdf) |
| 21 | Introdução à linguagem DML | [aula-21](aulas/aula-21.pdf) |
| 22 | Apresentando o SGBD MySQL | [aula-22](aulas/aula-22.pdf) |
| 23 | Instalação e configuração do MySQL | [aula-23](aulas/aula-23.pdf) |
| 24 | Primeiros passos: cliente modo texto | [aula-24](aulas/aula-24.pdf) |
| 25 | Clientes modo gráfico: MySQL Workbench | [aula-25](aulas/aula-25.pdf) |
| 26 | Criando um banco de dados no MySQL | [aula-26](aulas/aula-26.pdf) |
| 27 | Tipos de dados e campos | [aula-27](aulas/aula-27.pdf) |
| 28 | Criando tabelas de dados no SGBD | [aula-28](aulas/aula-28.pdf) |
| 29 | Criando tabelas: o papel das chaves primárias | [aula-29](aulas/aula-29.pdf) |
| 30 | Criando tabelas: o papel das chaves estrangeiras | [aula-30](aulas/aula-30.pdf) |
| 31 | Criando tabelas e estabelecendo relacionamentos | [aula-31](aulas/aula-31.pdf) |
| 32 | Integridade referencial na prática | [aula-32](aulas/aula-32.pdf) |
| 33 | Preenchendo tabelas com dados | [aula-33](aulas/aula-33.pdf) |
| 34 | Acessando o banco por outros programas | [aula-34](aulas/aula-34.pdf) |
| 35 | Prática: banco de dados completo | [aula-35](aulas/aula-35.pdf) |
| 36 | Síntese e revisão do 2º bimestre | [aula-36](aulas/aula-36.pdf) |

### 3º Bimestre — Linguagem SQL: Consultas e Manipulação

| # | Aula | PDF |
|---|------|-----|
| 37 | Revisão e introdução à linguagem SQL | [aula-37](aulas/aula-37.pdf) |
| 38 | O comando SELECT: estrutura geral | [aula-38](aulas/aula-38.pdf) |
| 39 | SELECT: colunas, alias e DISTINCT | [aula-39](aulas/aula-39.pdf) |
| 40 | SELECT ... WHERE: filtros básicos | [aula-40](aulas/aula-40.pdf) |
| 41 | WHERE: operadores de comparação e lógicos | [aula-41](aulas/aula-41.pdf) |
| 42 | WHERE: BETWEEN, IN, LIKE, IS NULL | [aula-42](aulas/aula-42.pdf) |
| 43 | SELECT: ordenação com ORDER BY | [aula-43](aulas/aula-43.pdf) |
| 44 | SELECT: funções de agregação | [aula-44](aulas/aula-44.pdf) |
| 45 | SELECT: agrupamento com GROUP BY | [aula-45](aulas/aula-45.pdf) |
| 46 | SELECT: filtrando grupos com HAVING | [aula-46](aulas/aula-46.pdf) |
| 47 | Funções de string e de data | [aula-47](aulas/aula-47.pdf) |
| 48 | INSERT: inserindo dados | [aula-48](aulas/aula-48.pdf) |
| 49 | INSERT: múltiplas linhas e valores padrão | [aula-49](aulas/aula-49.pdf) |
| 50 | UPDATE: atualizando dados | [aula-50](aulas/aula-50.pdf) |
| 51 | UPDATE ... WHERE: cuidados | [aula-51](aulas/aula-51.pdf) |
| 52 | DELETE: excluindo dados | [aula-52](aulas/aula-52.pdf) |
| 53 | Exercícios de fixação de SELECT | [aula-53](aulas/aula-53.pdf) |
| 54 | Síntese e revisão do 3º bimestre | [aula-54](aulas/aula-54.pdf) |

### 4º Bimestre — SQL Avançado, DDL e Integração com Aplicação

| # | Aula | PDF |
|---|------|-----|
| 55 | Mapeamento do modelo ER para o relacional | [aula-55](aulas/aula-55.pdf) |
| 56 | DDL: linguagem de definição de dados | [aula-56](aulas/aula-56.pdf) |
| 57 | DDL: CREATE TABLE | [aula-57](aulas/aula-57.pdf) |
| 58 | DDL: ALTER TABLE e DROP | [aula-58](aulas/aula-58.pdf) |
| 59 | Restrições: PRIMARY KEY e FOREIGN KEY | [aula-59](aulas/aula-59.pdf) |
| 60 | Restrições: NOT NULL, UNIQUE, CHECK e DEFAULT | [aula-60](aulas/aula-60.pdf) |
| 61 | JOIN: juntando dados de tabelas | [aula-61](aulas/aula-61.pdf) |
| 62 | INNER JOIN na prática | [aula-62](aulas/aula-62.pdf) |
| 63 | LEFT e RIGHT JOIN | [aula-63](aulas/aula-63.pdf) |
| 64 | Subconsultas (subqueries) | [aula-64](aulas/aula-64.pdf) |
| 65 | Views e índices | [aula-65](aulas/aula-65.pdf) |
| 66 | Transações e integridade | [aula-66](aulas/aula-66.pdf) |
| 67 | Acesso ao banco de dados por uma aplicação | [aula-67](aulas/aula-67.pdf) |
| 68 | Conectando a aplicação ao banco: visão geral | [aula-68](aulas/aula-68.pdf) |
| 69 | Projeto final: modelagem de um negócio | [aula-69](aulas/aula-69.pdf) |
| 70 | Projeto final: implementação no banco | [aula-70](aulas/aula-70.pdf) |
| 71 | Recuperação e reavaliação | [aula-71](aulas/aula-71.pdf) |
| 72 | Encerramento do ano letivo | [aula-72](aulas/aula-72.pdf) |

---

## Estrutura do repositório

```
.
├── README.md            # este arquivo
├── cronograma.md        # cronograma completo (72 aulas + avaliações)
└── aulas/
    ├── aula-01.pdf      # slides (para estudar)
    ├── aula-01-*.qmd     # fonte editável (Quarto/Markdown)
    └── ...
```

## Observações

- As **fontes** `.qmd` permitem editar o conteúdo e gerar novamente os PDFs com o Quarto.
- As aulas são apresentadas em **PDF (Beamer)** para leitura simples e impressão.
- Dúvidas e sugestões: fale com o professor.

## Licença

Material didático do IFSP. Uso educacional.
