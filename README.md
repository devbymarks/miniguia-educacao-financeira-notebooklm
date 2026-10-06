# 📚 Miniguia de Educação Financeira com NotebookLM

> Projeto desenvolvido para o desafio da DIO sobre o uso da Inteligência Artificial como ferramenta de aprendizagem ativa.

## 📌 Sobre o projeto

Este projeto apresenta a construção de um caderno temático no **NotebookLM** sobre **educação financeira pessoal**, utilizando fontes abertas e confiáveis para estudar, comparar conceitos e organizar conhecimentos.

Os principais temas abordados são:

- organização do orçamento pessoal;
- receitas e despesas;
- juros simples e compostos;
- reserva de emergência;
- liquidez, risco, inflação e rentabilidade;
- engenharia de prompts para aprendizagem.

> ⚠️ **Aviso:** este projeto possui finalidade exclusivamente educacional e não representa recomendação individual de investimento.

---

## 🎯 Objetivos

### Objetivo geral

Compreender fundamentos da educação financeira pessoal e utilizar a Inteligência Artificial como apoio ao processo de aprendizagem.

### Objetivos específicos

1. Entender a função do orçamento pessoal.
2. Diferenciar receitas, despesas fixas e variáveis.
3. Compreender juros simples e compostos.
4. Identificar os efeitos dos juros em investimentos e dívidas.
5. Entender a finalidade de uma reserva de emergência.
6. Conhecer conceitos básicos de liquidez, risco, inflação e rentabilidade.
7. Criar prompts reutilizáveis para estudos no NotebookLM.

---

## 🤖 Uso do NotebookLM

O NotebookLM foi utilizado como ferramenta de apoio para:

- analisar fontes selecionadas;
- resumir conteúdos;
- comparar conceitos;
- gerar perguntas de estudo;
- criar glossários;
- testar diferentes prompts;
- organizar o conhecimento;
- validar respostas utilizando as fontes disponíveis.

A proposta não é apenas obter respostas da IA, mas desenvolver uma **aprendizagem ativa**, fazendo perguntas melhores, comparando resultados e verificando as informações nas fontes originais.

---

## 📚 Fontes utilizadas

Foram selecionadas fontes abertas, priorizando materiais oficiais e introdutórios.

| Nº | Fonte | Instituição | Formato |
|---|---|---|---|
| 1 | Caderno de Educação Financeira — Gestão de Finanças Pessoais | Banco Central do Brasil | PDF |
| 2 | Orçamento Pessoal | Banco Central do Brasil | PDF |
| 3 | Glossário Simplificado de Termos Financeiros | Banco Central do Brasil | PDF |
| 4 | Juros Simples e Compostos | Portal do Investidor / Governo Federal | Texto |
| 5 | Tesouro Selic | Tesouro Direto | Texto |

As referências completas estão em [`fontes/fontes-utilizadas.md`](fontes/fontes-utilizadas.md).

---

## 🧠 Engenharia de Prompts

Durante o projeto foram testados prompts simples e posteriormente aprimorados.

### Exemplo

**Prompt inicial:**

> Resuma as fontes sobre educação financeira.

O resultado tende a ser genérico.

**Prompt aprimorado:**

> Usando somente as fontes adicionadas ao caderno, produza um resumo introdutório sobre educação financeira para uma pessoa sem conhecimento prévio. Organize a resposta em quatro partes: orçamento pessoal, controle de despesas, juros e reserva de emergência. Em cada parte, apresente a ideia principal, um exemplo cotidiano e as fontes utilizadas.

### Aprendizado

Prompts mais específicos, com objetivo, público, formato e restrições bem definidos, tendem a gerar respostas mais organizadas e úteis.

Os prompts utilizados no projeto estão disponíveis em [`prompts/prompts-testados.md`](prompts/prompts-testados.md).

---

# 📖 Miniguia de Estudo

## 1. Orçamento pessoal

O orçamento pessoal permite visualizar receitas, despesas e objetivos financeiros. Ele ajuda a entender quanto dinheiro entra, quanto sai e onde os recursos estão sendo utilizados.

### Passos iniciais

1. Registrar todas as receitas.
2. Registrar todas as despesas.
3. Separar os gastos por categorias.
4. Comparar receitas e despesas.
5. Identificar gastos que podem ser reduzidos.
6. Definir uma meta de economia.
7. Revisar o orçamento mensalmente.

### Exemplo

| Categoria | Valor |
|---|---:|
| Receita mensal | R$ 3.000 |
| Despesas essenciais | R$ 1.800 |
| Despesas variáveis | R$ 800 |
| Valor disponível | R$ 400 |

---

## 2. Receitas e despesas

### Receita

Dinheiro recebido em determinado período, como salário, comissão ou prestação de serviços.

### Despesa fixa

Gasto recorrente que tende a variar pouco, como aluguel ou mensalidade.

### Despesa variável

Gasto que pode mudar conforme o consumo, como lazer, alimentação e compras.

### Despesa imprevista

Gasto não planejado, como reparos, emergências ou redução inesperada de renda.

---

## 3. Juros simples e compostos

### Juros simples

A taxa incide sobre o capital inicial.

Exemplo com R$ 1.000, 1% ao mês durante 12 meses:

- juros totais: R$ 120;
- montante: R$ 1.120.

### Juros compostos

Os juros acumulados passam a fazer parte da base dos cálculos seguintes.

Com R$ 1.000, 1% ao mês durante 12 meses:

- montante aproximado: **R$ 1.126,83**.

A diferença tende a aumentar conforme aumentam o prazo, a taxa e o valor envolvido.

---

## 4. Reserva de emergência

A reserva de emergência é um valor separado para lidar com situações inesperadas ou períodos de redução de renda.

Alguns pontos importantes:

- segurança;
- disponibilidade;
- liquidez;
- planejamento;
- construção gradual.

O valor adequado depende da realidade de cada pessoa, de suas despesas e da estabilidade de sua renda.

### Exemplo de construção

Guardando R$ 400 por mês:

| Período | Total acumulado* |
|---|---:|
| 1 mês | R$ 400 |
| 3 meses | R$ 1.200 |
| 6 meses | R$ 2.400 |
| 12 meses | R$ 4.800 |

\* Sem considerar rendimentos.

---

# 🗓️ Roteiro de estudo de 30 dias

### Semana 1 — Diagnóstico

- registrar receitas;
- registrar despesas;
- identificar gastos recorrentes;
- separar despesas essenciais e não essenciais.

### Semana 2 — Organização

- criar categorias;
- identificar desperdícios;
- definir limites;
- estabelecer uma meta inicial.

### Semana 3 — Execução

- reduzir gastos escolhidos;
- separar o valor da meta;
- acompanhar o orçamento;
- evitar novas dívidas desnecessárias.

### Semana 4 — Revisão

- comparar planejado e realizado;
- identificar dificuldades;
- ajustar metas;
- preparar o próximo mês.

---

# 📘 Glossário

| Conceito | Definição |
|---|---|
| Receita | Dinheiro recebido em determinado período. |
| Despesa | Valor gasto para adquirir produtos, serviços ou cumprir obrigações. |
| Orçamento pessoal | Organização das receitas, despesas e objetivos financeiros. |
| Juros | Valor relacionado ao uso do dinheiro ao longo do tempo. |
| Juros simples | Juros calculados sobre o valor inicial. |
| Juros compostos | Juros calculados sobre o valor acumulado. |
| Liquidez | Facilidade de transformar um ativo em dinheiro disponível. |
| Rentabilidade | Retorno obtido em relação a um investimento. |
| Risco | Possibilidade de o resultado ser diferente do esperado. |
| Inflação | Aumento generalizado dos preços de bens e serviços. |
| Reserva de emergência | Valor destinado a situações financeiras inesperadas. |

---

# 🧪 Principais aprendizados

O projeto demonstrou que a Inteligência Artificial pode ser utilizada como ferramenta de aprendizagem quando existe uma metodologia de estudo.

Os principais aprendizados foram:

- fontes confiáveis são fundamentais;
- prompts genéricos podem gerar respostas superficiais;
- prompts estruturados produzem resultados mais úteis;
- respostas da IA devem ser conferidas nas fontes;
- exemplos práticos facilitam a compreensão;
- comparar fontes ajuda a desenvolver pensamento crítico;
- a IA pode apoiar leitura, revisão e organização do conhecimento.

---

## 🚧 Limitações

- O material possui caráter introdutório.
- Exemplos numéricos foram simplificados para fins didáticos.
- A situação financeira de cada pessoa é individual.
- Taxas, regras e condições financeiras podem mudar.
- Respostas geradas por IA devem ser verificadas nas fontes originais.
- O projeto não constitui recomendação de investimento.

---

## 📁 Estrutura do projeto

```text
miniguia-educacao-financeira-notebooklm/
│
├── README.md
│
├── prompts/
│   └── prompts-testados.md
│
├── fontes/
│   └── fontes-utilizadas.md
│
└── assets/
    └── README.md
```

---

## 🛠️ Tecnologias e ferramentas

- NotebookLM
- Inteligência Artificial
- GitHub
- Markdown
- Engenharia de Prompts

---

## 👨‍💻 Autor

**Matheus Marks**

Projeto desenvolvido como parte de um desafio da **DIO**, utilizando Inteligência Artificial como ferramenta de aprendizagem ativa.

---

⭐ **Gostou do projeto? Deixe uma estrela no repositório!**
