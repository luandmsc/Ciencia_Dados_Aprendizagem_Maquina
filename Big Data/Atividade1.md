# Atividade Prática — Detetives dos Dados

## Ciência de Dados e Aprendizagem de Máquina — Aula 01

*Tema:* Introdução à Ciência de Dados e Big Data  
*Metodologia:* Trabalho em equipe  
*Tempo:* 20 minutos  
*Entregável:* Mapa do Problema de Ciência de Dados

---

## 1. Identificação da equipe

| Campo | Resposta |
| --- | --- |
| *Turma:* | SI 7/8 Noturno |
| *Data:* | 19/08/2026 |
| *Equipe:* | Detetives dos Dados |
| *Integrante 1:* | Luan Damasceno Gualberto |

---

## 2. Objetivo da atividade

Nesta atividade, a equipe deverá analisar um *problema real* e pensar como uma equipe de Ciência de Dados poderia utilizar dados para compreender a situação e apoiar uma decisão.

O objetivo não é desenvolver um sistema ou modelo de Machine Learning neste momento.

O objetivo é aprender a *pensar como um cientista de dados*:

> *Problema → Dados → Informação → Análise → Decisão → Benefício*

---

## 3. Escolha do problema

*Área escolhida:* Educação

### Problema escolhido

> A evasão de alunos em cursos superiores noturnos. Muitos estudantes que trabalham durante o dia acabam trancando ou abandonando o curso ao longo dos semestres. A instituição pode utilizar dados para entender quais fatores estão associados à desistência e identificar alunos em risco antes que a evasão aconteça.

---

## 4. Quem possui esse problema?

> As instituições de ensino superior, principalmente as coordenações de curso e os setores responsáveis pela permanência estudantil.

### Quem é afetado pelo problema?

> Os próprios alunos, suas famílias, professores e a instituição de ensino. A sociedade também é afetada, pois a evasão resulta em menos profissionais formados.

---

## 5. Por que esse problema é importante?

> A evasão no ensino superior pode causar prejuízos para alunos e instituições. Para o aluno, pode representar perda de tempo e dinheiro investidos na graduação. Para a instituição, pode representar perda financeira e queda nos indicadores de conclusão. A análise de dados pode ajudar a identificar sinais de risco antes que o aluno abandone o curso.

---

## 6. Qual decisão precisa ser tomada?

> A instituição precisa decidir quais alunos apresentam maior risco de evasão e quais ações podem ser utilizadas para tentar mantê-los no curso, como apoio financeiro, monitoria, reforço, flexibilização de horários ou acompanhamento da coordenação.

---

## 7. Identificação dos dados

| Nº | Dado necessário | Por que esse dado é importante? |
| ---: | --- | --- |
| 1 | Frequência às aulas | Pode indicar queda no interesse ou dificuldades do aluno. |
| 2 | Notas e histórico de reprovações | Baixo desempenho pode estar relacionado à desistência. |
| 3 | Situação financeira | Dificuldades financeiras podem contribuir para o abandono. |
| 4 | Dados socioeconômicos | Ajudam a compreender a realidade do aluno. |
| 5 | Acessos ao ambiente virtual | Permitem analisar o nível de participação nas atividades. |
| 6 | Histórico de trancamentos e evasões | Permite identificar padrões de alunos que abandonaram anteriormente. |

---

## 8. Que informações queremos descobrir?

### Pergunta 1

> Quais fatores aparecem com maior frequência entre os alunos que abandonaram o curso?

### Pergunta 2

> Em qual semestre a evasão ocorre com maior frequência?

### Pergunta 3

> Existe relação entre a redução da frequência ou dos acessos ao ambiente virtual e a desistência?

### Pergunta 4

> Quais perfis de alunos apresentam maior risco de evasão?

---

## 9. Quais padrões podemos procurar?

- [x] Tendências
- [x] Comparações
- [x] Grupos semelhantes
- [x] Comportamentos recorrentes
- [x] Valores fora do padrão
- [x] Relações entre variáveis
- [x] Mudanças ao longo do tempo

### Explique um padrão que vocês gostariam de encontrar

> Gostaríamos de identificar sinais de alerta, como redução da frequência, diminuição dos acessos ao ambiente virtual e dificuldades financeiras. A combinação desses fatores poderia indicar que determinado aluno possui maior risco de abandonar o curso.

---

## 10. Qual análise poderia ser realizada?

- [x] Análise descritiva
- [x] Comparação entre grupos
- [x] Análise temporal
- [x] Visualização por gráficos
- [x] Identificação de padrões
- [x] Classificação
- [x] Previsão
- [x] Agrupamento

### Explique

> Primeiro poderiam ser realizadas análises descritivas para compreender o cenário geral. Depois poderiam ser feitas comparações entre diferentes grupos de alunos, análises temporais e identificação de perfis. Futuramente, modelos de classificação e previsão poderiam estimar o risco de evasão.

---

## 11. Qual decisão poderia ser tomada?

> A instituição poderia criar um programa de acompanhamento dos alunos em risco, oferecendo diferentes tipos de suporte de acordo com o problema identificado.

---

## 12. Qual seria o benefício?

> Para os alunos, aumentaria a possibilidade de receber apoio antes de abandonar o curso. Para a instituição, poderia reduzir a evasão e melhorar os indicadores de conclusão. Para a sociedade, poderia contribuir para a formação de mais profissionais.

---

## 13. Os 5 Vs do Big Data

| V | Pergunta | Resposta |
| --- | --- | --- |
| *Volume* | Existe uma grande quantidade de dados? | Sim. Uma instituição pode possuir dados de milhares de alunos ao longo de vários semestres. |
| *Velocidade* | Os dados são gerados ou processados rapidamente? | Sim. Frequência, acessos ao ambiente virtual e outras informações podem ser registrados diariamente. |
| *Variedade* | Existem diferentes tipos ou formatos de dados? | Sim. Existem notas, faltas, pagamentos, registros de acesso e informações cadastrais. |
| *Veracidade* | Os dados podem apresentar erros? | Sim. Podem existir registros incorretos, informações desatualizadas ou dados incompletos. |
| *Valor* | Os dados podem gerar benefícios? | Sim. Eles podem ajudar a identificar alunos em risco e apoiar decisões da instituição. |

### Qual dos 5 Vs é mais relevante para o problema?

> *Valor.*

### Justifique

> O objetivo principal não é apenas possuir uma grande quantidade de dados, mas transformar esses dados em informações que possam ajudar a instituição a tomar decisões e reduzir a evasão dos alunos.

---

## 14. Mapa do Problema de Ciência de Dados

*PROBLEMA*

Alta evasão de alunos no noturno.

↓

*DADOS*

Frequência, notas, situação financeira, AVA e perfil socioeconômico.

↓

*INFORMAÇÕES*

Fatores e perfis associados à desistência.

↓

*ANÁLISE*

Análise descritiva, temporal, agrupamento e previsão de risco.

↓

*DECISÃO*

Programa de retenção direcionado por perfil de risco.

↓

*BENEFÍCIO*

Menos evasão, mais alunos formados e recursos bem aplicados.

### Resuma cada etapa

*Problema:*

> Alta evasão de alunos em cursos superiores noturnos.

*Dados:*

> Frequência, notas, situação financeira, perfil socioeconômico, acessos ao ambiente virtual e histórico de evasões.

*Informação:*

> Identificar quais fatores e perfis estão relacionados à desistência.

*Análise:*

> Análise descritiva, comparação entre grupos, análise temporal, agrupamento e previsão.

*Decisão:*

> Criar ações de acompanhamento e retenção para os alunos em risco.

*Benefício:*

> Redução da evasão, aumento da quantidade de alunos formados e melhor utilização dos recursos da instituição.

---

## 15. Preparação para apresentação

### 1. Nosso problema

> A evasão de alunos em cursos superiores noturnos.

### 2. Precisamos destes dados

> Frequência, notas, situação financeira, dados socioeconômicos, acessos ao ambiente virtual e histórico de evasões.

### 3. Queremos descobrir

> Quais fatores estão relacionados à desistência e quais alunos apresentam sinais de risco.

### 4. Pretendemos analisar

> O cenário geral, a evolução ao longo do tempo, os diferentes grupos de alunos e os possíveis fatores relacionados à evasão.

### 5. A decisão poderia ser

> Criar um programa de acompanhamento direcionado aos alunos que apresentam maior risco.

### 6. O benefício esperado é

> Menos evasão, mais alunos concluindo o curso e melhor utilização dos recursos da instituição.

---

## 16. Checklist da equipe

- [x] Definimos um problema real.
- [x] Identificamos quem é afetado pelo problema.
- [x] Explicamos por que o problema é importante.
- [x] Identificamos os dados necessários.
- [x] Definimos perguntas que queremos responder.
- [x] Identificamos possíveis padrões.
- [x] Indicamos como os dados poderiam ser analisados.
- [x] Definimos uma possível decisão.
- [x] Identificamos o benefício esperado.
- [x] Analisamos os 5 Vs do Big Data.
- [x] Preenchemos o Mapa do Problema.

---

## 17. Reflexão final

### Ter muitos dados significa necessariamente tomar boas decisões? Por quê?

> Não. Ter muitos dados não significa necessariamente tomar boas decisões. Os dados precisam ter qualidade, ser analisados corretamente e utilizados para responder perguntas relevantes. Dados incorretos ou mal interpretados podem levar a decisões erradas. Por isso, o mais importante não é apenas possuir muitos dados, mas conseguir transformá-los em informações úteis para tomar boas decisões.

---

## Entrega

### Produto final

*Problema:* evasão de alunos no ensino superior noturno.

↓

*Dados necessários:* frequência, notas, situação financeira, AVA e perfil socioeconômico.

↓

*Informações desejadas:* fatores e sinais de risco de evasão.

↓

*Análise:* descritiva, temporal, agrupamento e previsão.

↓

*Decisão:* programa de acompanhamento direcionado.

↓

*Benefício esperado:* menos evasão e mais alunos formados.
