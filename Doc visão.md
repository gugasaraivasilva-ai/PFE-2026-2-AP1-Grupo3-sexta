# Documento de Visão - Portal PKZ / One Two One

> Documento de visão do projeto acadêmico de Front-End para a PKZ (Playmakerz) e a One Two One.

---

## 1. Introdução

### 1.1 Propósito

Este documento define a visão do portal web da **PKZ / One Two One**, alinhando o entendimento entre cliente, equipe de desenvolvimento e professor sobre o problema, o escopo, os usuários, as funcionalidades de alto nível, as restrições e os principais riscos do projeto.

O objetivo do produto é criar uma presença digital integrada para as duas marcas, permitindo que visitantes conheçam o grupo, entendam a diferença entre PKZ e One Two One e sejam direcionados para a experiência adequada ao seu perfil.

### 1.2 Público-alvo do documento

Este documento é destinado a:

- Cliente e responsáveis pela PKZ / One Two One.
- Equipe acadêmica responsável pelo projeto.
- Professor responsável pela disciplina.
- Demais integrantes envolvidos na validação de requisitos, protótipo e implementação.

### 1.3 Escopo do sistema

O projeto contempla um **portal web responsivo** composto por:

- Uma página inicial que funciona como hub do grupo.
- Apresentação geral da PKZ / One Two One.
- Direcionamento para uma página específica da PKZ.
- Direcionamento para uma página específica da One Two One.
- Conteúdo institucional sobre metodologia, serviços, estrutura e equipe.
- Fotos e vídeos fornecidos ou autorizados pelo cliente.
- Perguntas frequentes.
- Chamadas para contato, avaliação ou aula experimental.
- Acesso para cadastro e/ou área restrita de clientes, conforme a evolução do projeto.

Funcionalidades como agenda em tempo real, autenticação completa, relatórios automáticos, gráficos com dados reais, pagamentos, notificações e integrações externas dependem de backend e serviços adicionais. Essas funcionalidades poderão ser representadas no protótipo ou preparadas como evolução futura, mas não são assumidas como parte obrigatória da implementação inicial do front-end.

### 1.4 Definições e abreviações

| Termo                | Definição                                                                                                         |
| -------------------- | ----------------------------------------------------------------------------------------------------------------- |
| **PKZ / Playmakerz** | Marca do grupo voltada principalmente ao desenvolvimento esportivo e ao treinamento de atletas.                   |
| **One Two One**      | Marca do grupo voltada principalmente ao treinamento individualizado, musculação e atendimento de público adulto. |
| **Hub**              | Página inicial que reúne e direciona o usuário para as duas marcas.                                               |
| **Landing page**     | Página específica de uma marca, serviço ou objetivo.                                                              |
| **Área restrita**    | Espaço acessível somente por usuários autorizados.                                                                |
## 2. Posicionamento

### 2.1 Oportunidade

A PKZ e a One Two One possuem uma operação em crescimento, diferentes públicos e uma metodologia de atendimento individualizado, porém ainda não contam com um website institucional consolidado que organize essas informações e apresente as duas marcas de forma integrada.

O portal cria a oportunidade de:

- Fortalecer a presença digital do grupo.
- Explicar de forma clara a proposta de cada marca.
- Apresentar metodologia, equipe e estrutura.
- Facilitar o primeiro contato de novos interessados.
- Organizar o caminho entre conteúdo público e serviços destinados a clientes.
- Criar uma base visual para integrações futuras com os processos internos já utilizados pela empresa.

### 2.2 Problema a ser resolvido

Atualmente, grande parte das informações e contatos depende de comunicação direta, principalmente via WhatsApp. Além disso, PKZ e One Two One possuem públicos e abordagens diferentes, o que pode gerar dúvidas para quem ainda não conhece o grupo.

Também existem informações internas importantes, como agenda, relatórios e evolução dos alunos, que precisam permanecer separadas do conteúdo público.

O problema central é, portanto, *organizar a presença digital do grupo em uma experiência simples, visual e profissional, sem misturar conteúdos públicos com informações privadas de clientes*.

### 2.3 Proposta de solução

Criar um portal central que apresente o grupo e permita ao visitante escolher entre *PKZ* e *One Two One*.

A partir dessa escolha, o usuário será direcionado para uma página específica da marca, com conteúdo adequado ao seu público. Cada página poderá apresentar metodologia, serviços, estrutura, equipe, fotos, vídeos, perguntas frequentes e formas de contato.

Clientes já cadastrados terão um ponto de acesso separado para a área restrita, evitando que informações pessoais apareçam no ambiente público.

### 2.4 Declaração de posicionamento

| Elemento | Declaração |
|---|---|
| *Para* | Visitantes, atletas, pais/responsáveis e pessoas interessadas em treinamento individualizado. |
| *Que precisam* | Entender a proposta das marcas, conhecer os serviços e encontrar uma forma simples de iniciar contato. |
| *O produto* | É um portal web integrado para PKZ e One Two One. |
| *Que oferece* | Informação institucional clara, navegação por marca, conteúdo visual e acesso facilitado aos canais de contato. |
| *Diferencial* | Reúne as duas marcas em uma identidade comum, mas preserva a comunicação e a experiência específicas de cada público. |

---
### 3.1 Stakeholders

| Stakeholder | Interesse / necessidade |
|---|---|
| *Gestão da PKZ / One Two One* | Apresentar as marcas de forma profissional, fortalecer a identidade do grupo e facilitar a comunicação com o público. |
| *Professores e equipe técnica* | Ter as informações institucionais organizadas e, futuramente, acesso a recursos internos relacionados aos alunos. |
| *Recepção / atendimento* | Facilitar contato, cadastro, agendamentos e encaminhamento de interessados. |
| *Equipe acadêmica* | Transformar os requisitos do cliente em documentação, protótipo e front-end funcional. |
| *Professor da disciplina* | Acompanhar a aplicação das técnicas de projeto, documentação, UX e desenvolvimento front-end. |

### 3.2 Usuários

| Usuário | Necessidades principais |
|---|---|
| *Visitante / potencial cliente* | Entender o que é a empresa, comparar as duas marcas, conhecer serviços e entrar em contato. |
| *Atleta da PKZ* | Conhecer a metodologia, visualizar informações da PKZ e acessar sua área quando disponível. |
| *Pai ou responsável* | Entender o trabalho realizado com o atleta e acessar informações autorizadas de forma clara e segura. |
| *Cliente da One Two One* | Conhecer serviços e acessar recursos pessoais quando disponíveis. |
| *Professor / profissional interno* | Em etapas futuras, consultar informações de agenda e acompanhamento relacionadas aos alunos sob sua responsabilidade. |

---
## 4. Visão Geral do Produto

### 4.1 Estrutura geral

O portal será organizado em três níveis principais:

1. *Hub inicial do grupo*
   - Apresentação institucional.
   - Vídeo ou imagem de impacto.
   - Breve explicação do grupo.
   - Escolha entre PKZ e One Two One.
   
   2. *Página PKZ*
   - Apresentação da marca.
   - Público e metodologia.
   - Serviços e avaliações.
   - Fotos e vídeos.
   - Equipe.
   - Perguntas frequentes.
   - Contato e CTA.
   - Entrada para área do atleta/responsável.

.

3. *Página One Two One*
   - Apresentação da marca.
   - Público e metodologia.
   - Serviços e estrutura.
   - Fotos e vídeos.
   - Equipe.
   - Perguntas frequentes.
   - Contato e CTA.
   - Entrada para área do cliente.

   ### 4.2 Recursos principais

- Navegação simples por seções.
- Identidade visual baseada nos materiais oficiais do cliente.
- Conteúdo visual com fotos e vídeos.
- Apresentação da metodologia e dos serviços.
- Seção de equipe.
- Perguntas frequentes.
- Botões de contato.
- CTA para avaliação, aula experimental ou cadastro.
- Acesso separado para clientes.
- Estrutura responsiva.

### 4.3 Diferenciais do produto

- Uma única porta de entrada para duas marcas relacionadas.
- Comunicação específica para cada público.
- Separação clara entre visitante e cliente cadastrado.
- Conteúdo institucional organizado para reduzir dúvidas recorrentes.
- Estrutura preparada para crescimento e futuras integrações.
- Uso de informações visuais para facilitar a compreensão.

