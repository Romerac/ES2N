![Logo](https://bkpsitecpsnew.blob.core.windows.net/uploadsitecps/sites/212/2024/09/logo_fatec_sorocaba.png)

# Engenharia de Requisitos: Projeto e Implementação - Aula 06

<p align="center">
  <img src="https://img.shields.io/badge/Projeto%20e%20Implementação-FF6B00?style=for-the-badge&logo=checkmarx&logoColor=white" alt="Projeto e Implementação"/>
  <img src="https://img.shields.io/badge/UML-00599C?style=for-the-badge&logo=bookstack&logoColor=white" alt="UML"/>
  <img src="https://img.shields.io/badge/Casos%20de%20Uso-4CAF50?style=for-the-badge&logo=target&logoColor=white" alt="Casos de Uso"/>
</p>

Este material sintetiza o conteúdo ministrado na **Aula 6** da disciplina de **Engenharia de Software 2**, pela Profª Mª Denilce Veloso, abordando as fases de **Projeto e Implementação**, o **Projeto Orientado a Objetos com UML**, a construção e interpretação de **Diagramas de Casos de Uso** e o direcionamento prático para a próxima etapa do Projeto Integrador.

---

## 🎯 Objetivo da Aula

Compreender as atividades que compõem o projeto e a implementação de um software, com foco em:

- **Projeto e Implementação**: Relacionar as quatro atividades fundamentais de todo processo de software (Especificação, Desenvolvimento, Validação e Evolução).
- **Padrões de Projeto (Design Patterns)**: Reconhecer sua função como soluções reutilizáveis para problemas recorrentes de design.
- **UML e Projeto Orientado a Objetos**: Entender a linguagem gráfica utilizada para visualizar, especificar e documentar sistemas.
- **Modelos de Contexto e Casos de Uso**: Elaborar diagramas que delimitem o sistema e descrevam sua interação com atores externos.
- **Aplicação Prática**: Exercitar a identificação de atores, requisitos funcionais e a construção de Diagramas de Caso de Uso para o Projeto Integrador.

---

## 📚 Conteúdo Programático & Conceitos Chave

### 1. Projeto e Implementação
Todo Processo de Software deve incluir, de alguma forma, quatro atividades fundamentais (cada uma pode ser dividida em subatividades):
1. **Especificação** → Projeto
2. **Desenvolvimento** → Implementação
3. **Validação** → Testes
4. **Evolução**

O projeto e a implementação envolvem:
- Projeto Orientado a Objetos com UML;
- Padrões de Projeto (ex.: Singleton, Factory Method, Observer, Strategy);
- Questões de implementação (linguagens, frameworks, bibliotecas);
- Desenvolvimento Open Source.

### 2. Padrões de Projeto (Design Patterns)
São modelos de solução para problemas comuns de programação e projeto de software, orientando como organizar classes e objetos. Eles:
- Representam **boas práticas de design**;
- Ajudam a organizar melhor o sistema;
- Facilitam a manutenção e promovem reutilização;
- Padronizam soluções;
- **Não são código pronto** nem linguagem de programação — são ideias/modelos de solução implementados através da programação.

| Padrão | Problema que ajuda a resolver | Ideia principal |
|---|---|---|
| **Singleton** | Preciso garantir uma única instância de uma classe | Controlar a criação de uma única instância |
| **Factory Method** | Não quero que o código principal fique responsável diretamente por criar objetos | Delegar a criação dos objetos |
| **Observer** | Vários objetos precisam ser avisados quando algo muda | Criar uma relação de "notificação" |
| **Strategy** | Tenho várias formas de realizar uma determinada operação | Permitir escolher/trocar o algoritmo |

### 3. Implementação
- É o estágio do processo de engenharia de software no qual um **sistema de software executável é desenvolvido**.
- As atividades de projeto e implementação são invariavelmente **intercaladas** — o processo não é linear.
- O **projeto de software** é uma atividade criativa na qual se identificam componentes e seus relacionamentos com base nos requisitos do cliente.
- A **implementação** é o processo de realização do projeto em um programa de computador.

Inclui pelo menos três fases principais:
- **Projeto arquitetural** – define a estrutura modular do software (MVC, Camadas, Serviços etc.), as interfaces e as tecnologias de persistência (bancos SQL/NoSQL).
- **Projeto detalhado** – define a solução para cada módulo do projeto preliminar (ex.: autenticação, gerenciamento de usuário, pagamentos).
- **Implementação** – transcreve as decisões de projeto para a linguagem de programação escolhida.

> Em um processo de desenvolvimento orientado a objetos, o **projeto da arquitetura** normalmente é realizado por um **arquiteto de software**.

### 4. Projeto Orientado a Objetos com UML

**O que é UML?**
A UML (*Unified Modeling Language*) é uma linguagem padronizada de modelagem — uma **linguagem gráfica** para visualizar, especificar, construir e documentar um software através de diagramas compostos de gráficos, símbolos e texto, reduzindo ambiguidades e permitindo conexão com diferentes linguagens de programação.

Os processos de projeto orientados a objetos envolvem o desenvolvimento de vários modelos (Caso de Uso, Classes, Sequência, Atividades, Estado etc.), que exigem esforço tanto no desenvolvimento quanto na manutenção. Vantagens: código mais organizado, manutenção facilitada, reutilização e redução de erros — mas **não é a única abordagem** possível, sendo necessário analisar o **custo-benefício**.

**Estágios do processo**, entre outros:
- Definição do contexto e interações do sistema;
- Projeto de arquitetura do sistema;
- Identificação das principais classes e objetos;
- Desenvolvimento dos modelos de projeto;
- Especificações de interface de objetos.

**Objetivos principais da UML:**
- Delimitação do contexto de um sistema;
- Documentação e entendimento dos requisitos;
- Descrição dos requisitos funcionais;
- Utilização na análise e no projeto;
- Auxílio na modelagem.

### 5. Modelos de Contexto e Interações de Sistema
- **Modelo de contexto de sistema**: modelo estrutural que mostra outros sistemas no ambiente do sistema que está sendo desenvolvido.
- **Modelo de interação**: modelo dinâmico que mostra como o sistema interage com seu ambiente durante o uso.

Entender esses relacionamentos é essencial para decidir como estruturar a comunicação do sistema com o ambiente externo e para estabelecer os **limites do sistema** (o que será implementado internamente versus o que ficará a cargo de sistemas associados).

*Exemplos trabalhados em aula: contexto de um sistema de e-commerce (integração com APIs de transporte e pagamento) e contexto de uma estação meteorológica no deserto (Sistema de Controle, Sistema de Informação Meteorológica, Estação Meteorológica e Satélite).*

### 6. Ponte entre Requisitos e Análise
A UML atua como ponte entre a **Fase de Especificação dos Requisitos** e a **Fase de Análise**:


Especificação dos Requisitos / Modelagem do Contexto do Sistema 
                        ↓ 
       Modelo de Casos de Uso (interseção)
                        ↓
Modelo de Classes de Análise / Modelo Conceitual


### 7. Casos de Uso
**Caso de uso** é uma técnica de especificação que descreve uma sequência de ações que o sistema deve realizar para produzir uma resposta a um ator. Ele detalha **o que** o sistema deve fazer (e não como), descrevendo como uma funcionalidade é utilizada por um ator.

**Relacionamentos importantes na notação:**
- **`<<include>>`**: o caso de uso incluído é **sempre** executado como parte do fluxo do caso de uso principal.
- **`<<extend>>`**: o caso de uso estendido é executado **apenas condicionalmente**, em certas circunstâncias.
- **Generalização/Especialização**: ocorre quando atores possuem características semelhantes (ex.: "Pessoa" generalizando "Aluno", "Professor" e "Assistente").

*Exemplos trabalhados em aula: casos de uso de alto nível da estação meteorológica, de um cardápio digital (visão Administração e visão Cliente), de um sistema de almoxarifado e de um sistema escolar.*

---

## 🛠️ Ferramentas Gratuitas Sugeridas para UML

1. Edraw Max
2. Lucidchart
3. Draw.io
4. Creately
5. Cacoo
6. Visual Paradigm
7. PlantUML
8. Figma
9. Miro

---

## 📚 Referências

- BOOCH, Grady et al. **The Unified Modeling Language User Guide**. Addison Wesley, 2005.
- MEDEIROS, Ernani. **Desenvolvendo Software com UML 2.0: Definitivo**. Makron Books, 2006.
- PRESSMAN, Roger S. **Engenharia de Software: Uma Abordagem Profissional**. 7ª ed. Porto Alegre: McGraw-Hill, 2011.
- SOMMERVILLE, Ian. **Engenharia de Software**. 10ª ed. São Paulo: Pearson, 2019.

---

## 💻 Exercício Prático — Faculdade Alpha

A Faculdade Alpha está criando uma aplicação para utilização de vários tipos de usuários (atores):
- **Alunos** podem: realizar matrícula pela aplicação, solicitar histórico, solicitar transferência, consultar notas e frequência.
- Quando o aluno **solicita transferência**, ela deve ser **aprovada pelo funcionário da secretaria**.
- A **secretaria** pode cadastrar, alterar, excluir ou consultar um aluno, além de realizar matrículas.
- Os **professores** podem incluir, alterar, excluir ou consultar notas e frequência dos alunos.
- Todos os usuários precisam **fazer login**, podendo **fazer logout** e **recuperar a senha**.

**O que fazer:**
1. Identificar os atores;
2. Listar os Requisitos Funcionais;
3. Elaborar o Diagrama de Caso de Uso.

---

## 👩‍🏫 Professora

**Profª Mª Denilce Veloso**
📧 denilce.veloso@cps.sp.gov.br

---
## ✒️ Autores

**Aluno da FATEC Sorocaba**  
[![GitHub](https://img.shields.io/badge/GitHub-100000?style=for-the-badge&logo=github&logoColor=white)](https://github.com/romerac)  
[![LinkedIn](https://img.shields.io/badge/LinkedIn-0077B5?style=for-the-badge&logo=linkedin&logoColor=white)](https://www.linkedin.com/in/viniciusromerac/)
