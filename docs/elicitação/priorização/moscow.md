# MoSCoW
## 1. Introdução
MoSCoW é uma técnica de priorização de requisitos, que visa estabelecer um grau de prioridade para cada requisito do sistema que foi levantado, através das técnicas de elicitação. Essa priorização é útil para auxiliar o time a definir o que deve ser feito primeiro dentro do escopo do projeto.

## 2. Metodologia
Cada uma das letras em maiúsculo da sigla (M, S, C, W) faz referência a uma palavra originada do inglês, representando um tipo de categoria cada. Dessa forma, essa técnica de priorização de requisitos consiste na divisão dos requisitos levantados em 4 tipos:

- **_Must_**: requisitos de **extrema importância** e que devem obrigatoriamente estar presentes no sistema para que ele funcione.
- **_Should_**: requisitos que também são **importantes**, mas que, diferente da categoria anterior, não são considerados críticos; sua ausência não impede a entrega do produto mas agregam valor ao produto caso implementados.
- **_Could_**: requisitos que **podem ser adicionados**, mas **não são essenciais** para a entrega; possuem um impacto menor no projeto se não forem implmentados.
- **_Won't_**: requisitos que **não receberam muita importância** para a entrega dentro do prazo estipulado; por meio dessa categoria é possível evitar o crescimento desorganizado do projeto.

## 3. Resultados
Neste tópico serão apresentadas as categorizações de prioridade dos requisitos levantados por meio das técnicas de elicitação por [Introspecção](../introspeccao.md), [Questionário](../questionario.md) e _Brainstorming_.

### 1. Introspecção

#### Requisitos Funcionais
| ID | Requisitos | Prioridade |
|:--:|:--:|:--:|
| IF 01 | O usuário deve ser capaz de se registrar no aplicativo | must |
| IF 01 | O usuário deve ser capaz de fazer o login na sua conta | must |
| IF 02 | O usuário deve ser capaz de visualizar sua CNH eletrônica | must |
| IF 03 | O usuário deve ser capaz de visualizar suas multas | must |
| IF 04 | O usuário deve ser capaz de consultar os pontos da carteira | must |
| IF 05 | O usuário deve ser capaz de fazer um agendamento de atendimento presencial | should |
| IF 06 | O usuário deve ser capaz de encontrar os números de contato do Detran | should |
| IF 07 | O usuário deve ser capaz de solicitar 2ª via da CNH | should |
| IF 08 | O usuário deve ser capaz de gerar boletos para pagar suas multas | should |

#### Requisitos Não-Funcionais
| ID | Requisitos | Prioridade |
|:--:|:--:|:--:|
| INF 01 | O aplicativo deve rodar nas versões mais recentes (até 5 anos) de Android e iOS | must |
| INF 02 | O aplicativo deve ter uma latência máxima de 1000ms por requisição | must |
| INF 03 | O aplicativo deve estar disponível 24h | must |

## 4. Histórico de versão
| Versão | Data       | Descrição                                           | Autor        | Revisor |
| ------ | ---------- | --------------------------------------------------- | ------------ | ------- |
| 0.1    | 11/07/2022 | Criação do documento | Thiago Siqueira Gomes | Matheus Costa |
| 0.2    | 11/07/2022 | Adição de introdução | Thiago Siqueira Gomes | Matheus Costa |
| 0.2.1    | 11/07/2022 | Adição da classificação MoSCoW dos requisitos da Introspecção | Thiago Siqueira Gomes | Matheus Costa |
| 0.2.2    | 12/07/2022 | Adicão do tópico Metodologia | Thiago Siqueira Gomes | Matheus Costa |
| 0.2.3    | 12/07/2022 | Revisão e correção ortográfica em alguns textos | Matheus Costa | Thiago Gomes |
| 0.3    | 12/07/2022 | Revisão e correção ortográfica em alguns textos | Matheus Costa | Thiago Gomes |

