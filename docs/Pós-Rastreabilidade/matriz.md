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

| ID | Descrição | Origem | Uso | Implementação |
| -- | --------- | ------ | --- |--- |
| RFXX | Nome do requisito| [artefato de origem](../elicitacao/introspeccao.md)|  [Artefato que o utiliza]()  | [Implementado ou não]() |


_Autor:[Christian Hirsch Santos](https://github.com/crstyhs), 2024._

## Matriz

**Tabela 2** -   Modelo da Matriz

| ID | Descrição | Origem | Uso | Implementação |
| -- | --------- | ------ | --- |--- |
| RF01 | Logar pelo Gov| [AIU2](https://requisitos-de-software.github.io/2024.1-Sinesp_Cidadao/elicitacao/tecnicas/AnaliseDaInterface/) , [IP2](https://requisitos-de-software.github.io/2024.1-Sinesp_Cidadao/elicitacao/tecnicas/Introspeccao/), [DOC10](https://requisitos-de-software.github.io/2024.1-Sinesp_Cidadao/elicitacao/tecnicas/AnaliseDeDocumento/)|  EP01, TM02, HU01,CN1,2,3,4,5 e LX07  |Implementado |
| RF02 | Buscar por veículo|[AIU4](https://requisitos-de-software.github.io/2024.1-Sinesp_Cidadao/elicitacao/tecnicas/AnaliseDaInterface/), [IP4](https://requisitos-de-software.github.io/2024.1-Sinesp_Cidadao/elicitacao/tecnicas/Introspeccao/)|  EP01,TM01,,HU02,UC02,CN1,2,3,4,5, e LX08 | Implementado|
| RF03 | Informar dados do veículo| [AIU5](https://requisitos-de-software.github.io/2024.1-Sinesp_Cidadao/elicitacao/tecnicas/AnaliseDaInterface/), [IP5](https://requisitos-de-software.github.io/2024.1-Sinesp_Cidadao/elicitacao/tecnicas/Introspeccao/), [DOC1](https://requisitos-de-software.github.io/2024.1-Sinesp_Cidadao/elicitacao/tecnicas/AnaliseDeDocumento/)|  EP02,TM01,HU03,UC03,CN1,2,3,4,5, e LX10 | Implementado |
| RF04 | Adicionar carro como roubado|[AIU6](https://requisitos-de-software.github.io/2024.1-Sinesp_Cidadao/elicitacao/tecnicas/AnaliseDaInterface/), [IP6](https://requisitos-de-software.github.io/2024.1-Sinesp_Cidadao/elicitacao/tecnicas/Introspeccao/)|  EP03,TM01,HU03,CN1,2,3,4,5, e LX05  | Implementado|
| RF05 | Listar pessoas desaparecidas| [AIU9](https://requisitos-de-software.github.io/2024.1-Sinesp_Cidadao/elicitacao/tecnicas/AnaliseDaInterface/), [IP9](https://requisitos-de-software.github.io/2024.1-Sinesp_Cidadao/elicitacao/tecnicas/Introspeccao/)| EP02,TM01,HU04,UC02,CN1,2,3,4,5, e LX10 | Implementado |
| RF06| Vincular ao desaparecido|  [AIU11](https://requisitos-de-software.github.io/2024.1-Sinesp_Cidadao/elicitacao/tecnicas/AnaliseDaInterface/), [IP11](https://requisitos-de-software.github.io/2024.1-Sinesp_Cidadao/elicitacao/tecnicas/Introspeccao/)|  EP03,TM01,HU06,UC02,CN1,2,3,4,5, e LX05  | Implementado |
| RF07 | Vincular ao carro| [AIU12](https://requisitos-de-software.github.io/2024.1-Sinesp_Cidadao/elicitacao/tecnicas/AnaliseDaInterface/), [IP12](https://requisitos-de-software.github.io/2024.1-Sinesp_Cidadao/elicitacao/tecnicas/Introspeccao/)|  EP03,TM01,HU07,UC01,CN1,2,3,4,5, e LX05   | Implementado |
| RF08 | Buscar por mandados de prisão| [AIU13](https://requisitos-de-software.github.io/2024.1-Sinesp_Cidadao/elicitacao/tecnicas/AnaliseDaInterface/), [IP13](https://requisitos-de-software.github.io/2024.1-Sinesp_Cidadao/elicitacao/tecnicas/Introspeccao/), [DOC2](https://requisitos-de-software.github.io/2024.1-Sinesp_Cidadao/elicitacao/tecnicas/AnaliseDeDocumento/) | EP02,TM01,HU08,UC03,CN1,2,3,4,5, e LX10   | Implementado |
| RF09 | Fornecer informações sobre mandados de prisão|  [AIU14](https://requisitos-de-software.github.io/2024.1-Sinesp_Cidadao/elicitacao/tecnicas/AnaliseDaInterface/), [IP14](https://requisitos-de-software.github.io/2024.1-Sinesp_Cidadao/elicitacao/tecnicas/Introspeccao/), [DOC2](https://requisitos-de-software.github.io/2024.1-Sinesp_Cidadao/elicitacao/tecnicas/AnaliseDeDocumento/)| EP02,TM01,HU09,UC03,CN1,2,3,4,5, e LX10, LX03  | Implementado|
| RF10 | Buscar por procurados| [AIU16](https://requisitos-de-software.github.io/2024.1-Sinesp_Cidadao/elicitacao/tecnicas/AnaliseDaInterface/),  [IP16](https://requisitos-de-software.github.io/2024.1-Sinesp_Cidadao/elicitacao/tecnicas/Introspeccao/), [DOC4](https://requisitos-de-software.github.io/2024.1-Sinesp_Cidadao/elicitacao/tecnicas/AnaliseDeDocumento/)|  EP02,TM01,HU10,UC04,CN1,2,3,4,5, e LX10 | Implementado |
| RF11 | Fornecer informações sobre procurados| [AIU17](https://requisitos-de-software.github.io/2024.1-Sinesp_Cidadao/elicitacao/tecnicas/AnaliseDaInterface/), [IP17](https://requisitos-de-software.github.io/2024.1-Sinesp_Cidadao/elicitacao/tecnicas/Introspeccao/)|EP02,TM01,HU11,UC04,CN1,2,3,4,5, e LX10   | Implementado |
| RF12 | Sair do aplicativo| [AIU19](https://requisitos-de-software.github.io/2024.1-Sinesp_Cidadao/elicitacao/tecnicas/AnaliseDaInterface/)| EP04 , TM02,CN1,2,3,4,5, HU12, LX01, LX02| Implementado | 
| RF13 | Anunciar perturbação da vizinhança | [AIU20](https://requisitos-de-software.github.io/2024.1-Sinesp_Cidadao/elicitacao/tecnicas/AnaliseDaInterface/), [IP20](https://requisitos-de-software.github.io/2024.1-Sinesp_Cidadao/elicitacao/tecnicas/Introspeccao/)|  EP03,TM02,HU12,UC05,CN1,2,3,4,5, e LX02   | Implementado |
| RF14 |Ler texto para deficientes visuais| [IP1](https://requisitos-de-software.github.io/2024.1-Sinesp_Cidadao/elicitacao/tecnicas/Introspeccao/)|  EP04,TM03,HU41 e LX02  | Não Implementado |
| RF15 | Disponibilizar restrição| [AP2](https://requisitos-de-software.github.io/2024.1-Sinesp_Cidadao/elicitacao/tecnicas/AnaliseDeProtocolo/), [ENT2](https://requisitos-de-software.github.io/2024.1-Sinesp_Cidadao/elicitacao/tecnicas/Entrevista/)|  EP04,TM02 e LX05   | Implementado |
| RF16 | Visualizar informações institucionais| [AIU15](https://requisitos-de-software.github.io/2024.1-Sinesp_Cidadao/elicitacao/tecnicas/AnaliseDaInterface/)|  EP04,TM01,HU35,UC04,CN1,2,3,4,5, LX01 e LX10 |Implementado |
| RF17 | Disponibilizar informação do tipo de veículo| [AP3](https://requisitos-de-software.github.io/2024.1-Sinesp_Cidadao/elicitacao/tecnicas/AnaliseDeProtocolo/), [ENT3](https://requisitos-de-software.github.io/2024.1-Sinesp_Cidadao/elicitacao/tecnicas/Entrevista/), [STO2](https://requisitos-de-software.github.io/2024.1-Sinesp_Cidadao/elicitacao/tecnicas/storytelling/)|   EP04,TM03,UO01 e LX10  | Não Implementado |
| RF18 | Disponibilizar diversas opções de denúncia|[AP5](https://requisitos-de-software.github.io/2024.1-Sinesp_Cidadao/elicitacao/tecnicas/AnaliseDeProtocolo/), [ENT5](https://requisitos-de-software.github.io/2024.1-Sinesp_Cidadao/elicitacao/tecnicas/Entrevista/), [DOC5](https://requisitos-de-software.github.io/2024.1-Sinesp_Cidadao/elicitacao/tecnicas/AnaliseDeDocumento/), [DOC6](https://requisitos-de-software.github.io/2024.1-Sinesp_Cidadao/elicitacao/tecnicas/AnaliseDeDocumento/), [DOC7](https://requisitos-de-software.github.io/2024.1-Sinesp_Cidadao/elicitacao/tecnicas/AnaliseDeDocumento/), [DOC8](https://requisitos-de-software.github.io/2024.1-Sinesp_Cidadao/elicitacao/tecnicas/AnaliseDeDocumento/), [DOC9](https://requisitos-de-software.github.io/2024.1-Sinesp_Cidadao/elicitacao/tecnicas/AnaliseDeDocumento/)|   EP04,TM03,HU16,CN1,2,3,4,5 e LX02  | Implementado |
| RF19| Tutorial de uso do aplicativo| [AP7](https://requisitos-de-software.github.io/2024.1-Sinesp_Cidadao/elicitacao/tecnicas/AnaliseDeProtocolo/), [ENT7](https://requisitos-de-software.github.io/2024.1-Sinesp_Cidadao/elicitacao/tecnicas/Entrevista/)|   EP04,TM03,HU17,LX01 e LX02  |  Não Implementado |
| RF20 | Disponibilização de fotos do desaparecido|[AP8](https://requisitos-de-software.github.io/2024.1-Sinesp_Cidadao/elicitacao/tecnicas/AnaliseDeProtocolo/), [ENT8](https://requisitos-de-software.github.io/2024.1-Sinesp_Cidadao/elicitacao/tecnicas/Entrevista/)|   EP02,TM01,HU18,LX05,LX10 e LX13   |   Não Implementado |
| RF21 | Disponibilização de informações detalhadas do desaparecido| [ENT9](https://requisitos-de-software.github.io/2024.1-Sinesp_Cidadao/elicitacao/tecnicas/Entrevista/)|  EP02, TM01, 	HU19, LX10, LX13  | Não Implementado |
| RF22 | Ligar para a polícia| [AIU7](https://requisitos-de-software.github.io/2024.1-Sinesp_Cidadao/elicitacao/tecnicas/AnaliseDaInterface/), [IP7](https://requisitos-de-software.github.io/2024.1-Sinesp_Cidadao/elicitacao/tecnicas/Introspeccao/)|  EP06 , TM01 , HU21, UC05, CN01, CN02 , CN03 CN04 , CN05 , LX01, LX02   | Implementado |
| RF23 | Visualizar vínculos| [AIU8](https://requisitos-de-software.github.io/2024.1-Sinesp_Cidadao/elicitacao/tecnicas/AnaliseDaInterface/)|  EP02 , TM01, HU22, UC01, UC04 ,  CN01, CN02 , CN03 CN04 , CN05 , LX05, LX10  | Implementado |
| RF24 | Requisitar ajuda| [AIU18](https://requisitos-de-software.github.io/2024.1-Sinesp_Cidadao/elicitacao/tecnicas/AnaliseDaInterface/) |  EP04 , TM02, HU23 ,  CN01, CN02 , CN03 CN04 , CN05,  LX02   | Implementado |
| RF25 | Retornar ao início| [AIU21](https://requisitos-de-software.github.io/2024.1-Sinesp_Cidadao/elicitacao/tecnicas/AnaliseDaInterface/)| EP04 , TM02 , HU24 , CN01, CN02 , CN03 CN04 , CN05 , LX01, LX02 | Implementado |
| RF26 | Salvar histórico de busca| [AIU22](https://requisitos-de-software.github.io/2024.1-Sinesp_Cidadao/elicitacao/tecnicas/AnaliseDaInterface/), [IP15](https://requisitos-de-software.github.io/2024.1-Sinesp_Cidadao/elicitacao/tecnicas/Introspeccao/)|  EP05 , TM01, 	HU25, CN01, CN02 , CN03 CN04 , CN05 , LX11, LX12  | Implementado |
| RF27 | Disponibilizar filtro de pesquisa| [AIU23](https://requisitos-de-software.github.io/2024.1-Sinesp_Cidadao/elicitacao/tecnicas/AnaliseDaInterface/) |  EP04, TM02 , HU26 , CN01, CN02 , CN03 CN04 , CN05, LX08  | Implementado |
| RF28 | Possibilitar compartilhamento das informações de placa| [AIU25](https://requisitos-de-software.github.io/2024.1-Sinesp_Cidadao/elicitacao/tecnicas/AnaliseDaInterface/)|  EP06 , TM01 , HU27 , CN01, CN02 , CN03 CN04 , CN05, LX02   | Implementado |
| RF29 |  Notificar sobre atualizações sobre vínculo| [IP8](https://requisitos-de-software.github.io/2024.1-Sinesp_Cidadao/elicitacao/tecnicas/Introspeccao/)| EP04 , TM02 , HU29 , LX05, LX02  | Não Implementado |
| RF30 | Adicionar novas informações sobre perturbação da vizinhança| [IP21](https://requisitos-de-software.github.io/2024.1-Sinesp_Cidadao/elicitacao/tecnicas/Introspeccao/)|  EP03 , TM02 , HU30 , UC05 , LX13, LX05  | Não Implementado |
| RF31 | Acesso a mapa da região| [IP22](https://requisitos-de-software.github.io/2024.1-Sinesp_Cidadao/elicitacao/tecnicas/Introspeccao/)|  EP04 , TM03 , 	HU31 , LX09   | Não Implementado |
| RF32 | Fornecer feedback de periculosidade de áreas no mapa | [IP23](https://requisitos-de-software.github.io/2024.1-Sinesp_Cidadao/elicitacao/tecnicas/Introspeccao/)| EP04 , TM03 , HU32 , LX09, LX02   |Não Implementado |
| RF33 | Visualizar perfil| [AIU1](https://requisitos-de-software.github.io/2024.1-Sinesp_Cidadao/elicitacao/tecnicas/AnaliseDaInterface/)|  EP04 , TM03 , HU34, CN01, CN02 , CN03 CN04 , CN05, LX01, LX02  | Implementado |
| RF34 | Usar funcionalidades sem o cadastro do Gov| [ENT12](https://requisitos-de-software.github.io/2024.1-Sinesp_Cidadao/elicitacao/tecnicas/Entrevista/)| EP04 , TM03, HU38, LX02  | Não Implementado |
| RF35 | Editar perfil Gov| [AIU29](https://requisitos-de-software.github.io/2024.1-Sinesp_Cidadao/elicitacao/tecnicas/AnaliseDaInterface/)|  EP04 , TM01 ,CN01, CN02 , CN03 CN04 , CN05,  HU39 , LX01, LX06 | Implementado |
| RF36 | Buscar Por Pessoa Desaparecida| [DOC3](https://requisitos-de-software.github.io/2024.1-Sinesp_Cidadao/elicitacao/tecnicas/AnaliseDeDocumento/)|  EP02, TM01, HU04, UC02,CN01, CN02 , CN03 CN04 , CN05, LX10, LX13  | Implementado |
| RF37 | Cadastrar o próprio veículo| [DOC11](https://requisitos-de-software.github.io/2024.1-Sinesp_Cidadao/elicitacao/tecnicas/AnaliseDeDocumento/)|  EP03, 	TM01,CN01, CN02 , CN03 CN04 , CN05 , LX02, LX05  | Implementado |
| RF38 | Registrar Furto ou Roubo de veículo| [DOC12](https://requisitos-de-software.github.io/2024.1-Sinesp_Cidadao/elicitacao/tecnicas/AnaliseDeDocumento/)|   EP03, 	TM01,UC05 ,CN01, CN02 , CN03 CN04 , CN05 , LX14  | Implementado |
| RF39 | Inserir foto do desaparecido| [DOC13](https://requisitos-de-software.github.io/2024.1-Sinesp_Cidadao/elicitacao/tecnicas/AnaliseDeDocumento/)|  EP03 , TM01,HU37,CN01, CN02 , CN03 CN04 , CN05, UC02, LX05  | Implementado |
| RF40 | Inserir localização do desaparecido|  [DOC14](https://requisitos-de-software.github.io/2024.1-Sinesp_Cidadao/elicitacao/tecnicas/AnaliseDeDocumento/)|  EP03, TM01 ,CN01, CN02 , CN03 CN04 , CN05,LX09 | Implementado |
| RF40 | Inserir localização do desaparecido|  [DOC14](https://requisitos-de-software.github.io/2024.1-Sinesp_Cidadao/elicitacao/tecnicas/AnaliseDeDocumento/)|  EP03, TM01 ,CN01, CN02 , CN03 CN04 , CN05,LX09 | Implementado |
| RF40 | Inserir localização do desaparecido|  [DOC14](https://requisitos-de-software.github.io/2024.1-Sinesp_Cidadao/elicitacao/tecnicas/AnaliseDeDocumento/)|  EP03, TM01 ,CN01, CN02 , CN03 CN04 , CN05,LX09 | Implementado |
| RF40 | Inserir localização do desaparecido|  [DOC14](https://requisitos-de-software.github.io/2024.1-Sinesp_Cidadao/elicitacao/tecnicas/AnaliseDeDocumento/)|  EP03, TM01 ,CN01, CN02 , CN03 CN04 , CN05,LX09 | Implementado |
| RF40 | Inserir localização do desaparecido|  [DOC14](https://requisitos-de-software.github.io/2024.1-Sinesp_Cidadao/elicitacao/tecnicas/AnaliseDeDocumento/)|  EP03, TM01 ,CN01, CN02 , CN03 CN04 , CN05,LX09 | Implementado |
| RF40 | Inserir localização do desaparecido|  [DOC14](https://requisitos-de-software.github.io/2024.1-Sinesp_Cidadao/elicitacao/tecnicas/AnaliseDeDocumento/)|  EP03, TM01 ,CN01, CN02 , CN03 CN04 , CN05,LX09 | Implementado |
| RF40 | Inserir localização do desaparecido|  [DOC14](https://requisitos-de-software.github.io/2024.1-Sinesp_Cidadao/elicitacao/tecnicas/AnaliseDeDocumento/)|  EP03, TM01 ,CN01, CN02 , CN03 CN04 , CN05,LX09 | Implementado |
| RF40 | Inserir localização do desaparecido|  [DOC14](https://requisitos-de-software.github.io/2024.1-Sinesp_Cidadao/elicitacao/tecnicas/AnaliseDeDocumento/)|  EP03, TM01 ,CN01, CN02 , CN03 CN04 , CN05,LX09 | Implementado |
| RNF01 |Rápida disponibilização de informações| [AIU27](https://requisitos-de-software.github.io/2024.1-Sinesp_Cidadao/elicitacao/tecnicas/AnaliseDaInterface/), [AP1](https://requisitos-de-software.github.io/2024.1-Sinesp_Cidadao/elicitacao/tecnicas/AnaliseDeProtocolo/), [ENT1](https://requisitos-de-software.github.io/2024.1-Sinesp_Cidadao/elicitacao/tecnicas/Entrevista/), [IP27](https://requisitos-de-software.github.io/2024.1-Sinesp_Cidadao/elicitacao/tecnicas/Introspeccao/)|  EP04, TM03 e HU14 | Implementado |
| RNF02 |  Sigilo relativo de informações|   [AIU26](https://requisitos-de-software.github.io/2024.1-Sinesp_Cidadao/elicitacao/tecnicas/AnaliseDaInterface/) , [IP26](https://requisitos-de-software.github.io/2024.1-Sinesp_Cidadao/elicitacao/tecnicas/Introspeccao/)|  EP04, TM03 e HU15 | Implementado |
| RNF03 | Banco de dados ser constantemente atualizado|   [AP4](https://requisitos-de-software.github.io/2024.1-Sinesp_Cidadao/elicitacao/tecnicas/AnaliseDeProtocolo/), [IP25](https://requisitos-de-software.github.io/2024.1-Sinesp_Cidadao/elicitacao/tecnicas/Introspeccao/), [STO3](https://requisitos-de-software.github.io/2024.1-Sinesp_Cidadao/elicitacao/tecnicas/storytelling/)|  EP04, TM03 e HU40|  Não Implementado |






## Referência Bibliografia

> - POHL, Klaus; RUPP, Chris. Requirements Engineering Fundamentals: A Study Guide for the Certified Professional for Requirements Engineering Exam.
> - Slides da Aula 26 da Professora Milene Serrano e do Professor Maurício Serrano.

## Histórico de Versão

|Versão|Data|Descrição|Autor|Revisor|
|:----:|----|---------|-----|:-------:|
|`1.0`| 22/06/2024 | Criação do documento |[Christian Hirsch Santos](https://github.com/crstyhs)  | |
