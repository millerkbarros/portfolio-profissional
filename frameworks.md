# Ferramentas e frameworks

[← Voltar ao início](./README.md)

Esta página reúne ferramentas e estruturas de pensamento aplicadas à análise, à gestão de projetos e à investigação de problemas.

## 1. Simulador de Prazos de Projetos — PERT + Monte Carlo

**Objetivo:** tornar explícita a incerteza das estimativas de prazo e apoiar conversas mais realistas sobre previsão de entrega.

A ferramenta permite informar estimativas otimista, mais provável e pessimista para cada etapa, escolher o método de distribuição e executar simulações para observar a variação dos prazos.

**Principais recursos**
- Distribuições Beta-PERT e Triangular.
- Leitura de percentis como P50, P80 e P90.
- Análise da entrega restante a partir de um marco selecionado.
- Datas previstas descontando fins de semana e feriados nacionais.
- Relatório em PDF.

**Acessos:** [Aplicação publicada](https://millerkbarros.github.io/simulador-pert-monte-carlo/) · [Repositório do código](https://github.com/millerkbarros/simulador-pert-monte-carlo)
<img width="1308" height="819" alt="image" src="https://github.com/user-attachments/assets/0ffb9f05-b42e-49ef-9903-be41bed7836d" />


## 2. PALAVRA — abordagem para investigação de problemas recorrentes

PALAVRA é uma estrutura de investigação organizada em sete movimentos. A proposta é evitar que o primeiro relato seja tratado automaticamente como causa raiz e orientar a análise até que haja evidências suficientes.

- **P — Perceber:** reconhecer sinais, recorrência e impacto operacional.
- **A — Anotar:** registrar exemplos, contexto, frequência e evidências.
- **L — Localizar:** identificar sistemas, etapas, equipes ou condições envolvidas.
- **A — Aprofundar:** explorar hipóteses com perguntas estruturadas, como os 5 Porquês.
- **V — Verificar:** confrontar hipóteses com dados, testes e evidências.
- **R — Resolver:** encaminhar ações sobre a causa confirmada ou mais bem sustentada.
- **A — Acompanhar:** validar o resultado e observar se o problema voltou a ocorrer.

**Princípio central:** palavras recorrentes em chamados — como “bug”, “aguardando”, “dependência” ou “retrabalho” — são pistas para investigação, não provas isoladas de uma causa.
<img width="1024" height="559" alt="image" src="https://github.com/user-attachments/assets/4dfbd102-1761-4f1a-9916-50328a4c69db" />


## 3. VITREX — estrutura de gestão de projetos

VITREX é uma estrutura própria, em evolução, para ajudar a iniciar e conduzir projetos com clareza sobre a visão e o resultado esperado. O ponto de partida é entender o que precisa mudar, por que isso importa e quem será impactado antes de discutir a solução.

**Princípios de aplicação**
- Esclarecer a visão e o resultado esperado.
- Definir o problema e o objetivo que justificam o projeto.
- Identificar partes interessadas e impactos.
- Traduzir o entendimento em escopo, planejamento e critérios de validação.

<img width="1024" height="559" alt="image" src="https://github.com/user-attachments/assets/4b36d181-7ca8-48bf-bcb9-557afccd0b4a" />


## 4. Pareto aplicado à Gestão de Problemas

**O que é:** o Princípio de Pareto, ou regra 80/20, diz que poucas causas costumam gerar a maior parte dos efeitos. No gráfico, as barras mostram cada causa do maior para o menor, e a linha mostra o percentual acumulado. O ponto onde a linha cruza 80% indica onde está o foco.

**Quando uso:** quando a fila de chamados é maior do que a capacidade de correção e é preciso decidir com dado o que atacar primeiro.

**Como aplico**
1. **Agrupo os chamados por tema**, e não um a um. Descrições diferentes muitas vezes escondem a mesma causa.
2. **Conto a frequência de cada tema** e considero o impacto na operação.
3. **Ordeno do maior para o menor** e calculo o percentual acumulado.
4. **Priorizo os temas que somam cerca de 80%**, abrindo problema, responsável e análise de causa raiz para cada um.
5. **Repito a análise no ciclo seguinte** para confirmar se a correção reduziu a fila.

**Exemplo prático**

<img src="./pareto-exemplo.png" alt="Gráfico de Pareto com 140 chamados agrupados em 7 temas; os 3 primeiros somam 80%" width="900" />

Em um mês com 140 chamados, a fila parecia ter dezenas de assuntos. Agrupada por tema, mostrou que **3 problemas respondiam por 112 chamados (80%)**. Em vez de atender um a um, a correção começa por esses 3 junto ao fornecedor. Os outros 4 temas seguem no atendimento normal.

<sub>Dados ilustrativos.</sub>

## 5. Práticas de melhoria contínua

Práticas que combino conforme o problema:

- **Lean Thinking:** identificar desperdícios e gargalos no fluxo de trabalho.
- **Kaizen:** promover melhorias contínuas e incrementais.
- **5S:** organizar ambientes, informações e rotinas de trabalho.
- **Six Sigma:** usar análise estruturada para compreender variação e defeitos.
- **BPM:** compreender, mapear e melhorar processos de ponta a ponta.
- **Comunicação não violenta:** apoiar conversas objetivas, respeitosas e orientadas à solução.
