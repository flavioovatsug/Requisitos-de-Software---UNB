# Histórias de Usuários

## Introdução
Este documento refere-se as Histórias de Usuários, documentação exigida sobre Modelagem no projeto de requisitos de software pelo grupo 5 para explicar de forma clara e concisa as funcionalidades e os requisitos necessários do envolvidos no aplicativo Sinesp Cidadão 

## Metodologia
Este documento foi produzido com base nos requisitos elicitados com persona presentes no [Three Level Scale](https://github.com/Requisitos-de-Software/2024.1-Sinesp_Cidadao/blob/main/docs/elicitacao/priorizacao/three_scales.md) para o levantamento das histórias de usuário que sequem a seguinte estrutura da tabela 1 e figura 1 [1].

<font size="2"><p style="text-align: center">Figura 1: Estrutura da descrição </p></font>

<center>

![Figura 1](../assets/lexicos/)
</center>

<font size="2"><p style="text-align: center">Fonte: SERRANO M.; SERRANO M. Requisitos - Aula 15.</p></font>

<p style="text-align: center">Tabela 1 - Estrutura das Histórias de Usuários</p>

<center>
  
| identificador do léxico   | caraterísticas |
| -------- | ----------- |
| Título     | Nome da História de Usuário auto-explicativo  |
| Descrição     |  Descreve "quem", "o que" e o "por que" da funcionalidade   |
| Critérios de aceitação    |   Condições que devem ser atendidas para que a história seja considerada completa e aceita    |

<center>
  
<p style="text-align: center">Autor: <a href="https://github.com/crstyhs">Christian</a></p>


## Histórias de Usuários identificados
Abaixo nas tabelas de 1 a 16 podem ser visto as Histórias de Usuários .
<p style="text-align: center">Tabela 2 - História de Usuário Autenticação de Usuário</p>

<center>
  
| HU01   | características |
| -------- | ----------- |
| Título     | Autenticação de Usuário  |
| Descrição     |  Como um usuário do aplicativo Sinesp Cidadão, eu quero poder fazer login utilizando o Governo Federal (Gov) como método de autenticação, para acessar de forma segura as funcionalidades exclusivas do aplicativo.   |
| Critérios de aceitação    |  - O usuário deve ter a opção de selecionar o método de autenticação pelo Gov ao iniciar o processo de login. <br> - Após selecionar o Gov como método de autenticação, o usuário deve ser redirecionado para a página de login do Gov. <br> - Após autenticar com sucesso no Gov, o usuário deve ser redirecionado de volta para o aplicativo Sinesp Cidadão.<br> - O usuário deve ser autenticado com sucesso no aplicativo Sinesp Cidadão após retornar do Gov, permitindo o acesso às funcionalidades do aplicativo.    |

<center>
  
<p style="text-align: center">Autor: <a href="https://github.com/crstyhs">Christian Hirsch Santos</a></p>

<p style="text-align: center">Tabela 3 - História de Usuário Busca por Veículo</p>

<center>
  
| HU02   | características |
| -------- | ----------- |
| Título     | Busca por Veículo  |
| Descrição     |  Como um usuário do aplicativo Sinesp Cidadão, eu quero poder buscar informações sobre um veículo utilizando a placa, para obter detalhes sobre o mesmo.   |
| Critérios de aceitação    |   - O usuário deve ter a opção de inserir a placa do veículo na barra de busca. <br> - Após inserir a placa e confirmar a busca, o sistema deve exibir as informações disponíveis sobre o veículo. <br> - As informações exibidas devem incluir a situação atual do veículo, indicando se está registrado como roubado ou furtado.    |

<center>
  
<p style="text-align: center">Autor: <a href="https://github.com/crstyhs">Christian Hirsch Santos</a></p>

<p style="text-align: center">Tabela 4 - História de Usuário Adicionar carro como roubado</p>

<center>
  
| HU03   | características |
| -------- | ----------- |
| Título     | Adicionar carro como roubado  |
| Descrição     |  Como um usuário do aplicativo Sinesp Cidadão, eu quero ter a opção de informar dados sobre um veículo roubado , para contribuir com o banco de dados e auxiliar na identificação de veículos roubados ou furtados.   |
| Critérios de aceitação    |   - O usuário deve ter a opção de preencher um formulário com os dados do veículo, como modelo, cor e marca. <br> - Após preencher os dados do veículo, o usuário deve ter a opção de enviar as informações para o sistema. <br> - O sistema deve receber e armazenar as informações do veículo de forma segura e precisa no banco de dados. <br> - Após enviar as informações, o usuário deve receber uma confirmação de que os dados foram registrados com sucesso.    |

<center>
  
<p style="text-align: center">Autor: <a href="https://github.com/crstyhs">Christian Hirsch Santos</a></p>

<p style="text-align: center">Tabela 5 - História de Usuário Listar Pessoas Desaparecidas</p>

<center>
  
| HU04   | características |
| -------- | ----------- |
| Título     | 	Listar Pessoas Desaparecidas  |
| Descrição     |  Como um usuário do aplicativo Sinesp Cidadão, eu quero ter a opção de visualizar uma lista de pessoas desaparecidas, para auxiliar na busca e localização de indivíduos desaparecidos.   |
| Critérios de aceitação    |  - O usuário deve ter a opção de acessar a seção de pessoas desaparecidas no menu principal do aplicativo. - A lista de pessoas desaparecidas deve ser exibida de forma a mostrar a foto e o nome da pessoa desaparecida. <br> - Cada entrada na lista deve possibilitar seu selecionamento para obter mais informações. |

<center>
  
<p style="text-align: center">Autor: <a href="https://github.com/crstyhs">Christian Hirsch Santos</a></p>

<p style="text-align: center">Tabela 6 - História de Usuário Fornecer Informações Gerais sobre Desaparecidos</p>

<center>
  
| HU05   | características |
| -------- | ----------- |
| Título     | Fornecer Informações Gerais sobre Desaparecidos  |
| Descrição     |  Como um usuário do aplicativo Sinesp Cidadão, eu quero ter acesso a informações gerais sobre desaparecidos, como idade, tamanho, foto para a identificação do desaparecido   |
| Critérios de aceitação    |   - O usuário deve ter a opção de acessar a seção de informações gerais sobre desaparecidos ao selecionar a pessoa especifica na aba de desaparecidos. <br> - As informações gerais devem ser atualizadas diariamente.    |

<center>
  
<p style="text-align: center">Autor: <a href="https://github.com/crstyhs">Christian Hirsch Santos</a></p>

<p style="text-align: center">Tabela 7 - História de Usuário Vincular ao Desaparecido </p>

<center>
  
| HU06   | características |
| -------- | ----------- |
| Título     | Vincular ao Desaparecido  |
| Descrição     |  Como um usuário do aplicativo Sinesp Cidadão, eu quero ter a opção de vincular ao perfil uma pessoa desaparecida, para ajudar na centralização e organização das informações relacionadas ao cada caso e receber notificações de atualizações sobre ele.   |
| Critérios de aceitação    |   - O usuário deve ter a opção de acessar o perfil de uma pessoa desaparecida. <br> - Após acessar o perfil, o usuário deve ter a opção de vincular a pessoa desaparecida ao seu perfil. <br> - O sistema deve registrar e notificar as informações vinculadas ao perfil da pessoa desaparecida . <br> - O usuário deve poder visualizar todas as ocorrências e informações vinculadas ao seu perfil na aba de vínculos.    |

<center>
  
<p style="text-align: center">Autor: <a href="https://github.com/crstyhs">Christian Hirsch Santos</a></p>

<p style="text-align: center">Tabela 8 - História de Usuário Vincular ao Carro</p>

<center>
  
| HU07   | características |
| -------- | ----------- |
| Título     | Vincular ao Carro  |
| Descrição     |  	Como um usuário do aplicativo Sinesp Cidadão, eu quero ter a opção de vincular ao perfil um veículo , para ajudar na identificação e localização do veículo e receber notificações de atualizações sobre ele.   |
| Critérios de aceitação    |   - O usuário deve ter a opção de buscar o veículo . <br> - Após buscar pelo veículo, o usuário deve ter a opção de vincular o veículo ao seu perfil. <br> - O sistema deve registrar e notificar sobre atualizações das informações do veículo vinculo   . <br> - O usuário deve poder visualizar todas as ocorrências e informações vinculadas ao seu perfil na aba de vínculos.    |

<center>
  
<p style="text-align: center">Autor: <a href="https://github.com/crstyhs">Christian Hirsch Santos</a></p>

<p style="text-align: center">Tabela 9 - História de Usuário Buscar por Mandados</p>

<center>
  
| HU08   | características |
| -------- | ----------- |
| Título     | Buscar por Mandados  |
| Descrição     |  Como um usuário do aplicativo Sinesp Cidadão, eu quero ter a opção de buscar informações sobre mandados de prisão, para auxiliar na identificação e captura de indivíduos julgados pela justiça.   |
| Critérios de aceitação    |   - O usuário deve ter a opção de acessar a seção de busca por mandados no menu principal do aplicativo. <br> - O usuário deve poder pesquisar por mandados utilizando critérios como nome do procurado, número do mandado ou tipo de crime. <br> - O usuário deve poder visualizar detalhes adicionais sobre cada mandado ao selecionar um resultado da busca.   |

<center>
  
<p style="text-align: center">Autor: <a href="https://github.com/crstyhs">Christian Hirsch Santos</a></p>

<p style="text-align: center">Tabela 10 - História de Usuário Fornecer Informações sobre Mandados</p>

<center>
  
| HU09   | características |
| -------- | ----------- |
| Título     | Fornecer Informações sobre Mandados  |
| Descrição     |  	Como um usuário do aplicativo Sinesp Cidadão, eu quero ter acesso a informações detalhadas sobre mandados de prisão, para entender os motivos pelos quais os indivíduos estão sendo julgado pela justiça.   |
| Critérios de aceitação    |   - O usuário deve ter a opção de acessar a seção de informações sobre mandados no menu principal do aplicativo. <br> - O usuário deve poder acessar informações adicionais sobre cada mandado ao selecionar um item na lista. <br> - As informações sobre mandados devem ser apresentadas explicando os detalhes dos crimes pelos quais os indivíduos estão sendo procurados(Sentença, Expedição,Peça).   |

<center>
  
<p style="text-align: center">Autor: <a href="https://github.com/crstyhs">Christian Hirsch Santos</a></p>

<p style="text-align: center">Tabela 11 - História de Usuário Buscar por Procurados</p>

<center>
  
| HU10   | características |
| -------- | ----------- |
| Título     | 	Buscar por Procurados  |
| Descrição     |  Como um usuário do aplicativo Sinesp Cidadão, eu quero ter a opção de buscar informações sobre indivíduos procurados pela justiça, para contribuir com a identificação e captura dessas pessoas.   |
| Critérios de aceitação    |   - O usuário deve ter a opção de acessar a seção de busca por procurados no menu principal do aplicativo. <br> - O usuário deve poder visualizar detalhes adicionais sobre cada procurado ao selecionar uma foto em especifico   |

<center>
  
<p style="text-align: center">Autor: <a href="https://github.com/crstyhs">Christian Hirsch Santos</a></p>

<p style="text-align: center">Tabela 12 - História de Usuário Fornecer Informações sobre Procurados</p>

<center>
  
| HU11   | características |
| -------- | ----------- |
| Título     | Fornecer Informações sobre Procurados  |
| Descrição     |  Como um usuário do aplicativo Sinesp Cidadão, eu quero ter acesso a informações detalhadas sobre indivíduos procurados pela justiça, para entender os motivos pelos quais eles estão sendo procurados e contribuir com o processo de captura.   |
| Critérios de aceitação    |   - O usuário deve poder acessar informações adicionais sobre cada mandado ao selecionar um item na lista. <br> - As informações sobre mandados devem ser apresentadas explicando os detalhes dos crimes pelos quais os indivíduos estão sendo procurados(Sentença, Expedição,Peça).    |

<center>
  
<p style="text-align: center">Autor: <a href="https://github.com/crstyhs">Christian Hirsch Santos</a></p>

<p style="text-align: center">Tabela 13 - História de Usuário Sair do Aplicativo</p>

<center>
  
| HU12   | características |
| -------- | ----------- |
| Título     | Sair do Aplicativo  |
| Descrição     |  	Como um usuário do aplicativo Sinesp Cidadão, eu quero ter a opção de sair do aplicativo , para encerrar a sessão e proteger meus dados pessoais.   |
| Critérios de aceitação    |   - Ao selecionar a opção de sair, o sistema deve encerrar a sessão do usuário e retornar à tela de login. <br> - O usuário deve ser informado de que a sessão foi encerrada com sucesso e de que ele está desconectado do aplicativo. <br> - Após sair do aplicativo, o usuário não deve ter acesso às funcionalidades ou informações pessoais sem efetuar login novamente.     |

<center>
  
<p style="text-align: center">Autor: <a href="https://github.com/crstyhs">Christian Hirsch Santos</a></p>

<p style="text-align: center">Tabela 14 - História de Usuário Anunciar Perturbação da Vizinhança</p>

<center>
  
| HU13   | características |
| -------- | ----------- |
| Título     | 	Anunciar Perturbação da Vizinhança  |
| Descrição     |  Como um usuário do aplicativo Sinesp Cidadão, eu quero ter a opção de relatar ocorrências de perturbação da vizinhança, como barulhos excessivos ou atividades suspeitas, para alertar as autoridades e promover a segurança local.   |
| Critérios de aceitação    |   - O usuário deve ter a opção de relatar uma ocorrência de perturbação da vizinhança através do aplicativo. <br> - O usuário deve poder descrever a ocorrência de forma detalhada, incluindo informações como local, horário e tipo de perturbação. <br> - Após enviar o relato, o sistema deve registrar a ocorrência e encaminhá-la para as autoridades . <br> - O usuário deve receber uma confirmação de que o relato foi enviado com sucesso e está sendo processado pelas autoridades.    |

<center>
  
<p style="text-align: center">Autor: <a href="https://github.com/crstyhs">Christian</a></p>

<p style="text-align: center">Tabela 15 - História de Usuário Rápida Disponibilização de Informações</p>

<center>
  
| HU14   | características |
| -------- | ----------- |
| Título     | Rápida Disponibilização de Informações  |
| Descrição     |  	Como um usuário do aplicativo Sinesp Cidadão, eu quero ter acesso rápido a informações , para me manter informado em situações de urgência sobre desaparecidos , mandados e procurados.   |
| Critérios de aceitação    |   - O tempo de resposta nao deve exceder 300 ms     |

<center>
  
<p style="text-align: center">Autor: <a href="https://github.com/crstyhs">Christian</a></p>

<p style="text-align: center">Tabela 16 - História de Usuário Sigilo Relativo de Informações</p>

<center>
  
| HU15   | características |
| -------- | ----------- |
| Título     | Sigilo Relativo de Informações  |
| Descrição     |  	Como um usuário do aplicativo Sinesp Cidadão, eu quero que minhas informações pessoais sejam protegidas e mantidas em sigilo, para garantir minha privacidade e segurança ao utilizar o aplicativo.   |
| Critérios de aceitação    |   - As informações pessoais dos usuários não devem ser compartilhadas com terceiros sem consentimento prévio   |

<center>
  
<p style="text-align: center">Autor: <a href="https://github.com/crstyhs">Christian</a></p>

<p style="text-align: center">Tabela 17 - História de Usuário Disponibilizar Diversas Opções de Denúncia</p>

<center>
  
| HU16   | características |
| -------- | ----------- |
| Título     | Disponibilizar Diversas Opções de Denúncia  |
| Descrição     |  Como um usuário do aplicativo Sinesp Cidadão, eu quero ter acesso a diversas opções de denúncia, como crimes, violência doméstica e abuso infantil, para relatar incidentes e colaborar com as autoridades na manutenção da ordem pública.   |
| Critérios de aceitação    |  - O sistema deve oferecer uma variedade de categorias de denúncia, abrangendo diferentes tipos de crimes , violações e problemas(Vandalismo, Veículo Abandonado, Comércio Irregular,Iluminação publica).    |

<center>
  
<p style="text-align: center">Autor: <a href="https://github.com/crstyhs">Christian</a></p>

<p style="text-align: center">Tabela 18 - História de Usuário Tutorial de Uso do Aplicativo</p>

<center>
  
| HU17   | características |
| -------- | ----------- |
| Título     | Tutorial de Uso do Aplicativo  |
| Descrição     |  Como um usuário do aplicativo Sinesp Cidadão, eu quero ter acesso a um tutorial completo sobre o uso do aplicativo, para aprender como utilizar todas as funcionalidades disponíveis e aproveitar ao máximo a experiência do usuário.   |
| Critérios de aceitação    |   - O tutorial deve fornecer uma visão geral das principais funcionalidades do aplicativo, incluindo como realizar buscas, relatar ocorrências e acessar informações importantes. <br> - O tutorial deve ser fácil de entender e seguir, utilizando instruções claras e ilustrações visuais sempre que possível. <br> - O usuário deve ter a opção de revisitar o tutorial a qualquer momento, caso deseje aprender mais sobre uma funcionalidade específica do aplicativo.    |

<center>
  
<p style="text-align: center">Autor: <a href="https://github.com/crstyhs">Christian</a></p>

<p style="text-align: center">Tabela 19 - História de Usuário Disponibilização de Fotos do Desaparecido</p>

<center>
  
| HU18   | características |
| -------- | ----------- |
| Título     | 	Disponibilização de Fotos do Desaparecido  |
| Descrição     |  Como um usuário do aplicativo Sinesp Cidadão, eu quero ter acesso a fotos das pessoas desaparecidas, para ajudar na identificação e localização dos indivíduos desaparecidos.   |
| Critérios de aceitação    |   - O sistema deve exibir fotos das pessoas desaparecidas em uma galeria de imagens, acessível através do perfil de cada pessoa desaparecida. <br> - As fotos devem ser de alta qualidade e claramente identificáveis, para facilitar o reconhecimento dos indivíduos. <br> - O sistema deve permitir que o usuário navegue pela galeria de fotos e amplie as imagens para uma visualização mais detalhada.    |

<center>
  
<p style="text-align: center">Autor: <a href="https://github.com/crstyhs">Christian</a></p>

<p style="text-align: center">Tabela 20 - História de Usuário Disponibilização de Informações Detalhadas do Desaparecido</p>

<center>
  
| HU19   | características |
| -------- | ----------- |
| Título     | Disponibilização de Informações Detalhadas do Desaparecido  |
| Descrição     |  Como um usuário do aplicativo Sinesp Cidadão, eu quero ter acesso a informações detalhadas sobre cada pessoa desaparecida, como tatuagem, comportamento e características destacáveis, para ajudar na busca e localização dos indivíduos desaparecidos.   |
| Critérios de aceitação    |   - O sistema deve apresentar informações detalhadas sobre cada pessoa desaparecida em seus respectivos perfis, acessíveis através da lista de pessoas desaparecidas. <br> As informações detalhadas devem incluir características físicas, como altura, peso, cor dos olhos e cabelos, além de características distintivas, como tatuagens ou cicatrizes. <br> - O sistema deve fornecer informações sobre o último local visto da pessoa desaparecida, incluindo data, hora e circunstâncias do desaparecimento.    |

<center>
  
<p style="text-align: center">Autor: <a href="https://github.com/crstyhs">Christian</a></p>

<p style="text-align: center">Tabela 21 - História de Usuário Interface Simples</p>

<center>
  
| HU20   | características |
| -------- | ----------- |
| Título     | 	Interface Simples  |
| Descrição     |  Como um usuário do aplicativo Sinesp Cidadão, eu quero uma interface simples e intuitiva, para que eu possa navegar pelo aplicativo sem dificuldades e encontrar o que preciso com facilidade.   |
| Critérios de aceitação    |   - A navegação dentro do aplicativo deve ser intuitiva, com menus e botões dispostos de forma lógica e consistente. <br> - O sistema deve fornecer feedback visual para indicar ações e estados, como sucesso de uma operação ou erro na entrada de dados. <br> - O sistema deve minimizar a quantidade de passos necessários para realizar uma tarefa, reduzindo assim a carga cognitiva do usuário e aumentando a eficiência da interação.   |

<center>
  
<p style="text-align: center">Autor: <a href="https://github.com/crstyhs">Christian</a></p>

<p style="text-align: center">Tabela 22 - História de Usuário Ligar para a Polícia</p>

<center>
  
| HU21   | características |
| -------- | ----------- |
| Título     | Ligar para a Polícia  |
| Descrição     |  Como um usuário do aplicativo Sinesp Cidadão, eu quero ter a opção de ligar para a polícia diretamente do aplicativo, em caso de emergência ou necessidade de assistência imediata.   |
| Critérios de aceitação    |   - O sistema deve oferecer um botão de emergência na interface do usuário, visível e acessível em todas as telas do aplicativo. <br> - Ao selecionar o botão de emergência, o sistema deve iniciar uma chamada para o número de emergência da polícia local. <br> - O usuário deve receber uma confirmação visual de que a chamada foi iniciada com sucesso e está em andamento.   |

<center>
  
<p style="text-align: center">Autor: <a href="https://github.com/crstyhs">Christian</a></p>

<p style="text-align: center">Tabela 23 - História de Usuário Visualizar Vínculos</p>

<center>
  
| HU22   | características |
| -------- | ----------- |
| Título     | Visualizar Vínculos  |
| Descrição     |  	Como um usuário do aplicativo Sinesp Cidadão, eu quero ter a opção de visualizar vínculos entre ocorrências, pessoas desaparecidas, veículos e outras informações relevantes, para acessar mais facilmente diferentes casos.   |
| Critérios de aceitação    |   - O sistema deve fornecer opções de filtragem e busca para que o usuário possa encontrar e explorar vínculos específicos de interesse.    |

<center>
  
<p style="text-align: center">Autor: <a href="https://github.com/crstyhs">Christian</a></p>

<p style="text-align: center">Tabela 24 - História de Usuário Requisitar Ajuda</p>

<center>
  
| HU23   | características |
| -------- | ----------- |
| Título     | Requisitar Ajuda   |
| Descrição     |  Como um usuário do aplicativo Sinesp Cidadão, eu quero ter a opção de solicitar ajuda , para receber assistência rápida e eficaz .   |
| Critérios de aceitação    |   - O sistema deve possibilitar uma aba de ajuda onde está presente a resposta para as perguntas mais frequentes sobre o aplicativo    |

<center>
  
<p style="text-align: center">Autor: <a href="https://github.com/crstyhs">Christian</a></p>

<p style="text-align: center">Tabela 25 - História de Usuário Retornar ao Início</p>

<center>
  
| HU24   | características |
| -------- | ----------- |
| Título     | Retornar ao Início  |
| Descrição     |  Como um usuário do aplicativo Sinesp Cidadão, eu quero ter a opção de retornar rapidamente à tela inicial do aplicativo, para reiniciar a navegação ou acessar outras funcionalidades de forma conveniente.   |
| Critérios de aceitação    |  - O sistema deve fornecer um botão ou ícone claramente identificado para retornar à tela inicial, visível e acessível em todas as telas do aplicativo. <br> - Ao selecionar o botão ou ícone de retorno à tela inicial, o sistema deve redirecionar o usuário imediatamente para a página inicial do aplicativo. <br> - O usuário deve receber feedback visual de que o retorno à tela inicial foi realizado com sucesso, como uma animação de transição ou mensagem de confirmação. <br> - O sistema deve manter o estado atual da sessão do usuário ao retornar à tela inicial, preservando quaisquer informações ou configurações previamente selecionadas.    |

<center>
  
<p style="text-align: center">Autor: <a href="https://github.com/crstyhs">Christian</a></p>

<p style="text-align: center">Tabela 26 - História de Usuário Salvar Histórico de Busca</p>

<center>
  
| HU25   | características |
| -------- | ----------- |
| Título     | Salvar Histórico de Busca  |
| Descrição     |  Como um usuário do aplicativo Sinesp Cidadão, eu quero que o histórico de minhas buscas seja salvo no aplicativo, para que eu possa acessar facilmente buscas anteriores e retomar o trabalho onde parei.   |
| Critérios de aceitação    |  - O sistema deve registrar automaticamente todas as buscas realizadas pelo usuário durante a sessão no aplicativo. <br> - O usuário deve ter a opção de visualizar o histórico de suas buscas recentes, organizado por data e hora. <br> - O sistema deve permitir que o usuário clique em uma busca anterior no histórico para reexecutá-la imediatamente, sem a necessidade de inserir os termos de busca novamente. <br> - O sistema deve oferecer opções para limpar ou gerenciar o histórico de buscas, permitindo que o usuário remova buscas específicas ou limpe o histórico completo.    |

<center>
  
<p style="text-align: center">Autor: <a href="https://github.com/crstyhs">Christian</a></p>

<p style="text-align: center">Tabela 27 - História de Usuário 	Disponibilizar Filtro de Pesquisa</p>

<center>
  
| HU26   | características |
| -------- | ----------- |
| Título     | 	Disponibilizar Filtro de Pesquisa  |
| Descrição     |  Como um usuário do aplicativo Sinesp Cidadão, eu quero ter a opção de filtrar os resultados da minha pesquisa, para encontrar informações específicas ou refinar os resultados de acordo com meus critérios de interesse.   |
| Critérios de aceitação    |   - O sistema deve oferecer opções de filtro na interface de busca, permitindo que o usuário especifique critérios adicionais para refinar os resultados. <br> - Os filtros disponíveis devem ser relevantes para o contexto da pesquisa e adaptados às necessidades dos usuários, como tipo de ocorrência, data, localização ou gravidade. <br> - O sistema deve aplicar os filtros selecionados aos resultados da pesquisa em tempo real, exibindo apenas as informações que correspondem aos critérios especificados.<br> O usuário deve poder ajustar ou remover os filtros a qualquer momento durante a pesquisa, para explorar diferentes opções e encontrar os resultados desejados.    |

<center>
  
<p style="text-align: center">Autor: <a href="https://github.com/crstyhs">Christian</a></p>

<p style="text-align: center">Tabela 28 - História de Usuário Possibilitar Compartilhamento das Informações de Placa</p>

<center>
  
| HU27   | características |
| -------- | ----------- |
| Título     | 		Possibilitar Compartilhamento das Informações de Placa  |
| Descrição     |  Como um usuário do aplicativo Sinesp Cidadão, eu quero ter a opção de compartilhar informações sobre um veículo utilizando a placa, para alertar outras pessoas sobre veículos roubados ou suspeitos.  |
| Critérios de aceitação    |   - O sistema deve fornecer opções de compartilhamento ao exibir informações sobre um veículo encontrado através da busca pela placa. <br> - O usuário deve poder compartilhar as informações do veículo através de aplicativos de mensagens, redes sociais, e-mail ou outros meios de comunicação. <br> - O sistema deve garantir que as informações compartilhadas sejam precisas e atualizadas, refletindo os dados mais recentes disponíveis sobre o veículo. <br> - O usuário deve receber feedback visual de que as informações foram compartilhadas com sucesso e estar ciente das implicações legais e éticas do compartilhamento de informações pessoais.    |

<center>
  
<p style="text-align: center">Autor: <a href="https://github.com/crstyhs">Christian</a></p>

<p style="text-align: center">Tabela 29 - História de Usuário Instalação do Aplicativo em Diferentes Sistemas</p>

<center>
  
| HU28   | características |
| -------- | ----------- |
| Título     | 	Instalação do Aplicativo em Diferentes Sistemas  |
| Descrição     |  Como um usuário potencial do aplicativo Sinesp Cidadão, eu quero ter a opção de instalar o aplicativo em diferentes sistemas operacionais, como iOS, Android , para que eu possa acessar suas funcionalidades independentemente do dispositivo que estou usando.   |
| Critérios de aceitação    |   O sistema deve estar disponível para download e instalação em diferentes lojas de aplicativos, como App Store e Google Play Store .    |

<center>
  
<p style="text-align: center">Autor: <a href="https://github.com/crstyhs">Christian</a></p>

## Referências
[1] SALES, André Barros. Plano de ensino da disciplina. Disponível em: <https://aprender3.unb.br/pluginfile.php/2844903/mod_resource/content/40/Plano_de_Ensino%20RE%20012024%20Turma%201.pdf>. Acesso em 24 de Maio de 2024.</br>
[2] SERRANO, Milene; SERRANO, Maurício. Slides de Requisitos. Disponível em: <https://aprender3.unb.br/pluginfile.php/2845040/mod_resource/content/1/Requisitos%20-%20Aula%2015a.pdf>. Acesso em 24 de Maio de 2024.

## Histórico de Versões
| Versão | Data | Descrição | Autor | Revisor |
| :----: | :--: | :-------: | :---: | :-----: |
| 1.0 | 24/05/2024 | Criação do documento das Histórias de Usuários | [Christian](https://github.com/crstyhs)| [Italo Bruno](https://github.com/ItaloBrunoM) |
