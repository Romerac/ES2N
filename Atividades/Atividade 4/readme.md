![Logo](https://bkpsitecpsnew.blob.core.windows.net/uploadsitecps/sites/212/2024/09/logo_fatec_sorocaba.png)

# Engenharia de Software 2 – Aula 04: Validação de Requisitos e Estudo de Caso (Sala de Reunião)

<p align="center">
  <img src="https://img.shields.io/badge/Engenharia%20de%20Requisitos-00599C?style=for-the-badge&logo=diagramsdotnet&logoColor=white" alt="Engenharia de Requisitos"/>
  <img src="https://img.shields.io/badge/Especificação-FF6B00?style=for-the-badge&logo=read-the-docs&logoColor=white" alt="Especificação"/>
  <img src="https://img.shields.io/badge/Casos%20de%20Uso-4CAF50?style=for-the-badge&logo=unifiedmodelinglanguage&logoColor=white" alt="Casos de Uso"/>
</p>

Este documento contém a resolução completa da **Atividade 4** da disciplina de **Engenharia de Software 2**, ministrada pela **Profª Mª Denilce Veloso**. A atividade aborda a análise da situação atual, o levantamento de problemas, a proposta de solução e a especificação dos Requisitos Funcionais para o estudo de caso **Sistema de Gestão de Salas de Reunião**.

---

## 📌 Contexto do Problema (Sala de Reunião)

Patrícia é secretária e tem como responsabilidade controlar a utilização de três salas de reunião (Sala 101, Sala 105 e Sala 201), que são utilizadas por todos os setores da empresa.

Atualmente, o controlo é realizado manualmente através de ficheiros do Excel (uma pasta de trabalho por mês, contendo entre 28 e 31 folhas de cálculo, uma para cada dia do mês). Nas folhas de cálculo, existem colunas de horários e três colunas dedicadas às salas. Adicionalmente, num registo separado, a secretária mantém os dados dos colaboradores (nome, cargo e ramal).

---

## 🔍 1. Análise da Situação Atual e Problemas Identificados

### **Situação Atual**
* O processo de agendamento e controlo é totalmente manual e descentralizado.
* A informação está fragmentada em 12 ficheiros anuais do Excel, dezenas de abas diárias e um registo paralelo com os dados dos funcionários.
* As realocações de reuniões (mudança de sala, data e/ou horário) e as consultas de disponibilidade efetuadas pelos Diretores ocorrem com elevada frequência.

### **Problemas Identificados**
* **Fragmentação e Descentralização dos Dados**: Informação dispersa em múltiplos ficheiros e registos externos, dificultando a manutenção e a integridade dos dados.
* **Elevado Risco de Conflitos de Horário (*Double-Booking*)**: A alteração manual de datas, salas e horários em folhas de cálculo separadas propicia erros humanos e sobreposição de marcações.
* **Lentidão no Atendimento a Consultas**: Responder a solicitações dos Diretores sobre salas livres numa determinada data e faixa horária exige a verificação manual folha a folha, gerando ineficiência operacional.
* **Falta de Informação Integrada**: A capacidade máxima (número de lugares) das salas não está visível de forma direta no mapa de agendamento principal.
* **Ausência de Histórico e Indicadores**: Dificuldade em extrair relatórios de taxa de ocupação, utilização por setor ou histórico de alterações.

---

## 💡 2. Proposta de Solução

Desenvolvimento do **Sistema Web de Gestão e Agendamento de Salas de Reunião**, uma plataforma centralizada e acessível em tempo real via navegador.

### **Principais Funcionalidades da Solução proposta:**
* **Mapa de Agendamento Interativo**: Visualização dinâmica da agenda (diária, semanal e mensal) com indicação do estado das salas e respetiva lotação.
* **Procura Automatizada de Disponibilidade**: Filtro inteligente que permite encontrar salas livres informando a data, intervalo de horário e número de lugares necessários.
* **Validação Automática de Conflitos**: Impedimento automático de sobreposição de horários no momento da reserva ou realocação.
* **Registo Unificado de Colaboradores e Salas**: Centralização dos dados dos funcionários (nome, cargo, ramal e setor) e das salas (código, localização e capacidade de lugares).
* **Notificações Automáticas**: Envio de confirmações e alertas por e-mail aos participantes sempre que uma reunião for agendada, alterada ou cancelada.

---

## 📝 3. Lista de Requisitos Funcionais (RFs)

### **Gestão de Infraestrutura e Utilizadores**
* **RF01 - Manter Registo de Salas**: O sistema deve permitir registar, alterar, consultar e inativar salas de reunião, armazenando a identificação (ex.: Sala 101), localização e capacidade máxima de lugares.
* **RF02 - Manter Registo de Colaboradores**: O sistema deve permitir registar, alterar, consultar e inativar colaboradores, armazenando nome, cargo, ramal, e-mail e setor.

### **Agendamento e Movimentação**
* **RF03 - Efetuar Agendamento de Reunião**: O sistema deve permitir agendar uma reunião selecionando a sala, data, horário de início, horário de término, assunto e o colaborador responsável.
* **RF04 - Realocar Reunião**: O sistema deve permitir alterar a sala, data e/ou horário de uma reunião já agendada, revalidando a disponibilidade da nova opção.
* **RF05 - Cancelar Agendamento**: O sistema deve permitir o cancelamento de uma reunião agendada, libertando instantaneamente a sala no mapa de reservas.

### **Consultas e Validações**
* **RF06 - Validar Conflitos de Horário**: O sistema deve impedir automaticamente o agendamento ou a realocação de reuniões em salas, datas e horários coincidentes.
* **RF07 - Consultar Salas Livres**: O sistema deve permitir pesquisar salas disponíveis filtrando por data, faixa horária e/ou capacidade mínima de lugares.
* **RF08 - Visualizar Agenda das Salas**: O sistema deve disponibilizar uma visualização em grelha/calendário do mapa de ocupação diário, semanal e mensal de todas as salas.

### **Notificações e Relatórios**
* **RF09 - Enviar Notificação de Agendamento**: O sistema deve enviar um e-mail de notificação ao colaborador responsável sempre que uma reunião for marcada, realocada ou cancelada.
* **RF10 - Emitir Relatórios de Utilização**: O sistema deve gerar relatórios estatísticos sobre a taxa de ocupação das salas por período e por setor solicitante.

---


---

## 📚 Referências

* PRESSMAN, Roger S. **Engenharia de Software: Uma Abordagem Profissional**. 7ª ed. Porto Alegre: McGraw-Hill, 2011.
* SOMMERVILLE, Ian. **Engenharia de Software**. 10ª ed. São Paulo: Pearson, 2019.

---

## 👩‍🏫 Professora

**Profª Mª Denilce Veloso**  
📧 `denilce.veloso@cps.sp.gov.br` | `denilce.veloso@fatec.sp.gov.br`

---

## ✒️ Autores

**Aluno da FATEC Sorocaba**  
[![GitHub](https://img.shields.io/badge/GitHub-100000?style=for-the-badge&logo=github&logoColor=white)](https://github.com/romerac)  
[![LinkedIn](https://img.shields.io/badge/LinkedIn-0077B5?style=for-the-badge&logo=linkedin&logoColor=white)](https://www.linkedin.com/in/viniciusromerac/)
