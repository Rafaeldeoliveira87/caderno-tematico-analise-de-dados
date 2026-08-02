# 📊 Caderno Temático — Análise de Dados com Python

> Projeto de estudo desenvolvido a partir da curadoria de fontes e utilização do NotebookLM como ferramenta de apoio à pesquisa, organização do conhecimento e engenharia de prompts.

---

## 📌 Sobre o Projeto

Este projeto foi desenvolvido como parte do desafio de criação de um **Repositório Nota 10**, com o objetivo de demonstrar um processo estruturado de estudo utilizando inteligência artificial como ferramenta de apoio à aprendizagem.

O tema escolhido para o caderno temático foi **Análise de Dados com Python**, área de grande relevância no mercado de tecnologia e que combina conceitos de programação, estatística, manipulação de dados e geração de insights.

Durante o desenvolvimento do projeto, foram selecionadas fontes confiáveis e abertas sobre Python, Pandas, NumPy e Análise Exploratória de Dados (EDA). Esses materiais foram utilizados como fontes de conhecimento no NotebookLM.

A partir dessas fontes, foram desenvolvidos e testados diferentes prompts, buscando compreender como a formulação das perguntas influencia a qualidade, a organização e a profundidade das respostas geradas pela inteligência artificial.

O projeto também documenta as dificuldades encontradas durante o processo, os ajustes realizados nos prompts e os resultados obtidos, permitindo analisar a evolução da interação com a ferramenta.

---

## 🎯 Objetivos

### Objetivo Geral

Consolidar conhecimentos fundamentais sobre **Análise de Dados com Python** utilizando fontes confiáveis e ferramentas de inteligência artificial como apoio ao processo de estudo e pesquisa.

### Objetivos Específicos

* Compreender os fundamentos da análise de dados;
* Entender o papel do Python no processo de análise;
* Estudar a utilização da biblioteca Pandas;
* Conhecer os fundamentos da biblioteca NumPy;
* Compreender o conceito de Análise Exploratória de Dados (EDA);
* Identificar as principais etapas de um processo de análise de dados;
* Desenvolver técnicas de engenharia de prompts;
* Avaliar a qualidade das respostas geradas por IA;
* Documentar problemas e melhorias encontradas durante o processo;
* Criar um material de estudo reutilizável para futuras revisões.

---

## 📚 Tema Escolhido

### Análise de Dados com Python

A análise de dados consiste no processo de examinar, organizar, transformar e interpretar dados com o objetivo de identificar padrões, tendências e informações relevantes para apoiar a tomada de decisões.

Dentro desse contexto, o Python possui grande importância devido ao seu amplo ecossistema de bibliotecas voltadas para manipulação, processamento, análise e visualização de dados.

Este caderno temático concentra seus estudos principalmente nos seguintes conceitos:

* Fundamentos de Python;
* Manipulação de dados;
* DataFrames;
* Pandas;
* NumPy;
* Limpeza e preparação de dados;
* Análise Exploratória de Dados (EDA);
* Identificação de padrões e anomalias;
* Visualização de dados;
* Geração de insights.

---

# 🔎 Curadoria de Fontes

Para desenvolver o estudo, foram selecionadas fontes abertas e confiáveis relacionadas ao tema.

As fontes foram adicionadas ao NotebookLM e utilizadas como base para as pesquisas e perguntas realizadas durante o desenvolvimento do projeto.

| Nº | Fonte                               | Tema                  | Objetivo                                                        |
| -- | ----------------------------------- | --------------------- | --------------------------------------------------------------- |
| 1  | Python — Documentação Oficial       | Fundamentos de Python | Compreender os conceitos fundamentais da linguagem              |
| 2  | Pandas — Documentação Oficial       | Manipulação de dados  | Estudar estruturas e ferramentas para análise de dados          |
| 3  | NumPy — Documentação Oficial        | Computação numérica   | Compreender arrays e operações numéricas                        |
| 4  | IBM — Análise Exploratória de Dados | EDA                   | Estudar exploração, padrões, anomalias e interpretação de dados |

### Fontes utilizadas

* [Documentação oficial do Python](https://docs.python.org/pt-br/3/tutorial/index.html)
* [Documentação oficial do Pandas](https://pandas.pydata.org/pandas-docs/stable/getting_started/)
* [Documentação oficial do NumPy](https://numpy.org/doc/stable/user/)
* [IBM — Análise Exploratória de Dados](https://www.ibm.com/br-pt/think/topics/exploratory-data-analysis)

---

# 🤖 Uso do NotebookLM

O NotebookLM foi utilizado como ferramenta de apoio ao estudo e à organização do conhecimento.

As fontes selecionadas foram inseridas na ferramenta para permitir a realização de perguntas baseadas nos materiais previamente selecionados.

O objetivo não foi utilizar a inteligência artificial apenas para gerar respostas, mas também analisar como diferentes formas de elaboração de prompts poderiam influenciar os resultados obtidos.

O processo utilizado foi:

```text
Seleção do tema
       ↓
Curadoria das fontes
       ↓
Upload das fontes no NotebookLM
       ↓
Criação dos prompts iniciais
       ↓
Análise das respostas
       ↓
Identificação de problemas
       ↓
Aprimoramento dos prompts
       ↓
Comparação dos resultados
       ↓
Consolidação do conhecimento
       ↓
Criação do Miniguia de Estudo
```

---

# 🧠 Engenharia de Prompts

Durante o desenvolvimento do projeto, foram elaborados diferentes prompts com o objetivo de explorar o conteúdo das fontes e melhorar a qualidade das respostas.

O processo foi realizado de forma incremental, começando com perguntas mais simples e evoluindo para prompts mais estruturados e específicos.

## Exemplo de evolução

### Prompt inicial

> O que é análise de dados?

Esse prompt foi utilizado para obter uma visão inicial sobre o conceito.

### Prompt aprimorado

> Com base nas fontes disponíveis neste notebook, explique o que é análise de dados e apresente suas principais etapas.

A pergunta passou a delimitar melhor o objetivo da resposta.

### Prompt estruturado

> Com base exclusivamente nas fontes disponíveis neste notebook, explique o conceito de análise de dados. Organize a resposta em: definição, objetivos, principais etapas, ferramentas utilizadas e exemplos de aplicação. Ao final de cada seção, informe quais fontes foram utilizadas. Caso uma informação não esteja presente nas fontes, informe explicitamente.

Esse formato buscou obter uma resposta mais organizada, aprofundada e fundamentada nas fontes selecionadas.

A documentação completa dos prompts utilizados está disponível em:

📁 [`engenharia-de-prompts/`](./engenharia-de-prompts/)

---

# 🩹 Cicatrizes e Troubleshooting

Durante a interação com o NotebookLM, foram identificadas algumas dificuldades na obtenção das respostas desejadas.

Esses problemas foram documentados como parte do processo de aprendizagem e aprimoramento da engenharia de prompts.

## Problema 1 — Respostas genéricas

### Situação

Algumas perguntas iniciais produziram respostas muito amplas e pouco aprofundadas.

### Possível causa

O prompt utilizado não especificava o nível de detalhamento ou a estrutura esperada.

### Solução

Foram adicionadas instruções mais específicas, definindo os tópicos que deveriam ser abordados na resposta.

---

## Problema 2 — Falta de estrutura

### Situação

As informações apresentadas estavam corretas, porém não estavam organizadas de maneira adequada para estudo.

### Solução

Foi solicitado que as respostas fossem divididas em seções e tópicos, facilitando a leitura e a revisão posterior.

---

## Problema 3 — Necessidade de fundamentação nas fontes

### Situação

Foi necessário garantir que as respostas fossem baseadas nos materiais selecionados para o projeto.

### Solução

Os prompts passaram a solicitar explicitamente que o NotebookLM utilizasse as fontes disponíveis e identificasse as referências utilizadas.

---

## Aprendizado

A principal conclusão obtida durante esse processo foi que a qualidade da resposta depende não apenas da ferramenta utilizada, mas também da qualidade das instruções fornecidas.

Prompts mais específicos, contextualizados e estruturados tendem a produzir resultados mais adequados ao objetivo de estudo.

A documentação detalhada das dificuldades e soluções está disponível em:

📁 [`engenharia-de-prompts/cicatrizes.md`](./engenharia-de-prompts/cicatrizes.md)

---

# 📖 Miniguia de Estudo

Como resultado final do projeto, foi desenvolvido um miniguia consolidando os principais conhecimentos estudados.

O material está dividido em três partes:

### 📝 Resumo

Apresenta os principais conceitos estudados sobre análise de dados, Python, Pandas, NumPy e Análise Exploratória de Dados.

📁 [`miniguia/resumo.md`](./miniguia/resumo.md)

### 📚 Glossário

Reúne os principais termos e conceitos encontrados durante o estudo, acompanhados de suas respectivas definições.

📁 [`miniguia/glossario.md`](./miniguia/glossario.md)

### 🤖 Prompts Reutilizáveis

Apresenta prompts desenvolvidos durante o projeto que podem ser reutilizados para futuras sessões de estudo, revisão e aprofundamento.

📁 [`miniguia/prompts-reutilizaveis.md`](./miniguia/prompts-reutilizaveis.md)

---

# 💡 Principais Aprendizados

O desenvolvimento deste projeto permitiu compreender não apenas conceitos relacionados à análise de dados, mas também aspectos relacionados ao uso responsável e estratégico de ferramentas de inteligência artificial.

Entre os principais aprendizados estão:

* A importância da curadoria de fontes confiáveis;
* A necessidade de validar informações geradas por IA;
* A influência da qualidade do prompt na resposta obtida;
* A importância de fornecer contexto e delimitar objetivos;
* A utilização de fontes como base para respostas mais confiáveis;
* A importância de documentar erros e tentativas durante um processo de desenvolvimento;
* A possibilidade de utilizar IA como ferramenta de apoio à aprendizagem;
* A importância de transformar informações obtidas em conhecimento estruturado.

---

# 🚀 Conclusão

Este projeto representa um processo de aprendizagem baseado na combinação entre **pesquisa, curadoria de fontes, inteligência artificial e engenharia de prompts**.

A utilização do NotebookLM permitiu explorar os materiais selecionados de forma interativa, enquanto a documentação dos prompts e das dificuldades encontradas possibilitou analisar criticamente o processo de obtenção das informações.

O resultado final é um material estruturado que pode ser utilizado tanto como registro do processo de aprendizagem quanto como base para futuras revisões sobre **Análise de Dados com Python**.

---

## 👨‍💻 Autor

Projeto desenvolvido como parte de um desafio de aprendizagem e desenvolvimento de habilidades em tecnologia, análise de dados e engenharia de prompts.
