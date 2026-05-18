##  Miniguia de Estudo: Python Fundamental (Entrega Final)

Este miniguia consolida o conhecimento extraído e organizado através do NotebookLM, servindo como uma base sólida de consulta para estudantes e desenvolvedores iniciantes em Python.

## Objetivo:
A ideia principal é utilizar essas fontes primárias para um estudo profundo sobre o tema linguagem de programação Python.

Acontece que os livros que utilizei para os estudos estão desatualizados em algumas partes (embora ainda sejam ótimos). Com isso, achei melhor trazer também a documentação oficial do Python. Ao utilizá-la e aplicar prompts claros ao NotebookLM, garanti que, caso alguma informação dos livros não bata com o que a documentação oficial declara, a IA me avise e me ensine o que é utilizado atualmente, sabendo aproveitar o melhor do conteúdo dos livros.

Isso garante que eu utilize uma 'edição 2026' de cada livro, por assim dizer.

## Curadoria de Fontes:
As fontes utilzadas até o momento são:
- Documentação Python: https://docs.python.org/pt-br/3/contents.html
- Livro De Python: https://github.com/CodesdaLu/Programming-Books/blob/main/BACK-END/PYTHON/Livro%20de%20Python.pdf
- Livro De Python e (Automatize tarefas): https://github.com/CodesdaLu/Programming-Books/blob/main/BACK-END/PYTHON/Livro%20de%20Python%20(Automatize%20tarefas%20maçantes).pdf
- Data Science Do Zero Primeiras Regras Com O Python: https://github.com/CodesdaLu/Programming-Books/blob/main/BACK-END/PYTHON/Data%20Science%20do%20zero_%20Primeiras%20-%20Joel%20Grus.pdf


### 1. Resumos Estruturados do Assunto

#### A. Sintaxe Básica e Tipagem Dinâmica
Python é uma linguagem de alto nível, interpretada e de tipagem dinâmica. Isso significa que o tipo da variável é inferido em tempo de execução, dispensando a declaração explícita de tipos (embora o uso de *type hints* seja uma boa prática recomendada).
* **Identação:** Ao contrário de linguagens que usam chaves `{}`, Python utiliza a identação (espaços em branco) para definir blocos de código. Uma identação incorreta resulta em `IndentationError`.
* **Estruturas de Dados Nativas:** As principais estruturas para armazenamento de dados são Listas (mutáveis e ordenadas), Tuplas (imutáveis e ordenadas), Dicionários (chave-valor) e Conjuntos/Sets (elementos únicos não ordenados).

#### B. Estruturas de Controle e Funções
* **Condicionais:** Utiliza `if`, `elif` e `else` para desvio de fluxo.
* **Laços de Repetição:** O `for` é predominantemente utilizado para iterar sobre sequências (listas, strings, ranges), enquanto o `while` executa um bloco de código enquanto uma condição for verdadeira.
* **Funções (`def`):** Blocos de código reutilizáveis. Python incentiva o princípio DRY (*Don't Repeat Yourself*). Funções podem receber parâmetros posicionais, nomeados (`kwargs`) e retornar múltiplos valores.

#### C. Orientação a Objetos (POO) e Boas Práticas (PEP 8)
* **POO:** Python suporta totalmente o paradigma orientado a objetos, permitindo a criação de `classes`, encapsulamento, herança e polimorfismo.
* **PEP 8:** É o guia de estilo oficial para código Python. Ele dita regras como: uso de 4 espaços para identação, nomes de funções e variáveis em `snake_case`, e nomes de classes em `CamelCase`.

---

### 2. Glossário de Principais Conceitos

* **PEP 8:** *Python Enhancement Proposal nº 8*. O manual de estilo padrão para escrita de código limpo e legível em Python.
* **List Comprehension:** Uma forma concisa e performática de criar novas listas baseadas em listas existentes (ex: `[x**2 for x in range(10)]`).
* **Docstring:** Strings literais que aparecem logo no início de uma definição de função, classe ou módulo, utilizadas para documentação interna do código.
* **Dunder Methods (Double Under):** Métodos especiais que possuem duplo sublinhado no início e no fim (ex: `__init__`, `__str__`). Eles permitem interagir com as funcionalidades internas da linguagem (como inicialização de objetos ou sobrecarga de operadores).
* **Virtual Environment (venv):** Um ambiente isolado que permite instalar dependências de um projeto específico sem interferir no sistema operacional ou em outros projetos.
* **Zen of Python:** Uma coleção de 19 princípios de software que guiam o design da linguagem Python (pode ser lido executando `import this` no terminal).

---

### 3. Conjunto de Prompts Reutilizáveis para Revisão

Para apoiar revisões futuras ou expandir este caderno temático, utilize os seguintes prompts estruturados no NotebookLM ou em outras IAs:

#### Prompt 1: Revisão Teórica e Fixação de Conceitos
> "Com base nas fontes fornecidas sobre Python, aja como um tutor acadêmico e elabore um questionário com 5 perguntas de múltipla escolha sobre estruturas de dados (Listas, Tuplas e Dicionários). Após eu responder, forneça o gabarito comentado justificando o porquê de cada alternativa estar certa ou errada."

#### Prompt 2: Análise de Código e Engenharia Reversa
> "Analise o conceito de  Dunder Methods explicado nos textos e forneça um exemplo prático de código que seja simples, comentado linha por linha, e que siga estritamente as regras de estilo da PEP 8."

#### Prompt 3: Resumo Avançado focado em Analogias
> "Explique o funcionamento do conceito de Programação Orientada a Objetos em Python (focando em Classes e Herança) utilizando uma analogia com o mundo real (como carros ou gerenciamento de uma biblioteca). Mantenha a explicação simples e crie um resumo em tópicos ao final."
