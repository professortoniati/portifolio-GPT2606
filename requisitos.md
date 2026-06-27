# Documento de Requisitos de Software

## Portfólio de Projetos em IA Generativa

**Versão:** 1.0
**Data:** 27/06/2026
**Tipo de documento:** Documento de Requisitos de Software
**Aplicação analisada:** Página web single page de portfólio acadêmico/profissional

---

# 1. Identificação do Projeto

| Item                     | Descrição                                                                                                                                                                                        |
| ------------------------ | ------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------ |
| Nome do sistema          | Portfólio de Projetos em IA Generativa                                                                                                                                                           |
| Tipo de aplicação        | Página web single page portfolio                                                                                                                                                                 |
| Objetivo principal       | Apresentar projetos desenvolvidos durante um curso de programação com IA generativa e ChatGPT, evidenciando competências técnicas, tecnologias utilizadas e evolução de aprendizagem.            |
| Público-alvo             | Professores, avaliadores acadêmicos, recrutadores, colegas de curso, profissionais de tecnologia e visitantes interessados nos projetos apresentados.                                            |
| Contexto de uso          | Divulgação acadêmica e profissional de projetos práticos desenvolvidos com apoio de inteligência artificial generativa.                                                                          |
| Responsável pelo projeto | **Premissa:** Ronaldo L. Diniz, inferido a partir da URL pública e do contexto do projeto.                                                                                                       |
| Finalidade               | Demonstrar conhecimento prático em desenvolvimento web, automação, integração de APIs, uso de frameworks, Java, JavaScript e aplicação de IA generativa no ciclo de desenvolvimento de software. |

---

# 2. Visão Geral do Sistema

A aplicação analisada é uma página web do tipo **single page portfolio**, com layout moderno, navegação por seções e foco na apresentação de projetos desenvolvidos com apoio de IA generativa e ChatGPT.

A página tem como finalidade central demonstrar a evolução prática do autor no uso de tecnologias de desenvolvimento, automação inteligente, refatoração de código, integração de APIs e construção de interfaces web.

## 2.1 Principais seções identificadas

A página apresenta as seguintes seções principais:

* Seção inicial de apresentação, também chamada de Hero;
* Seção sobre a jornada em engenharia de prompt;
* Seção de projetos em destaque;
* Seção de evolução de competências;
* Seção de tecnologias e ferramentas;
* Seção de destaque para Chatbot com IA Generativa;
* Seção de contato e chamada para ação;
* Rodapé com identificação acadêmica e créditos.

## 2.2 Principais funcionalidades observadas

* Exibição de apresentação inicial do portfólio;
* Navegação por âncoras entre seções da página;
* Apresentação de projetos em cards;
* Exibição de imagens relacionadas aos projetos;
* Destaque visual para o projeto de Chatbot com IA;
* Exibição de tecnologias utilizadas;
* Botões de chamada para ação, como visualizar projetos, contato, repositórios e projeto do chatbot;
* Organização visual dos projetos por categoria e tecnologia.

## 2.3 Tecnologias web identificadas ou inferidas

* HTML5;
* CSS3;
* JavaScript ES6+;
* Tailwind CSS;
* Bootstrap;
* GitHub Pages;
* Recursos visuais baseados em cards, ícones e imagens;
* **Premissa:** estrutura estática, sem backend próprio, por estar publicada como página web estática.

## 2.4 Características visuais e estruturais

A página possui identidade visual moderna, com aparência tecnológica, uso de cards, botões, tags de tecnologias, imagens ilustrativas e textos curtos para apresentação dos projetos. A estrutura favorece a leitura rápida e a navegação direta pelas seções.

---

# 3. Escopo do Sistema

O escopo do sistema compreende a criação e publicação de uma página web estática para apresentação de portfólio de projetos relacionados ao curso de programação com IA generativa e ChatGPT.

## 3.1 O que o sistema contempla

O sistema contempla:

* Página inicial de apresentação do portfólio;
* Menu de navegação por seções;
* Seção sobre o uso de IA generativa e engenharia de prompt;
* Apresentação dos projetos desenvolvidos;
* Card do projeto Jogo da Cobrinha;
* Card do projeto Refatoração de Sites;
* Card do projeto Aplicações em Java;
* Card do projeto Chatbot com IA;
* Card do projeto Integração de API;
* Card do projeto Utilização de Frameworks;
* Seção de competências desenvolvidas;
* Seção de tecnologias e ferramentas utilizadas;
* Destaque especial para o projeto de Chatbot;
* Imagens ou avatares relacionados aos projetos;
* Botões de navegação e chamadas para ação;
* Rodapé com créditos e informações finais;
* Publicação em ambiente web acessível ao público.

## 3.2 O que está fora do escopo

Os seguintes recursos não fazem parte do escopo da aplicação:

* Sistema de login;
* Cadastro de usuários;
* Banco de dados;
* Área administrativa;
* Painel de gerenciamento de conteúdo;
* Processamento de pagamentos;
* Carrinho de compras;
* Chatbot funcional em tempo real dentro da página;
* Integração dinâmica com APIs externas;
* Sistema de comentários;
* Upload de arquivos;
* Controle de permissões;
* Relatórios administrativos;
* Funcionalidades complexas incompatíveis com uma página estática de portfólio.

## 3.3 Limitações identificadas

* A página apresenta os projetos de forma resumida, sem detalhamento técnico completo de cada implementação;
* **Premissa:** os botões de repositório ou demonstração podem depender de links externos corretamente configurados;
* Não há evidência de área administrativa para atualização dinâmica do conteúdo;
* Não há evidência de armazenamento de dados em banco;
* Não há evidência de formulário funcional com envio de mensagens;
* O conteúdo depende de manutenção manual no código-fonte;
* A acessibilidade pode ser melhorada com revisão de textos alternativos, contraste, semântica HTML e navegação por teclado;
* A documentação técnica complementar, como README e descrição individual dos projetos, pode ser ampliada.

---

# 4. Requisitos Funcionais

| Código | Nome do Requisito                                | Descrição                                                                                                                                  | Prioridade | Critério de Aceitação                                                                                                                                      |
| ------ | ------------------------------------------------ | ------------------------------------------------------------------------------------------------------------------------------------------ | ---------- | ---------------------------------------------------------------------------------------------------------------------------------------------------------- |
| RF001  | Exibir apresentação do portfólio                 | O sistema deve apresentar uma seção inicial com o título do portfólio, descrição geral e chamada para navegação.                           | Alta       | A seção inicial deve ser exibida corretamente ao carregar a página.                                                                                        |
| RF002  | Exibir menu de navegação                         | O sistema deve disponibilizar links de navegação para as principais seções da página.                                                      | Alta       | O visitante deve conseguir acessar as seções por meio do menu.                                                                                             |
| RF003  | Navegar por seções                               | O sistema deve permitir navegação interna para Hero, About, Projects, Learning, Technologies e Contact.                                    | Alta       | Ao clicar nos itens do menu, a página deve direcionar o visitante para a seção correspondente.                                                             |
| RF004  | Apresentar objetivo do portfólio                 | O sistema deve informar que o portfólio demonstra projetos desenvolvidos com IA generativa e ChatGPT.                                      | Alta       | O visitante deve compreender a finalidade do portfólio na seção inicial ou na seção sobre.                                                                 |
| RF005  | Apresentar projeto Jogo da Cobrinha              | O sistema deve exibir o projeto Jogo da Cobrinha com título, descrição e tecnologias relacionadas.                                         | Alta       | O card do projeto deve estar visível e legível na seção de projetos.                                                                                       |
| RF006  | Apresentar projeto Refatoração de Sites          | O sistema deve exibir o projeto de refatoração de sites, destacando modernização, otimização e organização de código.                      | Alta       | O card do projeto deve apresentar título, descrição e categoria correspondente.                                                                            |
| RF007  | Apresentar aplicações em Java                    | O sistema deve exibir o projeto relacionado a aplicações em Java.                                                                          | Alta       | O visitante deve conseguir identificar o projeto Java e sua descrição.                                                                                     |
| RF008  | Apresentar Chatbot com IA                        | O sistema deve exibir o projeto de Chatbot com IA Generativa.                                                                              | Alta       | O projeto deve aparecer na lista de projetos e também em seção de destaque.                                                                                |
| RF009  | Exibir avatar ou imagem do Chatbot               | O sistema deve apresentar imagem ou avatar relacionado ao projeto de Chatbot.                                                              | Média      | A imagem deve carregar corretamente e estar relacionada ao conteúdo do projeto.                                                                            |
| RF010  | Apresentar Integração de API                     | O sistema deve exibir projeto relacionado ao consumo e integração de APIs.                                                                 | Alta       | O visitante deve conseguir identificar o projeto de integração de API na seção de projetos.                                                                |
| RF011  | Apresentar uso de Frameworks                     | O sistema deve exibir projeto ou competência relacionada ao uso de frameworks.                                                             | Alta       | A seção de projetos deve apresentar o uso de frameworks de forma clara.                                                                                    |
| RF012  | Exibir competências desenvolvidas                | O sistema deve apresentar competências como engenharia de prompt, desenvolvimento responsivo e IA como copiloto.                           | Média      | A seção de competências deve estar visível e organizada.                                                                                                   |
| RF013  | Exibir tecnologias utilizadas                    | O sistema deve listar as principais tecnologias e ferramentas usadas nos projetos.                                                         | Alta       | A seção de tecnologias deve apresentar itens como HTML5, CSS3, JavaScript, Java, APIs REST, JSON, Streamlit, Tailwind, Bootstrap, ChatGPT e IA Generativa. |
| RF014  | Disponibilizar chamadas para ação                | O sistema deve apresentar botões ou links para visualizar projetos, entrar em contato, acessar repositórios ou acessar projeto específico. | Média      | Os botões devem estar visíveis e, quando aplicável, direcionar corretamente o visitante.                                                                   |
| RF015  | Exibir rodapé institucional                      | O sistema deve apresentar rodapé com informações finais, créditos ou links complementares.                                                 | Baixa      | O rodapé deve ser exibido no final da página.                                                                                                              |
| RF016  | Permitir visualização em dispositivos diferentes | O sistema deve permitir visualização adequada em desktop, tablet e smartphone.                                                             | Alta       | O layout deve se adaptar corretamente aos principais tamanhos de tela.                                                                                     |

---

# 5. Requisitos Não Funcionais

| Código | Categoria                       | Descrição                                                                                                                        | Prioridade | Critério de Aceitação                                                                                             |
| ------ | ------------------------------- | -------------------------------------------------------------------------------------------------------------------------------- | ---------- | ----------------------------------------------------------------------------------------------------------------- |
| RNF001 | Responsividade                  | A página deve adaptar seu layout para diferentes tamanhos de tela.                                                               | Alta       | A aplicação deve ser visualizada corretamente em desktop, tablet e smartphone.                                    |
| RNF002 | Usabilidade                     | A navegação deve ser simples, intuitiva e objetiva.                                                                              | Alta       | O visitante deve localizar rapidamente os projetos e informações principais.                                      |
| RNF003 | Acessibilidade                  | A página deve seguir boas práticas de acessibilidade, incluindo textos alternativos, contraste adequado e navegação por teclado. | Média      | Imagens relevantes devem possuir texto alternativo e os elementos interativos devem ser acessíveis.               |
| RNF004 | Desempenho                      | A página deve carregar em tempo adequado, mesmo com imagens e recursos visuais.                                                  | Alta       | O carregamento inicial deve ocorrer sem atrasos significativos em conexão comum.                                  |
| RNF005 | Compatibilidade com navegadores | A aplicação deve funcionar nos principais navegadores modernos.                                                                  | Alta       | A página deve ser compatível com Chrome, Edge, Firefox e Safari em versões recentes.                              |
| RNF006 | Manutenibilidade                | O código deve ser organizado para permitir manutenção e evolução do portfólio.                                                   | Média      | Arquivos HTML, CSS e JavaScript devem possuir estrutura clara e nomenclatura compreensível.                       |
| RNF007 | Segurança básica                | A página deve evitar exposição de dados sensíveis e utilizar links seguros.                                                      | Média      | Não deve haver chaves de API, credenciais ou informações privadas no código público.                              |
| RNF008 | Organização visual              | O layout deve apresentar hierarquia visual clara, com seções bem definidas.                                                      | Alta       | Títulos, cards, botões e textos devem seguir uma organização visual consistente.                                  |
| RNF009 | Padronização de layout          | A interface deve manter padrão de cores, tipografia, espaçamento e componentes.                                                  | Média      | Os elementos visuais devem seguir a mesma identidade visual ao longo da página.                                   |
| RNF010 | Boas práticas de HTML           | A estrutura HTML deve utilizar elementos semânticos sempre que possível.                                                         | Média      | O código deve conter tags adequadas como header, main, section, nav e footer.                                     |
| RNF011 | Boas práticas de CSS            | Os estilos devem ser organizados, reutilizáveis e compatíveis com responsividade.                                                | Média      | O CSS deve evitar repetições desnecessárias e facilitar manutenção.                                               |
| RNF012 | Boas práticas de JavaScript     | Scripts devem ser utilizados apenas quando necessários e sem prejudicar o carregamento da página.                                | Média      | A página deve funcionar sem erros de JavaScript no console.                                                       |
| RNF013 | SEO básico                      | A página deve possuir título, descrição, hierarquia de headings e conteúdo indexável.                                            | Média      | O código deve conter título adequado, meta description e estrutura textual compreensível por mecanismos de busca. |
| RNF014 | Disponibilidade                 | A página deve permanecer acessível pela URL pública de publicação.                                                               | Alta       | O visitante deve conseguir abrir a página sem erro 404 ou falha de carregamento.                                  |
| RNF015 | Legibilidade                    | Os textos devem ser claros, objetivos e revisados.                                                                               | Alta       | Não devem existir erros graves de ortografia, textos confusos ou informações duplicadas.                          |

---

# 6. Regras de Negócio

| Código | Regra de Negócio                            | Descrição                                                                                                                            |
| ------ | ------------------------------------------- | ------------------------------------------------------------------------------------------------------------------------------------ |
| RN001  | Organização dos projetos                    | Os projetos devem ser apresentados de maneira clara, preferencialmente em cards com título, descrição e tecnologias associadas.      |
| RN002  | Evidência de aprendizagem                   | A página deve demonstrar que os projetos fazem parte de uma jornada de aprendizagem em programação com IA generativa e ChatGPT.      |
| RN003  | Clareza do objetivo                         | O visitante deve compreender rapidamente que a página é um portfólio de projetos.                                                    |
| RN004  | Relação entre imagem e conteúdo             | As imagens e avatares devem estar relacionados ao projeto ou competência apresentada.                                                |
| RN005  | Destaque para IA generativa                 | O conteúdo deve reforçar o uso de IA generativa como apoio ao desenvolvimento, automação, refatoração e criação de soluções.         |
| RN006  | Identificação das tecnologias               | Cada projeto deve apresentar, quando aplicável, tecnologias, linguagens ou ferramentas utilizadas.                                   |
| RN007  | Navegação simplificada                      | Por se tratar de uma single page, a navegação deve priorizar âncoras internas e fluxo linear de leitura.                             |
| RN008  | Ausência de funcionalidades administrativas | A aplicação não deve apresentar funcionalidades de login, cadastro ou administração, pois seu objetivo é apenas expositivo.          |
| RN009  | Chamada para ação                           | A página deve permitir que o visitante acesse projetos, repositórios ou formas de contato, quando esses links estiverem disponíveis. |
| RN010  | Coerência acadêmica e profissional          | O conteúdo deve manter linguagem adequada para apresentação em contexto acadêmico e uso como portfólio profissional.                 |

---

# 7. Casos de Uso

## UC001 — Visualizar Portfólio

**Ator principal:** Visitante da Página

**Objetivo:** Acessar a página e visualizar a apresentação geral do portfólio.

**Pré-condição:** O visitante deve possuir acesso à internet e abrir a página pública do projeto.

**Fluxo principal:**

1. O visitante acessa a página do portfólio.
2. O sistema carrega a seção inicial.
3. O visitante visualiza o título, a descrição e os botões principais.
4. O visitante identifica o objetivo geral do portfólio.

**Resultado esperado:**
O visitante compreende que a página apresenta projetos desenvolvidos com IA generativa e ChatGPT.

---

## UC002 — Navegar pelas Seções

**Ator principal:** Visitante da Página

**Objetivo:** Acessar rapidamente as principais seções da página.

**Pré-condição:** A página deve estar carregada no navegador.

**Fluxo principal:**

1. O visitante visualiza o menu de navegação.
2. O visitante seleciona uma seção, como Projects, Learning, Technologies ou Contact.
3. O sistema direciona a visualização para a seção escolhida.
4. O visitante consulta o conteúdo da seção.

**Resultado esperado:**
O visitante consegue navegar pelas seções sem dificuldade.

---

## UC003 — Consultar Projetos em Destaque

**Ator principal:** Visitante da Página

**Objetivo:** Visualizar os projetos desenvolvidos no curso.

**Pré-condição:** A seção de projetos deve estar disponível.

**Fluxo principal:**

1. O visitante acessa a seção de projetos.
2. O sistema exibe os cards dos projetos.
3. O visitante lê os títulos, descrições e tecnologias associadas.
4. O visitante identifica os tipos de projetos desenvolvidos.

**Resultado esperado:**
O visitante compreende quais projetos fazem parte do portfólio.

---

## UC004 — Visualizar Projeto Chatbot com IA

**Ator principal:** Visitante da Página

**Objetivo:** Consultar o projeto de Chatbot com IA Generativa.

**Pré-condição:** O projeto de Chatbot deve estar cadastrado visualmente na página.

**Fluxo principal:**

1. O visitante acessa a seção de projetos ou a seção de destaque do Chatbot.
2. O sistema exibe o projeto Chatbot com IA.
3. O visitante visualiza descrição, imagem/avatar e características do projeto.
4. O visitante identifica que o projeto envolve processamento de linguagem natural e IA generativa.

**Resultado esperado:**
O visitante entende o propósito e o destaque do projeto Chatbot.

---

## UC005 — Consultar Tecnologias Utilizadas

**Ator principal:** Visitante da Página

**Objetivo:** Verificar quais tecnologias foram utilizadas no desenvolvimento dos projetos.

**Pré-condição:** A seção de tecnologias deve estar disponível.

**Fluxo principal:**

1. O visitante acessa a seção de tecnologias.
2. O sistema lista linguagens, frameworks e ferramentas.
3. O visitante analisa a stack apresentada.
4. O visitante associa as tecnologias aos projetos exibidos.

**Resultado esperado:**
O visitante identifica as principais competências técnicas demonstradas no portfólio.

---

## UC006 — Consultar Competências Desenvolvidas

**Ator principal:** Visitante da Página

**Objetivo:** Compreender as competências adquiridas durante a jornada de aprendizagem.

**Pré-condição:** A seção de evolução de competências deve estar disponível.

**Fluxo principal:**

1. O visitante acessa a seção de competências.
2. O sistema exibe tópicos como Prompt Engineering, Responsive Web e IA como Copilot.
3. O visitante lê as descrições das competências.
4. O visitante compreende a evolução técnica apresentada.

**Resultado esperado:**
O visitante reconhece as habilidades desenvolvidas no curso.

---

## UC007 — Acessar Contato ou Repositórios

**Ator principal:** Visitante da Página

**Objetivo:** Utilizar botões de contato ou acesso a repositórios.

**Pré-condição:** Os botões ou links devem estar configurados corretamente.

**Fluxo principal:**

1. O visitante acessa a seção final ou os botões de chamada para ação.
2. O visitante clica em contato, repositórios ou projeto específico.
3. O sistema redireciona para o destino configurado.
4. O visitante acessa informações complementares.

**Resultado esperado:**
O visitante consegue entrar em contato ou acessar materiais externos relacionados ao portfólio.

---

# 8. Critérios de Aceitação Gerais

Para que a aplicação seja considerada concluída e adequada para publicação, os seguintes critérios devem ser atendidos:

* A página deve carregar corretamente pela URL pública;
* O conteúdo deve estar organizado e legível;
* O objetivo do portfólio deve estar claro na seção inicial;
* Os projetos devem ser apresentados de forma clara;
* A seção de projetos deve conter os projetos principais do curso;
* A navegação interna deve funcionar corretamente;
* O layout deve ser responsivo;
* As imagens devem carregar corretamente;
* Os textos devem estar revisados;
* A página deve funcionar nos principais navegadores modernos;
* O design deve transmitir aparência profissional;
* Os botões e links devem funcionar corretamente, quando configurados;
* O código deve estar organizado e ser de fácil manutenção;
* A página não deve expor dados sensíveis, credenciais ou chaves de acesso;
* O conteúdo deve manter coerência com a proposta de portfólio acadêmico e profissional;
* A aplicação deve permanecer compatível com publicação em ambiente estático, como GitHub Pages.

---

# 9. Sugestões de Melhorias

## 9.1 Melhorias de experiência do usuário

* Inserir descrições mais detalhadas para cada projeto;
* Adicionar botões individuais de “Ver demonstração” e “Ver repositório” em cada card;
* Incluir uma seção de linha do tempo da aprendizagem;
* Melhorar a hierarquia visual dos projetos mais relevantes;
* Criar uma seção com breve resumo do curso realizado.

## 9.2 Melhorias de conteúdo

* Informar o objetivo técnico de cada projeto;
* Descrever quais problemas cada projeto resolve;
* Indicar quais tecnologias foram usadas em cada projeto;
* Inserir aprendizados obtidos em cada desenvolvimento;
* Padronizar os textos dos cards para manter consistência.

## 9.3 Melhorias visuais

* Padronizar tamanhos de imagens dos cards;
* Garantir alinhamento uniforme entre títulos, descrições e tags;
* Revisar contraste entre fundo, textos e botões;
* Otimizar espaçamentos para dispositivos móveis;
* Evitar excesso de elementos visuais que possam competir com o conteúdo principal.

## 9.4 Melhorias de acessibilidade

* Adicionar textos alternativos descritivos em todas as imagens;
* Garantir navegação completa por teclado;
* Aplicar contraste adequado entre texto e fundo;
* Usar corretamente a hierarquia de títulos;
* Evitar que informações importantes dependam apenas de cores ou ícones.

## 9.5 Melhorias técnicas

* Separar adequadamente arquivos HTML, CSS e JavaScript;
* Utilizar HTML semântico com header, main, section, article, nav e footer;
* Revisar o JavaScript para evitar código não utilizado;
* Otimizar imagens para reduzir tempo de carregamento;
* Utilizar nomes de classes e arquivos claros;
* Remover trechos de código, comentários ou componentes não utilizados;
* Criar um README técnico para o projeto.

## 9.6 Melhorias de SEO básico

* Inserir meta description com resumo do portfólio;
* Definir título de página claro e objetivo;
* Usar apenas um H1 principal;
* Utilizar headings em ordem hierárquica;
* Inserir textos indexáveis sobre projetos, tecnologias e finalidade da página;
* Adicionar atributos alt relevantes nas imagens.

## 9.7 Melhorias de documentação

* Criar README.md contendo:

  * Nome do projeto;
  * Objetivo;
  * Tecnologias utilizadas;
  * Como executar localmente;
  * Estrutura de pastas;
  * Links dos projetos;
  * Créditos acadêmicos;
  * Prints da aplicação.
* Documentar requisitos funcionais e não funcionais;
* Criar histórico de versões;
* Registrar melhorias futuras em uma seção de roadmap.

---

# 10. Conclusão

A documentação de requisitos é uma etapa essencial para organizar, compreender e evoluir uma aplicação de software. Mesmo em projetos aparentemente simples, como uma página single page de portfólio, o documento de requisitos permite registrar o objetivo do sistema, seu escopo, suas funcionalidades, suas limitações e os critérios mínimos de qualidade esperados.

No caso do Portfólio de Projetos em IA Generativa, a documentação contribui para transformar uma página de apresentação em um projeto tecnicamente estruturado, facilitando futuras manutenções, melhorias visuais, inclusão de novos projetos e evolução da experiência do usuário.

Os requisitos funcionais ajudam a definir o que a página deve apresentar ao visitante, enquanto os requisitos não funcionais estabelecem padrões de qualidade relacionados a responsividade, acessibilidade, desempenho, manutenibilidade, segurança básica e organização visual.

Além disso, o portfólio possui relevância acadêmica e profissional por evidenciar a aplicação prática de conhecimentos em desenvolvimento web, programação, integração de APIs, frameworks e uso de IA generativa com ChatGPT. Dessa forma, a aplicação funciona não apenas como vitrine de projetos, mas também como registro da evolução técnica e da capacidade de aplicar inteligência artificial no ciclo de desenvolvimento de software.
