![Logo](https://bkpsitecpsnew.blob.core.windows.net/uploadsitecps/sites/212/2024/09/logo_fatec_sorocaba.png)

# Engenharia de Software 2 – Aula 06: Projeto, Implementação e Modelagem UML

<p align="center">
  <img src="https://img.shields.io/badge/Projeto%20%26%20Implementação-00599C?style=for-the-badge&logo=diagramsdotnet&logoColor=white" alt="Projeto e Implementação"/>
  <img src="https://img.shields.io/badge/Design%20Patterns-FF6B00?style=for-the-badge&logo=codefactor&logoColor=white" alt="Design Patterns"/>
  <img src="https://img.shields.io/badge/Modelagem%20UML-4CAF50?style=for-the-badge&logo=unifiedmodelinglanguage&logoColor=white" alt="Modelagem UML"/>
</p>

Este material sintetiza o conteúdo ministrado na **Aula 6** da disciplina de **Engenharia de Software 2**, pela **Profª Mª Denilce Veloso**, abordando a transição da Engenharia de Requisitos para as fases de **Projeto e Implementação**, os conceitos essenciais de **Padrões de Projeto (Design Patterns)**, **Modelagem Arquitetural e de Contexto com UML** e a resolução da **Atividade 6 (Estudo de Caso - Faculdade Alpha)**.

---

## 🎯 Objetivo da Aula

Compreender e aplicar os conceitos fundamentais do projeto e implementação de software, focando em:

- **Atividades de Projeto e Implementação**: Compreender a relação não linear entre conceber a arquitetura e implementar o código executável.
- **Padrões de Projeto (Design Patterns)**: Conhecer modelos de solução reutilizáveis (*Singleton*, *Factory Method*, *Observer*, *Strategy*).
- **Arquitetura de Software**: Identificar modelos organizacionais (MVC, arquitetura em camadas, comunicação cliente-servidor/API REST).
- **Modelagem de Contexto e Interação**: Mapear as fronteiras do sistema e as integrações com APIs/serviços externos.
- **Casos de Uso UML**: Elaborar diagramas e especificações detalhadas de requisitos funcionais.

---

## 📋 Conteúdo Programático

### 1. Projeto e Implementação de Software
Apesar da diversidade de metodologias, o desenvolvimento envolve a transição da **Especificação** para as fases de **Projeto (Design)** e **Implementação (Codificação)**:
- **Projeto de Software**: Atividade criativa que identifica os componentes do sistema e seus relacionamentos com base nos requisitos.
- **Implementação**: Processo de tradução das decisões de projeto em código executável em uma linguagem de programação.
- **Processo Intercalado**: Na prática, projeto e implementação ocorrem simultaneamente e de forma iterativa.

---

### 2. Padrões de Projeto (Design Patterns)
Os padrões de projeto são modelos de solução comprovados para problemas recorrentes na arquitetura de software. Eles representam boas práticas, promovem a reutilização de código e facilitam a manutenção.

| Padrão | Problema que Ajuda a Resolver | Ideia Principal |
| :--- | :--- | :--- |
| **Singleton** | Necessidade de garantir que uma classe tenha apenas uma única instância em todo o sistema. | Controlar e centralizar o acesso a uma única instância global. |
| **Factory Method** | Evitar a criação direta de objetos acoplados no código principal. | Delegar a responsabilidade de instanciação para subclasses ou métodos fábrica. |
| **Observer** | Notificar múltiplos objetos quando o estado de um objeto principal for alterado. | Criar uma relação de "inscrição e notificação" entre objetos dependentes. |
| **Strategy** | Necessidade de alternar entre diferentes algoritmos ou regras de negócio em tempo de execução. | Encapsular cada algoritmo em classes separadas e permitir sua troca dinâmica. |

---

### 3. Fases do Projeto e Arquitetura de Software
O projeto de software divide-se em três etapas principais:
1. **Projeto Arquitetural**: Define a estrutura modular global (ex.: MVC, Microsserviços), interfaces e persitência em banco de dados (SQL/NoSQL).
2. **Projeto Detalhado**: Especifica as soluções internas de cada módulo (autenticação, regras de negócio, rotas).
3. **Implementação**: Codificação final nas linguagens e *frameworks* escolhidos (ex.: Next.js, Node.js, Express, MongoDB, MySQL).

---

### 4. Modelagem de Contexto e Interação com UML
- **Modelos de Contexto**: Definem os limites e o ambiente externo do sistema, mostrando quais subsistemas e APIs externas interagem com a aplicação (ex.: APIs de Pagamento, APIs de Transporte, Satélites).
- **Modelos de Interação**: Descrevem dinamicamente as trocas de mensagens e serviços entre o sistema e seus atores.
- **Ponte de Análise**: O modelo de Casos de Uso atua como ponto de intersecção entre a Especificação de Requisitos e o Modelo Conceitual/Classes de Análise.

---

## 📚 Referências

- BOOCH, Grady et al. **The Unified Modeling Language User Guide**. Addison Wesley, 2005.
- MEDEIROS, Ernani. **Desenvolvendo Software com UML 2.0: Definitivo**. Makron Books, 2006.
- PRESSMAN, Roger S. **Engenharia de Software: Uma Abordagem Profissional**. 7ª ed. Porto Alegre: McGraw-Hill, 2011.
- SOMMERVILLE, Ian. **Engenharia de Software**. 10ª ed. São Paulo: Pearson, 2019.

---

## 👩‍🏫 Professora

**Profª Mª Denilce Veloso**  
📧 `denilce.veloso@cps.sp.gov.br`

---

## ✒️ Autores

**Aluno da FATEC Sorocaba**  
[![GitHub](https://img.shields.io/badge/GitHub-100000?style=for-the-badge&logo=github&logoColor=white)](https://github.com/romerac)  
[![LinkedIn](https://img.shields.io/badge/LinkedIn-0077B5?style=for-the-badge&logo=linkedin&logoColor=white)](https://www.linkedin.com/in/viniciusromerac/)
