# Banco de Dados — Aulas

Material didático da disciplina **Banco de Dados (BDDA)**
do **Curso Técnico em Redes de Computadores** do **IFSP — Câmpus Boituva**.

- **Professores:** Rogerio dos Santos · Ricardo Pasquati Pontarolli
- **Contato:** pasquati@ifsp.edu.br
- **Carga horária:** 60 h (60 h em laboratório) — 2 aulas por semana
- **Formato das aulas:** slides em PDF (Beamer) gerados a partir de fontes Quarto/Markdown

---

## Como usar este repositório

As aulas estão na pasta [`aulas/`](aulas/), organizadas em **40 semanas** (`s01` a `s40`). Cada **semana** reúne as **2 aulas** do período num único arquivo.

- Para **estudar**, abra o arquivo **`.pdf`** da semana (ex.: [`aulas/s01.pdf`](aulas/s01.pdf)).
- Cada semana também tem a **fonte editável** `.qmd` (mesmo nome), para quem quiser adaptar o conteúdo.
- As **avaliações** (`.gift`, com gabarito) ficam na pasta `aulas/` junto das aulas e **não** são publicadas.

> Dica: no GitHub, clique no arquivo `.pdf` e depois em **Download** para abrir os slides.

---

## Plano de Ensino

> Baseado no **Plano de Ensino** e no **Plano de Aulas** do PPC do curso (arquivos `BTVBDDA.pdf` e `plano-de-aula.pdf`).

### Identificação

| Campo | Valor |
|---|---|
| Curso | Técnico em Redes de Computadores Integrado ao Ensino Médio |
| Componente curricular | Banco de Dados |
| Tipo | Obrigatório/Técnica |
| Núcleo | NET |
| Série | 2º |
| Sigla | BTVBDDA |
| Aulas semanais | 2 |
| Total de aulas | 80 |
| Carga horária presencial | 60 h |
| Carga horária em laboratório | 60 h |
| Docentes | Rogerio dos Santos · Ricardo Pasquati Pontarolli |

### Conhecimentos essenciais do currículo de referência

Programação/Redes de Computadores.

### Ementa

O componente curricular aborda fundamentos e conceitos de banco de dados e as técnicas para o projeto, implementação e uso de bancos de dados. Apresenta o modelo relacional, instalação e configuração de um sistema gerenciador de banco de dados, a manipulação de informações armazenadas por meio da linguagem SQL e o acesso a banco de dados a partir de uma linguagem de programação.

### Objetivos

- Compreender e utilizar modelos para definição e projeto de Banco de Dados;
- Aplicar ferramentas no desenvolvimento e manipulação de bancos de dados em um Sistema Gerenciador de Banco de Dados com comandos SQL padrão ANSI;
- Implementar e usar bancos de dados, com a linguagem SQL para criação, armazenamento e recuperação de dados e na integração com uma linguagem de programação.

### Conteúdo Programático

> Lista ordenada pela semana em que cada tópico é trabalhado (segue a ordem das aulas, de `s01` a `s40`). Os valores entre parênteses indicam as semanas correspondentes; marque o checkbox ao confirmar a cobertura.

- [ ] Introdução a Banco de Dados, Modelo Conceitual, Modelo Lógico e Modelo Físico (s01 a s04)
- [ ] Bases da análise de requisitos para elaboração do modelo conceitual (s04 a s06)
- [ ] Modelo Entidade-Relacionamento (s06 a s09)
- [ ] Instalação e configuração de um sistema gerenciador de bancos de dados (s11 a s14)
- [ ] Acesso ao banco de dados utilizando clientes modo texto e modo gráfico (s13 a s14)
- [ ] Modelo Relacional (s16 a s18, s31)
- [ ] Acesso ao banco de dados por uma aplicação (s19, s37)
- [ ] Linguagem SQL (s21 a s29)
- [ ] DML — *Data Manipulation Language* (s21 a s29)
- [ ] DDL — *Data Definition Language* (s31 a s33)
- [ ] Mapeamento do Modelo Entidade-Relacionamento para o Modelo Relacional (s31 a s33)

### Avaliação

**Instrumentos:** avaliação por exercícios em sala de aula; avaliação por projetos em laboratório; avaliação por instrumento escrito em sala de aula e em laboratório; avaliação da evolução individual.

**Critérios:** média simples de todas as notas do bimestre para as notas bimestrais; média simples de todas as notas para a nota final.

### Bibliografia Básica

- ROB, Peter; CORONEL, Carlos. *Sistemas de banco de dados: projeto, implementação e gerenciamento*. São Paulo: Cengage Learning, 2011.

### Bibliografia Complementar

- ELMASRI, Ramez; NAVATHE, Shamkant B. *Sistemas de banco de dados*. 6. ed. São Paulo: Pearson Education do Brasil, 2011.
- HEUSER, Carlos Alberto. *Projeto de banco de dados*. 6. ed. Porto Alegre: Bookman, 2009.
- SILBERSCHATZ, Abraham; KORTH, Henry F.; SUDARSHAN, S. *Sistema de banco de dados*. Rio de Janeiro: Elsevier, 2012.

---

## Conteúdo por Bimestre

Cronograma com **64 aulas de conteúdo** (16 por bimestre), organizadas em **32 semanas de 2 aulas** cada, e **8 avaliações** (2 por bimestre), em formato **GIFT** para importação no Moodle (10 questões cada).

### 1º Bimestre — Fundamentos e Modelagem Conceitual

| Semana | Conteúdo | PDF | Fonte (.qmd) |
|---|---|---|---|
| 1 | **Aula 1:** Apresentação da Disciplina e Metodologia · **Aula 2:** Introdução ao Conceito de Dados | [s01](aulas/s01.pdf) | [.qmd](aulas/s01.qmd) |
| 2 | **Aula 3:** De Sistemas de Arquivos a Banco de Dados · **Aula 4:** Organização de Dados e Normalização: Conceitos | [s02](aulas/s02.pdf) | [.qmd](aulas/s02.qmd) |
| 3 | **Aula 5:** Exercícios de Normalização · **Aula 6:** Tabelas e Relacionamentos: Abordagem Lúdica | [s03](aulas/s03.pdf) | [.qmd](aulas/s03.qmd) |
| 4 | **Aula 7:** Estudo de Caso Comercial: o Vendedor de Pipoca · **Aula 8:** Análise de requisitos e redação descritiva (minimundo) | [s04](aulas/s04.pdf) | [.qmd](aulas/s04.qmd) |
| 5 | **Avaliação 1 (GIFT, 10 questões)** | — | `s05-avaliacao-1.gift` |
| 6 | **Aula 9:** Modelo Entidade-Relacionamento: Visão Geral · **Aula 10:** Entidades e Tipos Formais de Representação | [s06](aulas/s06.pdf) | [.qmd](aulas/s06.qmd) |
| 7 | **Aula 11:** Atributos no Modelo ER · **Aula 12:** Relacionamentos no Modelo ER | [s07](aulas/s07.pdf) | [.qmd](aulas/s07.qmd) |
| 8 | **Aula 13:** Cardinalidades e Participação · **Aula 14:** Chave Primária: Conceito | [s08](aulas/s08.pdf) | [.qmd](aulas/s08.qmd) |
| 9 | **Aula 15:** Chave Estrangeira: Conceito · **Aula 16:** Exercícios de Fixação da Modelagem | [s09](aulas/s09.pdf) | [.qmd](aulas/s09.qmd) |
| 10 | **Avaliação 2 (GIFT, 10 questões)** | — | `s10-avaliacao-2.gift` |

### 2º Bimestre — SGBD e Criação de Tabelas com SQL

| Semana | Conteúdo | PDF | Fonte (.qmd) |
|---|---|---|---|
| 1 | **Aula 17:** Introdução aos Sistemas Gerenciadores de Banco de Dados · **Aula 18:** Componentes e Arquitetura de um SGBD | [s11](aulas/s11.pdf) | [.qmd](aulas/s11.qmd) |
| 2 | **Aula 19:** Introdução à Linguagem DML · **Aula 20:** Apresentando o SGBD MySQL | [s12](aulas/s12.pdf) | [.qmd](aulas/s12.qmd) |
| 3 | **Aula 21:** Instalação e Configuração do MySQL · **Aula 22:** Clientes MySQL: modo texto e Workbench | [s13](aulas/s13.pdf) | [.qmd](aulas/s13.qmd) |
| 4 | **Aula 23:** Criando um Banco de Dados no MySQL · **Aula 24:** Tipos de Dados e Campos | [s14](aulas/s14.pdf) | [.qmd](aulas/s14.qmd) |
| 5 | **Avaliação 1 (GIFT, 10 questões)** | — | `s15-avaliacao-1.gift` |
| 6 | **Aula 25:** Criando Tabelas de Dados no SGBD · **Aula 26:** Criando Tabelas: o Papel das Chaves Primárias | [s16](aulas/s16.pdf) | [.qmd](aulas/s16.qmd) |
| 7 | **Aula 27:** Criando Tabelas: o Papel das Chaves Estrangeiras · **Aula 28:** Criando Tabelas e Estabelecendo Relacionamentos | [s17](aulas/s17.pdf) | [.qmd](aulas/s17.qmd) |
| 8 | **Aula 29:** Integridade Referencial na Prática · **Aula 30:** Preenchendo Tabelas com Dados | [s18](aulas/s18.pdf) | [.qmd](aulas/s18.qmd) |
| 9 | **Aula 31:** Acessando o Banco por Outros Programas · **Aula 32:** Prática: Banco de Dados Completo | [s19](aulas/s19.pdf) | [.qmd](aulas/s19.qmd) |
| 10 | **Avaliação 2 (GIFT, 10 questões)** | — | `s20-avaliacao-2.gift` |

### 3º Bimestre — Linguagem SQL: Consultas e Manipulação

| Semana | Conteúdo | PDF | Fonte (.qmd) |
|---|---|---|---|
| 1 | **Aula 33:** Revisão e Introdução à Linguagem SQL · **Aula 34:** O Comando SELECT: Estrutura Geral | [s21](aulas/s21.pdf) | [.qmd](aulas/s21.qmd) |
| 2 | **Aula 35:** SELECT: Colunas, Alias e DISTINCT · **Aula 36:** SELECT ... WHERE: Filtros Básicos | [s22](aulas/s22.pdf) | [.qmd](aulas/s22.qmd) |
| 3 | **Aula 37:** WHERE: Operadores de Comparação e Lógicos · **Aula 38:** WHERE: BETWEEN, IN, LIKE e IS NULL | [s23](aulas/s23.pdf) | [.qmd](aulas/s23.qmd) |
| 4 | **Aula 39:** SELECT: Ordenação com ORDER BY · **Aula 40:** SELECT: Funções de Agregação | [s24](aulas/s24.pdf) | [.qmd](aulas/s24.qmd) |
| 5 | **Avaliação 1 (GIFT, 10 questões)** | — | `s25-avaliacao-1.gift` |
| 6 | **Aula 41:** SELECT: Agrupamento com GROUP BY · **Aula 42:** SELECT: Filtrando Grupos com HAVING | [s26](aulas/s26.pdf) | [.qmd](aulas/s26.qmd) |
| 7 | **Aula 43:** Funções de String e de Data · **Aula 44:** INSERT: inserindo dados | [s27](aulas/s27.pdf) | [.qmd](aulas/s27.qmd) |
| 8 | **Aula 45:** UPDATE: Atualizando Dados · **Aula 46:** UPDATE ... WHERE: Cuidados | [s28](aulas/s28.pdf) | [.qmd](aulas/s28.qmd) |
| 9 | **Aula 47:** DELETE: Excluindo Dados · **Aula 48:** Exercícios de Fixação de SELECT | [s29](aulas/s29.pdf) | [.qmd](aulas/s29.qmd) |
| 10 | **Avaliação 2 (GIFT, 10 questões)** | — | `s30-avaliacao-2.gift` |

### 4º Bimestre — SQL Avançado, DDL e Integração com Aplicação

| Semana | Conteúdo | PDF | Fonte (.qmd) |
|---|---|---|---|
| 1 | **Aula 49:** Mapeamento do Modelo ER para o Relacional · **Aula 50:** DDL: Linguagem de Definição de Dados | [s31](aulas/s31.pdf) | [.qmd](aulas/s31.qmd) |
| 2 | **Aula 51:** DDL: CREATE TABLE, ALTER e DROP · **Aula 52:** Restrições: PRIMARY KEY e FOREIGN KEY | [s32](aulas/s32.pdf) | [.qmd](aulas/s32.qmd) |
| 3 | **Aula 53:** Restrições: NOT NULL, UNIQUE, CHECK e DEFAULT · **Aula 54:** JOIN: Juntando Dados de Tabelas | [s33](aulas/s33.pdf) | [.qmd](aulas/s33.qmd) |
| 4 | **Aula 55:** INNER JOIN na Prática · **Aula 56:** LEFT e RIGHT JOIN | [s34](aulas/s34.pdf) | [.qmd](aulas/s34.qmd) |
| 5 | **Avaliação 1 (GIFT, 10 questões)** | — | `s35-avaliacao-1.gift` |
| 6 | **Aula 57:** Subconsultas (Subqueries) · **Aula 58:** Views e Índices | [s36](aulas/s36.pdf) | [.qmd](aulas/s36.qmd) |
| 7 | **Aula 59:** Transações e Integridade · **Aula 60:** Acesso ao banco de dados por uma aplicação | [s37](aulas/s37.pdf) | [.qmd](aulas/s37.qmd) |
| 8 | **Aula 61:** Projeto Final: Modelagem de um Negócio · **Aula 62:** Projeto Final: Implementação no Banco | [s38](aulas/s38.pdf) | [.qmd](aulas/s38.qmd) |
| 9 | **Aula 63:** Recuperação e Reavaliação · **Aula 64:** Encerramento do Ano Letivo | [s39](aulas/s39.pdf) | [.qmd](aulas/s39.qmd) |
| 10 | **Avaliação 2 (GIFT, 10 questões)** | — | `s40-avaliacao-2.gift` |

---


## Estrutura do repositório

```
.
├── README.md            # este arquivo (inclui o cronograma)
└── aulas/
    ├── s01.pdf         # slides da semana (para estudar)
    ├── s01.qmd         # fonte editável (Quarto/Markdown)
    ├── s05-avaliacao-1.gift      # avaliações (não publicadas)
    ├── images/         # ilustrações e diagramas
    └── ...
```

## Observações

- As **fontes** `.qmd` permitem editar o conteúdo e gerar novamente os PDFs com o Quarto.
- As aulas são apresentadas em **PDF (Beamer)** para leitura simples e impressão.
- Dúvidas e sugestões: fale com o professor.

## Licença

Material didático do IFSP. Uso educacional.
