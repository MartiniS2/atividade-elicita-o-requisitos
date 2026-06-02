# Atividade Prática – Elicitação de Requisitos

## Sistema de Apoio à Permanência Estudantil e Prevenção da Evasão Acadêmica

---

## Sobre a Atividade

Esta atividade tem como objetivo aplicar técnicas de elicitação de requisitos para o desenvolvimento de um sistema acadêmico voltado à identificação precoce de estudantes em situação de risco de evasão.

A proposta considera o contexto do Instituto Federal Farroupilha (IFFar), que enfrenta dificuldades no acompanhamento contínuo dos estudantes devido à dispersão de informações acadêmicas em diferentes sistemas e processos manuais.

O sistema proposto busca centralizar dados acadêmicos, indicadores de frequência, desempenho e acompanhamento estudantil, permitindo ações preventivas por parte da coordenação, docentes e setores de apoio.

---

# Objetivos

- Identificar fatores relacionados à evasão acadêmica;
- Aplicar técnicas de levantamento de requisitos;
- Elaborar requisitos funcionais e não funcionais;
- Simular necessidades reais de um sistema acadêmico;
- Desenvolver documentação inicial do projeto.

---

# Stakeholder Escolhido

## Docentes
Responsáveis pela identificação de dificuldades acadêmicas, baixo desempenho e mudanças de comportamento.

---

# Entrevistas com Docentes

Durante a atividade foram realizadas entrevistas com docentes do curso de Sistemas de Informação, buscando compreender os principais fatores relacionados à evasão acadêmica e as dificuldades encontradas no acompanhamento dos estudantes.

## Perguntas Aplicadas

1. Quais sinais em sala de aula indicam que um aluno pode estar em risco de evasão e quais você considera mais relevantes para identificar dificuldades?

2. Quais fatores você acredita que mais contribuem para o baixo desempenho ou desistência dos alunos em sua disciplina?

3. Como você acompanha hoje o desempenho dos alunos e quais são as principais dificuldades nesse processo?

4. Em que momento você percebe que deve intervir para ajudar um aluno?

5. Que estratégias você já utilizou para apoiar alunos com baixo desempenho?

6. Que tipo de informação ou apoio faria diferença para você conseguir agir mais cedo na prevenção da evasão?

---

# Principais Resultados das Entrevistas

A partir das entrevistas realizadas, foram identificados os seguintes pontos como principais indicadores de risco de evasão:

- Baixa frequência e ausências consecutivas;
- Falta de participação e engajamento nas aulas;
- Queda no rendimento acadêmico;
- Dificuldades em disciplinas práticas, principalmente programação;
- Dificuldade de conciliar trabalho e estudos;
- Problemas pessoais, familiares e emocionais;
- Necessidade de monitorias e acompanhamento mais próximo;
- Importância da comunicação entre docentes e coordenação.

---

# Questionário com Estudantes

Também foi elaborado um questionário voltado aos estudantes, buscando compreender fatores que influenciam sua permanência ou possível desistência do curso.

## Perguntas Aplicadas

1. Você já pensou em trancar seu curso? Com que frequência isso ocorre?

2. A dificuldade em conciliar estudos, trabalho e vida pessoal afeta sua permanência no curso.

3. Quanto às dificuldades de aprendizagem e o rendimento nas disciplinas influenciam sua motivação para continuar o curso?

4. Você diria que o curso atingiu suas expectativas iniciais?

5. Como você avalia o suporte institucional no auxílio à evasão acadêmica?

### Escala Utilizada

- 1 = Discordo totalmente
- 2 = Discordo parcialmente
- 3 = Concordo parcialmente
- 4 = Concordo totalmente

---

# Requisitos Funcionais

### RF01 – Monitoramento de Frequência
O sistema deverá acompanhar automaticamente a frequência dos estudantes, identificando ausências consecutivas ou índices elevados de faltas.

### RF02 – Emissão de Alertas Automáticos
O sistema deverá emitir alertas automáticos para coordenação e docentes quando forem identificados sinais de risco de evasão.

### RF03 – Histórico Individual do Estudante
O sistema deverá permitir a visualização centralizada do histórico acadêmico e comportamental do estudante.

### RF04 – Registro de Observações dos Professores
O sistema deverá permitir que docentes registrem observações sobre comportamento, participação, rendimento e dificuldades percebidas em sala de aula.

### RF05 – Comunicação Automática com Estudantes
O sistema deverá enviar mensagens automáticas por e-mail ou notificações para estudantes identificados em situação de risco acadêmico.

### RF06 – Solicitação de Apoio Estudantil
O sistema deverá permitir que estudantes solicitem apoio acadêmico, psicológico ou orientação estudantil diretamente pela plataforma.

### RF07 – Gerenciamento de Monitorias Acadêmicas
O sistema deverá permitir o cadastro e acompanhamento de monitorias acadêmicas, conectando estudantes com dificuldades a monitores ou grupos de estudo.

### RF08 – Painel de Indicadores de Risco
O sistema deverá apresentar indicadores de risco de evasão, permitindo acompanhamento rápido por parte da coordenação e docentes.

### RF09 – Compartilhamento de Informações entre Setores
O sistema deverá permitir o compartilhamento de informações relevantes entre coordenação, docentes e setores de apoio estudantil.

### RF10 – Análise de Rematrícula
O sistema deverá identificar estudantes que ainda não realizaram a rematrícula nos primeiros prazos, permitindo ações preventivas antes do encerramento do período.

---

# Requisitos Não Funcionais

### RNF01 – Privacidade e Segurança
O sistema deverá garantir a proteção e confidencialidade dos dados dos estudantes, em conformidade com a Lei Geral de Proteção de Dados (LGPD).

### RNF02 – Disponibilidade e Confiabilidade
O sistema deverá permanecer disponível durante períodos críticos, como fechamento de notas e rematrículas.

### RNF03 – Performance e Processamento de Dados
O sistema deverá processar grandes volumes de dados acadêmicos e gerar alertas de risco em tempo hábil.

---

# Técnicas de Elicitação Utilizadas

Durante o levantamento de requisitos foram utilizadas as seguintes técnicas:

- Entrevistas com docentes;
- Aplicação de questionários com estudantes;
- Brainstorming de funcionalidades;
- Análise de necessidades institucionais.

# Product Backlog

| Prioridade | ID   | Requisito Funcional |
|------------|------|---------------------|
| 01 | RF05 | Comunicação Automática com Estudantes |
| 02 | RF01 | Monitoramento de Frequência |
| 03 | RF08 | Painel de Indicadores de Risco |
| 04 | RF02 | Emissão de Alertas Automáticos |
| 05 | RF10 | Análise de Rematrícula |
| 06 | RF06 | Solicitação de Apoio Estudantil |
| 07 | RF07 | Gerenciamento de Monitorias Acadêmicas |
| 08 | RF09 | Compartilhamento de Informações entre Setores |
| 09 | RF03 | Histórico Individual do Estudante |
| 10 | RF04 | Registro de Observações dos Professores |


---


# User Stories

US01 (RF05) – Comunicação Automática com Estudantes

Card

Como estudante em situação de risco acadêmico,

eu quero receber mensagens automáticas de orientação,

para que eu possa tomar medidas antes de comprometer meu desempenho acadêmico.

Conversation

As mensagens podem ser enviadas por e-mail ou notificação.

Apenas estudantes classificados em risco devem receber mensagens.

As mensagens devem conter orientações e canais de apoio.

Confirmation

O sistema deve enviar mensagens automaticamente para estudantes em risco.

A mensagem deve conter orientações de apoio acadêmico.

O envio deve ser registrado no sistema.

---

US02 (RF01) – Monitoramento de Frequência

Card

Como coordenador acadêmico,

eu quero acompanhar automaticamente a frequência dos estudantes,

para que eu possa identificar possíveis casos de evasão.

Conversation

O sistema deve registrar faltas automaticamente.

A frequência deve ser calculada em tempo real.

Frequências abaixo de 75% devem gerar sinalização.

Confirmation

O sistema deve calcular a frequência automaticamente.

O sistema deve registrar ausências consecutivas.

O sistema deve sinalizar estudantes com frequência inferior a 75%.

---

US03 (RF08)– Painel de Indicadores de Risco

Card

Como coordenador acadêmico,

eu quero visualizar indicadores de risco em um painel centralizado,

para que eu possa acompanhar rapidamente estudantes com risco de evasão.

Conversation

Os indicadores devem ser atualizados diariamente.

O painel deve permitir filtros por curso e turma.

Os dados devem ser apresentados de forma visual.

Confirmation

O painel deve exibir indicadores de risco.

O sistema deve permitir filtros de pesquisa.

Os dados devem ser atualizados automaticamente.

---

US04 (RF02)– Emissão de Alertas Automáticos

Card

Como coordenador acadêmico,

eu quero receber alertas automáticos sobre estudantes em situação de risco,

para que eu possa agir preventivamente e reduzir a evasão.

Conversation

Os alertas devem considerar frequência e desempenho.

Apenas usuários autorizados podem visualizar alertas.

O alerta deve ser gerado automaticamente.

Confirmation

O sistema deve gerar alertas automaticamente.

O alerta deve identificar o estudante em risco.

O alerta deve ser exibido no painel da coordenação.

---

US05 (RF10) – Análise de Rematrícula

Card

Como coordenador acadêmico,

eu quero identificar estudantes que ainda não realizaram a rematrícula,

para que eu possa entrar em contato antes do encerramento do prazo.

Conversation

O sistema deve verificar diariamente o status da rematrícula.

Apenas estudantes pendentes devem aparecer na lista.

A coordenação deve conseguir consultar a lista a qualquer momento.

Confirmation

O sistema deve listar estudantes sem rematrícula.

A lista deve ser atualizada automaticamente.

O coordenador deve conseguir visualizar os estudantes pendentes.



# Cenários BDD

US01 – Comunicação Automática com Estudantes

Caminho Feliz

Cenário: Envio automático de mensagem para estudante em risco


Dado que o estudante João foi classificado como estudante em risco

Quando o sistema realizar a análise diária

Então uma mensagem automática deve ser enviada para João

E o envio deve ser registrado no sistema



Fluxo de Exceção

Cenário: Falha no envio da mensagem



Dado que o estudante João foi classificado como estudante em risco

Quando o sistema tentar enviar uma mensagem

E o serviço de e-mail estiver indisponível

Então o envio não deve ser realizado

E o sistema deve registrar a falha



---

# Cenários BDD

US02 – Monitoramento de Frequência

Caminho Feliz

Cenário: Identificação de baixa frequência



Dado que o estudante João possui frequência de 80%

Quando novas faltas forem registradas

E sua frequência cair para 74%

Então o sistema deve classificá-lo como estudante em risco



Fluxo de Exceção

Cenário: Falha no cálculo da frequência



Dado que existem registros de presença incompletos

Quando o sistema calcular a frequência

Então deve informar inconsistência nos dados

E não deve gerar indicadores de risco



---

US04 – Emissão de Alertas Automáticos

Caminho Feliz

Cenário: Geração automática de alerta



Dado que o estudante João está classificado como estudante em risco

Quando o sistema concluir a análise dos dados

Então um alerta deve ser criado

E o coordenador deve ser notificado



Fluxo de Exceção

Cenário: Usuário sem permissão acessa alertas



Dado que um usuário comum está autenticado

Quando tentar visualizar os alertas de risco

Então o sistema deve negar o acesso

E exibir uma mensagem de permissão insuficiente





# Autoavaliação INVEST


| Letra  | Critério    | US01 | US02 | US03 | US04 | US05 |
|--------|-------------|------|------|------|------|------|
| I      | Independent | Sim  | Sim  | Sim  | Sim  | Sim  |
| N      | Negotiable  | Sim  | Sim  | Sim  | Sim  | Sim  |
| V      | Valuable    | Sim  | Sim  | Sim  | Sim  | Sim  |
| E      | Estimable   | Sim  | Sim  | Sim  | Sim  | Sim  |
| S      | Small       | Sim  | Sim  | Sim  | Sim  | Sim  |
| T      | Testable    | Sim  | Sim  | Sim  | Sim  | Sim  |




---

# Integrantes

- Matheus Gomes Bianchin Martini
- Vinícius da Silva de Souza

---

# Disciplina

Processo de Software e Engenharia de Requisitos

Instituto Federal de Educação, Ciência e Tecnologia Farroupilha — Campus São Borja

Docente: Rafael Baldiati Parizi

Semestre 2026/1 
```
