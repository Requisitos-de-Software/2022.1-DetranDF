# MoSCoW
## 1. Introdução
MoSCoW é uma técnica de priorização de requisitos, que visa estabelecer um grau de prioridade para cada requisito do sistema que foi levantado, através das técnicas de elicitação. Essa priorização é útil para auxiliar o time a definir o que deve ser feito primeiro dentro do escopo do projeto.

## 2. Metodologia
Cada uma das letras em maiúsculo da sigla (M, S, C, W) faz referência a uma palavra originada do inglês, representando um tipo de categoria cada. Dessa forma, essa técnica de priorização de requisitos consiste na divisão dos requisitos levantados em 4 tipos:

- **_Must_**: requisitos de **extrema importância** e que devem obrigatoriamente estar presentes no sistema para que ele funcione.
- **_Should_**: requisitos que também são **importantes**, mas que, diferente da categoria anterior, não são considerados críticos; sua ausência não impede a entrega do produto mas agregam valor ao produto caso implementados.
- **_Could_**: requisitos que **podem ser adicionados**, mas **não são essenciais** para a entrega; possuem um impacto menor no projeto se não forem implmentados.
- **_Won't_**: requisitos que **não receberam muita importância** para a entrega dentro do prazo estipulado; por meio dessa categoria é possível evitar o crescimento desorganizado do projeto.

## 3. Priorização dos requisitos
Neste tópico serão apresentadas as categorizações de prioridade MoSCoW dos requisitos, que foram elicitados por meio das técnicas de [Introspecção](../introspeccao.md), [Questionário](../questionario.md) e [_Brainstorming_](../brainstorm.md), além de sua separação e classificação entre requisitos funcionais e não-funcionais.


#### Requisitos Funcionais

Na *Tabela 1* abaixo foram categorizados os requisitos funcionais elicitados.

| ID | Requisitos | Prioridade |
|:--:|:--:|:--:|
| RF1 |O usuário deve ser capaz de se registrar no aplicativo                            |must|
| RF2 |O usuário deve ser capaz de fazer o login na sua conta                            |must|
| RF3 |O usuário deve ser capaz de visualizar sua CNH eletrônica                         |must|
| RF4 |O usuário deve ser capaz de visualizar suas multas                                |must|
| RF5 |O usuário deve ser capaz de consultar os pontos da carteira                       |must|
| RF6 |O usuário deve ser capaz de fazer um agendamento de atendimento presencial        |must|
| RF7 |O usuário deve ser capaz de encontrar os números de contato do Detran             |should|
| RF8 |O usuário deve ser capaz de solicitar 2ª via da CNH                               |must|
| RF9 |O usuário deve ser capaz de gerar boletos para pagar suas multas                  |should|
| RF10 |Deverá ser possível acessar a habilitação	                                     |must|
| RF11 |Deverá ser possível consultar o veículo                                          |must|
| RF12 |Deverá ser possível consultar infrações                                          |must|
| RF13 |Deverá ser possível agendar atendimentos                                         |should|
| RF14 |Deve ser possível consultar informações sobre multas                               |must|
| RF15 |Deve ser possível consultar informações sobre documentos                           |must|
| RF16 |Deve ser possível realizar transferências de veículos de forma eletrônica          |could|
| RF17 |Deve ser possível consultar informações históricas sobre o veículo                 |should|
| RF18 |Deve ser possível emitir eletrônicamente o CRLV                                    |should|
| RF19 |Deve ser possível alterar o endereço do proprietário do veículo                    |should|
| RF20 |Deve ser possível emitir o ATPV                                                    |should|
| RF21 |Deve ser possível agendar vistorias veiculares                                     |could|
| RF22 |Deve ser possível emitir CNH eletrônica                                            |must|
| RF24 |Deve ser possível consultar pontuação de infrações associadas ao condutor          |shoud|
| RF23 |Deve ser possível consultar informações sobre bloqueios                            |should|
| RF24 |Deve ser possível consultar informações sobre ocorrências                          |should|
| RF25 |Deve ser possível emitir documento de nada consta                                  |could|
| RF26 |Deve ser possível consultar informações sobre processo de obtenção da habilitação  |should|
| RF27 |Deve ser possível solicitar CNH definitiva                                         |must|
| RF28 |Deve ser possível solicitar 2ª via de CNH                                          |must|
| RF29 |Deve ser possível solicitar autorização de estacionamento para idosos              |must|
| RF30 |Deve ser possível solicitar autorização de estacionamento para PCDs                |must|
| RF31 |Deve ser possível modificar endereço do proprietário da CNH                        |should|
| RF32 |Deve ser possível consultar infrações                                              |must|
| RF33 |Deve ser possível transferir pontos de infrações                                   |should|
| RF34 |Deve ser possível transferir titularidade de multa                                 |should|
| RF35 |Deve ser possível realizar pagamento de multa                                      |should|
| RF36 |Deve ser possível agendar serviços                                                 |could|
| RF37 |Deve ser possível escolher data de agendamento                                     |could|
| RF38 |Deve ser possível escolher unidade de agendamento                                  |could|
| RF39 |Deve ser possível escolher hora de agendamento                                     |could|
| RF40 |Deve ser possível consulta endereço de unidades                                    |should|
| RF41 |Deve ser possível realizar contato com ouvidoria                                   |should|
| RF42 |Deve ser possível alterar email                                                    |must|
| RF43 |Deve ser possível alterar senha                                                    |must|
| RF44 |Deve ser possível reenviar e-mail de validação                                     |must|
| RF45 |Deve ser possível cadastrar biometria                                              |must|
| RF46 |Deve ser possível cadastrar Cpf/Cnpj                                               |must|
| RF48 |Deve ser possível cadastrar uma senha                                              |must|
<h6 align = "center">Tabela 1: Requisitos funcionais</h6>

#### Requisitos Não-Funcionais

Na *Tabela 2* abaixo foram categorizados os requisitos não-funcionais elicitados.

| ID | Requisitos | Prioridade |
|:--:|:--:|:--:|
| RNF 01 | O aplicativo deve rodar nas versões mais recentes (até 5 anos) de Android e iOS | must |
| RNF 02 | O aplicativo deve ter uma latência máxima de 1000ms por requisição | must |
| RNF 03 | O aplicativo deve estar disponível 24h | must |
<h6 align = "center">Tabela 2: Requisitos não-funcionais</h6>




## Referências

> BECKER, Alice. **Aprenda como o método MoSCoW poderá ajudá-lo a priorizar as tarefas da sua empresa**. Voitto, 2020. Disponível em: [https://www.voitto.com.br/blog/artigo/metodo-moscow](https://www.voitto.com.br/blog/artigo/metodo-moscow). Acesso em: 12 de jul. de 2022.

> CARVALHO, Henrique. **O framework de priorizacao: MoSCoW**. Vida de produto, 2019. Disponível em: [https://vidadeproduto.com.br/framework-moscow/#O_framework_MoSCoW](https://vidadeproduto.com.br/framework-moscow/#O_framework_MoSCoW). Acesso em: 12 de jul. de 2022.

> PIRES, Rafael. **Aprenda a usar a técnica MoSCoW nos projetos da sua agência!**. Rockcontent, 2019. Disponível em: [https://rockcontent.com/br/blog/metodo-moscow/](https://rockcontent.com/br/blog/metodo-moscow/#:~:text=O%20que%20%C3%A9%20a%20t%C3%A9cnica%20MoSCoW%3F,elas%20atribuem%20a%20cada%20requisito.). Acesso em: 12 de jul. de 2022.

***
## Histórico de Versão
| Versão | Data       | Descrição                                           | Autor        | Revisor |
| ------ | ---------- | --------------------------------------------------- | ------------ | ------- |
| 0.1    | 11/07/2022 | Criação do documento, Adição de introdução, Adição da classificação MoSCoW dos requisitos da Introspecção | Thiago Gomes | Matheus Costa |
| 0.2    | 12/07/2022 | Correções de português e layout, adição de legendas, Adicão do tópico Metodologia |     Paulo Gontijo     | Thiago Gomes
| 0.3    | 12/07/2022 | Revisão e correção ortográfica em alguns textos, Adição de Referências, Adição da classificação MoSCoW dos requisitos de Questionários | Matheus Costa | Thiago Gomes |
| 0.4    | 13/07/2022 | Separação de requisitos do Questionário entre funcionais e não funcionais, Reestruturação do documento | Matheus Costa | Thiago Gomes |
| 0.5    | 12/07/2022 | Adiciona priorização de requisitos do brainstorm | Thiago Gomes | Matheus Costa |

