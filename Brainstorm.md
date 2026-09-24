# Brainstorm - Site PKZ / One to One

> Projeto acadêmico de Front-End para criação de uma presença web integrada para a PKZ (Playmakerz) e a One to One.

---

## 1. Definição do problema

A PKZ e a One to One fazem parte da mesma operação, mas atendem públicos e necessidades diferentes. O projeto precisa apresentar as duas marcas de forma integrada, profissional e clara, permitindo que visitantes entendam rapidamente a proposta de cada uma e sejam direcionados para a experiência mais adequada.

Além da apresentação institucional, o cliente demonstrou interesse em facilitar o acesso a informações, contato, cadastro e, futuramente, recursos restritos para alunos e responsáveis.

### Problemas identificados

- Ausência de um website institucional consolidado para apresentar as duas marcas.
- Necessidade de explicar que PKZ e One to One pertencem ao mesmo grupo, mas possuem públicos e abordagens diferentes.
- Dificuldade de apresentar de forma simples a metodologia, os serviços, a estrutura e a equipe.
- Necessidade de uma comunicação mais visual, profissional e coerente com a identidade da marca.
- Dependência do WhatsApp para grande parte do contato com alunos, responsáveis e potenciais clientes.
- Necessidade de separar conteúdos públicos de informações privadas de alunos e atletas.
- Existência de funcionalidades internas importantes, como agenda, relatórios e evolução do aluno, que podem ser integradas ao projeto em etapas futuras.

---

## 2. Pergunta norteadora

**Como criar um site único para o grupo PKZ / One to One que apresente as duas marcas de forma clara, permita ao visitante escolher a experiência adequada ao seu perfil e mantenha espaço para futuras integrações com os serviços já utilizados pela empresa?**

---

## 3. Geração livre de ideias

Nesta etapa, as ideias são registradas sem julgamento ou descarte imediato.

- Criar uma página inicial funcionando como um **hub** para PKZ e One to One.
- Utilizar um vídeo ou imagens de treinamento na primeira seção do site.
- Apresentar uma frase curta que explique a proposta geral do grupo.
- Criar duas áreas visuais principais na página inicial: **PKZ** e **One to One**.
- Permitir que cada área leve para uma página específica da respectiva marca.
- Explicar que as duas marcas pertencem à mesma empresa e compartilham uma metodologia de atendimento individualizado.
- Criar uma seção "Sobre nós" contando brevemente a história do grupo.
- Apresentar a diferença entre o público e a abordagem da PKZ e da One to One.
- Mostrar a metodologia de trabalho de cada marca.
- Criar uma seção para apresentar serviços e tipos de treinamento.
- Criar uma seção com fotos e vídeos da estrutura e dos treinamentos.
- Utilizar a paleta oficial em branco e azul fornecida pelo cliente.
- Criar uma seção com os profissionais da equipe.
- Mostrar nome, função, formação e especialidade dos profissionais quando essas informações forem fornecidas pelo cliente.
- Criar uma seção de perguntas frequentes.
- Incluir perguntas sobre metodologia, horários, serviços e funcionamento.
- Evitar exibir um preço fixo como informação principal, pois os pacotes podem variar conforme a necessidade do cliente.
- Utilizar chamadas para **conhecer a empresa**, **agendar uma avaliação/aula experimental** ou **entrar em contato**.
- Disponibilizar acesso ao WhatsApp.
- Separar o contato da PKZ e da One to One dentro das respectivas páginas.
- Criar uma área para início de cadastro de novos interessados.
- Criar um acesso reservado para clientes já cadastrados.
- Deixar agenda, relatórios, histórico de treinos e gráficos de evolução dentro de uma área restrita.
- Apresentar gráficos de evolução de forma visual e acompanhados de observações explicativas.
- Permitir que informações relevantes do treino anterior possam aparecer na experiência do cliente/professor em uma evolução futura.
- Considerar fila de espera e notificações de agendamento como evolução futura do sistema.
- Priorizar navegação simples, com poucas etapas para chegar às informações principais.
- Criar layout responsivo para celular, tablet e computador.
- Aplicar boas práticas de acessibilidade e contraste.
- Evitar exposição de dados pessoais de alunos e atletas na área pública.
- Preparar a estrutura visual do front-end para futuras integrações com backend, agenda, relatórios e autenticação.
- Utilizar elementos visuais diferentes para PKZ e One to One sem perder a identidade comum do grupo.
- Criar uma navegação por seções na página inicial, inspirada em sites institucionais com rolagem simples e conteúdo progressivo.

--## 4. Agrupamento das ideias ### 4.1 Página inicial / Hub
- Apresentação geral do grupo.
- Vídeo ou imagem de impacto.
- Introdução curta sobre PKZ e One to One.
- Escolha visual entre as duas marcas.
- História resumida do grupo.
- Identidade visual comum.

### 4.2 Página PKZ
- Explicação da PKZ.
- Público predominantemente infantojuvenil e esportivo.
- Metodologia voltada ao desenvolvimento de atletas.
- Avaliações físicas e acompanhamento da evolução.
- Fotos e vídeos de treinamentos.
- Equipe.
- Perguntas frequentes.
- Contato e chamada para avaliação.
- Acesso do atleta/responsável à área restrita.

### 4.3 Página One to One
- Explicação da One to One.
- Público predominantemente adulto.
- Treinamento individualizado e musculação.
- Serviços oferecidos.
- Estrutura e equipamentos.
- Equipe.
- Perguntas frequentes.
- Contato e chamada para aula experimental.
- Acesso do cliente à área restrita.

### 4.4 Área restrita / Evoluções futuras
- Login e cadastro.
- Agenda.
- Agendamento e cancelamento.
- Histórico de treinos.
- Relatórios.
- Gráficos de evolução.
- Observações do treino anterior.
- Notificações.
- Fila de espera.
- Informações financeiras.

--## 5. Análise e seleção das ideias

| Prioridade | Ideias selecionadas |
|---|---|
| **Essencial para o site** | Hub inicial, apresentação das marcas, páginas separadas para PKZ e One to One, metodologia, serviços, equipe, fotos/vídeos, FAQ, contato e identidade ↩ visual responsiva. |
| **Importante** | Cadastro inicial, chamadas para avaliação/aula experimental, acesso à área do cliente e estrutura preparada para integração. |
| **Evolução futura** | Agenda em tempo real, cancelamento, fila de espera, notificações, relatórios, gráficos de evolução, observações de treino, financeiro e outras automações. |

--## 6. Direção escolhida

A proposta inicial é desenvolver um **portal central do grupo**, com uma página de entrada que apresenta a identidade comum e direciona o usuário para a PKZ ou para a One to One. Cada marca terá sua própria página, com conteúdo, linguagem e imagens adequadas ao seu público. O visitante poderá conhecer a empresa, entender a metodologia, visualizar a estrutura e entrar em contato. Clientes já cadastrados terão um ponto de acesso separado para uma área restrita, cuja integração completa dependerá das próximas etapas do projeto. O site deverá ser visual, responsivo, acessível e organizado por seções, priorizando clareza e facilidade de navegação.