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

O problema central é, portanto, _organizar a presença digital do grupo em uma experiência simples, visual e profissional, sem misturar conteúdos públicos com informações privadas de clientes_.

### 2.3 Proposta de solução

Criar um portal central que apresente o grupo e permita ao visitante escolher entre _PKZ_ e _One Two One_.

A partir dessa escolha, o usuário será direcionado para uma página específica da marca, com conteúdo adequado ao seu público. Cada página poderá apresentar metodologia, serviços, estrutura, equipe, fotos, vídeos, perguntas frequentes e formas de contato.

Clientes já cadastrados terão um ponto de acesso separado para a área restrita, evitando que informações pessoais apareçam no ambiente público.

### 2.4 Declaração de posicionamento

| Elemento       | Declaração                                                                                                            |
| -------------- | --------------------------------------------------------------------------------------------------------------------- |
| _Para_         | Visitantes, atletas, pais/responsáveis e pessoas interessadas em treinamento individualizado.                         |
| _Que precisam_ | Entender a proposta das marcas, conhecer os serviços e encontrar uma forma simples de iniciar contato.                |
| _O produto_    | É um portal web integrado para PKZ e One Two One.                                                                     |
| _Que oferece_  | Informação institucional clara, navegação por marca, conteúdo visual e acesso facilitado aos canais de contato.       |
| _Diferencial_  | Reúne as duas marcas em uma identidade comum, mas preserva a comunicação e a experiência específicas de cada público. |

---

### 3.1 Stakeholders

| Stakeholder                    | Interesse / necessidade                                                                                               |
| ------------------------------ | --------------------------------------------------------------------------------------------------------------------- |
| _Gestão da PKZ / One Two One_  | Apresentar as marcas de forma profissional, fortalecer a identidade do grupo e facilitar a comunicação com o público. |
| _Professores e equipe técnica_ | Ter as informações institucionais organizadas e, futuramente, acesso a recursos internos relacionados aos alunos.     |
| _Recepção / atendimento_       | Facilitar contato, cadastro, agendamentos e encaminhamento de interessados.                                           |
| _Equipe acadêmica_             | Transformar os requisitos do cliente em documentação, protótipo e front-end funcional.                                |
| _Professor da disciplina_      | Acompanhar a aplicação das técnicas de projeto, documentação, UX e desenvolvimento front-end.                         |

### 3.2 Usuários

| Usuário                            | Necessidades principais                                                                                               |
| ---------------------------------- | --------------------------------------------------------------------------------------------------------------------- |
| _Visitante / potencial cliente_    | Entender o que é a empresa, comparar as duas marcas, conhecer serviços e entrar em contato.                           |
| _Atleta da PKZ_                    | Conhecer a metodologia, visualizar informações da PKZ e acessar sua área quando disponível.                           |
| _Pai ou responsável_               | Entender o trabalho realizado com o atleta e acessar informações autorizadas de forma clara e segura.                 |
| _Cliente da One Two One_           | Conhecer serviços e acessar recursos pessoais quando disponíveis.                                                     |
| _Professor / profissional interno_ | Em etapas futuras, consultar informações de agenda e acompanhamento relacionadas aos alunos sob sua responsabilidade. |

---

## 4. Visão Geral do Produto

### 4.1 Estrutura geral

O portal será organizado em três níveis principais:

1. _Hub inicial do grupo_
   - Apresentação institucional.
   - Vídeo ou imagem de impacto.
   - Breve explicação do grupo.
   - Escolha entre PKZ e One Two One.
   2. _Página PKZ_
   - Apresentação da marca.
   - Público e metodologia.
   - Serviços e avaliações.
   - Fotos e vídeos.
   - Equipe.
   - Perguntas frequentes.
   - Contato e CTA.
   - Entrada para área do atleta/responsável.

.

3. _Página One Two One_
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

## 5. Requisitos de Alto Nível

### 5.1 Requisitos funcionais

| ID     | Requisito funcional                                                                                                                    |
| ------ | -------------------------------------------------------------------------------------------------------------------------------------- |
| _RF01_ | O portal deve apresentar a PKZ e a One Two One como marcas pertencentes ao mesmo grupo.                                                |
| _RF02_ | A página inicial deve permitir que o usuário escolha entre PKZ e One Two One.                                                          |
| _RF03_ | O sistema deve direcionar o usuário para uma página específica da marca selecionada.                                                   |
| _RF04_ | Cada página de marca deve apresentar descrição, público, metodologia e serviços.                                                       |
| _RF05_ | O site deve permitir a exibição de fotos e vídeos autorizados pelo cliente.                                                            |
| _RF06_ | O site deve apresentar uma seção com os profissionais da equipe quando os dados forem fornecidos pelo cliente.                         |
| _RF07_ | O site deve apresentar perguntas frequentes relacionadas a metodologia, horários, serviços e funcionamento.                            |
| _RF08_ | O site deve disponibilizar formas de contato, com destaque para WhatsApp nas páginas específicas de cada marca.                        |
| _RF09_ | O site deve oferecer chamadas para avaliação, aula experimental, cadastro ou contato, conforme a marca.                                |
| _RF10_ | O portal deve possuir um ponto de entrada para login/cadastro ou área restrita de clientes.                                            |
| _RF11_ | Informações privadas, como agenda, relatórios e evolução individual, devem ficar fora da área pública.                                 |
| _RF12_ | O protótipo poderá representar telas de agenda, histórico, relatórios e gráficos de evolução como preparação para futuras integrações. |
| _RF13_ | O usuário deve conseguir retornar ao hub e alternar entre as páginas das duas marcas sem dificuldade.                                  |

### 5.2 Requisitos não funcionais

| ID                          | Requisito não funcional                                                                                                      |
| --------------------------- | ---------------------------------------------------------------------------------------------------------------------------- |
| _RNF01 - Usabilidade_       | As informações principais devem ser encontradas com poucos passos e com linguagem clara.                                     |
| _RNF02 - Responsividade_    | O layout deve se adaptar a celular, tablet e computador.                                                                     |
| _RNF03 - Acessibilidade_    | O projeto deve observar contraste adequado, legibilidade, textos alternativos em imagens e navegação compreensível.          |
| _RNF04 - Identidade visual_ | O front-end deve utilizar a identidade visual oficial disponibilizada pelo cliente, mantendo coerência entre as duas marcas. |
| _RNF05 - Desempenho_        | Imagens e vídeos devem ser utilizados de forma otimizada para evitar carregamento excessivamente lento.                      |
| _RNF06 - Compatibilidade_   | A interface deve funcionar adequadamente nos principais navegadores modernos, incluindo Chrome, Safari e Firefox.            |
| _RNF07 - Privacidade_       | Nenhum dado pessoal real de aluno ou atleta deve ser exposto na área pública ou em protótipos acadêmicos.                    |
| _RNF08 - Manutenibilidade_  | A estrutura do front-end deve ser organizada para permitir inclusão de novas seções e futuras integrações.                   |
| _RNF09 - Consistência_      | Componentes, botões, tipografia, espaçamento e padrões de navegação devem manter comportamento visual consistente.           |

## 6. Restrições e Premissas

### 6.1 Restrições

•⁠ ⁠O projeto atual é acadêmico e possui foco em _Front-End_.
•⁠ ⁠Integrações reais com backend, banco de dados, autenticação, pagamentos e WhatsApp dependem de tecnologias e serviços adicionais.
•⁠ ⁠Dados pessoais reais de alunos, atletas e responsáveis não devem ser utilizados no protótipo público.
•⁠ ⁠Imagens de alunos, especialmente menores de idade, dependem de autorização adequada do cliente.
•⁠ ⁠O website não deve apresentar um preço único como regra geral, pois os pacotes podem variar conforme o serviço e a necessidade do cliente.
•⁠ ⁠O prazo de desenvolvimento é limitado ao calendário da disciplina.

### 6.2 Premissas

•⁠ ⁠O cliente fornecerá logos, paleta oficial e demais elementos de identidade visual.
•⁠ ⁠O cliente fornecerá ou autorizará fotos e vídeos que poderão ser usados no site.
•⁠ ⁠O conteúdo institucional será validado pelo cliente antes da versão final.
•⁠ ⁠PKZ e One Two One continuarão sendo apresentadas como partes do mesmo grupo.
•⁠ ⁠A página inicial funcionará como ponto de entrada comum e as páginas internas terão comunicação específica para cada marca.
•⁠ ⁠Funcionalidades privadas poderão ser prototipadas mesmo que a integração completa não seja realizada na primeira versão.
