# Backward-From

## Introdução
## Metodologia

Os principais elos de rastreabilidade são:
> - Satisfação: classe origem tem dependência de satisfação com a classe destino.
> - Recurso: classe origem tem dependência de recurso com a classe destino.
> - Responsabilidade: registra a participação, responsabilidade e ação de pessoas sobre artefatos.
> - Representação: captura a representação ou modelagem dos requisitos em outras linguagens.
> - Alocado: classe origem está relacionada à classe destino, que representa um subsistema.
> - Agregação: indica “composição” de elementos.

**Legendas:**

> - RF: Requisito Funcional
> - RNF: Requisito Não Funcional
> - ENT: Entrevista
> - IP: Introspecção
> - STO: Storytelling
> - AP: Analise de protocolo
> - AIU: Analise de Interface
> - DOC: Analise de documento

**Tabela 1** - Requisitos funcionais elicitados

|ID| Elicitação | Origem | Status |
| ---- | ---- |---- |---- |
| RF01 | Logar pelo Gov | AIU2 , IP, DOC10| Implementado|
| RF02 | Buscar por veículo | AIU4, IP4| Implementado|
| RF03 | Informar dados do veículo | AIU5, IP5, DOC1| Implementado|
| RF04 | Adicionar carro como roubado | AIU6, IP6 | Implementado|
| RF05 | Listar pessoas desaparecidas| AIU9, IP9| Implementado|
| RF06 | Vincular ao desaparecido | AIU11, IP11| Implementado|
| RF07 | Vincular ao carro | AIU12, IP12| Implementado|
| RF08 | Buscar por mandados de prisão | AIU13, IP13, DOC2| Implementado|
| RF09 | Fornecer informações sobre mandados de prisão | AIU14, IP14, DOC2| Implementado|
| RF10 | Buscar por procurados | AIU16,  IP16, DOC4| Implementado|
| RF11 | Fornecer informações sobre procurados |AIU17, IP17| Implementado|
| RF12 | Sair do aplicativo | AIU19| Implementado|
| RF13 | Anunciar perturbação da vizinhança | AIU20, IP20| Implementado|
| RF14 | Ler texto para deficientes visuais | IP1| Não Implementado|
| RF15 | Disponibilizar restrição |AP2, ENT2| Implementado|
| RF16 | Disponibilizar informação das características do veículo | RF| Implementado|
| RF17 | Disponibilizar informação do tipo de veículo | AP3, ENT3, STO2| Não Implementado|
| RF18 | Disponibilizar diversas opções de denúncia | AP5, ENT5, DOC5, DOC6, DOC7, DOC8, DOC9| Implementado|
| RF19 | Tutorial de uso do aplicativo | AP7, ENT7| Não Implementado|
| RF20 | Disponibilização de fotos do desaparecido | AP8, ENT8| Não Implementado|
| RF21 | Disponibilização de informações detalhadas do desaparecido | RF| Não Implementado|
| RF22 | Ligar para a polícia | AIU7, IP7| Implementado|
| RF23 | Visualizar vínculos |AIU8| Implementado|
| RF24 | Requisitar ajuda | AIU18, | Implementado|
| RF25 | Retornar ao início | AIU21, | Implementado|
| RF26 | Salvar histórico de busca | AIU22, IP15| Implementado|
| RF27 | Disponibilizar filtro de pesquisa | AIU23| Implementado|
| RF28 | Possibilitar compartilhamento das informações de placa | AIU25 | Implementado|
| RF29 | Notificar sobre atualizações sobre vínculo | IP8| Não Implementado|
| RF30 | Adicionar novas informações sobre perturbação da vizinhança | IP21| Não Implementado|
| RF31 | Acesso a mapa da região | IP22| Não Implementado|
| RF32 | Fornecer feedback de periculosidade de áreas no mapa | IP23| Não Implementado|
| RF33 | visualizar perfil  |AIU1| Implementado|
| RF31 | Visualizar informações institucionais |AIU15| Implementado|
| RF32 | Tirar foto | IP18| Não Implementado|
| RF33 | Comparar foto com desaparecido, procurado ou mandado | IP19| Não Implementado|
| RF34 | Usar funcionalidades sem o cadastro do Gov | ENT12| Não Implementado|
| RF35 | Editar perfil Gov |AIU29|Implementado|
| RF36 | Buscar Por Pessoa Desaparecida |DOC3|Implementado|
| RF37 | Cadastrar o próprio veículo |DOC11|Implementado|
| RF38 | Registrar Furto ou Roubo de veículo |DOC12|Implementado|
| RF39 | Inserir foto do desaparecido | DOC13|Implementado|
| RF40 | Inserir localização do desaparecido | DOC14|Implementado|

_Autor:[Italo Bruno](https://github.com/ItaloBrunoM), [Flávio Melo](https://github.com/flavioovatsug), 2024._

**Tabela 2** - Requisitos não funcionais elicitados

| ID | Código | Elicitação | Origem | Status |
| ---- | ---- | ---- |---- |---- |
| RNF01 | Rápida disponibilização de informações | AIU27	, AP1, ENT1, IP27| Implementado|
| RNF02 | Sigilo relativo de informações | AIU26 , IP26| Implementado|
| RNF03 | Banco de dados ser constantemente atualizado | AP4, IP25, STO3| Não Implementado|
| RNF04 | Ajudar o trabalho policial e a comunidade | ENT11| Implementado|
| RNF05 | Interface simples | AIU3, IP3, STO1| Implementado|
| RNF06 | Instalação do aplicativo em diferentes sistemas | AIU28, IP28| Implementado|
| RNF07 | Aplicativo deve ser constantemente divulgado | AP6,STO4| Não Implementado|

_Autor:[Italo Bruno](https://github.com/ItaloBrunoM), [Flávio Melo](https://github.com/flavioovatsug), 2024._


## Elos

Neste segmento, abordaremos os vínculos dos requisitos identificados nas tabelas 1 e 2. De acordo com a metodologia mencionada, todos os requisitos serão categorizados com base no tipo de vínculo. No entanto, é importante observar que todos esses requisitos identificados pertencem à categoria de Desenvolvimento. Eles derivam de artefatos criados durante o processo de desenvolvimento do trabalho, sem qualquer relação com a organização ou a gestão do projeto. A partir desses requisitos, compilamos a tabela 3, que apresenta todos os vínculos (elos) envolvidos.


**Tabela 3** - Elos funcionais

| ID | Requisito  | Tipo de Elo |
| :---: | :---: | :---: |
| ELO01| RF01 / AIU2, IP, DOC10 | **Recurso:** [AIU2](LINK_PLACEHOLDER), [IP](LINK_PLACEHOLDER), [DOC10](LINK_PLACEHOLDER) |
| ELO02| RF02 / AIU4, IP4 | **Recurso:** [AIU4](LINK_PLACEHOLDER), [IP4](LINK_PLACEHOLDER) |
| ELO03| RF03 / AIU5, IP5, DOC1 | **Recurso:** [AIU5](LINK_PLACEHOLDER), [IP5](LINK_PLACEHOLDER), [DOC1](LINK_PLACEHOLDER) |
| ELO04| RF04 / AIU6, IP6 | **Recurso:** [AIU6](LINK_PLACEHOLDER), [IP6](LINK_PLACEHOLDER) |
| ELO05| RF05 / AIU9, IP9 | **Recurso:** [AIU9](LINK_PLACEHOLDER), [IP9](LINK_PLACEHOLDER) |
| ELO06| RF06 / AIU11, IP11 | **Recurso:** [AIU11](LINK_PLACEHOLDER), [IP11](LINK_PLACEHOLDER) |
| ELO07| RF07 / AIU12, IP12 | **Recurso:** [AIU12](LINK_PLACEHOLDER), [IP12](LINK_PLACEHOLDER) |
| ELO08| RF08 / AIU13, IP13, DOC2 | **Recurso:** [AIU13](LINK_PLACEHOLDER), [IP13](LINK_PLACEHOLDER), [DOC2](LINK_PLACEHOLDER) |
| ELO09| RF09 / AIU14, IP14, DOC2 | **Recurso:** [AIU14](LINK_PLACEHOLDER), [IP14](LINK_PLACEHOLDER), [DOC2](LINK_PLACEHOLDER) |
| ELO10| RF10 / AIU16, IP16, DOC4 | **Recurso:** [AIU16](LINK_PLACEHOLDER), [IP16](LINK_PLACEHOLDER), [DOC4](LINK_PLACEHOLDER) |
| ELO11| RF11 / AIU17, IP17 | **Recurso:** [AIU17](LINK_PLACEHOLDER), [IP17](LINK_PLACEHOLDER) |
| ELO12| RF12 / AIU19 | **Recurso:** [AIU19](LINK_PLACEHOLDER) |
| ELO13| RF13 / AIU20, IP20 | **Recurso:** [AIU20](LINK_PLACEHOLDER), [IP20](LINK_PLACEHOLDER) |
| ELO14| RF14 / IP1 | **Recurso:** [IP1](LINK_PLACEHOLDER) |
| ELO15| RF15 / AP2, ENT2 | **Recurso:** [AP2](LINK_PLACEHOLDER), [ENT2](LINK_PLACEHOLDER) |
| ELO16| RF16 / RF | **Recurso:** [RF](LINK_PLACEHOLDER) |
| ELO17| RF17 / AP3, ENT3, STO2 | **Recurso:** [AP3](LINK_PLACEHOLDER), [ENT3](LINK_PLACEHOLDER), [STO2](LINK_PLACEHOLDER) |
| ELO18| RF18 / AP5, ENT5, DOC5, DOC6, DOC7, DOC8, DOC9 | **Recurso:** [AP5](LINK_PLACEHOLDER), [ENT5](LINK_PLACEHOLDER), [DOC5](LINK_PLACEHOLDER), [DOC6](LINK_PLACEHOLDER), [DOC7](LINK_PLACEHOLDER), [DOC8](LINK_PLACEHOLDER), [DOC9](LINK_PLACEHOLDER) |
| ELO19| RF19 / AP7, ENT7 | **Recurso:** [AP7](LINK_PLACEHOLDER), [ENT7](LINK_PLACEHOLDER) |
| ELO20| RF20 / AP8, ENT8 | **Recurso:** [AP8](LINK_PLACEHOLDER), [ENT8](LINK_PLACEHOLDER) |
| ELO21| RF21 / RF | **Recurso:** [RF](LINK_PLACEHOLDER) |
| ELO22| RF22 / AIU7, IP7 | **Recurso:** [AIU7](LINK_PLACEHOLDER), [IP7](LINK_PLACEHOLDER) |
| ELO23| RF23 / AIU8 | **Recurso:** [AIU8](LINK_PLACEHOLDER) |
| ELO24| RF24 / AIU18 | **Recurso:** [AIU18](LINK_PLACEHOLDER) |
| ELO25| RF25 / AIU21 | **Recurso:** [AIU21](LINK_PLACEHOLDER) |
| ELO26| RF26 / AIU22, IP15 | **Recurso:** [AIU22](LINK_PLACEHOLDER), [IP15](LINK_PLACEHOLDER) |
| ELO27| RF27 / AIU23 | **Recurso:** [AIU23](LINK_PLACEHOLDER) |
| ELO28| RF28 / AIU25 | **Recurso:** [AIU25](LINK_PLACEHOLDER) |
| ELO29| RF29 / IP8 | **Recurso:** [IP8](LINK_PLACEHOLDER) |
| ELO30| RF30 / IP21 | **Recurso:** [IP21](LINK_PLACEHOLDER) |
| ELO31| RF31 / IP22 | **Recurso:** [IP22](LINK_PLACEHOLDER) |
| ELO32| RF32 / IP23 | **Recurso:** [IP23](LINK_PLACEHOLDER) |
| ELO33| RF33 / AIU1 | **Recurso:** [AIU1](LINK_PLACEHOLDER) |
| ELO34| RF34 / ENT12 | **Recurso:** [ENT12](LINK_PLACEHOLDER) |
| ELO35| RF35 / AIU29 | **Recurso:** [AIU29](LINK_PLACEHOLDER) |
| ELO36| RF36 / DOC3 | **Recurso:** [DOC3](LINK_PLACEHOLDER) |
| ELO37| RF37 / DOC11 | **Recurso:** [DOC11](LINK_PLACEHOLDER) |
| ELO38| RF38 / DOC12 | **Recurso:** [DOC12](LINK_PLACEHOLDER) |
| ELO39| RF39 / DOC13 | **Recurso:** [DOC13](LINK_PLACEHOLDER) |
| ELO40| RF40 / DOC14 | **Recurso:** [DOC14](LINK_PLACEHOLDER) |

_Autor:[Italo Bruno](https://github.com/ItaloBrunoM), [Flávio Melo](https://github.com/flavioovatsug), 2024._

**Tabela 4** - Elos não funcionais

| ID   | Requisito | Tipo de Elo|
| :---: | :---: | :---: |
| ELO41| RNF01 / AIU27, AP1, ENT1, IP27 | **Recurso:** [AIU27](LINK_PLACEHOLDER), [AP1](LINK_PLACEHOLDER), [ENT1](LINK_PLACEHOLDER), [IP27](LINK_PLACEHOLDER) |
| ELO42| RNF02 / AIU26, IP26 | **Recurso:** [AIU26](LINK_PLACEHOLDER), [IP26](LINK_PLACEHOLDER) |
| ELO43| RNF03 / AP4, IP25, STO3 | **Recurso:** [AP4](LINK_PLACEHOLDER), [IP25](LINK_PLACEHOLDER), [STO3](LINK_PLACEHOLDER) |
| ELO44| RNF04 / ENT11 | **Recurso:** [ENT11](LINK_PLACEHOLDER) |
| ELO45| RNF05 / AIU3, IP3, STO1 | **Recurso:** [AIU3](LINK_PLACEHOLDER), [IP3](LINK_PLACEHOLDER), [STO1](LINK_PLACEHOLDER) |
| ELO46| RNF06 / AIU28, IP28 | **Recurso:** [AIU28](LINK_PLACEHOLDER), [IP28](LINK_PLACEHOLDER) |
| ELO47| RNF07 / AP6, STO4 | **Recurso:** [AP6](LINK_PLACEHOLDER), [STO4](LINK_PLACEHOLDER) |

_Autor:[Italo Bruno](https://github.com/ItaloBrunoM), [Flávio Melo](https://github.com/flavioovatsug), 2024._


## Conclusão

Considerando o Meta-modelo de Toranzo como referência, este documento apresenta 30 elos de rastreabilidade que permitem avaliar a qualidade e a coerência dos requisitos elicitados para o projeto do aplicativo do Economia-Df. Esses elos abrangem as diferentes dimensões e níveis de abstração dos requisitos, bem como as relações entre eles. Assim, é possível verificar se os requisitos atendem às necessidades e expectativas dos stakeholders, se são consistentes e completos, e se estão alinhados com os objetivos do projeto.


## Referência Bibliografia

> POHL, Klaus; RUPP, Chris. Requirements Engineering Fundamentals: A Study Guide for the Certified Professional for Requirements Engineering Exam.

> Slides da Aula 26 da Professora Milene Serrano e do Professor Maurício Serrano.

## Histórico de Versões
|Versão|Data|Descrição|Autor|Revisor|
|:----:|----|---------|-----|:-------:|
|`1.0`| 14/06/2024 |Criação do documento|[Flávio Melo](https://github.com/flavioovatsug) e [Italo Bruno](https://github.com/Italobrunom) | |
