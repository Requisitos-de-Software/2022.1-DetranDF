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

### 3.1. Introspecção

#### Requisitos Funcionais

Na Tabela 1 abaixo foram categorizados os requisitos funcionais elicitados por Introspecção.

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
<h6 align = "center">Tabela 1: Requisitos funcionais Introspecção</h6>

#### Requisitos Não-Funcionais

Na Tabela 2 abaixo foram categorizados os requisitos não-funcionais elicitados por Introspecção.

| ID | Requisitos | Prioridade |
|:--:|:--:|:--:|
| INF 01 | O aplicativo deve rodar nas versões mais recentes (até 5 anos) de Android e iOS | must |
| INF 02 | O aplicativo deve ter uma latência máxima de 1000ms por requisição | must |
| INF 03 | O aplicativo deve estar disponível 24h | must |
<h6 align = "center">Tabela 2: Requisitos não-funcionais Introspecção</h6>

### 3.2 Questionário
#### Requisitos Funcionais

Na Tabela 3 abaixo foram categorizados os requisitos funcionais elicitados por Questionários.

| ID  | Requisitos                               | Prioridade         |
|---------|-----------------------------------------|--------------|
|<center>QF1|A interface deverá ser de fácil uso      | should |
|<center>QF2|Deverá ser possível acessar a habilitação| must |
|<center>QF3|Deverá ser possível consultar o veículo  | must |
|<center>QF4|Deverá ser possível consultar infrações  | must |
|<center>QF5|Deverá ser possível agendar atendimentos | must |
|<center>QNF6|Aplicativo deverá funcionar 24h        | should |
<h6 align = "center">Tabela 3: Requisitos funcionais elicitados Questionário</h6>

#### Requisitos Funcionais

Na Tabela 3 abaixo foram categorizados os requisitos não funcionais elicitados por Questionários.

| ID  | Requisitos                               | Prioridade         |
|---------|-----------------------------------------|--------------|
|<center>QNF6|Aplicativo deverá funcionar 24h        | should |
<h6 align = "center">Tabela 4: Requisitos não funcionais elicitados Questionário</h6>


## Referências

> BECKER, Alice. **Aprenda como o método MoSCoW poderá ajudá-lo a priorizar as tarefas da sua empresa**. Voitto, 2020. Disponível em: [https://www.voitto.com.br/blog/artigo/metodo-moscow](https://www.voitto.com.br/blog/artigo/metodo-moscow). Acesso em: 12 de jul. de 2022.

> CARVALHO, Henrique. **O framework de priorizacao: MoSCoW**. Vida de produto, 2019. Disponível em: [https://vidadeproduto.com.br/framework-moscow/#O_framework_MoSCoW](https://vidadeproduto.com.br/framework-moscow/#O_framework_MoSCoW). Acesso em: 12 de jul. de 2022.

> PIRES, Rafael. **Aprenda a usar a técnica MoSCoW nos projetos da sua agência!**. Rockcontent, 2019. Disponível em: [https://rockcontent.com/br/blog/metodo-moscow/](https://rockcontent.com/br/blog/metodo-moscow/#:~:text=O%20que%20%C3%A9%20a%20t%C3%A9cnica%20MoSCoW%3F,elas%20atribuem%20a%20cada%20requisito.). Acesso em: 12 de jul. de 2022.

***
## Histórico de Versão
| Versão | Data       | Descrição                                           | Autor        | Revisor |
| ------ | ---------- | --------------------------------------------------- | ------------ | ------- |
| 0.1    | 11/07/2022 | Criação do documento | Thiago Siqueira Gomes | Matheus Costa |
| 0.2    | 11/07/2022 | Adição de introdução | Thiago Siqueira Gomes | Matheus Costa |
| 0.3    | 11/07/2022 | Adição da classificação MoSCoW dos requisitos da Introspecção | Thiago Siqueira Gomes | Matheus Costa |
| 0.4    | 12/07/2022 | Correções de português e layout, adição de legendas |     Paulo Gontijo     |
| 0.5    | 12/07/2022 | Adicão do tópico Metodologia | Thiago Siqueira Gomes | Matheus Costa |
| 0.6    | 12/07/2022 | Revisão e correção ortográfica em alguns textos | Matheus Costa | Thiago Gomes |
| 0.7    | 12/07/2022 | Adição de Referências | Matheus Costa | Thiago Gomes |
| 0.8    | 13/07/2022 | Adição da classificação MoSCoW dos requisitos de Questionários | Matheus Costa | Thiago Gomes |
| 0.9    | 13/07/2022 | Separação de requisitos do Questionário entre funcionais e não funcionais | Matheus Costa | Thiago Gomes |
