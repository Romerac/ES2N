![Logo](https://bkpsitecpsnew.blob.core.windows.net/uploadsitecps/sites/212/2024/09/logo_fatec_sorocaba.png)

# Engenharia de Requisitos: Elicitação e Especificação - Aula 04

<p align="center">
  <img src="https://img.shields.io/badge/Engenharia%20de%20Requisitos-00599C?style=for-the-badge&logo=bookstack&logoColor=white" alt="Engenharia de Requisitos"/>
  <img src="https://img.shields.io/badge/Elicitação%20%26%20Análise-FF6B00?style=for-the-badge&logo=target&logoColor=white" alt="Elicitação & Análise"/>
  <img src="https://img.shields.io/badge/Especificação%20IEEE%20830-4CAF50?style=for-the-badge&logo=ieee&logoColor=white" alt="Especificação IEEE 830"/>
</p>

Este material sintetiza o conteúdo ministrado na **Aula 4** da disciplina de **Engenharia de Software 2**, pela Profª Mª Denilce Veloso, abordando as atividades fundamentais do processo de software, técnicas de **Elicitação e Análise de Requisitos**, modelos de **Especificação de Requisitos** e a estrutura do **Padrão IEEE/ANSI 830/1998**.

---

## 🎯 Objetivo da Aula

Compreender e aplicar os conceitos fundamentais da Engenharia de Requisitos, focando em:

- **Atividades do Processo de Software**: Identificar as etapas de Especificação, Desenvolvimento, Validação e Evolução.
- **Elicitação e Descoberta de Requisitos**: Dominar as técnicas de coleta com *stakeholders* e identificar os principais desafios do processo.
- **Técnicas Práticas**: Aplicar entrevistas (abertas/fechadas), etnografia (observação do fluxo real e *workarounds*) e o uso de histórias e cenários.
- **Especificação e Notações**: Diferenciar requisitos de usuário e de sistema utilizando Linguagem Natural, Estruturada, Notações Gráficas (Casos de Uso UML) e Especificações Matemáticas.
- **Documentação de Requisitos**: Estruturar a Especificação de Requisitos de Software (SRS) segundo a norma **IEEE/ANSI 830/1998**.

---

## 📋 Conteúdo Programático

### 1. Atividades Fundamentais do Processo de Software
De acordo com Sommerville (2019), todo processo de desenvolvimento inclui quatro atividades essenciais:

1. **Especificação**: Definição clara do que o sistema deve fazer e das suas restrições de operação.
2. **Desenvolvimento**: Fase de projeto (arquitetura/design) e programação do software.
3. **Validação**: Assegurar que o sistema atende rigorosamente às necessidades e demandas do cliente.
4. **Evolução**: Adequação e modificação do software para atender a novas necessidades do cliente e mudanças do mercado.

### 2. Engenharia de Requisitos – Elicitação de Requisitos
A elicitação (ou descoberta) ocorre após o estudo de viabilidade, onde a equipe técnica trabalha diretamente com os **stakeholders** (usuários finais, gerentes, equipe de manutenção, especialistas de domínio, etc.) para mapear os serviços do sistema e suas restrições.

#### ⚠️ Principais Desafios da Elicitação:
- *Stakeholders* não sabem exatamente o que querem ou usam linguagem informal/ambígua.
- Conflitos de interesses e requisitos entre diferentes perfis de usuários.
- Mudanças contínuas no ambiente de negócios e dinâmica dos *stakeholders*.
- Fatores organizacionais e políticos que influenciam as decisões.

#### 🔄 Etapas do Ciclo Iterativo de Elicitação e Análise:
1. **Descoberta e Compreensão**: Interação ativa para identificar os requisitos do sistema e do domínio.
2. **Classificação e Organização**: Agrupamento dos requisitos relacionados em blocos coerentes.
3. **Priorização e Negociação**: Resolução de conflitos de requisitos e ordenação por grau de relevância.
4. **Documentação / Especificação**: Registro formal dos requisitos para realimentar as próximas iterações.

### 3. Técnicas de Elicitação de Requisitos

- **Entrevistas**:
  - *Fechadas*: Baseadas em uma lista pré-determinada de perguntas.
  - *Abertas*: Discussão livre e exploração de diversas questões com os *stakeholders*.
  - *Boas Práticas*: Manter a mente aberta, evitar ideias pré-concebidas, utilizar protótipos e incentivar o entrevistado a guiá-lo pelo fluxo operacional.
- **Etnografia (Observação)**:
  - Observação direta das pessoas executando seu trabalho para entender os artefatos reais utilizados.
  - *Etnografia Focada*: Foco em problemas específicos, revelando *workarounds* (gambiarras), interrupções do ambiente físico e o fluxo de trabalho real (não documentado).
- **Histórias e Cenários**:
  - *Histórias*: Narrativas práticas e sem termos técnicos que facilitam a empatia dos *stakeholders*.
  - *Cenários*: Descrições mais estruturadas e técnicas da interação passo a passo entre usuário e sistema.

### 4. Especificação de Requisitos & Notações

A especificação visa registrar os requisitos em um documento formal:
- **Requisitos de Usuário**: Escritos em linguagem acessível a clientes e usuários finais sem conhecimento técnico.
- **Requisitos de Sistema**: Descrições detalhadas e técnicas que servem de base para desenvolvimento e contratos.

| Notação | Descrição | Exemplo Prático |
| :--- | :--- | :--- |
| **Linguagem Natural** | Frases numeradas claras. Usa-se *"deve"* para requisitos obrigatórios e *"pode"* para desejáveis. | *"O sistema deve medir o nível de açúcar no sangue a cada 10 minutos."* |
| **Linguagem Natural Estruturada** | Formato baseado em formulários ou *templates* com campos específicos (Entradas, Saídas, Ações, Pré/Pós-condições). | *Especificação de controle da bomba de insulina (DoseComp).* |
| **Notações Gráficas** | Modelos visuais (UML) acompanhados de documentação textual. | *Diagramas de Casos de Uso (`<<include>>`, `<<extend>>`) para Ponto Biométrico ou Sistema Bancário.* |
| **Especificações Matemáticas** | Expressões formais inequívocas para reduzir ambiguidades em sistemas críticos. | *Fórmulas explícitas para cálculo de produção ou lucro semanal.* |

#### ⚠️ Cuidados ao Redigir em Linguagem Natural:
- Evitar a **Falta de Clareza** (ambiguidade), **Confusão de Requisitos** (misturar funcionais com não funcionais) e **Fusão de Requisitos** (agrupar múltiplos requisitos em uma só frase).

### 5. Documento de Requisitos de Software (Padrão IEEE/ANSI 830/1998)

Estrutura recomendada para a elaboração do *Software Requirements Specification* (SRS):

1. **Introdução**
   - 1.1 Propósito do documento de requisitos
   - 1.2 Escopo do produto
   - 1.3 Definições, siglas e abreviaturas
   - 1.4 Referências
   - 1.5 Visão geral do restante do documento
2. **Descrição Geral**
   - 2.1 Perspectiva do produto
   - 2.2 Funções do produto
   - 2.3 Características dos usuários
   - 2.4 Restrições gerais
   - 2.5 Suposições e dependências
3. **Requisitos Específicos** (Requisitos Funcionais e Não Funcionais)
4. **Índice**
5. **Apêndices**

---

## 📚 Referências

- MACHADO, Felipe Nery Rodrigues. **Análise e gestão de requisitos de software: onde nascem os sistemas**. 1ª ed. São Paulo: Érica, 2011.
- PRESSMAN, Roger S. **Engenharia de Software: Uma Abordagem Profissional**. 7ª ed. Porto Alegre: McGraw-Hill, 2011.
- SOMMERVILLE, Ian. **Engenharia de Software**. 10ª ed. São Paulo: Pearson, 2019.

---

## 👩‍🏫 Professora

**Profª Mª Denilce Veloso**  
📧 denilce.veloso@cps.sp.gov.br  

---

## ✒️ Autores

**Aluno da FATEC Sorocaba**  
[![GitHub](https://img.shields.io/badge/GitHub-100000?style=for-the-badge&logo=github&logoColor=white)](https://github.com/romerac)  
[![LinkedIn](https://img.shields.io/badge/LinkedIn-0077B5?style=for-the-badge&logo=linkedin&logoColor=white)](https://www.linkedin.com/in/viniciusromerac/)
