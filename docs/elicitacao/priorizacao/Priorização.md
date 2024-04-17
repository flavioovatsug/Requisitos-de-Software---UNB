# Priorização

## Introdução

A priorização em requisitos de software é crucial para focarmos nos aspectos mais importantes do projeto. Envolve identificar e classificar os requisitos com base em valor para o negócio, impacto nos objetivos e viabilidade técnica. 
 
Esse documento vai armazenar as priotizações do aplicativo Sinest Cindadão. E para tanto, optamos por utilizar a metodologia **MOSCOW** (Must Have, Should Have, Could Have, Won't Have), onde **Must Have** (deve ter) são requisitos essenciais e indispensáveis para o projeto, **Should Have** (deveria ter) são importantes, mas podem ser adiados, **Could Have** (pode ter) são desejáveis mas não tão essesnciais, e **Won't Have** são requisitos que não devem ser considerados no escopo do projeto.

Abaixo está presente todos os dados que obtivemos após a priotização

### Must Have

- Logar pelo Gov (RF)
- Buscar por veículo (RF)
- Informar dados do veículo (RF)
- Adicionar carro como roubado (RF)
- Listar pessoas desaparecidas (RF)
- Fornecer informações gerais sobre desaparecidos (RF)
- Vincular ao desaparecido (RF)
- Vincular ao carro (RF)
- Buscar por mandados (RF)
- Fornecer informações sobre mandados (RF)
- Buscar por procurados (RF)
- Fornecer informações sobre procurados (RF)
- Sair do aplicativo (RF)
- Anunciar perturbação da vizinhança (RF)
- Rápida disponibilização de informações (RNF)
- Sigilo relativo de informações (RNF)

### Should Have

- Interface simples (RNF)
- Ligar para a polícia (RF)
- Visualizar vínculos (RF)
- Requisitar ajuda (RF)
- Retornar ao início (RF)
- Salvar histórico de busca (RF)
- Disponibilizar filtro de pesquisa (RF)
- Possibilitar compartilhamento das informações de placa (RF)
- Instalação do aplicativo em diferentes sistemas (RNF)

### Could Have

- Visualizar perfil (RF)
- Visualizar informações institucionais (RF)
- Comparar foto com desaparecido, procurado ou mandado (RF)
- Usar funcionalidades sem o cadastro do Gov (RF)

### Won't Have

- Editar perfil Gov (RF)

# **100$**
O termo **100$** refere-se à técnica de estimativa utilizada em projetos de software, onde cada funcionalidade ou requisito é avaliado com uma unidade relativa de esforço ou complexidade, como **$100**. Isso ajuda as equipes a priorizar e planejar o trabalho com base na percepção de complexidade de cada item, facilitando a gestão de projetos e a alocação de recursos de forma mais eficiente.  
No nosso caso, escolhemos analisar e discutir os 100$ disponíveis para o grupo como um todo, e assim atribuímos valores às funcionalidades com base na importância que atribuímos a cada uma.


| Funcionalidade | Tipo | Preço |
| --------------------------- | ---- | ---------- |
| Logar pelo Gov | RF | 1,50$ |
| Buscar por veículo | RF | 3,55$ |
| Informar dados do veículo | RF | 3,55$ |
| Adicionar carro como roubado | RF | 1,75$ |
| Listar pessoas desaparecidas | RF | 3,55$ |
| Fornecer informações gerais sobre desaparecidos | RF | 1,00$ |
| Vincular ao desaparecido | RF | 1,50$ |
| Vincular ao carro | RF | 1,50$ |
| Buscar por mandados | RF | 3,55$ |
| Fornecer informações sobre mandados | RF | 1,75$ |
| Buscar por procurados | RF | 3,55$ |
| Fornecer informações sobre procurados | RF | 1,75$ |
| Sair do aplicativo | RF | 1,25$ |
| Anunciar perturbação da vizinhança | RF | 1,75$ |
| Rápida disponibilização de informações | RNF | 3,55$ |
| Sigilo relativo de informações | RNF | 3,55$ |
| Ler texto para deficientes visuais | RF | 1,75$ (Não Implementado) |
| Constante atualização de informações | RNF | 3,55$ (Não Implementado) |
| Disponibilizar restrição sem erros | RF | 3,55$ (Não Implementado) |
| Disponibilizar informação das características do veículo | RF | 1,75$ |
| Disponibilizar informação do tipo de veículo | RF | 1,50$ (Não Implementado) |
| Banco de dados ser constantemente atualizado | RNF | 3,55$ |
| Disponibilizar diversas opções de denúncia | RF | 1,75$ (Implementado) |
| Tutorial de uso do aplicativo | RF | 1,00$ (Implementado) |
| Disponibilização de fotos do desaparecido | RF | 3,55$ (Não Implementado) |
| Disponibilização de informações detalhadas do desaparecido | RF | 3,55$ (Não Implementado) |
| Ajudar o trabalho policial e a comunidade | RNF | 3,55$ (Implementado) |
| Interface simples | RNF | 3,55$ |
| Ligar para a polícia | RF | 1,00$ |
| Visualizar vínculos | RF | 1,50$ |
| Requisitar ajuda | RF | 1,00$ |
| Retornar ao início | RF | 1,00$ |
| Salvar histórico de busca | RF | 1,75$ |
| Disponibilizar filtro de pesquisa | RF | 1,50$ |
| Possibilitar compartilhamento das informações de placa | RF | 1,25$ |
| Instalação do aplicativo em diferentes sistemas | RNF | 1,75$ |
| Notificar sobre atualizações sobre vínculo | RF | 3,55$ (Não Implementado) |
| Adicionar novas informações sobre perturbação da vizinhança | RF | 1,50$ (Implementado) |
| Acesso a mapa da região | RF | 1,75$ (Não Implementado) |
| Fornecer feedback de periculosidade de áreas no mapa | RF | 1,75$ (Implementado) |
| Aplicativo deve ser constantemente divulgado | RNF | 1,25$ (Não Implementado) |
| Visualizar perfil | RF | 1,00$ |
| Visualizar informações institucionais | RF | 1,50$ |
| Tirar foto | RF | 1,00$ (Não Implementado) |
| Comparar foto com desaparecido, procurado ou mandado | RF | 3,55$ (Não Implementado) |
| Usar funcionalidades sem o cadastro do Gov | RF | 1,50$ (Não Implementado) |
| Editar perfil Gov | RF | 0,95$ |
| **Total** | | **100$** |

##  Histórico de versões

| Versão | Data   | Descrição | Autor(es) | Revisor(es)     |
| ------ | ---------- | ---------------- | ------------------ | ----------- |
| 1.0    | 16/05 |Construção da documentação de priotização |[Flávio Melo](https://github.com/flavioovatsug)| | 