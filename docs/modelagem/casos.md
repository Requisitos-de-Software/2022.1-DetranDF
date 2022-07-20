# Casos de Uso

## 1. Introdução
Os casos de usos, também chamados de diagramas comportamentais na notação UML, são usados para descrever um conjunto de ações que um sistema ou um conjunto de sistemas deve desempenhar em colaboração com um ou mais usuários externos ao sistema. Os casos de uso devem prover um resultado observável e de valor para os atores ou outros interessados do sistema.

## 2. Diagrama de Casos de Uso
Foi utilizada a ferramenta "LucidChart" para a produção dos diagramas de casos de uso

### 2.1 Diagrama de Caso de uso geral
<img src="..\..\images\casos_de_uso\CasosdeUsoDetran-DF.png">
<center>

*Figura 01: Diagrama Geral do sistema*
</center>

### 2.2 Diagrama de Caso de uso específico - "Visualizar CNH"
<img src="..\..\images\casos_de_uso\DiagramaVisualizarCNH.png">
<center>

*Figura 02: Diagrama de Caso de uso específico - "Visualizar CNH"*
</center>

### 2.3 Diagrama de Caso de uso específico - "Visualizar Veículo"
<img src="..\..\images\casos_de_uso\DiagramaVisualizarVeículo.png">
<center>

*Figura 03: Diagrama de Caso de uso específico - "Visualizar Veículo"*
</center>

## 3. Especificação de casos de uso

### 3.1 Caso 1: Fazer Cadastro
<center>

| Caso 1         | Informações |
|----------------|-------------|
|Descrição       |Quando o aplicativo é acessado pela primeira vez depois da sua instalação, o ator necessita fazer um cadastro para acessar e verificar se os dados são reais |
|Ator/es         |Usuário |
|Pré-Condições   |Ter o aplicativo já instalado em seu dispositivo e ter acesso à internet |
|Fluxo           |1 - O ator abre o aplicativo <br/> 2 - Insere seus dados pessoais(Nome, E-Mail, CPF, Data de nascimento, etc) <br/> 3 - Insere sua Senha|
|Pós-Condições   |O ator poderá fazer login e ter acesso a todos as áreas do aplicativo |
|Rastreabilidade |Requisito Funcional:<br/> RF1 - O usuário deve ser capaz de se registrar no aplicativo <br/><br/> Pasta: Elicitação -> Resultado

</center>

### 3.2 Caso 2: Fazer Login
<center>

| Caso 2         | Informações |
|----------------|-------------|
|Descrição       |O ator, ao iniciar o aplicativo, pode efetuar o Login para acessar o aplicativo e utilizá-lo |
|Ator/es         |Usuário |
|Pré-Condições   |Ter o aplicativo já instalado em seu dispositivo e ter acesso à internet |
|Fluxo           |1 - O ator abre o aplicativo <br/> 2 - Insere seu login e sua senha ou biometria|
|Pós-Condições   |O ator poderá utilizar as áreas do aplicativo |
|Rastreabilidade |Requisito Funcional:<br/> RF2 - O usuário deve ser capaz de fazer o login na sua conta <br/><br/> Pasta: Elicitação -> Resultado

</center>

### 3.3 Caso 3: Visualizar CNH
<center>

| Caso 3         | Informações |
|----------------|-------------|
|Descrição       |O ator, ao fazer login, pode acessar a área de visualizar CNH |
|Ator/es         |Usuário |
|Pré-Condições   |Estar logado |
|Fluxo           |1 - O ator seleciona a area de CNH|
|Pós-Condições   |O ator poderá utilizar as áreas específicas da Carteira |
|Rastreabilidade |Requisito Funcional:<br/> RF3 - O usuário deve ser capaz de visualizar sua CNH eletrônica <br/> RF4 - O usuário deve ser capaz de visualizar sua CNH eletrônica <br/> RF5 - O usuário deve ser capaz de consultar os pontos da carteira <br/> RF8 - O usuário deve ser capaz de solicitar 2ª via da CNH <br/> RF10 - Deverá ser possível acessar a habilitação <br/> RF22 - Deve ser possível emitir CNH eletrônica <br/> RF25 - Deve ser possível emitir documento de nada consta <br/> RF26 - Deve ser possível consultar informações sobre processo de obtenção da habilitação <br/> RF27 - Deve ser possível solicitar CNH definitiva <br/> RF28 - Deve ser possível solicitar 2ª via de CNH <br/> RF29 - Deve ser possível solicitar autorização de estacionamento para idosos <br/> RF30 - Deve ser possível solicitar autorização de estacionamento para PCDs <br/> RF31 - Deve ser possível modificar endereço do proprietário da CNH <br/><br/> Pasta: Elicitação -> Resultado

</center>

### 3.4 Caso 4: Visualizar Veículo
<center>

| Caso 4         | Informações |
|----------------|-------------|
|Descrição       |O ator, ao fazer login, pode acessar a área de visualizar Veículo |
|Ator/es         |Usuário |
|Pré-Condições   |Estar logado |
|Fluxo           |1 - O ator seleciona a area de veículos|
|Pós-Condições   |O ator poderá utilizar as áreas específicas de veículo |
|Rastreabilidade |Requisito Funcional:<br/> RF11 - Deverá ser possível consultar o veículo <br/> RF12 - Deverá ser possível consultar infrações <br/> RF14 - Deve ser possível consultar informações sobre multas <br/> RF15 - Deve ser possível consultar informações sobre documentos <br/> RF16 - Deve ser possível realizar transferências de veículos de forma eletrônica <br/> RF17 - Deve ser possível consultar informações históricas sobre o veículo <br/> RF17 - Deve ser possível consultar informações históricas sobre o veículo <br/> RF19 -Deve ser possível alterar o endereço do proprietário do veículo <br/> RF20 - Deve ser possível emitir o ATPV <br/> RF21 - Deve ser possível agendar vistorias veiculares <br/><br/> Pasta: Elicitação -> Resultado

</center>

### 3.5 Caso 5: Visualizar Infrações
<center>

| Caso 5         | Informações |
|----------------|-------------|
|Descrição       |O ator, ao fazer login, pode acessar a área de visualizar Infrações |
|Ator/es         |Usuário |
|Pré-Condições   |Estar logado |
|Fluxo           |1 - O ator seleciona a area de infrações|
|Pós-Condições   |O ator poderá utilizar as áreas específicas de infrações |
|Rastreabilidade |Requisito Funcional:<br/> RF9 - O usuário deve ser capaz de gerar boletos para pagar suas multas <br/> RF33 - Deve ser possível transferir pontos de infrações <br/> RF34 - Deve ser possível transferir titularidade de multa <br/><br/> Pasta: Elicitação -> Resultado

</center>

### 3.6 Caso 6: Agendar Atendimentos
<center>

| Caso 5         | Informações |
|----------------|-------------|
|Descrição       |O ator, ao fazer login, pode acessar a área de agendar atendimentos |
|Ator/es         |Usuário |
|Pré-Condições   |Estar logado |
|Fluxo           |1 - O ator seleciona a area de agendar atendimentos|
|Pós-Condições   |O ator poderá utilizar as áreas específicas de atendimentos |
|Rastreabilidade |Requisito Funcional:<br/> RF6 - O usuário deve ser capaz de fazer um agendamento de atendimento presencial <br/> RF36 - Deve ser possível agendar serviços <br/> RF37 - Deve ser possível escolher data de agendamento <br/> RF38 - Deve ser possível escolher unidade de agendamento <br/> RF39 - Deve ser possível escolher hora de agendamento <br/> RF40 - Deve ser possível consulta endereço de unidades <br/> RF41 - Deve ser possível realizar contato com ouvidoria <br/><br/> Pasta: Elicitação -> Resultado

</center>


## 4. Referências Bibliográfias

> SOMMERVILLE, Ian. Engenharia de Software. 9.ed. São Paulo: Pearson Prentice Hall, 2011. 529 p.

## 5. Histórico de Versão

| Versão |     Data     |              Descrição               |      Autor      | Revisor |
|:------:|:------------:|:------------------------------------:|:---------------:|:-------:|
|0.1     |19/07         |Criação da página                     |Arthur Henrique e Thiago Gomes  |Alex     |