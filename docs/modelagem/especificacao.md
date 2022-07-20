# Especificação Suplementar
***

## 1. Introdução
Um documento de especificação suplementar trata-se de um documento no qual são descritos os requisitos não funcionais.
Com isso, este documento visa abranger os requisitos não captados pelos Casos de uso e trazer uma complitude para a apresentação dos [requisitos levantados](../elicita%C3%A7%C3%A3o/resultado.md).

## 2. Escopo
O escopo dessa especificação restringe-se à aplicação Detran-DF. Essa aplicação tem como objetivo possibilitar ao usuário a realização de diversos serviços por meio do celular, como por exemplo diversas consultas sobre sua habilitação, seus veículos, gerar documentos digitais, entre outros.

## 3. Definições, acrônimos e abreviações
Para maiores definições, consultar [léxicos](lexico.md).

## 4. Metodologia
A descrição dos requisitos foi construída em cima do modelo FURPS+, que diz respeito a um sistema para a classificação de requisitos. (QualidadeBR, 2008)

### 4.1. Sobre o FURPS+
Seu acrônimo representa categorias que podem ser usadas na definição de requisitos.

- **F** - _Functionality_ (Funcionalidade): representa todo o aspecto funcional do software, ou seja, seus requisitos (nesse caso já explicitados nos [casos de uso](casos.md)).

- **U** - _Usability_ (Usabilidade): é o atributo que avalia a interface com o usuário, em conformidade com os principíos de usabilidade propostos por Nielsen (PREECE; ROGERS; SHARP; 2005, p. 48-49); "O quão fácil é para o usuário realizar suas demandas via o software?".

- **R** - _Reliability_ (Confiabilidade): refere-se a integridade, conformidade e interoperabilidade do software. Requisitos a serem considerados nessa categoria podem ser do tipo: frequência e gravidade de falha, tempo médio entre falhas, possibilidade de recuperação, etc.

- **P** - _Performance_ (Desempenho): avalia os requisitos de desempenho do software, podendo usar como medida diversos aspectos, entre eles: tempo de resposta, consumo de memória, disponibilidade da aplicação, entre outros.

- **S** - _Supportability_ (Suportabilidade) – os requisitos de suportabilidade agrupam várias características, como: testabilidade, adaptabilidade, manutenibilidade, compatibilidade, escalabilidade, localizabilidade, entre outros.

- **"+"**: este símbolo do acrônimo engloba outros requisitos não-funcionais que devem ser lembrados, como por exemplo:
    - Requisitos de design: muitas vezes chamado de restrição de design; um exemplo: uso de ferramentas de desenvolvimento.
    - Requisitos de implementação: um requisito de implementação especifica ou restringe o código ou a construção de um sistema; ex: padrões obrigatórios ou linguagens de implementação.
    - Requisitos de interface: especifica ou restringe as funcionalidades inerentes a interface do sistema com usuário.
    - Requisitos físicos: especifica uma limitação física pelo hardware utilizado, por exemplo: material, forma, tamanho ou peso.

## 5. Categorização
Diante do exposto anteriormente, a categorização dos requisitos não-funcionais foi implementada e pode ser visualizada na tabela a seguir.

<center>

| Requisitos | Categoria  |
|:------: | :------: | 
| RNF1 | Suportabilidade |
| RNF2 | Performance |
| RNF3 | Performance |

<figcaption>Tabela 1: categorização dos requisitos não funcionais</figcaption>

</center>

## Referências

> FURPS+. **QualidadeBR**, 2008. Disponível em: [https://qualidadebr.wordpress.com/2008/07/10/furps/](https://qualidadebr.wordpress.com/2008/07/10/furps/). Acesso em: 20 de jul. de 2022.

> PREECE, Jennifer; ROGERS, Yvonne; SHARP, Helen. O que é _Desing_ de Interação?. **Design de Interação: Além da Interação Humano-Computador**. 1ª Edição. Bookman, 2005.


***
## Histórico de Versão

|  Versão  | Data       | Descrição           | Autor  | Revisor|
|:-------:|------------|---------------------|--------|--------|
| 0.1 | 19/07/2022 |Criação do Documento | Alex | Matheus   |
| 0.2 | 20/07/2022 |Adição do corpo do texto - tópicos de 1 a 5 | Matheus   | Alex
