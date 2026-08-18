**Disciplina: Engenharia de Software 2 – Turma Noite – prof.ª Denilce Veloso**



**Proposta de Projeto Integrador** 



**Data: 18/08/2026   Grupo: FaDevs**

1. **Nome Projeto:** Sistema de controle estudantil e merenda escolar

1. **Nome Usuário no GitHub:** Neste item deve ser colocado o nome de usuário que foi criado o repositório do grupo no github.

1. **Grupo de Alunos:**

|**RA**|**Nome**|**e-mail**|
| :- | :- | :- |
|**0030482423047**|Isabelli Alves Pêgo|**isabelli.pego@aluno.cps.sp.gov.br**|
|**00304824230**|Jean Ortiz|**@aluno.cps.sp.gov.br**|
|**00304824230**|Rian Couto|**@aluno.cps.sp.gov.br**|
|**00304824230**|Thales Godoy|**@aluno.cps.sp.gov.br**|
|0030482423024|Vinicius Romera|vinicius.carvalho4@aluno.cps.sp.gov.br|

1. **Compreensão do Problema**	

Atualmente, o controle de frequência da escola depende de processos manuais. Diariamente, um funcionário precisa percorrer todas as salas de aula para realizar a chamada em papel, registrando o total de alunos presentes e ausentes por turma. Quando identificada a necessidade de contatar os responsáveis por conta de ausências recorrentes a equipe precisa realizar o levantamento histórico folheando os registros físicos de chamada para contabilizar as faltas do aluno e, posteriormente, consultar uma base de dados separada para localizar o telefone ou e-mail dos pais. Além disso o planejamento das refeições depende do repasse manual da contagem de presença para as merendeiras.

1. **Proposta de Solução de Software e Viabilidade**

O objetivo do projeto é desenvolver um sistema para registro diário de frequência escolar realizado diretamente pelos professores. A partir dos lançamentos, o sistema consolidará os dados em tempo real em um painel administrativo voltado à diretoria, exibindo o quantitativo de alunos presentes e ausentes por turma, sala e período (manhã, tarde e noite). O software contará também com uma regra de negócio configurável para o controle de assiduidade: ao atingir um limite predefinido de faltas consecutivas, o sistema alterará automaticamente o status do aluno para **"Atenção"**. A partir desse alerta, a equipe diretiva poderá disparar uma mensagem automática para os responsáveis, notificando-os sobre as ausências.

1. **Visão Geral dos Pré-Requisitos**

   **Registro de Frequência:** O sistema deve permitir que os professores lancem a presença ou falta diária individual por aluno.

   **Consolidação em Tempo Real:** O sistema deve exibir para a diretoria o total de alunos presentes e ausentes, filtrados por período (manhã, tarde e noite), sala e turma.

   **Alerta de Assiduidade:** O sistema deve alterar o status do aluno para "Atenção" caso ele atinja um número configurável de faltas consecutivas.

   **Notificação Automatizada:** O sistema deve permitir o disparo de mensagens automáticas aos responsáveis quando o aluno atingir o status de "Atenção".

   **Painel da Merenda:** O sistema deve disponibilizar à equipe da cozinha a contagem exata de alunos presentes no dia para o planejamento de refeições.

\
   **Usabilidade:** A interface de lançamento de frequência deve ser otimizada para uso rápido em dispositivos móveis (tablets e smartphones).

\
   **Segurança:** O acesso às funcionalidades deve ser restrito por perfis de usuário (Professor, Diretoria e Cozinha).

\
   **Desempenho:** A consolidação dos dados de presença no painel da diretoria deve ser atualizada instantaneamente após o envio do professor.

1. **Conceitos e Tecnologias Envolvidos**

   **Conceitos:** Modelagem de Dados, Design de Interfaces e Usabilidade, Arquitetura Cliente-Servidor.

   **Tecnologias**: MySql, Java, API de notificação, HTML, CSS e JavaScript.

1. **Situação atual (estado-da-arte)**

**Sistemas de Gestão Escolar Tradicionais (Ex: Totvs Educacional, Sophia, iEducar):** São softwares robustos focados em boletins, matrículas e financeiro. Embora possuam módulo de chamada, não integram a contagem em tempo real com a equipe da cozinha/merenda, mantendo o desperdício alimentar.

**Aplicativos de Comunicação Escolar (Ex: ClassApp, Agenda Edu):** Excelentes para enviar recados aos pais, mas funcionam apenas como meio de comunicação. Não possuem inteligência de regra de negócio para alternar automaticamente o status do aluno para "Atenção" por faltas consecutivas sem intervenção humana manual.

**Cadernos de Chamada em Papel e Planilhas (Excel/Google Sheets):** Soluções amplamente utilizadas por não gerarem custos diretos. Contudo, geram alto tempo de processamento manual, lentidão na consolidação de dados para a diretoria, risco de perda de informações e total falta de integração entre presença, contato dos pais e refeitório.

1. **Estimativa de custo do projeto**

Estimar quanto custa para o projeto ficar operacional: ferramentas, hospedagem etc.

1. **Glossário**

Neste item deve-se fazer um levantamento do vocabulário relativo ao domínio, contendo os principais termos utilizados para descrever as características do problema.
Documento: ES2N-Proposta

