# MoSCoW

## 1. Introdução
MoSCoW é uma técnica de priorização de requisitos que consiste na divisão dos requisitos levantados em 4 tipos:

- Must: requisitos que devem obrigatoriamente estar presentes no sistema para que ele funcione.
- Should: requisitos que grande importância que devem estar no sistema.
- Could: requisitos que podem ser adicionados, mas possuem um impacto menor no projeto.
- Won't: requisitos que não valem a pena serem implementados
## 2. Resultado
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