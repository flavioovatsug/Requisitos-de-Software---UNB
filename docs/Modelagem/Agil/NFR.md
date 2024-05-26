## Introdução

O NFR Framework é uma ferramenta valiosa para representar e analisar Requisitos Não-Funcionais, com foco na implementação de resoluções específicas. Esse framework considera as características gerais do sistema e seu domínio para realizar essa tarefa. No NFR Framework, utiliza-se o modelo Softgoal Interdependency Graph (SIG) para facilitar a visualização e a interdependência dos requisitos.

### Tipos de Softgoal
Existem três categorias de softgoals conhecidas como: Softgoals NFR, Softgoals de Operacionalização e Softgoals de Afirmação. Cada uma delas é explicada a seguir:

**Softgoals NFR:** representam os Requisitos Não-Funcionais e podem ser interconectados. Eles são organizados em catálogos e apresentados de forma hierárquica durante o desenvolvimento do projeto (CHUNG et al., 2000).

**Softgoals de Operacionalização:** representações de soluções de implementação destinadas a atender aos softgoals NFR ou a outros softgoals de operacionalização. Essas soluções englobam operações, processos, representações de dados, estruturação e restrições no sistema-alvo, com o objetivo de atender às necessidades indicadas pelos softgoals NFR e de operacionalização (CHUNG et al., 2000).

**Softgoals de Afirmação:** permitem que as características do domínio, como prioridades e carga de trabalho, sejam consideradas e adequadamente incorporadas ao processo de tomada de decisão. Eles servem como justificativas para apoiar ou contestar a forma como os softgoals são priorizados, refinados e os componentes são selecionados. Os softgoals de afirmação oferecem razões para as decisões de desenvolvimento, tornando mais fácil a revisão, a justificação e a modificação do sistema, bem como a melhoria da rastreabilidade (CHUNG et al., 2000).




<center>

![TIPOS](../../assets/NRF/tiposdesoftgoal.png)

</center>


### Interdependências

As interdependências são definições para as associações que ocorrem entre softgoals. Tais são divididas em decomposições e contribuições:

#### Decomposições

As decomposições podem ocorrer em todos os níveis de abstração: Softgoals de NFR, de Operacionalização e de Afirmação. Nas três primeiras decomposições, os softgoals são subdivididos em softgoals especificados (SILVA, 2019)<a id="anchor_1" href="#REF1">^1^</a>. Os quatro tipos estão explicitados na figura 2.

- Decomposição NFR: ajuda a dividir vicissitudes primordiais em partes menores, o que reduz as ambiguidades e facilita a priorização.
- Decomposição de Operacionalização: tem por finalidade refinar uma solução geral em soluções particulares.
- Decomposição de Afirmação: serve como afirmação ou negação de justificativas específicas do projeto.
- Decomposição de Priorização: trata-se de uma decomposição especial, na qual o softgoal é refinado em outro softgoal de mesmo tipo e tópico. No entanto, associa-se uma prioridade.



<font size="3"><p style="text-align: center"><b>Figura 2</b> - Tipos de Decomposição</p></font>

<center>

![DECOMPOSIÇÃO](../../assets/NRF/decomposicao_nrf.png)

</center>
<font size="3"><p style="text-align: center"> Fonte: (SILVA, 2019)</p></font>



#### Contribuições

Num NFR Framework, os softgoals se especializam cada vez mais. Por conseguinte, o um softgoal derivado de outro pode contribuir de forma integral ou truncada, e também de forma positiva ou negativa, para o softgoal do qual ele derivou. Portanto, listar-se-á os tipos de contribuição.

- AND: se os softgoals derivados forem satisfeitos, o softgoal primordial também será.
- OR: se algum dos softgoals derivados forem satisfeitos, o softgoal primordial também será.
- MAKE(++): um softgoal originado contribui de forma plenamente positiva, logo o softgoal original também será satisfeito.
- BREAK(--): um softgoal originado contribui de forma plenamente negativa, logo o softgoal original será negado.
- HELP(+): um softgoal originado realiza uma contribuição restritamente positiva, o que reflete da mesma forma e na mesma intensidade no softgoal primordial.
- HURT(-): um softgoal originado realiza uma contribuição restritamente negativa, o que reflete da mesma forma e na mesma intensidade no softgoal primordial.
- UNKNOWN(?): contribuição incógnita.
- EQUALS: relação direta entre as satisfações do softgoal derivado e a do primordial.
- SOME: a forma de contribuição é conhecida, no entanto, a intensidade dessa contribuição é desconhecida.

#### Propagação de Impactos

A propagação de impactos no NFR Framework  envolve a identificação das relações de dependência entre os requisitos não funcionais, bem como a análise de como uma mudança em um requisito pode afetar outros requisitos relacionados. Isso requer uma compreensão clara das interações entre os requisitos, bem como a capacidade de avaliar as prioridades e trade-offs entre eles. Ao considerar a propagação de impactos, os engenheiros de requisitos podem tomar decisões informadas sobre mudanças e gerenciar os possíveis efeitos colaterais de forma eficaz. A seguir são apresentados os tipos de softgoals de impacto e suas respectivas notações:

<font size="3"><p style="text-align: center"><b>Figura 3</b> - Tipos de Propagação</p></font>
<center>
    ![Propagação](../../assets/NRF/rotulos_nrf.png)
</center>
<font size="3"><p style="text-align: center"> Fonte: (SILVA, 2019)</p></font>


- ✓ (satisfeito): Indica que um requisito não funcional contribui positivamente para a satisfação de outro requisito.
- 𝒲+ (fracamente satisfeito): indica uma relação de impacto positiva, mas menos forte do que a notação ✓.
- X (negado): Indica que um requisito não funcional afeta negativamente outro requisito, negando ou contradizendo sua realização. 
- 𝒲- (fracamente negado): Similar à notação X, mas com uma relação de negação mais fraca. 
- e (conflitante): Indica uma relação de conflito entre requisitos não funcionais. Isso significa que os requisitos possuem características positivas e negativas.
- u (indeterminado): Uma relação indeterminada ou desconhecida entre requisitos não funcionais. Isso ocorre quando não há informações suficientes para determinar o impacto de um requisito em outro.




## NFR 01 - Usabilidade

<center>

<b>Tabela 1</b> - Cartão de Especificação 1

| Tópico | Informação |
|------------| ------------|
| Descrição | Usabilidade refere-se à capacidade do sistema de entregar uma boa usabilidade para os usuários do aplicativo do "Sinesp Cidadão". |
| Justificativa| Uma boa Usabilidade é fundamental para garantir que os usuários possam utilizar o aplicativo com eficiência e garantir uma satisfação do usuário, aumentando a acessibilidade e por consequência tendo uma redução de erros.O sistema deve ser capaz de direcionar eventos ao usuário a partir de suas preferências |pessoais. Assim o usuário não irá perder tempo buscando por eventos que se adéquem ao seu perfil. |
| Origem do Requisito| Requisitos elicitados. |
| Critério de Aceitação | O sistema deve ser capaz de recomendar ao usuário eventos condizentes com suas preferências. |
| Dependências| Atividade do Usuário |
| Prioridade| Alta |
| Conflitos| Nenhum |
| História| 26/05/2024|

</center>
<font size="3"><p style="text-align: center"> Autor: [Italo Bruno](https://github.com/italobrunom)</p></font>


<font size="3"><p style="text-align: center"><b>Figura 5</b> - SIG Usabilidade</p></font>

<figure markdown markdown class="usecaseElement">

![SIG Usabilidade]()

</figure>

<font size="3"><p style="text-align: center"> Autor: [Italo Bruno](https://github.com/italobrunom)</p></font>

### Propagação dos Impactos - Usabilidade

A seguir, na Tabela 7, temos a avaliação da propagação dos impactos relativa à Figura 5.

<center>

<b>Tabela 7</b> - Impactos Usabilidade

| NFR | Impacto | Avaliador |
|-----|---------|-------|
|Usabilidade|  𝒲-| [Gabriel Campello](https://github.com/G16C)|
|Antecipação |  𝒲+|  [Gabriel Campello](https://github.com/G16C)|
|Sugestões| 𝒲-|[Gabriel Campello](https://github.com/G16C)|
|Adaptação| 𝒲-|[Gabriel Campello](https://github.com/G16C)|
|Sugestões Gerais| 𝒲+|[Gabriel Campello](https://github.com/G16C)|
|Atividade do Usuário| ✓ |[Gabriel Campello](https://github.com/G16C)|
|Acessibilidade| 𝒲+|[Gabriel Campello](https://github.com/G16C)|
|Busca| 𝒲+|[Gabriel Campello](https://github.com/G16C)|
|Filtro| 𝒲-|[Gabriel Campello](https://github.com/G16C)|
|Opções de Filtro| X|[Gabriel Campello](https://github.com/G16C)|
|Busca Multivalorada| X|[Gabriel Campello](https://github.com/G16C)|
|Informações Relevantes| ✓ |[Gabriel Campello](https://github.com/G16C)|
|Exibir Inf. do Evento| ✓ |[Gabriel Campello](https://github.com/G16C)|
|Página Única| X|[Gabriel Campello](https://github.com/G16C)|

Fonte: [Gabriel Campello](https://github.com/G16C)

</center>

## NFR 02 - Eficiência

<center>

<b>Tabela x</b> - Cartão de Especificação 2

| Tópico | Informação |
|------------| ------------|
| Descrição | Usabilidade refere-se à capacidade do sistema de entregar uma boa usabilidade para os usuários do aplicativo do "Sinesp Cidadão". |
| Justificativa| Uma boa Usabilidade é fundamental para garantir que os usuários possam utilizar o aplicativo com eficiência e garantir uma satisfação do usuário, aumentando a acessibilidade e por consequência tendo uma redução de erros.O sistema deve ser capaz de direcionar eventos ao usuário a partir de suas preferências |pessoais. Assim o usuário não irá perder tempo buscando por eventos que se adéquem ao seu perfil. |
| Origem do Requisito| Requisitos elicitados. |
| Critério de Aceitação | O sistema deve ser capaz de recomendar ao usuário eventos condizentes com suas preferências. |
| Dependências| Atividade do Usuário |
| Prioridade| Alta |
| Conflitos| Nenhum |
| História| 26/05/2024|

</center>
<font size="3"><p style="text-align: center"> Autor: [Italo Bruno](https://github.com/italobrunom)</p></font>


Os Requisitos utilizados para a confecção da Figura 6 estão presentes na Tabela 12:

- <a id="anchor_NF02" href="#NF02">RNF02</a>: infere que todas as informações de um evento devem estar contidas em uma única página, sem páginas adicionais ou pop-ups.
- <a id="anchor_NF03" href="#NF03">RNF03</a>: limita em até 5 a quantidade de páginas para realizar a compra.
- <a id="anchor_NF04" href="#NF04">RNF04</a>: limita o tempo de resposta a 200ms.


<font size="3"><p style="text-align: center"><b>Figura 6</b> - SIG Eficiência</p></font>
<figure markdown class="usecaseElement">

![SIG Eficiência](../../assets/nfr-framework/eficiencia.png){width: 300}

</figure>
<font size="3"><p style="text-align: center"> Fonte: [Arthur de Melo](https://github.com/arthurmlv)</p></font>

Legenda:

- Processar em até 200ms: refere-se ao <a id="anchor_NF04" href="#NF04">RNF04</a>, o qual limita o tempo de resposta a 200ms.
- Apresentar 5 categorias de informações: informações suficientemente relevantes para a realização de um processo.

### Requisitos Não-Funcionais - Eficiência

Na Tabela 8, estão listados os RNF presentes no NFR Famework de Eficiência:

<center>

<b>Tabela 8</b> - Requisitos Não-Funcionais 2

| RNF (Fonte) | Descrição | Classificação | Origem |
|-------------|---------|-------|-------|
| Processar em até 200ms (<a id="anchor_FE1" href="#FE1">FE1</a> e <a id="anchor_FE2" href="#FE2">FE2</a>) | O sistema deve possuir uma limitação superior do tempo de processamento de uma requisição de 200ms. | Eficiência | Tempo de Resposta e Processar Requisitos |
| Limite de 5 Páginas (<a id="anchor_FE2" href="#FE2">FE2</a>) | O sistema deve possuir uma limitação da quantidade de páginas para a realização de uma tarefa. | Eficiência | Limite de Páginas |
| Apresentar 5 categorias de informações (<a id="anchor_FE1" href="#FE1">FE1</a>) | O sistema deve exibir as informações do evento específico. | Eficiência | Apresentar Informações e Limite de 5 páginas |

Fonte: [Arthur de Melo](https://github.com/arthurmlv)

</center>

### Propagação dos Impactos - Eficiência

Na Tabela 9, está presente a avaliação da propagação dos impactos referentes à Figura 6.

<center>

<b>Tabela 9</b> - Impactos Eficiência

| NFR | Impacto | Avaliador |
|-----|---------|-------|
|Eficiência|  𝒲+| [Gabriel Campello](https://github.com/G16C)|
|Executar Apropriadamente |  𝒲+|  [Gabriel Campello](https://github.com/G16C)|
|Processar Requisitos| 𝒲+|[Gabriel Campello](https://github.com/G16C)|
|Processar Corretamente| 𝒲+|[Gabriel Campello](https://github.com/G16C)|
|Recuperar de Erros| 𝒲+|[Gabriel Campello](https://github.com/G16C)|
|Prevenção de Erros|  𝒲+|[Gabriel Campello](https://github.com/G16C)|
|Limitações| ✓|[Gabriel Campello](https://github.com/G16C)|
|Limite de Páginas| 𝒲+|[Gabriel Campello](https://github.com/G16C)|
|Apresentar Informações| ✓|[Gabriel Campello](https://github.com/G16C)|
|Apresentar 5 categorias de informações| ✓|[Gabriel Campello](https://github.com/G16C)|
|Limite de 5 Páginas| X|[Gabriel Campello](https://github.com/G16C)|
|Tempo de Resposta| ✓ |[Gabriel Campello](https://github.com/G16C)|
|Processar em até 200ms| ✓ |[Gabriel Campello](https://github.com/G16C)|


Fonte: [Gabriel Campello](https://github.com/G16C)

</center>

## NFR 03 - Segurança

<center>

<b>Tabela 1</b> - Cartão de Especificação 3

| Tópico | Informação |
|------------| ------------|
| Descrição | Usabilidade refere-se à capacidade do sistema de entregar uma boa usabilidade para os usuários do aplicativo do "Sinesp Cidadão". |
| Justificativa| Uma boa Usabilidade é fundamental para garantir que os usuários possam utilizar o aplicativo com eficiência e garantir uma satisfação do usuário, aumentando a acessibilidade e por consequência tendo uma redução de erros.O sistema deve ser capaz de direcionar eventos ao usuário a partir de suas preferências |pessoais. Assim o usuário não irá perder tempo buscando por eventos que se adéquem ao seu perfil. |
| Origem do Requisito| Requisitos elicitados. |
| Critério de Aceitação | O sistema deve ser capaz de recomendar ao usuário eventos condizentes com suas preferências. |
| Dependências| Atividade do Usuário |
| Prioridade| Alta |
| Conflitos| Nenhum |
| História| 26/05/2024|

</center>
<font size="3"><p style="text-align: center"> Autor: [Italo Bruno](https://github.com/italobrunom)</p></font>


Os Requisitos utilizados para a confecção da Figura 7 estão presentes na Tabela 12:

- <a id="anchor_NF03" href="#NF03">RNF03</a>: limita em até 5 a quantidade de páginas para realizar a compra.
- <a id="anchor_NF04" href="#NF04">RNF04</a>: limita o tempo de resposta a 200ms.

<font size="3"><p style="text-align: center"><b>Figura 7</b> - SIG Desempenho</p></font>
<figure markdown class="usecaseElement">

![SIG Desempenho](../../assets/nfr-framework/desempenhoL.png){width: 300}

</figure>
<font size="3"><p style="text-align: center"> Fonte: [Arthur de Melo](https://github.com/arthurmlv) e [Sidney Fernando](https://github.com/nando3d3)</p></font>

Legenda:

- Ordem Lógica: uma compra deve aplicar a ordem lógica observada na vida real.
- Limite de 5 páginas: refere-se ao <a id="anchor_NF03" href="#NF03">RNF03</a>, o qual limita a quantidade de páginas em até 5 para a compra.
- Velocidade: refere-se ao <a id="anchor_NF04" href="#NF04">RNF04</a>, o qual limita o tempo de resposta a 200ms.

### Requisitos Não-Funcionais - Desempenho

Na Tabela 10, estão listados os RNF presentes no NFR Famework de Desempenho :

<center>

<b>Tabela 10</b> - Requisitos Não-Funcionais 3

| RNF (Fonte) | Descrição | Classificação | Origem |
|-------------|---------|-------|-------|
| Tempo de Resposta (<a id="anchor_FE1" href="#FE1">FE1</a> e <a id="anchor_FE2" href="#FE2">FE2</a>) |  O sistema deve possuir uma limitação superior do tempo de processamento de uma requisição. | Desempenho | Desempenho |
| Infraestrutura (<a id="anchor_FE2" href="#FE2">FE2</a>) | O sistema deve possuir uma infraestrutura para processar os dados. | Desempenho | Tempo de Resposta |
| Servidores (<a id="anchor_FE2" href="#FE2">FE2</a>) | O sistema deve possuir servidores para perdurar os dados. | Desempenho | Infraestrutura |
| Manutenção em tempo real (<a id="anchor_FE1" href="#FE1">FE1</a> e <a id="anchor_FE2" href="#FE2">FE2</a>) | O sistema deve ser capaz de realizar a manutenção dos servidores e de outros aspectos da infraestrutura. | Desempenho | Servidores e Infraestrutura |

Fonte: [Arthur de Melo](https://github.com/arthurmlv)

</center>

### Propagação dos Impactos - Desempenho

Na Tabela 11, está presente a avaliação da propagação dos impactos referentes à Figura 6.

<center>

<b>Tabela 11</b> - Impactos Desempenho

| NFR | Impacto | Avaliador |
|-----|---------|-------|
|Desempenho |  🗲| [Arthur de Melo](https://github.com/arthurmlv)|
|Realizar Ações| 🗲|[Arthur de Melo](https://github.com/arthurmlv)|
|Compra| 🗲|[Arthur de Melo](https://github.com/arthurmlv)|
|Ordem Lógica| ✓|[Arthur de Melo](https://github.com/arthurmlv)|
|Processar em até 200ms|  X|[Arthur de Melo](https://github.com/arthurmlv)|
|Limite de 5 páginas| 𝒲-|[Arthur de Melo](https://github.com/arthurmlv)|
|Velocidade| 𝒲-|[Arthur de Melo](https://github.com/arthurmlv)|
|Processar Corretamente| ✓|[Arthur de Melo](https://github.com/arthurmlv)|
|Tempo de Resposta| 𝒲+|[Arthur de Melo](https://github.com/arthurmlv)|
|Infraestrutura| 𝒲+|[Arthur de Melo](https://github.com/arthurmlv)|
|Servidores| 𝒲+ |[Arthur de Melo](https://github.com/arthurmlv)|
|Manutenção em tempo real| ✓ |[Arthur de Melo](https://github.com/arthurmlv)|


Fonte: [Arthur de Melo](https://github.com/arthurmlv)

</center>

## NFR 04 - Portabilidade

<center>

<b>Tabela 1</b> - Cartão de Especificação 4

| Tópico | Informação |
|------------| ------------|
| Descrição | Usabilidade refere-se à capacidade do sistema de entregar uma boa usabilidade para os usuários do aplicativo do "Sinesp Cidadão". |
| Justificativa| Uma boa Usabilidade é fundamental para garantir que os usuários possam utilizar o aplicativo com eficiência e garantir uma satisfação do usuário, aumentando a acessibilidade e por consequência tendo uma redução de erros.O sistema deve ser capaz de direcionar eventos ao usuário a partir de suas preferências |pessoais. Assim o usuário não irá perder tempo buscando por eventos que se adéquem ao seu perfil. |
| Origem do Requisito| Requisitos elicitados. |
| Critério de Aceitação | O sistema deve ser capaz de recomendar ao usuário eventos condizentes com suas preferências. |
| Dependências| Atividade do Usuário |
| Prioridade| Alta |
| Conflitos| Nenhum |
| História| 26/05/2024|

</center>
<font size="3"><p style="text-align: center"> Autor: [Italo Bruno](https://github.com/italobrunom)</p></font>


Os Requisitos utilizados para a confecção da Figura 7 estão presentes na Tabela 12:

- <a id="anchor_NF03" href="#NF03">RNF03</a>: limita em até 5 a quantidade de páginas para realizar a compra.
- <a id="anchor_NF04" href="#NF04">RNF04</a>: limita o tempo de resposta a 200ms.

<font size="3"><p style="text-align: center"><b>Figura 7</b> - SIG Desempenho</p></font>
<figure markdown class="usecaseElement">

![SIG Desempenho](../../assets/nfr-framework/desempenhoL.png){width: 300}

</figure>
<font size="3"><p style="text-align: center"> Fonte: [Arthur de Melo](https://github.com/arthurmlv) e [Sidney Fernando](https://github.com/nando3d3)</p></font>

Legenda:

- Ordem Lógica: uma compra deve aplicar a ordem lógica observada na vida real.
- Limite de 5 páginas: refere-se ao <a id="anchor_NF03" href="#NF03">RNF03</a>, o qual limita a quantidade de páginas em até 5 para a compra.
- Velocidade: refere-se ao <a id="anchor_NF04" href="#NF04">RNF04</a>, o qual limita o tempo de resposta a 200ms.

### Requisitos Não-Funcionais - Desempenho

Na Tabela 10, estão listados os RNF presentes no NFR Famework de Desempenho :

<center>

<b>Tabela 10</b> - Requisitos Não-Funcionais 3

| RNF (Fonte) | Descrição | Classificação | Origem |
|-------------|---------|-------|-------|
| Tempo de Resposta (<a id="anchor_FE1" href="#FE1">FE1</a> e <a id="anchor_FE2" href="#FE2">FE2</a>) |  O sistema deve possuir uma limitação superior do tempo de processamento de uma requisição. | Desempenho | Desempenho |
| Infraestrutura (<a id="anchor_FE2" href="#FE2">FE2</a>) | O sistema deve possuir uma infraestrutura para processar os dados. | Desempenho | Tempo de Resposta |
| Servidores (<a id="anchor_FE2" href="#FE2">FE2</a>) | O sistema deve possuir servidores para perdurar os dados. | Desempenho | Infraestrutura |
| Manutenção em tempo real (<a id="anchor_FE1" href="#FE1">FE1</a> e <a id="anchor_FE2" href="#FE2">FE2</a>) | O sistema deve ser capaz de realizar a manutenção dos servidores e de outros aspectos da infraestrutura. | Desempenho | Servidores e Infraestrutura |

Fonte: [Arthur de Melo](https://github.com/arthurmlv)

</center>

### Propagação dos Impactos - Desempenho


<center>



</center>



## Bibliografia

> PAIM, F. R. S., CASTRO, J. F. B. Enhancing Data Warehouse Design with the NFR Framework. Centro de Informática UFPE, Recife, 2019. Disponível em: <http://wer.inf.puc-rio.br/WERpapers/artigos/artigos_WER02/paim.pdf>. 

> <a id="REF2" href="#anchor_2"></a>CHUNG, L., NIXON, B. A., YU, E., MYLOPOULOS, J. Non-functional requirementsin software engineering. Springer Science & Business Media: [S.l.], 2000. v. 5.


## Histórico de Versões
| Versão | Data | Descrição | Autor | Revisor |
| :----: | :--: | :-------: | :---: | :-----: |
| 1.0 | 25/05/2024 | Criação do documento NFR | [Italo Bruno](https://github.com/ItaloBrunoM)  |  |