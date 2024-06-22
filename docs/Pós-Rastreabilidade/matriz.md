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
| RF12 | Sair do aplicativo|  [AIU19](https://requisitos-de-software.github.io/2024.1-Sinesp_Cidadao/elicitacao/tecnicas/AnaliseDaInterface/)| Implementado|
| RF13 | Anunciar perturbação da vizinhança | [AIU20](https://requisitos-de-software.github.io/2024.1-Sinesp_Cidadao/elicitacao/tecnicas/AnaliseDaInterface/), [IP20](https://requisitos-de-software.github.io/2024.1-Sinesp_Cidadao/elicitacao/tecnicas/Introspeccao/)|  EP03,TM02,HU12,UC05,CN1,2,3,4,5, e LX02   | Implementado |
| RF14 |Ler texto para deficientes visuais| [IP1](https://requisitos-de-software.github.io/2024.1-Sinesp_Cidadao/elicitacao/tecnicas/Introspeccao/)|  EP04,TM03,HU41 e LX02  | Não Implementado |
| RF15 | Disponibilizar restrição| [AP2](https://requisitos-de-software.github.io/2024.1-Sinesp_Cidadao/elicitacao/tecnicas/AnaliseDeProtocolo/), [ENT2](https://requisitos-de-software.github.io/2024.1-Sinesp_Cidadao/elicitacao/tecnicas/Entrevista/)|  EP04,TM02 e LX05   | Implementado |
| RF16 | Visualizar informações institucionais| [AIU15](https://requisitos-de-software.github.io/2024.1-Sinesp_Cidadao/elicitacao/tecnicas/AnaliseDaInterface/)|  EP04,TM01,HU35,UC04,CN1,2,3,4,5, LX01 e LX10 |Implementado |
| RF17 | Disponibilizar informação do tipo de veículo| [AP3](https://requisitos-de-software.github.io/2024.1-Sinesp_Cidadao/elicitacao/tecnicas/AnaliseDeProtocolo/), [ENT3](https://requisitos-de-software.github.io/2024.1-Sinesp_Cidadao/elicitacao/tecnicas/Entrevista/), [STO2](https://requisitos-de-software.github.io/2024.1-Sinesp_Cidadao/elicitacao/tecnicas/storytelling/)|   EP04,TM03,UO01 e LX10  | Não Implementado |
| RF18 | Disponibilizar diversas opções de denúncia|[AP5](https://requisitos-de-software.github.io/2024.1-Sinesp_Cidadao/elicitacao/tecnicas/AnaliseDeProtocolo/), [ENT5](https://requisitos-de-software.github.io/2024.1-Sinesp_Cidadao/elicitacao/tecnicas/Entrevista/), [DOC5](https://requisitos-de-software.github.io/2024.1-Sinesp_Cidadao/elicitacao/tecnicas/AnaliseDeDocumento/), [DOC6](https://requisitos-de-software.github.io/2024.1-Sinesp_Cidadao/elicitacao/tecnicas/AnaliseDeDocumento/), [DOC7](https://requisitos-de-software.github.io/2024.1-Sinesp_Cidadao/elicitacao/tecnicas/AnaliseDeDocumento/), [DOC8](https://requisitos-de-software.github.io/2024.1-Sinesp_Cidadao/elicitacao/tecnicas/AnaliseDeDocumento/), [DOC9](https://requisitos-de-software.github.io/2024.1-Sinesp_Cidadao/elicitacao/tecnicas/AnaliseDeDocumento/)|   EP04,TM03,HU16,CN1,2,3,4,5 e LX02  | Implementado |
| RF19| Tutorial de uso do aplicativo| [AP7](https://requisitos-de-software.github.io/2024.1-Sinesp_Cidadao/elicitacao/tecnicas/AnaliseDeProtocolo/), [ENT7](https://requisitos-de-software.github.io/2024.1-Sinesp_Cidadao/elicitacao/tecnicas/Entrevista/)|   EP04,TM03,HU17,LX01 e LX02  |  Não Implementado |
| RF20 | Disponibilização de fotos do desaparecido|[AP8](https://requisitos-de-software.github.io/2024.1-Sinesp_Cidadao/elicitacao/tecnicas/AnaliseDeProtocolo/), [ENT8](https://requisitos-de-software.github.io/2024.1-Sinesp_Cidadao/elicitacao/tecnicas/Entrevista/)|   EP02,TM01,HU18,LX05,LX10 e LX13   |   Não Implementado |
| RF01 | Logar pelo Gov| [artefato de origem](../elicitacao/introspeccao.md)|  [Artefato que o utiliza]()  | [Implementado ou não]() |
| RF01 | Logar pelo Gov| [artefato de origem](../elicitacao/introspeccao.md)|  [Artefato que o utiliza]()  | [Implementado ou não]() |
| RF01 | Logar pelo Gov| [artefato de origem](../elicitacao/introspeccao.md)|  [Artefato que o utiliza]()  | [Implementado ou não]() |
| RF01 | Logar pelo Gov| [artefato de origem](../elicitacao/introspeccao.md)|  [Artefato que o utiliza]()  | [Implementado ou não]() |
| RF01 | Logar pelo Gov| [artefato de origem](../elicitacao/introspeccao.md)|  [Artefato que o utiliza]()  | [Implementado ou não]() |
| RF01 | Logar pelo Gov| [artefato de origem](../elicitacao/introspeccao.md)|  [Artefato que o utiliza]()  | [Implementado ou não]() |
| RF01 | Logar pelo Gov| [artefato de origem](../elicitacao/introspeccao.md)|  [Artefato que o utiliza]()  | [Implementado ou não]() |
| RF01 | Logar pelo Gov| [artefato de origem](../elicitacao/introspeccao.md)|  [Artefato que o utiliza]()  | [Implementado ou não]() |
| RF01 | Logar pelo Gov| [artefato de origem](../elicitacao/introspeccao.md)|  [Artefato que o utiliza]()  | [Implementado ou não]() |
| RF01 | Logar pelo Gov| [artefato de origem](../elicitacao/introspeccao.md)|  [Artefato que o utiliza]()  | [Implementado ou não]() |
| RF01 | Logar pelo Gov| [artefato de origem](../elicitacao/introspeccao.md)|  [Artefato que o utiliza]()  | [Implementado ou não]() |
| RF01 | Logar pelo Gov| [artefato de origem](../elicitacao/introspeccao.md)|  [Artefato que o utiliza]()  | [Implementado ou não]() |
| RF01 | Logar pelo Gov| [artefato de origem](../elicitacao/introspeccao.md)|  [Artefato que o utiliza]()  | [Implementado ou não]() |
| RF01 | Logar pelo Gov| [artefato de origem](../elicitacao/introspeccao.md)|  [Artefato que o utiliza]()  | [Implementado ou não]() |
| RF01 | Logar pelo Gov| [artefato de origem](../elicitacao/introspeccao.md)|  [Artefato que o utiliza]()  | [Implementado ou não]() |
| RF01 | Logar pelo Gov| [artefato de origem](../elicitacao/introspeccao.md)|  [Artefato que o utiliza]()  | [Implementado ou não]() |
| RF01 | Logar pelo Gov| [artefato de origem](../elicitacao/introspeccao.md)|  [Artefato que o utiliza]()  | [Implementado ou não]() |
| RF01 | Logar pelo Gov| [artefato de origem](../elicitacao/introspeccao.md)|  [Artefato que o utiliza]()  | [Implementado ou não]() |
| RF01 | Logar pelo Gov| [artefato de origem](../elicitacao/introspeccao.md)|  [Artefato que o utiliza]()  | [Implementado ou não]() |
| RF01 | Logar pelo Gov| [artefato de origem](../elicitacao/introspeccao.md)|  [Artefato que o utiliza]()  | [Implementado ou não]() |
| RF01 | Logar pelo Gov| [artefato de origem](../elicitacao/introspeccao.md)|  [Artefato que o utiliza]()  | [Implementado ou não]() |
| RF01 | Logar pelo Gov| [artefato de origem](../elicitacao/introspeccao.md)|  [Artefato que o utiliza]()  | [Implementado ou não]() |


## Referência Bibliografia

> - POHL, Klaus; RUPP, Chris. Requirements Engineering Fundamentals: A Study Guide for the Certified Professional for Requirements Engineering Exam.
> - Slides da Aula 26 da Professora Milene Serrano e do Professor Maurício Serrano.

## Histórico de Versão

|Versão|Data|Descrição|Autor|Revisor|
|:----:|----|---------|-----|:-------:|
|`1.0`| 22/06/2024 | Criação do documento |[Christian Hirsch Santos](https://github.com/crstyhs)  | |
