# Documento de Visão

**Projeto:** PKZ/Playmakers e One Two One

## 1. Contexto e Problema Central

A empresa possui duas frentes de atuação: a PKZ/Playmakers (focada no desenvolvimento de atletas) e a One Two One (voltada a treinamento personalizado para diferentes públicos).
Atualmente, a operação utiliza planilhas, Google Drive, WhatsApp e um aplicativo criado no Lovable. O principal problema enfrentado é a dificuldade de centralizar dados de alunos, avaliações, treinos, agenda, relatórios, arquivos, comunicação e cobranças. Com o volume de alunos e a expansão para novas unidades, os processos manuais estão cada vez mais difíceis de gerenciar.

## 2. Objetivos do Projeto

- Reduzir o trabalho manual e organizar todas as informações em um ambiente mais integrado.
- Dar mais autonomia ao aluno para consultar informações, agendar e desmarcar horários.
- Facilitar a comunicação com alunos, pais e responsáveis.
- Mostrar a evolução do atleta de forma visual e simples, utilizando gráficos e dashboards ao invés de relatórios longos.
- Melhorar a apresentação da marca, entregando uma solução mais profissional, coesa, visual e funcional.
- Automatizar os processos internos sem perder a proximidade e o relacionamento humano com o cliente.

## 3. Perfis de Usuários

- Aluno/atleta
- Pais ou responsáveis
- Professores
- Coordenação/gestão
- Recepção/administrativo
- Visitantes e potenciais clientes

## 4. Requisitos Funcionais

### 4.1. Website (Escopo Institucional)

- Apresentação das marcas: Explicar claramente PKZ e One Two One, mostrando que fazem parte do mesmo grupo, mas possuem públicos e objetivos diferentes.
- Portfólio: Apresentar serviços, tipos de treinamento e diferenciais de cada operação.
- Fotos e vídeos: Mostrar treinos e atividades para tornar o site mais visual e fortalecer a imagem da marca.
- Contato: Facilitar o contato com a empresa, principalmente via WhatsApp.
- Cadastro: Permitir que o aluno inicie o cadastro pelo website.
- Integração com o app: O website pode servir como porta de entrada para o aplicativo, login, inscrição ou agendamento.
- Experiência visual: Interface moderna, clara, intuitiva e fácil de usar, reforçando a identidade da empresa.

### 4.2. Sistema / Aplicativo (Gestão e Operação)

- Registrar testes físicos e gerar automaticamente relatórios/dashboards a partir dos dados inseridos.
- Comparar resultados conforme idade e modalidade e mostrar a evolução do atleta ao longo das reavaliações.
- Controlar retestes e destacar alunos com avaliação atrasada ou próxima do vencimento.
- Permitir ao professor registrar o relatório de cada treino e ao aluno consultar o histórico.
- Mostrar ao professor, já na agenda, informações relevantes do treino anterior para evitar buscas manuais.
- Permitir agendamento e cancelamento pelo próprio aluno, mostrando horários e vagas disponíveis.
- Enviar lembretes de agendamento, preferencialmente via WhatsApp.
- Controlar presença, professor responsável e relatórios pendentes.
- Permitir anexar arquivos externos, como documentos de fisioterapia.
- Controlar créditos e a frequência dos alunos.
- Criar área financeira contemplando mensalidades, vencimentos, pendências e formas de pagamento.
- (Evolução Futura) Automatização de scout e análise de desempenho esportivo.

## 5. Requisitos Não Funcionais (Qualidades Esperadas)

- ⁠Usabilidade: Deve exigir poucos cliques, ter acesso rápido e visualização simples.
- ⁠Clareza: Capacidade de traduzir números técnicos para gráficos e informações compreensíveis.
- Automação: O sistema deve evitar tarefas repetitivas e buscas manuais.
- ⁠Escalabilidade: A arquitetura deve suportar o crescimento do número de alunos, unidades e parcerias.
- ⁠Controle de acesso: O sistema deve garantir que cada perfil de usuário acesse apenas as funções adequadas a ele
- ⁠Integração: A plataforma deve permitir a possível ligação entre website, aplicativo, WhatsApp e meios de pagamentos
- ⁠Identidade visual: O design precisa transmitir uma imagem profissional e consistente da marca.

## 6. Regras de Negócio

- ⁠As avaliações físicas e técnicas devem obrigatoriamente considerar a faixa etária e a modalidade esportiva do atleta.
- ⁠O ciclo de vida do treinamento determina que o atleta é avaliado, recebe um planejamento de treino e, posteriormente, deve ser reavaliado para medir sua evolução.
- ⁠Os créditos semanais de aulas são renovados e não são cumulativos.
- ⁠O relatório de treino só deve ser criado e preenchido após a confirmação da presença do aluno.
- ⁠Somente o professor responsável por ministrar a aula tem permissão para preencher o relatório daquele treino.

## 7. Restrições e Pontos de Atenção

- ⁠Escopo: É preciso separar claramente as funcionalidades do website institucional do sistema completo de gestão, pois os dois temas estão misturados na visão do cliente.
- ⁠ ⁠Complexidade Externa: Dependências como integração com WhatsApp, gateways de pagamentos, sistemas de login e uso de IA aumentam a complexidade técnica e dependem de serviços externos.
- ⁠Segurança e Privacidade: O sistema lidará com dados pessoais de alunos e atletas, incluindo menores de idade, exigindo forte adequação à LGPD, privacidade e rígido controle de acesso.
- ⁠Escopo Futuro: A ideia de automatização de scout/análise de vídeo por IA é de alta complexidade e não deve compor o escopo do requisito básico do site atual.

## 8. Prioridades de Implementação

- ⁠*Essencial (Fase 1 - Site):* Apresentação das marcas PKZ e One Two One, exposição de serviços, fotos/vídeos, diferenciais, facilitação de contato/WhatsApp, identidade visual e responsividade.
- ⁠*Evolução (Fase 2 - Integração e App):* Cadastro e login de usuários, módulo de agenda, relatórios e gráficos de desempenho, notificações e controle financeiro.
- ⁠*Fora do Escopo Inicial (Fase 3):* Automação avançada de scout por vídeo.
