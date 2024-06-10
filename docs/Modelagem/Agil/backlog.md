# Backlog

## Introdução

O backlog é uma lista estruturada de tarefas, funcionalidades ou requisitos que ainda precisam ser completados em um projeto, geralmente utilizada em metodologias ágeis como Scrum. Essa lista se divide em Product Backlog, que contém todas as funcionalidades e melhorias desejadas para o produto, e Sprint Backlog, que inclui as tarefas selecionadas para serem concluídas em um ciclo de desenvolvimento específico (sprint). A gestão do backlog é crucial para priorizar e planejar o trabalho da equipe, garantindo que os itens mais importantes sejam abordados primeiro, promovendo uma progressão do projeto de maneira eficiente e organizada.

## Metodologia

Para a produção desse artefato ,foi utilizado o documento de [Requisitos Elicitados](https://requisitos-de-software.github.io/2024.1-Sinesp_Cidadao/elicitacao/tecnicas/Requisitos_elicitados/) e houve a participação de uma Persona fazendo o papel de PO do projeto, a gravação da encenação de priorização foi feita via Teamns com a Persona Primária Rafeal valério as 13h do dia 26/05/2024 e podem ser vistos detalhes na Tabela 1. Nesse sentido,a persona priorizou as [Histórias de Usuário](Sinesp_Cidadao) elicitadas no outro documento.Concomitantemente, foi feito a divisão em Temas e épicos, que é melhor explicado a seguir.

No vídeo a seguir também pode ser visto o vídeo de priorização dos épicos e histórias de usuário:

<center>

<iframe width="560" height="315" src="https://www.youtube.com/embed/Cvb86eASWiI?si=_fY94IBdPUp1pP2R" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>

</center>

## Temas

- **Funcionalidade** : Funcionalidades que o sistema oferece ao usuário para completar um objetivo no app.
- **Ações de usuário** : Funcionalidades que o sistema possui para que o usuário consiga utilizar o próprio sistema.
- **Qualidade**: Funcionalidades que o sistema possui para melhorar a qualidade do app, e a experiênia de usúario.

## Épicos

Depois de definir os temas, eles são divididos em épicos para reduzir ainda mais a abstração das atividades a serem realizadas no projeto. Os eṕicos foram abstraidos a partir a função principal que realizam no sistema.


<center>

**Tabela 1** - Participantes da Encenação.

| **Participante**                                        | **Função**     |
| :------------------------------------------------------ | :------------- |
| <span style = "color: orange"> Rafael Valério</span>    | Entrevistado   |
|     [Flávio Melo](https://github.com/flavioovatsug)     | Desenvolvedor  |
|   [Harryson Campos](https://github.com/harry-cmartin)   | Desenvolvedor  |

</center>

A seguir na Tabela 2 pode ser visto a tabela construída com os Temas, épicos, Historia de Usuário correspondente e sua prioridade.

<center>


<div align="center">
<font size="3"><p style="text-align: center"><b>Tabela 2:</b> Tabela de backlog</p></font>
</div>

<table>
<thead>
    <tr>
        <th>Tema</th>
        <th>Épico</th>
        <th>História de usuário</th>
        <th>Prioridade</th>
    </tr>
</thead>
<tbody>
    <tr>
        <td rowspan="18"> TM01- Funcionalidade </td>
        <td rowspan="11"> EP02 - Busca </td>
        <td> HU02 - Autenticação de Usuário </td>
        <td>  Alta</td>
    </tr>
    <tr>
        <td> HU04 - Listar Pessoas Desaparecidas </td>
        <td> Alta</td>
    </tr>
    <tr>
        <td> HU05 - Fornecer Informações Gerais sobre Desaparecidos </td>
        <td> Alta </td>
    <tr>
        <td> HU08 - Buscar por Mandados </td>
        <td> Alta </td>
    </tr>
     <tr>
        <td> HU09 - Fornecer Informações sobre Mandados </td>
        <td> Alta </td>
    </tr>
     <tr>
        <td> HU10 - Buscar por Procurados </td>
        <td> Alta </td>
    </tr>
      <tr>
        <td> HU11 - Fornecer Informações sobre Procurados </td>
        <td> Alta </td>
    </tr>
      <tr>
        <td> HU18 - Disponibilização de Fotos do Desaparecido </td>
        <td> Médio </td>
    </tr>
      <tr>
        <td> HU19 - Disponibilização de Informações Detalhadas do Desaparecido </td>
        <td> Alta </td>
    </tr>
      <tr>
        <td> HU22 - Visualizar Vínculos </td>
        <td> Média </td>
    </tr>
     <tr>
        <td> HU26 - Disponibilizar Filtro de Pesquisa </td>
        <td> Alta  </td>
    </tr>
    <tr>
        <td rowspan="4"> EP03 - Cadastro </td>
        <td> HU03 - Adicionar carro como roubado </td>
        <td> Alta </td>
    </tr>
     <tr>
        <td> HU06 - Vincular ao Desaparecido </td>
        <td> Médio </td>
    </tr>
     <tr>
        <td> HU07 - Vincular ao Carro </td>
        <td> Médio </td>
    </tr>
     <tr>
        <td> HU13 - Anunciar Perturbação da Vizinhança </td>
        <td> Alta </td>
    </tr>
        <tr>
        <td rowspan="1"> EP05 - Histórico </td>
        <td> HU25 - Salvar Histórico de Busca </td>
        <td> Alta </td>
    </tr>
          <tr>
        <td rowspan="2"> EP06 - Compartilhamento </td>
        <td> HU21 - Ligar para a Polícia </td>
        <td> Médio </td>
    </tr>
     <tr>
        <td> HU27 - Possibilitar Compartilhamento das Informações de Placa </td>
        <td> Médio </td>
    </tr>
    <tr>
        <td rowspan="5"> TM02 - Ações de usuário </td>
        <td rowspan="4"> EP04 - Experiência de Usuário </td>
        <td> HU12 - Sair do App </td>
        <td> Baixo </td>
    </tr>
     <tr>
        <td>HU23 - Recuperar Senha</td>
        <td>Baixo</td>
    </tr>
    <tr>
        <td>HU24 - Alterar Senha</td>
        <td>Baixo</td>
    </tr>
    <tr>
        <td>HU28 - Instalação do app em diferentes sistemas </td>
        <td>Médio</td>
    </tr>
    <tr>
        <td rowspan="1">EP01 - Login</td>
        <td>HU01 - Autenticação de Usuário</td>
        <td>Alto</td>
    </tr>
     <tr>
        <td rowspan="6"> TM03 - Qualidade</td>
        <td rowspan="6"> EP04 - Experiência de usuário</td>
        <td>HU14 - Rápida Disponibilização de Informações </td>
        <td>Alto</td>
    </tr>
    <tr>
        <td>HU15 - Sigilo Relativo de Informações </td>
        <td>Médio</td>
    </tr>
    <tr>
        <td>HU16 - Disponibilizar Diversas Opções de Denúncia </td>
        <td>Alta</td>
    </tr>
    <tr>
        <td>HU17 - Tutorial de Uso do Aplicativo </td>
        <td>Baixo</td>
    </tr>
     <tr>
        <td>HU20 - Interface Simples </td>
        <td>Alto</td>
    </tr>
   
</tbody>
</table>



Autores: [Flávio Melo](https://github.com/flavioovatsug) e [Harryson Campos](https://github.com/harry-cmartin).

</center>



## Bibliografia


> Bourque, P., Fairley, R. E. Guide to the Software Engineering Body of Knowledge, Version 3.0. SWEBOK. IEEE Computer Society, 2014. Disponível em: http://www.computer.org/web/swebok/v3. p. 38.


> Bilheteria Digital. Backlog. REPositório da disciplina de Requisitos de Software da Universidade de Brasília, 2023.Disponível em https://requisitos-de-software.github.io/2023.1-BilheteriaDigital/modelagem/agil/backlog/.




## Histórico de Versões
| Versão | Data | Descrição | Autor | Revisor |
| :----: | :--: | :-------: | :---: | :-----: |
| 1.0 | 26/05/2024 | Criação do documento de Backlog |  [Harryson Campos Martins](https://github.com/harry-cmartin) e [Flávio Melo](https://github.com/flavioovatsug)| [Italo Bruno](https://github.com/ItaloBrunoM) |
|1.1  |27/05/2024 | Correções |[Harryson Campos Martins](https://github.com/harry-cmartin)|[Italo Bruno](https://github.com/ItaloBrunoM)|
