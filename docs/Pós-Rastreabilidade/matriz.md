# Matriz

## Introdução

A Matriz é o documento responsável em agregar as rastreabolidades Forward-from e Backward-from em um unico documento contendo de onde foram elicitados os requisitos e onde estão sendo implementados

## Metodologia

A estrutura a ser seguida para a elaboração da matriz está presente nas tabela 1 e 2 com o proposito de facilitar a rastreabilidade dos requisitos e elaboração da tabela 3

Os símbolos abaixo representa os símbolos para mapeamento:


<center>

Tabela 1: Símbolos

  | Legenda | Artefato |
  | ------- | ------------------------- |
  | AI| Análise de interface |
  | C | Cenários |
  | EP | Épico |
  |TM |Tema |
  | ENT | Entrevista |
  | ES | Especificação Suplementar |
  | AD | Analise de Documento |
  | INT | Introspecção |
  | LX | Léxico |
  | AP | Análise de Protocolo |
  | Q | Questionário |
  | RF | Requisitos Funcionais |
  | RNF | Requisitos não Funcionais |
  | ST | Storytelling |
  | UC | Casos de Uso |
  | US | Histórias de usuário |
  
_Autor:[Harryson Campos Martins](https://github.com/harry-cmartin), 2024._


</center>

Abaixo a tabela com o modelo da Matriz:

**Tabela 2** -   Modelo da Matriz

| ID | Descrição | Origem | Uso | Implementação | Versão |
| -- | --------- | ------ | --- |--- |--- |
| RFXX | Nome do requisito| artefato de origem|  Artefato que o utiliza  | Implementado ou não | |


_Autor:[Christian Hirsch Santos](https://github.com/crstyhs), 2024._

## Matriz

**Tabela 2** -   Matriz

| ID   | Descrição                                      | Origem                                                                                                                                                                                                                                 | Uso                                                           | Implementação   | Versão |
| ---- | ---------------------------------------------- | -------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- | ------------------------------------------------------------- | --------------- | ------ |
| RF01 | Logar pelo Gov                                 | [AIU2](https://requisitos-de-software.github.io/2024.1-Sinesp_Cidadao/elicitacao/tecnicas/AnaliseDaInterface/), [IP2](https://requisitos-de-software.github.io/2024.1-Sinesp_Cidadao/elicitacao/tecnicas/Introspeccao/), [DOC10](https://requisitos-de-software.github.io/2024.1-Sinesp_Cidadao/elicitacao/tecnicas/AnaliseDeDocumento/) | EP01, TM02, HU01,CN1,2,3,4,5 e LX07                          | Implementado     | 1.0    |
| RF02 | Buscar por veículo                             | [AIU4](https://requisitos-de-software.github.io/2024.1-Sinesp_Cidadao/elicitacao/tecnicas/AnaliseDaInterface/), [IP4](https://requisitos-de-software.github.io/2024.1-Sinesp_Cidadao/elicitacao/tecnicas/Introspeccao/)                 | EP01,TM01,HU02,UC02,CN1,2,3,4,5, e LX08                      | Implementado     | 1.0    |
| RF03 | Informar dados do veículo                      | [AIU5](https://requisitos-de-software.github.io/2024.1-Sinesp_Cidadao/elicitacao/tecnicas/AnaliseDaInterface/), [IP5](https://requisitos-de-software.github.io/2024.1-Sinesp_Cidadao/elicitacao/tecnicas/Introspeccao/), [DOC1](https://requisitos-de-software.github.io/2024.1-Sinesp_Cidadao/elicitacao/tecnicas/AnaliseDeDocumento/) | EP02,TM01,HU03,UC03,CN1,2,3,4,5, e LX10                      | Implementado     | 1.0    |
| RF04 | Adicionar carro como roubado                   | [AIU6](https://requisitos-de-software.github.io/2024.1-Sinesp_Cidadao/elicitacao/tecnicas/AnaliseDaInterface/), [IP6](https://requisitos-de-software.github.io/2024.1-Sinesp_Cidadao/elicitacao/tecnicas/Introspeccao/)                 | EP03,TM01,HU03,CN1,2,3,4,5, e LX05                           | Implementado     | 1.0    |
| RF05 | Listar pessoas desaparecidas                   | [AIU9](https://requisitos-de-software.github.io/2024.1-Sinesp_Cidadao/elicitacao/tecnicas/AnaliseDaInterface/), [IP9](https://requisitos-de-software.github.io/2024.1-Sinesp_Cidadao/elicitacao/tecnicas/Introspeccao/)                 | EP02,TM01,HU04,UC02,CN1,2,3,4,5, e LX10                      | Implementado     | 1.0    |
| RF06 | Vincular ao desaparecido                       | [AIU11](https://requisitos-de-software.github.io/2024.1-Sinesp_Cidadao/elicitacao/tecnicas/AnaliseDaInterface/), [IP11](https://requisitos-de-software.github.io/2024.1-Sinesp_Cidadao/elicitacao/tecnicas/Introspeccao/)               | EP03,TM01,HU06,UC02,CN1,2,3,4,5, e LX05                      | Implementado     | 1.0    |
| RF07 | Vincular ao carro                              | [AIU12](https://requisitos-de-software.github.io/2024.1-Sinesp_Cidadao/elicitacao/tecnicas/AnaliseDaInterface/), [IP12](https://requisitos-de-software.github.io/2024.1-Sinesp_Cidadao/elicitacao/tecnicas/Introspeccao/)               | EP03,TM01,HU07,UC01,CN1,2,3,4,5, e LX05                      | Implementado     | 1.0    |
| RF08 | Buscar por mandados de prisão                  | [AIU13](https://requisitos-de-software.github.io/2024.1-Sinesp_Cidadao/elicitacao/tecnicas/AnaliseDaInterface/), [IP13](https://requisitos-de-software.github.io/2024.1-Sinesp_Cidadao/elicitacao/tecnicas/Introspeccao/), [DOC2](https://requisitos-de-software.github.io/2024.1-Sinesp_Cidadao/elicitacao/tecnicas/AnaliseDeDocumento/) | EP02,TM01,HU08,UC03,CN1,2,3,4,5, e LX10                      | Implementado     | 1.0    |
| RF09 | Fornecer informações sobre mandados de prisão  | [AIU14](https://requisitos-de-software.github.io/2024.1-Sinesp_Cidadao/elicitacao/tecnicas/AnaliseDaInterface/), [IP14](https://requisitos-de-software.github.io/2024.1-Sinesp_Cidadao/elicitacao/tecnicas/Introspeccao/), [DOC2](https://requisitos-de-software.github.io/2024.1-Sinesp_Cidadao/elicitacao/tecnicas/AnaliseDeDocumento/) | EP02,TM01,HU09,UC03,CN1,2,3,4,5, e LX10, LX03                | Implementado     | 1.0    |
| RF10 | Buscar por procurados                          | [AIU16](https://requisitos-de-software.github.io/2024.1-Sinesp_Cidadao/elicitacao/tecnicas/AnaliseDaInterface/), [IP16](https://requisitos-de-software.github.io/2024.1-Sinesp_Cidadao/elicitacao/tecnicas/Introspeccao/), [DOC4](https://requisitos-de-software.github.io/2024.1-Sinesp_Cidadao/elicitacao/tecnicas/AnaliseDeDocumento/) | EP02,TM01,HU10,UC04,CN1,2,3,4,5, e LX10                      | Implementado     | 1.0    |
| RF11 | Fornecer informações sobre procurados          | [AIU17](https://requisitos-de-software.github.io/2024.1-Sinesp_Cidadao/elicitacao/tecnicas/AnaliseDaInterface/), [IP17](https://requisitos-de-software.github.io/2024.1-Sinesp_Cidadao/elicitacao/tecnicas/Introspeccao/)               | EP02,TM01,HU11,UC04,CN1,2,3,4,5, e LX10                      | Implementado     | 1.0    |
| RF12 | Sair do aplicativo                             | [AIU19](https://requisitos-de-software.github.io/2024.1-Sinesp_Cidadao/elicitacao/tecnicas/AnaliseDaInterface/)                                                                                                                          | EP04 , TM02,CN1,2,3,4,5, HU12, LX01, LX02                    | Implementado     | 1.0    |
| RF13 | Anunciar perturbação da vizinhança             | [AIU20](https://requisitos-de-software.github.io/2024.1-Sinesp_Cidadao/elicitacao/tecnicas/AnaliseDaInterface/), [IP20](https://requisitos-de-software.github.io/2024.1-Sinesp_Cidadao/elicitacao/tecnicas/Introspeccao/)               | EP03,TM02,HU12,UC05,CN1,2,3,4,5, e LX02                      | Implementado     | 1.0    |
| RF14 | Ler texto para deficientes visuais             | [IP1](https://requisitos-de-software.github.io/2024.1-Sinesp_Cidadao/elicitacao/tecnicas/Introspeccao/)                                                                                                                                | EP04,TM03,HU41 e LX02                                        | Não Implementado | 1.0    |
| RF15 | Disponibilizar restrição                       | [AP2](https://requisitos-de-software.github.io/2024.1-Sinesp_Cidadao/elicitacao/tecnicas/AnaliseDeProtocolo/), [IP3](https://requisitos-de-software.github.io/2024.1-Sinesp_Cidadao/elicitacao/tecnicas/Introspeccao/)                 | EP03,TM01,HU07,UC01,CN1,2,3,4,5, e LX05                      | Implementado     | 1.0    |
| RF16 | Disponibilizar área                            | [IP4](https://requisitos-de-software.github.io/2024.1-Sinesp_Cidadao/elicitacao/tecnicas/Introspeccao/)                                                                                                                                | EP03,TM01,HU02,UC01,CN1,2,3,4,5, e LX08                      | Implementado     | 1.0    |
| RF17 | Mostrar o resultado da busca do veículo        | [AIU2](https://requisitos-de-software.github.io/2024.1-Sinesp_Cidadao/elicitacao/tecnicas/AnaliseDaInterface/), [IP3](https://requisitos-de-software.github.io/2024.1-Sinesp_Cidadao/elicitacao/tecnicas/Introspeccao/), [DOC4](https://requisitos-de-software.github.io/2024.1-Sinesp_Cidadao/elicitacao/tecnicas/AnaliseDeDocumento/) | EP01, TM01, HU01,UC01, CN1,2,3,4,5 e LX09                   | Implementado     | 1.0    |
| RF18 | Adicionar restrição                            | [IP5](https://requisitos-de-software.github.io/2024.1-Sinesp_Cidadao/elicitacao/tecnicas/Introspeccao/)                                                                                                                                | EP03,TM01,HU02,UC01,CN1,2,3,4,5, e LX08                      | Implementado     | 1.0    |
| RF19 | Adicionar foto ao veículo                      | [AP1](https://requisitos-de-software.github.io/2024.1-Sinesp_Cidadao/elicitacao/tecnicas/AnaliseDeProtocolo/)                                                                                                                           | EP02,TM01,HU03,CN1,2,3,4,5, e LX10                          | Implementado     | 1.0    |
| RF20 | Adicionar foto a pessoa desaparecida           | [IP2](https://requisitos-de-software.github.io/2024.1-Sinesp_Cidadao/elicitacao/tecnicas/Introspeccao/), [DOC2](https://requisitos-de-software.github.io/2024.1-Sinesp_Cidadao/elicitacao/tecnicas/AnaliseDeDocumento/)                 | EP03,TM01,HU04,CN1,2,3,4,5, e LX05                          | Implementado     | 1.0    |
| RF21 | Adicionar foto ao procurado                    | [IP3](https://requisitos-de-software.github.io/2024.1-Sinesp_Cidadao/elicitacao/tecnicas/Introspeccao/)                                                                                                                                | EP03,TM01,HU05,CN1,2,3,4,5, e LX05                          | Implementado     | 1.0    |
| RF22 | Adicionar foto ao mandato de prisão            | [AP4](https://requisitos-de-software.github.io/2024.1-Sinesp_Cidadao/elicitacao/tecnicas/AnaliseDeProtocolo/)                                                                                                                           | EP03,TM01,HU06,CN1,2,3,4,5, e LX05                          | Implementado     | 1.0    |
| RF23 | Adicionar nome ao mandato de prisão            | [AP5](https://requisitos-de-software.github.io/2024.1-Sinesp_Cidadao/elicitacao/tecnicas/AnaliseDeProtocolo/)                                                                                                                           | EP03,TM01,HU07,CN1,2,3,4,5, e LX05                          | Implementado     | 1.0    |
| RF24 | Adicionar nome ao procurado                    | [AP6](https://requisitos-de-software.github.io/2024.1-Sinesp_Cidadao/elicitacao/tecnicas/AnaliseDeProtocolo/), [DOC3](https://requisitos-de-software.github.io/2024.1-Sinesp_Cidadao/elicitacao/tecnicas/AnaliseDeDocumento/)          | EP03,TM01,HU08,CN1,2,3,4,5, e LX05                          | Implementado     | 1.0    |
| RF25 | Adicionar nome a pessoa desaparecida           | [AP7](https://requisitos-de-software.github.io/2024.1-Sinesp_Cidadao/elicitacao/tecnicas/AnaliseDeProtocolo/), [DOC4](https://requisitos-de-software.github.io/2024.1-Sinesp_Cidadao/elicitacao/tecnicas/AnaliseDeDocumento/)          | EP03,TM01,HU09,CN1,2,3,4,5, e LX05                          | Implementado     | 1.0    |
| RF26 | Adicionar restrição ao veículo                 | [IP4](https://requisitos-de-software.github.io/2024.1-Sinesp_Cidadao/elicitacao/tecnicas/Introspeccao/)                                                                                                                                | EP03,TM01,HU10,CN1,2,3,4,5, e LX05                          | Implementado     | 1.0    |
| RF27 | Adicionar restrição a pessoa desaparecida      | [IP5](https://requisitos-de-software.github.io/2024.1-Sinesp_Cidadao/elicitacao/tecnicas/Introspeccao/)                                                                                                                                | EP03,TM01,HU11,CN1,2,3,4,5, e LX05                          | Implementado     | 1.0    |
| RF28 | Adicionar restrição ao procurado               | [IP6](https://requisitos-de-software.github.io/2024.1-Sinesp_Cidadao/elicitacao/tecnicas/Introspeccao/), [DOC5](https://requisitos-de-software.github.io/2024.1-Sinesp_Cidadao/elicitacao/tecnicas/AnaliseDeDocumento/)                | EP03,TM01,HU12,CN1,2,3,4,5, e LX05                          | Implementado     | 1.0    |
| RF29 | Adicionar restrição ao mandato de prisão       | [AP8](https://requisitos-de-software.github.io/2024.1-Sinesp_Cidadao/elicitacao/tecnicas/AnaliseDeProtocolo/)                                                                                                                           | EP03,TM01,HU13,CN1,2,3,4,5, e LX05                          | Implementado     | 1.0    |
| RF30 | Anunciar pessoa desaparecida                   | [AP9](https://requisitos-de-software.github.io/2024.1-Sinesp_Cidadao/elicitacao/tecnicas/AnaliseDeProtocolo/)                                                                                                                           | EP03,TM01,HU14,CN1,2,3,4,5, e LX05                          | Implementado     | 1.0    |
| RF31 | Notificar pessoa desaparecida                  | [IP8](https://requisitos-de-software.github.io/2024.1-Sinesp_Cidadao/elicitacao/tecnicas/Introspeccao/)                                                                                                                                | EP03,TM01,HU15,CN1,2,3,4,5, e LX05                          | Implementado     | 1.0    |
| RF32 | Notificar sobre mandado de prisão              | [AP10](https://requisitos-de-software.github.io/2024.1-Sinesp_Cidadao/elicitacao/tecnicas/AnaliseDeProtocolo/), [DOC6](https://requisitos-de-software.github.io/2024.1-Sinesp_Cidadao/elicitacao/tecnicas/AnaliseDeDocumento/)         | EP03,TM01,HU16,CN1,2,3,4,5, e LX05                          | Implementado     | 1.0    |
| RF33 | Notificar sobre procurado                      | [AP11](https://requisitos-de-software.github.io/2024.1-Sinesp_Cidadao/elicitacao/tecnicas/AnaliseDeProtocolo/), [DOC7](https://requisitos-de-software.github.io/2024.1-Sinesp_Cidadao/elicitacao/tecnicas/AnaliseDeDocumento/)         | EP03,TM01,HU17,CN1,2,3,4,5, e LX05                          | Implementado     | 1.0    |
| RF34 | Realizar backup das informações                | [IP7](https://requisitos-de-software.github.io/2024.1-Sinesp_Cidadao/elicitacao/tecnicas/Introspeccao/), [DOC8](https://requisitos-de-software.github.io/2024.1-Sinesp_Cidadao/elicitacao/tecnicas/AnaliseDeDocumento/)                | EP04,TM01,HU18,CN1,2,3,4,5, e LX06                          | Implementado     | 1.0    |
| RF35 | Restaurar backup das informações               | [IP8](https://requisitos-de-software.github.io/2024.1-Sinesp_Cidadao/elicitacao/tecnicas/Introspeccao/), [DOC9](https://requisitos-de-software.github.io/2024.1-Sinesp_Cidadao/elicitacao/tecnicas/AnaliseDeDocumento/)                | EP04,TM01,HU19,CN1,2,3,4,5, e LX06                          | Implementado     | 1.0    |
| RF36 | Manter aplicação disponível                    | [IP10](https://requisitos-de-software.github.io/2024.1-Sinesp_Cidadao/elicitacao/tecnicas/Introspeccao/)                                                                                                                               | EP04,TM02,HU20,CN1,2,3,4,5, e LX02                          | Implementado     | 1.0    |
| RF37 | Atualizar aplicativo                           | [IP11](https://requisitos-de-software.github.io/2024.1-Sinesp_Cidadao/elicitacao/tecnicas/Introspeccao/), [DOC10](https://requisitos-de-software.github.io/2024.1-Sinesp_Cidadao/elicitacao/tecnicas/AnaliseDeDocumento/)               | EP04,TM03,HU21,CN1,2,3,4,5, e LX02                          | Não Implementado | 1.0    |
| RF38 | Validar login                                  | [IP12](https://requisitos-de-software.github.io/2024.1-Sinesp_Cidadao/elicitacao/tecnicas/Introspeccao/)                                                                                                                               | EP01,TM02,HU22,CN1,2,3,4,5, e LX08                          | Implementado     | 1.0    |
| RF39 | Restringir acesso às informações               | [AP12](https://requisitos-de-software.github.io/2024.1-Sinesp_Cidadao/elicitacao/tecnicas/AnaliseDeProtocolo/)                                                                                                                          | EP01,TM02,HU23,CN1,2,3,4,5, e LX08                          | Implementado     | 1.0    |
| RF40 | Definir permissões para perfis de usuário      | [AP13](https://requisitos-de-software.github.io/2024.1-Sinesp_Cidadao/elicitacao/tecnicas/AnaliseDeProtocolo/), [DOC11](https://requisitos-de-software.github.io/2024.1-Sinesp_Cidadao/elicitacao/tecnicas/AnaliseDeDocumento/)        | EP01,TM02,HU24,CN1,2,3,4,5, e LX08                          | Implementado     | 1.0    |
| RNF01 |Rápida disponibilização de informações| [AIU27](https://requisitos-de-software.github.io/2024.1-Sinesp_Cidadao/elicitacao/tecnicas/AnaliseDaInterface/), [AP1](https://requisitos-de-software.github.io/2024.1-Sinesp_Cidadao/elicitacao/tecnicas/AnaliseDeProtocolo/), [ENT1](https://requisitos-de-software.github.io/2024.1-Sinesp_Cidadao/elicitacao/tecnicas/Entrevista/), [IP27](https://requisitos-de-software.github.io/2024.1-Sinesp_Cidadao/elicitacao/tecnicas/Introspeccao/)|  EP04, TM03 e HU14 | Implementado |1.0    |
| RNF02 |  Sigilo relativo de informações|   [AIU26](https://requisitos-de-software.github.io/2024.1-Sinesp_Cidadao/elicitacao/tecnicas/AnaliseDaInterface/) , [IP26](https://requisitos-de-software.github.io/2024.1-Sinesp_Cidadao/elicitacao/tecnicas/Introspeccao/)|  EP04, TM03 e HU15 | Implementado | 1.0    |
| RNF03 | Banco de dados ser constantemente atualizado|   [AP4](https://requisitos-de-software.github.io/2024.1-Sinesp_Cidadao/elicitacao/tecnicas/AnaliseDeProtocolo/), [IP25](https://requisitos-de-software.github.io/2024.1-Sinesp_Cidadao/elicitacao/tecnicas/Introspeccao/), [STO3](https://requisitos-de-software.github.io/2024.1-Sinesp_Cidadao/elicitacao/tecnicas/storytelling/)|  EP04, TM03 e HU40|  Não Implementado | 1.0    |
| RNF04 | Ajudar o trabalho policial e a comunidade|  [ENT11](https://requisitos-de-software.github.io/2024.1-Sinesp_Cidadao/elicitacao/tecnicas/Entrevista/)|  EP04, TM02 | Implementado | 1.0    |
| RNF05 | Interface simples|  [AIU3](https://requisitos-de-software.github.io/2024.1-Sinesp_Cidadao/elicitacao/tecnicas/AnaliseDaInterface/), [IP3](https://requisitos-de-software.github.io/2024.1-Sinesp_Cidadao/elicitacao/tecnicas/Introspeccao/), [STO1](https://requisitos-de-software.github.io/2024.1-Sinesp_Cidadao/elicitacao/tecnicas/storytelling/)|  EP04, TM03 ,HU20, LX01 | Implementado | 1.0    |
| RNF06 | Instalação do aplicativo em diferentes sistemas|  [AIU28](https://requisitos-de-software.github.io/2024.1-Sinesp_Cidadao/elicitacao/tecnicas/AnaliseDaInterface/), [IP28](https://requisitos-de-software.github.io/2024.1-Sinesp_Cidadao/elicitacao/tecnicas/Introspeccao/)| EP04, TM03 ,HU28 | Implementado | 1.0    |
| RNF07 | Aplicativo deve ser constantemente divulgado| [AP6](https://requisitos-de-software.github.io/2024.1-Sinesp_Cidadao/elicitacao/tecnicas/AnaliseDeProtocolo/), [STO4](https://requisitos-de-software.github.io/2024.1-Sinesp_Cidadao/elicitacao/tecnicas/storytelling/)|  EP04, TM03 ,HU40 | Não Implementado | 1.0    |

_Autor:[Christian Hirsch Santos](https://github.com/crstyhs) e [Ian Lucca](https://github.com/IanLucca12), 2024._






## Referência Bibliografia

> - POHL, Klaus; RUPP, Chris. Requirements Engineering Fundamentals: A Study Guide for the Certified Professional for Requirements Engineering Exam.
> - Slides da Aula 26 da Professora Milene Serrano e do Professor Maurício Serrano.

## Histórico de Versão

|Versão|Data|Descrição|Autor|Revisor|
|:----:|----|---------|-----|:-------:|
|`1.0`| 22/06/2024 | Criação do documento |[Christian Hirsch Santos](https://github.com/crstyhs)  | [Flávio Melo](https://github.com/flavioovatsug)|
