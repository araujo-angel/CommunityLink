# Proposta Técnica – CommunityLink


## 1. Sobre o documento
O presente documento apresenta uma proposta técnica para a execução do projeto **CommunityLink**.


## 2. Contexto e Motivação
### 2.1 Problema/Motivação
Atualmente, ações de voluntariado e projetos comunitários enfrentam dificuldades em atrair e organizar voluntários de forma eficiente. As iniciativas são divulgadas de maneira descentralizada (redes sociais, e-mails, grupos de mensagens), dificultando:  
- A comunicação entre organizadores e voluntários.  
- A inscrição e acompanhamento de atividades.  
- A centralização de informações em um único sistema confiável.  

O **CommunityLink** surge para solucionar este problema ao oferecer uma **plataforma web** que conecta voluntários e organizadores, possibilitando o cadastro, a gestão e a participação em ações comunitárias de forma simples e segura.  

[![](https://mermaid.ink/img/pako:eNp1k9Fu2jAUhl_F8tUmBZpQQiAXkyjQahItsBYmLeHCkEOwSGxmO1VbysNMu9jVLvcEvNhOEkShY5Ei-djnfD7_b3tD5zIC6tNYsfWSPHRDEQqdzcpwmDDDFlKlLAjpW0A6Mk0zwc1zn4sV-fAVZh9DOg0FwW8cjHW2-6G4JBUykUkmTBFNSaXyibx2WMS0UdIin4WeK777tfspX0-JJWhwDBqomAn-wiKp3oFIBIQh5Q_os5jTXovSO2n4gs_3VRbpc21YDAIB4_8W3YA22OrJdoNQgIhOLOt9z_ga0K5ykKd3QYN4lMkjT0EYeXCq25s4wRWbr5CBEu_XiouYXElp3hJqwbWSwpQZbRFnCVP71VE7GLUvHrAt0NNDIzm0aPidFTnr3PyofW72SNC9YStYyiQCpVHWcUh6TwaUkPogaXB3E-CvyQXp735jDugcnZOLk9T7vN7tMOila1xmmgyZmgNX7EgFMkrXvwDaqLmROfIaIJqhX_-cM-LOpE9YwiN2_oJRC288j6i_YIkGi6aA9zqP6SbvMKRmCSmE1MdhxNQqpKHYYtGaiW9SptQ3KsMyJbN4eYBk64gZ6HKGzqWHWYWaQHUkPgTqu45dQKi_oU_Ur3iNqm3Xmm695TYbNcdpWfSZ-rWaXXW91qXbdFy77np1b2vRl2Jfp2pfNhpN1226Lc9t1D2LQoSC1W35jovnvP0Lbm9WoA?type=png)](https://mermaid.live/edit#pako:eNp1k9Fu2jAUhl_F8tUmBZpQQiAXkyjQahItsBYmLeHCkEOwSGxmO1VbysNMu9jVLvcEvNhOEkShY5Ei-djnfD7_b3tD5zIC6tNYsfWSPHRDEQqdzcpwmDDDFlKlLAjpW0A6Mk0zwc1zn4sV-fAVZh9DOg0FwW8cjHW2-6G4JBUykUkmTBFNSaXyibx2WMS0UdIin4WeK777tfspX0-JJWhwDBqomAn-wiKp3oFIBIQh5Q_os5jTXovSO2n4gs_3VRbpc21YDAIB4_8W3YA22OrJdoNQgIhOLOt9z_ga0K5ykKd3QYN4lMkjT0EYeXCq25s4wRWbr5CBEu_XiouYXElp3hJqwbWSwpQZbRFnCVP71VE7GLUvHrAt0NNDIzm0aPidFTnr3PyofW72SNC9YStYyiQCpVHWcUh6TwaUkPogaXB3E-CvyQXp735jDugcnZOLk9T7vN7tMOila1xmmgyZmgNX7EgFMkrXvwDaqLmROfIaIJqhX_-cM-LOpE9YwiN2_oJRC288j6i_YIkGi6aA9zqP6SbvMKRmCSmE1MdhxNQqpKHYYtGaiW9SptQ3KsMyJbN4eYBk64gZ6HKGzqWHWYWaQHUkPgTqu45dQKi_oU_Ur3iNqm3Xmm695TYbNcdpWfSZ-rWaXXW91qXbdFy77np1b2vRl2Jfp2pfNhpN1226Lc9t1D2LQoSC1W35jovnvP0Lbm9WoA)

### 2.2 Contexto
- **Interfaces técnicas e organizacionais**:  
  - **Equipe de Desenvolvimento**: responsável pelo backend, frontend e testes.  
  - **Stakeholders (ONGs, empresas, líderes comunitários)**: fornecem requisitos e validam entregas.  
  - **Usuários finais**: voluntários e organizadores, envolvidos nos testes de usabilidade.  

- **Integração com outros softwares**:  
  - Nesta versão inicial **não haverá integrações externas** (ex.: CRMs, APIs de terceiros, exceto para notificações).  
  - O foco está em entregar um **MVP funcional web**.  

## 3. Objetivos do Projeto
### Objetivos SMART
Desenvolver uma **plataforma web de voluntariado comunitário** com propriedades de **cadastro de usuários, ações e inscrições**, através da utilização de **Spring Boot (backend) e Angular (frontend) em metodologia ágil (Scrum)**, para **facilitar a conexão entre voluntários e organizadores em um ambiente centralizado e acessível**, em tempo estimado de **3 sprints, com entrega final em fevereiro de 2025**.

## 4. Detalhamento do Escopo
### 4.1 Funcionalidades por módulo  

**Módulo Usuário (Voluntários e Organizadores)**  
- Cadastro, login e autenticação.  
- Gerenciamento de perfil.  

**Módulo Ações Comunitárias**  
- Cadastro e edição de ações (apenas para organizadores).  
- Listagem de ações disponíveis.  
- Busca e filtros por interesse.  
- Inscrição em ações (para voluntários).  

**Módulo Comunicação Básica**  
- Notificações simples via web (ex.: confirmação de inscrição).  
- Listagem das ações inscritas por cada usuário.

### 4.2 Escopo Negativo
- Não haverá versão **mobile** (Android/iOS).  
- Não haverá **análise de impacto social/ambiental** nesta versão.  
- Não haverá integração com **APIs externas** nesta fase.  
- Não serão incluídos módulos avançados (pontuação/recompensas, enquetes, relatórios analíticos).  

### 4.3 Características de Inovação
Embora já existam ferramentas de divulgação de ações (redes sociais, aplicativos específicos), o **CommunityLink** se diferencia por:  
- Ser uma **plataforma web dedicada exclusivamente ao voluntariado comunitário**.  
- Oferecer **simplicidade e centralização** de cadastros, inscrições e comunicação.  

## 5 Processo de Desenvolvimento  
- **Metodologia Ágil (Scrum)** com ciclos de **sprint de 3 semanas**.  
- Reuniões de acompanhamento conforme calendário acadêmico.  
- Entregas incrementais com revisão, retrospectiva e planejamento a cada sprint.
  
### 5.1 Recursos Necessários  

- **Infraestrutura de Software**:  
  - Backend: Spring Boot + banco relacional (PostgreSQL).  
  - Frontend: Angular + Angular Material.    

- **Recursos Humanos**:  
  - 1 desenvolvedora backend.  
  - 1 desenvolvedora frontend.  
  - 1 QA.  

- **Outros Recursos**:  
  - Repositório GitHub.  
  - Ferramentas de gestão (OpenProject).  

## 6. Restrições Tecnológicas e Legais  
- Backend: **Spring Boot**.  
- Frontend: **Angular**.  
- Banco de dados: **PostgreSQL**.  
- Legislação: conformidade básica com **LGPD** (armazenamento seguro de dados pessoais).
- Integrações: Nenhuma prevista nesta versão.
- Dados de terceiros: Não há dependência externa nesta fase.

## 7. Premissas  
- Os usuários (voluntários e organizadores) terão acesso à internet e a navegadores modernos.  
- O cliente fornecerá feedback contínuo durante as sprints.  
- A infraestrutura mínima de nuvem estará disponível até o fim da Sprint 1.  

## 8. Análise dos Riscos  

| Risco                               | Tipo      | Probabilidade | Impacto | P*I | Mitigação                                                                 | Contingência                                                                 |
|-------------------------------------|-----------|---------------|---------|-----|---------------------------------------------------------------------------|----------------------------------------------------------------------------|
| Atraso na entrega das sprints       | Projeto   | Médio         | Alto    | Risco Alto  | Planejamento detalhado e acompanhamento semanal                           | Repriorizar backlog e reduzir escopo de funcionalidades menos críticas      |
| Dificuldade técnica (Spring/Angular)| Técnico   | Médio         | Médio   | Risco Médio | Treinamentos rápidos e divisão equilibrada de tarefas                     | Substituição temporária por soluções mais simples ou apoio externo          |
| Falta de engajamento dos stakeholders| Negócio  | Baixo         | Alto    | Risco Médio | Reuniões periódicas de alinhamento e feedback                             | Decisões assumidas pela equipe de desenvolvimento com base em requisitos já validados |
| Problemas de infraestrutura (deploy)| Técnico   | Médio         | Médio   | Risco Médio | Uso de ambientes de nuvem gratuitos confiáveis e testes prévios de deploy | Migração rápida para outro provedor ou uso de ambiente local temporário     |

- **Observações:**
  - A escala usada foi qualitativa (Baixo = 1, Médio = 2, Alto = 3).
  - O P*I é o produto da probabilidade pelo impacto (ex.: Médio = 2, Alto = 3 → 2×3 = 6).

## 9. Estimativa de Tamanho
### 9.1 Contagem NESMA (estimativa)

Com base no escopo atual, o sistema é classificado como pequeno porte, com aproximadamente 80 a 100 PF (pontos de função), considerando as funcionalidades de cadastro, listagem, consulta e notificações.

### 9.2 Contagem IFPUG (detalhada)

- ALIs (Arquivos Lógicos Internos): Usuário, Ação Comunitária, Inscrição → 3 ALIs.
- AIEs (Arquivos de Interface Externa): não previstos nesta versão.
- Entradas Externas: Cadastro de usuário, login, cadastro de ação, inscrição em ação → 4 entradas.
- Consultas Externas: Busca/listagem de ações, listagem de inscrições do usuário → 2 consultas.
- Saídas Externas: Notificações básicas (confirmação de inscrição) → 1 saída.

Estimativa final: ~95 pontos de função.

## 10. Cronograma
Baseado no calendário acadêmico e priorizando valor ao cliente:  

- **Sprint 1 (30/out – 16/nov)**  
  - Configuração inicial do ambiente (backend e frontend).  
  - Cadastro/Login de usuários (base para acesso ao sistema).  
  - Cadastro e listagem de ações comunitárias.  

- **Sprint 2 (17/nov – 14/dez)**  
  - Inscrição de voluntários em ações.  
  - Interface com filtros de busca para facilitar navegação.  
  - Estrutura inicial de notificações (confirmação de inscrição).  

- **Sprint 3 (15/dez – 04/fev)**  
  - Lista de ações inscritas por usuário (área do voluntário).  
  - Notificações básicas adicionais.  
  - Ajustes finais, testes e deploy em ambiente de produção.   

## 11. Equipe  
- 1 dev backend (Spring Boot).  
- 1 dev frontend (Angular).  
- 1 QA.

## 12. Orçamento  
Considerando o valor médio de R$ 900,00 por ponto de função (valor de referência acadêmica), e a estimativa de 95 pontos de função, o custo total estimado do projeto seria de:

- 95 PF × R$ 900,00 = R$ 85.500,00

Esse valor inclui custos de desenvolvimento, testes e documentação, desconsiderando custos de infraestrutura de nuvem (uso de serviços gratuitos).

---

## Artefatos documentais da aplicação

- [Documento de Visão](./Documentacao/DocumentoDeVisao.md)
- [Requisitos de Software](./Documentacao/RequisitosDeSoftware.md)
