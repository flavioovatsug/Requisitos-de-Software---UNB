# Especificação Suplementar

## Introdução

A Especificação Suplementar é um documento em linguagem natural que descreve os requisitos adicionais de um sistema, complementando os casos de uso que capturam os requisitos funcionais. Ela aborda aspectos não funcionais, como requisitos legais e de regulamentação, padrões de aplicativos, atributos de qualidade (como segurança e desempenho), confiabilidade, usabilidade, suportabilidade, e outros requisitos técnicos e operacionais.

## Metodologia

Iremos utilizar o FURPS+, que é uma metodologia para categorizar os requisitos de um sistema de software, garantindo uma abordagem abrangente. O acrônimo representa Funcionalidade (as capacidades específicas do sistema), Usabilidade (facilidade de uso e experiência do usuário), Confiabilidade (disponibilidade e tolerância a falhas), Desempenho (eficiência e tempo de resposta), e Suportabilidade (facilidade de manutenção e suporte). Já o "+" abrange requisitos não-funcionais (Requisitos de design, Requisitos de implementação, Requisitos de interface e Requisitos físicos).

## Funcionalidade
...

## Usabilidade

Usabilidade refere-se à facilidade com que os usuários podem interagir com o sistema. Isso inclui a intuitividade da interface do usuário, a eficiência e eficácia com que os usuários podem completar tarefas, a curva de aprendizado, e a satisfação geral dos usuários ao utilizar o sistema. Usabilidade é crucial para garantir que o sistema não só funcione corretamente, mas também seja acessível e agradável para os seus usuários.

Na tabela 1, é possível os requisitos identificados para Usabilidade.

<font><p style="text-align: center">**Tabela 1** Usabilidade.</p></font>

<center>

| ID    | Descrição                                                                                                                                |
| ----- | ---------------------------------------------------------------------------------------------------------------------------------------- |
| USA01 | O aplicativo deve apresentar todas as funcionalidades que o app fornece de maneira clara e objetiva.                          |                                                                 |
| USA02 | O aplicativo deve possuir caminhos curtos para assim ser permitindo que os usuários realizem suas consultas com no máximo 6 cliques.                                  |
| USA03 | O aplicativo deve possibilitar que os usuários desfaçam ações sempre que possível, oferecendo um botão de "voltar" sempre que possível.  |
| USA04 | O aplicativo deve assegurar um design e comportamento uniformes, aplicando cores, fontes e ícones de forma consistente em todas as interfaces.                                                                          |

</center>

<font size="3"><p style="text-align: center">Fonte: [Flávio Melo](https://github.com/flavioovatsug).</p></font>

## Confiabilidade

Confiabilidade refere-se à capacidade do sistema de funcionar corretamente e sem falhas, garantindo alta disponibilidade e consistência no desempenho. Isso inclui aspectos como tolerância a falhas, tempo de atividade (uptime), integridade dos dados e recuperação de erros, assegurando que o sistema seja confiável e previsível para os usuários.

Na tabela 2, é possível os requisitos identificados para Confiabilidade.

<font><p style="text-align: center">**Tabela 2** Confiabilidade.</p></font>

<center>

| ID    | Descrição                                                                                                                         |
| ----- | --------------------------------------------------------------------------------------------------------------------------------- |
| CON01 | O aplicativo deve funcionar durante todos os dias da semana 24 horas por dia.                                                                 |
| CON02 | As atualizações de software e manutenções devem ser realizadas fora dos períodos de maior uso do aplicativo, como durante a noite, com notificação prévia aos usuários.                                          |
| CON03 | O aplicativo deve possuir uma interface que permita aos usuários resolver problemas em até três interações simples, como cliques ou toques.                                   |
| CON04 | O aplicativo deve ser distribuído entre múltiplos servidores.                                                                            |

</center>

<font size="3"><p style="text-align: center">Fonte: [Flávio Melo](https://github.com/flavioovatsug).</p></font>

## Desempenho

Desempenho refere-se à eficiência com que o sistema executa suas funções. Isso inclui tempo de resposta, capacidade de processamento, utilização de recursos, e escalabilidade, garantindo que o sistema opere de maneira rápida e eficiente mesmo sob condições de carga elevada.

Na tabela 3, é possível os requisitos identificados para Desempenho.

<font><p style="text-align: center">**Tabela 3** - Desempenho.</p></font>

| ID    | Descrição                                                                                          |
| ----- | -------------------------------------------------------------------------------------------------- |
| DES03 | O aplicativo não deve demorar mais que 1 segundo para fazer uma consulta                                 |
| DES02 | O aplicativo não deve ter um tempo de resposta maior que 300ms.                                      |
| DES04 | O aplicativo deve oferecer uma experiência de usuário suave, com transições rápidas e uma organização intuitiva dos menus. |

<font size="3"><p style="text-align: center">Fonte: [Flávio Melo](https://github.com/flavioovatsug).</p></font>

## Suportabilidade

Suportabilidade refere-se à facilidade com que o sistema pode ser mantido, atualizado e corrigido. Isso inclui a capacidade de diagnosticar problemas, realizar manutenções, aplicar atualizações de software, e a disponibilidade de documentação e ferramentas para suporte técnico, garantindo que o sistema possa ser gerido de forma eficiente ao longo do tempo.

Na tabela 4, é possível os requisitos identificados para Suportabilidade.

<font><p style="text-align: center">**Tabela 4** - Suportabilidade</p></font>

| ID    | Descrição                                                                                                                                                                                                                                                 |
| ----- | -------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| SUP01 | O aplicativo deve ser construído de forma a simplificar a manutenção, utilizando um código limpo e organizado de.                                           |
| SUP02 | O aplicativo deve garantir que a interface do usuário se adapte de forma responsiva a uma variedade de tamanhos de tela e orientações.                                           |
| SUP03 | O aplicativo deve ser projetado com capacidade de expansão para incorporar novas funcionalidades e adaptar-se às mudanças.                                                                                   |
| SUP04 | Deve-se executar testes de integração nos dispositivos das marcas Samsung, Apple, Motorola, Xiaomi, entre outras, assegurando assim que a experiência do usuário seja consistente e sem falhas em diferentes plataformas.                                                                   |
| SUP05 | As atualizações do aplicativo devem ser enviadas e validadas de forma ágil nas lojas de aplicativos pertinentes, como a App Store da Apple e a Google Play Store. |

<font size="3"><p style="text-align: center">Fonte: [Flávio Melo](https://github.com/flavioovatsug).</p></font>

## Referências Bibliográficas

> <a id="REF1" href="#anchor_1">1.</a> SALES, André Barros. Plano de ensino da disciplina. Disponível em: <https://aprender3.unb.br/pluginfile.php/2844903/mod_resource/content/40/Plano_de_Ensino%20RE%20012024%20Turma%201.pdf>. Acesso em 17 de Maio de 2024

##  Histórico de versões

| Versão | Data   | Descrição | Autor(es) | Revisor(es)     |
| ------ | ---------- | ---------------- | ------------------ | ----------- |
| 1.0    | 17/05 | Adicionando o Moscow |[Flávio Melo](https://github.com/flavioovatsug)| [Harryson Campos](https://github.com/harry-cmartin) | 