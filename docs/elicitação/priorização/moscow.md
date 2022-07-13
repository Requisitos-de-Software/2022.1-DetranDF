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
| RF 01 | O usuário deve ser capaz de se registrar no aplicativo | must |
| RF 02 | O usuário deve ser capaz de fazer o login na sua conta | must |
| RF 03 | O usuário deve ser capaz de visualizar sua CNH eletrônica | must |
| RF 04 | O usuário deve ser capaz de visualizar suas multas | must |
| RF 05 | O usuário deve ser capaz de consultar os pontos da carteira | must |
| RF 06 | O usuário deve ser capaz de fazer um agendamento de atendimento presencial | should |
| RF 07 | O usuário deve ser capaz de encontrar os números de contato do Detran | should |
| RF 08 | O usuário deve ser capaz de solicitar 2ª via da CNH | should |
| RF 09 | O usuário deve ser capaz de gerar boletos para pagar suas multas | should |
| RF 10 | O usuário deve ser capaz de consultar dados do veículo | should |
| RF 11 | O usuário deve ser capaz de consultar infrações do veículo | should |
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
| 0.1    | 11/07/2022 | Criação do documento, Adição de introdução, Adição da classificação MoSCoW dos requisitos da Introspecção | Thiago Siqueira Gomes | Matheus Costa |
| 0.2    | 12/07/2022 | Correções de português e layout, adição de legendas, Adicão do tópico Metodologia |     Paulo Gontijo     | Thiago Siqueira Gomes
| 0.3    | 12/07/2022 | Revisão e correção ortográfica em alguns textos, Adição de Referências, Adição da classificação MoSCoW dos requisitos de Questionários | Matheus Costa | Thiago Gomes |
| 0.4    | 13/07/2022 | Separação de requisitos do Questionário entre funcionais e não funcionais, Reestruturação do documento | Matheus Costa | Thiago Gomes |
