![Logo](https://bkpsitecpsnew.blob.core.windows.net/uploadsitecps/sites/212/2024/09/logo_fatec_sorocaba.png)

# Engenharia de Requisitos: Validação e Gerenciamento - Aula 05

<p align="center">
  <img src="https://img.shields.io/badge/Validação%20de%20Requisitos-FF6B00?style=for-the-badge&logo=checkmarx&logoColor=white" alt="Validação de Requisitos"/>
  <img src="https://img.shields.io/badge/Gerenciamento%20de%20Mudanças-00599C?style=for-the-badge&logo=bookstack&logoColor=white" alt="Gerenciamento de Mudanças"/>
  <img src="https://img.shields.io/badge/Rastreabilidade-4CAF50?style=for-the-badge&logo=target&logoColor=white" alt="Rastreabilidade"/>
</p>

Este material sintetiza o conteúdo ministrado na **Aula 5** da disciplina de **Engenharia de Software 2**, pela Profª Mª Denilce Veloso, abordando os processos de **Validação de Requisitos**, as **Verificações de Qualidade**, o **Gerenciamento e Evolução de Requisitos**, a **Rastreabilidade** e os critérios para o desenvolvimento dos artefatos do Projeto Integrador.

---

## 🎯 Objetivo da Aula

Compreender e aplicar as etapas finais da Engenharia de Requisitos, focando em:

- **Validação de Requisitos**: Assegurar que os requisitos especificados definem com precisão o sistema que o cliente deseja e necessita.
- **Verificações de Qualidade**: Aplicar as 5 verificações fundamentais (validade, consistência, completude, realismo e verificabilidade).
- **Técnicas Práticas de Validação**: Executar revisões sistemáticas, prototipação e geração de casos de teste.
- **Gerenciamento de Mudanças & Rastreabilidade**: Controlar o ciclo de vida dos requisitos e mapear dependências (fonte, requisitos dependentes e módulos de projeto).
- **Adequação do Projeto Integrador**: Elaborar os requisitos funcionais, estruturar a pesquisa de campo e aplicar o TCLE (Termo de Consentimento Livre e Esclarecido).

---

## 📋 Resolução da Atividade 5

### 1. Por que a fase de validação de requisitos é tão crítica e quais as consequências de ignorá-la?
- **Importância**: A validação assegura que o sistema a ser construído reflete exatamente as necessidades e expectativas do cliente. Como destaca a *Perspectiva de Produto* (Marty Cagan), o maior desperdício em software não é construir de forma ineficiente, mas construir o produto errado.
- **Consequências de ignorar**: O custo de correção de erros de requisitos cresce exponencialmente nas fases avançadas. Ignorar essa etapa pode resultar em:
  - Gastos elevados com alocação de profissionais para correções emergenciais;
  - Inatividade do sistema (*downtime*);
  - Perda de dados sigilosos e falhas de segurança;
  - Desperdício de transações financeiras e operacionais;
  - Danos à reputação e credibilidade da organização.

### 2. Identificar as cinco principais verificações (ou conferências) que são feitas no processo de validação.
1. **Verificação da Validade**: Avalia se o sistema oferece as funções que melhor atendem às reais necessidades do cliente e dos usuários finais.
2. **Verificação da Consistência**: Garante que não existam contradições ou conflitos entre diferentes requisitos especificados.
3. **Verificação da Completude**: Certifica-se de que todas as funcionalidades, regras de negócio e restrições operacionais solicitadas foram devidamente incluídas.
4. **Verificação do Realismo**: Examina se os requisitos podem ser efetivamente implementados considerando as limitações tecnológicas, orçamentárias e de prazo.
5. **Facilidade de Verificação (Verificabilidade)**: Assegura que o requisito é mensurável e testável na prática (através de testes automatizados, inspeções ou documentação).

### 3. Quais são as três técnicas principais de validação? Explique.
1. **Revisões de Requisitos**: Análise manual e sistemática conduzida por uma equipe multidisciplinar (clientes e desenvolvedores) para conferir a clareza, completude, consistência e rastreabilidade do documento.
2. **Prototipação**: Criação de modelos visuais ou executáveis do sistema para permitir que o usuário interaja e valide a dinâmica do software antes da codificação final.
3. **Geração de Casos de Teste**: Elaboração antecipada de cenários e testes de aceitação derivados dos requisitos para garantir a corretude durante o desenvolvimento.

---

## 📚 Conteúdo Programático & Conceitos Chave

### 1. Mudança e Evolução de Requisitos
Os requisitos de um software são dinâmicos e evoluem devido a:
- Mudanças no ambiente tecnológico (SO, hardware ou integrações);
- Alterações em legislações e normas regulatórias (ex.: LGPD);
- Conflitos de interesses entre quem financia o sistema (clientes) e quem o opera (usuários finais);
- Amadurecimento do entendimento do problema durante o desenvolvimento.

### 2. Rastreabilidade de Requisitos
Capacidade de acompanhar o histórico e os relacionamentos de cada requisito ao longo do ciclo de vida:
- **Rastreabilidade da Fonte**: Associa o requisito aos *stakeholders* que o solicitaram.
- **Rastreabilidade de Requisitos Dependentes**: Mapeia o vínculo e a interdependência entre os próprios requisitos.
- **Rastreabilidade de Projeto**: Conecta os requisitos aos componentes arquiteturais, módulos de código e tabelas do banco de dados.
- **Matriz de Rastreabilidade**: Tabela utilizada para visualizar relacionamentos ($R$) e dependências ($D$) diretas entre requisitos.


### 3. Ferramentas Recomendadas
- **Gerenciamento de Requisitos Especializado**: Visure Requirements, IBM Rational DOORS, Jama Software, Helix ALM, ReQtest.
- **Gestão Ágil e de Projetos**: Jira, Azure DevOps, Trello, Asana.

---

## 📚 Referências

- MACHADO, Felipe Nery Rodrigues. **Análise e gestão de requisitos de software: onde nascem os sistemas**. 1ª ed. São Paulo: Érica, 2011.
- PRESSMAN, Roger S. **Engenharia de Software: Uma Abordagem Profissional**. 7ª ed. Porto Alegre: McGraw-Hill, 2011.
- SOMMERVILLE, Ian. **Engenharia de Software**. 10ª ed. São Paulo: Pearson, 2019.

---

## 👩‍🏫 Professora

**Profª Mª Denilce Veloso**  
📧 denilce.veloso@fatec.sp.gov.br

---

## ✒️ Autores

**Aluno da FATEC Sorocaba**  
[![GitHub](https://img.shields.io/badge/GitHub-100000?style=for-the-badge&logo=github&logoColor=white)](https://github.com/romerac)  
[![LinkedIn](https://img.shields.io/badge/LinkedIn-0077B5?style=for-the-badge&logo=linkedin&logoColor=white)](https://www.linkedin.com/in/viniciusromerac/)
