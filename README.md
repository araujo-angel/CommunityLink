# Proposta Técnica – CommunityLink

## 1. Problema que o projeto se propõe a solucionar
Atualmente, ações de voluntariado e projetos comunitários enfrentam dificuldades em atrair e organizar voluntários de forma eficiente. As iniciativas são divulgadas de maneira descentralizada (redes sociais, e-mails, grupos de mensagens), dificultando:  
- A comunicação entre organizadores e voluntários.  
- A inscrição e acompanhamento de atividades.  
- A centralização de informações em um único sistema confiável.  

O **CommunityLink** surge para solucionar este problema ao oferecer uma **plataforma web** que conecta voluntários e organizadores, possibilitando o cadastro, a gestão e a participação em ações comunitárias de forma simples e segura.  

---

## 2. Escopo  

### Objetivos SMART
Desenvolver uma **plataforma web de voluntariado comunitário** com propriedades de **cadastro de usuários, ações e inscrições**, através da utilização de **Spring Boot (backend) e Angular (frontend) em metodologia ágil (Scrum)**, para **facilitar a conexão entre voluntários e organizadores em um ambiente centralizado e acessível**, em tempo estimado de **3 sprints, com entrega final em fevereiro de 2025**.

### Funcionalidades por módulo  

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

---

## 3. Contexto  

- **Interfaces técnicas e organizacionais**:  
  - **Equipe de Desenvolvimento**: responsável pelo backend, frontend e testes.  
  - **Stakeholders (ONGs, empresas, líderes comunitários)**: fornecem requisitos e validam entregas.  
  - **Usuários finais**: voluntários e organizadores, envolvidos nos testes de usabilidade.  

- **Integração com outros softwares**:  
  - Nesta versão inicial **não haverá integrações externas** (ex.: CRMs, APIs de terceiros).  
  - O foco está em entregar um **MVP funcional web**.  

---

## 4. Características de Inovação
Embora já existam ferramentas de divulgação de ações (redes sociais, aplicativos específicos), o **CommunityLink** se diferencia por:  
- Ser uma **plataforma web dedicada exclusivamente ao voluntariado comunitário**.  
- Oferecer **simplicidade e centralização** de cadastros, inscrições e comunicação.  

---

## 5. Recursos Necessários  

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

---

## 6. Metodologia / Processo de Desenvolvimento  
- **Metodologia Ágil (Scrum)** com ciclos de **sprint de 3 semanas**.  
- Reuniões de acompanhamento conforme calendário acadêmico.  
- Entregas incrementais com revisão, retrospectiva e planejamento a cada sprint.  

---

## 7. Escopo Negativo  
- Não haverá versão **mobile** (Android/iOS).  
- Não haverá **análise de impacto social/ambiental** nesta versão.  
- Não haverá integração com **APIs externas** nesta fase.  
- Não serão incluídos módulos avançados (pontuação/recompensas, enquetes, relatórios analíticos).  

---

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

---

## 9. Restrições Tecnológicas e Legais  
- Backend: **Spring Boot**.  
- Frontend: **Angular**.  
- Banco de dados: **PostgreSQL**.  
- Legislação: conformidade básica com **LGPD** (armazenamento seguro de dados pessoais).  

---

## 10. Premissas  
- Os usuários (voluntários e organizadores) terão acesso à internet e a navegadores modernos.  
- O cliente fornecerá feedback contínuo durante as sprints.  
- A infraestrutura mínima de nuvem estará disponível até o fim da Sprint 1.  

---

## 11. Estimativas  

### Tempo (Cronograma)  
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

### Equipe  
- 1 dev backend (Spring Boot).  
- 1 dev frontend (Angular).  
- 1 QA.  
---

## Artefatos documentais da aplicação

- [Documento de Visão](./Documentacao/DocumentoDeVisao.md)
- [Requisitos de Software](./Documentacao/RequisitosDeSoftware.md)
