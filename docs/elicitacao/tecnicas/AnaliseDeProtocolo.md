# Análise de Protocolo

## Introdução
Este documento refere-se à análise de protocolo, documentação de umas das metodologias aplicadas sobre o projeto de requisitos de software pelo grupo 5 para a elicitação dos requisitos presentes no aplicativo Sinesp Cidadão disponibilizada na tabela 2

## Metodologia
Essa metodologia propõe uma interação direta com o usuário, solicitando que ele execute atividades dentro do sistema. Isso permite aos desenvolvedores obter uma compreensão detalhada de como as tarefas são realizadas pelo usuário, identificando eventuais dificuldades ou pontos de melhoria. Durante essa interação, o usuário é encorajado a narrar em voz alta suas ações e explicar o que está fazendo, seguindo os comandos do sistema. Essa abordagem, conhecida como análise de protocolo, proporciona um maior entendimento sobre o fluxo de trabalho do usuário e suas necessidades, 
contribuindo para o desenvolvimento de requisitos mais precisos e orientados para a experiência do usuário [6]

## Processo
Durante uma reunião realizada dia 10/04/2024, estabelecida entre os integrantes do grupo 5, [Marcos](https://github.com/Bittarx) e [Christian](https://github.com/crstyhs) com um ex-policial, foi
requisitado que o usuário seguisse alguns comando e expressasse sua opinião sobre a usabilidade . Foi pedido a não divulgação do vídeo da reunião.

Abaixo a tabela 1 com um resumo das questões levantadas

<center>

Tabela 1 - Questões levantadas

| Comando | Questões  |
| ---- | ---- |
| Faça uma busca de um veículo de dada placa | - O imediatismo de informação entre a placa Mercosul e a versão antiga </br> - O uso do rádio comparado a velocidade do aplicativo e sua necessidade de internet </br> - A falta de informação e a presença de erro ao não conseguir fornecer informações quanto ao restrição | 
||
| Faça uma busca de um mandato de dada pessoa | - A Necessidade de atualização e alimentação do banco de dados para evitar falhas no sistema público </br> - A utilidade desta função para colaboração na apreensão de suspeitos no exercício do trabalho policial|
||
| Acesse a aba de participação cidadã | - A presença de uma diversa gama de assuntos a serem denunciados através do aplicativo </br> - A necessidade de maior divulgação do aplicativo e explicitação de suas funcionalidades|
||
| Acesse a aba de desaparecidos | - Carência de dados sobre o desaparecido|

</center>

## Requisitos Elicitados

<center>

Tabela 2 - Requisitos elicitados

| ID | Elicitação | Tipo | Status |
| ---- | ---- |---- |---- |
| AP1 | Retorno rápido de informação | RNF| Implementado |
| AP2 | Disponibilizar restrição sem erros | RF| Não Implementado|
| AP3 | Disponibilizar informação do tipo de veículo | RF| Não Implementado|
| AP4 | Banco de dados ser constantemente atualizado | RNF| |
| AP5 | Disponibilizar diversas opções de denuncia | RF| Implementado|
| AP6 | Aplicativo deve ser constantemente divulgado | RNF| Não Implementado |
| AP7 | Tutorial de uso do aplicativo | RF| Implementado|
| AP8 | Disponibilização de fotos do desaparecido | RF| Não Implementado|
| AP9 | Disponibilização de informações detalhadas do desaparecido | RF| Não Implementado|

</center>

## Referências
[1] Sinesp Cidadão. Disponível em: [Gov](https://www.gov.br/pt-br/apps/sinesp-cidadao). Acesso em 13 de abril de 2024.</br>
[2] VAZQUEZ, Carlos Eduardo ; SIMOES, Guilherme Siqueira. Engenharia de Requisitos: Software Orientado ao Negocio. Brasport, 2016.</br>
[3] SALES, André Barros. Plano de ensino da disciplina. Disponível em: <https://aprender3.unb.br/pluginfile.php/2844903/mod_resource/content/40/Plano_de_Ensino%20RE%20012024%20Turma%201.pdf>. Acesso em 13 de abril de 2024.</br>
[4] SERRANO, Milene; SERRANO, Maurício. Slides de Requisitos. Disponível em: <https://aprender3.unb.br/pluginfile.php/2844984/mod_resource/content/2/Requisitos%20-%20Aula%2007.pdf>. Acesso em 13 de abril de 2024.
[5] BEATTY, Joy; WIEGERS, Karl. Software Requirements (Developer Best Practices). Edição 3. Microsoft Press , 2013.</br>
[6] REtraining. Disponível em: <https://retraining.inf.ufsc.br/guia/app/classificacoes/tecnicas-de-elicitacao-de-requisitos/entidades/tecnicas-de-elicitacao-de-requisitos-analise-de-protocolo>. Acesso em 13 de abril de 2024.
## Histórico de Versões
| Versão | Data | Descrição | Autor | Revisor |
| :----: | :--: | :-------: | :---: | :-----: |
| 1.0 | 13/04/2024 | Criação do documento da Análise de Protocolo | [Christian](https://github.com/crstyhs)| [Italo Bruno](https://github.com/ItaloBrunoM) |
| 1.1 | 14/04/2024 | Adição dos requisitos elicitados  | [Christian](https://github.com/crstyhs)| [Italo Bruno](https://github.com/ItaloBrunoM) |
| 1.2 | 17/04/2024 | Atualização das identificações  | [Christian](https://github.com/crstyhs)| [Italo Bruno](https://github.com/ItaloBrunoM) |

