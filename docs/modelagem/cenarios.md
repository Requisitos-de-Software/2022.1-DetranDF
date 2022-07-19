## 1. introdução

<p style="text-indent: 20px; text-align: justify">
Cenários são considerados descrições evolutivas de situações num ambiente, sendo compostos por um conjunto ordenado de interações entre seus
participantes. 
Cenários são utilizados para descrever as situações de uso do sistema pelos seus usuários e os relacionamentos entre o sistema em desenvolvimento e outros sistemas externos, auxiliando no entendimento e na descoberta de novos requisitos. 
</p>
## 2. Cenários

### C01
|<h3>**Realizar cadastro**</h3>||
|--- |--- |
|**Objetivo:**|- Criar conta de usuário|
|**Contexto:** |Local:<dd>- Tela inicial do aplicativo</dd>Pré-condição:<dd>- Não estar logado<br>- Ter acesso a internet<br>- Carteira nacional de habilitação</dd>|
|**Atores:**| - Usuário<br>- Sistema|
|**Recursos:**| - Aplicativo<br>- internet<br>- CPF/CNPJ<br>- Email<br>- smartphone com câmera<br>Documento oficial com foto|
|**Episódios:**|- Usuário seleciona opção meu cadastro<br>- Usuário seleciona primeiro acesso<br>- Usuário insere CPF/CNPJ<br>- Usuário aceita termo de uso e politica de provacidade<br>- Usuário tira foto de documento oficial com foto<br>- Usuário insere numero da CNH<br>- Usuário insere data de nascimento e nome do pai<br>- Usuário insere nome completo, telefone e E-mail|
|**Restrição:**| - Usuário deve possuir documentação válida |
|**Exceção:**|- CPF/CNPJ não encontrado<br>- Sem acesso a internet<br>- Servidores do aplicativo fora do ar<br>- Dados incorretos|

### C02
|<h3>**Realizar login**</h3>||
|--- |--- |
|**Objetivo:**|- Fazer login no aplicativo|
|**Contexto:** |Local:<dd>tela inicial do aplicativo.</dd>Pré-condição:<dd>- Não estar logado.<br>- Ter acesso a internet.<br>- Ter cadastro ativo no aplicativo</dd>|
|**Atores:**| - Usuário<br>- Sistema|
|**Recursos:**| - CPF/CNPJ<br>- Senha válida<br>- Internet<br>- Aplicativo instalado|
|**Episódios:**| - Usuário seleciona opção login<br>-  Usuário insere CPF/CNPJ e senha|
|**Restrição:**| - Usuário deve possuir cadastro|
|**Exceção:**|- CPF/CNPJ ou senha inválidos<br>- Sem acesso a internet<br>- Servidores do aplicativo fora do ar |

### C03
|<h3>**Pesquisar serviços**</h3>||
|--- |--- |
|**Objetivo:**|Encontrar serviço desejado|
|**Contexto:** |Local:<dd>- Tela inicial do aplicativo</dd>Pré-condição<dd>- Estar logado no aplicativo<br>- Ter acesso a internet</dd> |
|**Atores:**| Usuário |
|**Recursos:**| - Internet<br>- Aplicativo instalado|
|**Episódios:**|- Usuário seleciona caixa de pesquisa<br>-  Usuário escreve o nome do serviço a ser encontrado<br>- Usuário seleciona o serviço |
|**Restrição:**|- Usuário deve estar logado no aplicativo<br>|
|**Exceção:**|- Serviço não encontrado<br>- Serviço não pertence ao aplicativo<br>- Sem acesso a internet<br>- Servidores do aplicativo fora do ar  |

### C04
|<h3>**Acessar seção de veículos**</h3>||
|--- |--- |
|**Objetivo:**|Acessar serviços relacionados com um ou mais veículos|
|**Contexto:** | Local:<dd>- Tela inicial do aplicativo</dd>Pré-condição<dd>- Ter dados do veículo a ser consultado<br>- Ter veículos associados ao usuário</dd>|
|**Atores:**|- Usuário<br>- Sistema |
|**Recursos:**| - Internet<br>- Aplicativo instalado<br>- Dados do veículo |
|**Episódios:**| - Usuário clica no botão veículos na tela inicial<br>- Usuário seleciona consultar veículo<br>- Usuário seleciona emitir CRLV-e<br>- Usuário seleciona Alterar endereço do veículo<br>- Usuário seleciona Consultar placa de identificação do veículo<br>- Usuário seleciona tranferência eletronica inteligente<br>- Usuário seleciona pre transferência entre agências<br>- Usuário seleciona vistoria|
|**Restrição:**|- Usuário não ter dados válidos do veículo|
|**Exceção:**|- Dados inválidos<br>- Sem acesso a internet<br>- Servidores do aplicativo fora do ar  |

### C05
|<h3>**Acessar seção de habilitação**</h3>||
|--- |--- |
|**Objetivo:**|Acessar serviços relacionados a habilitação|
|**Contexto:** | Local:<dd>Tela inicial do aplicativo</dd>Pré-condição<dd>- Estar logado no aplicativo<br>- Ter Habilitação</dd>|
|**Atores:**|- Usuário<br>- Sistema |
|**Recursos:**|- Carteira nacional de habilitação<br>- Aplicativo instaldo<br>- Internet |
|**Episódios:**|- Usuário clica no botão de habilitação na tela inicial <br>- Usuário seleciona emitir CNH-e<br>- Usuário seleciona consultar CNH<br>- Usuário seleciona consultar processo de habilitação <br>- Usuário seleciona alterar endereço de CNH<br>- Usuário seleciona autorização de estacionamento para idoso<br>- Usuário seleciona 2° via de CNH|
|**Restrição:**|- Usuário não ter habilitação<br>- Usuário não ter feito login|
|**Exceção:** |- Dados inválidos<br>- Sem acesso a internet<br>- Servidores do aplicativo fora do ar |

### C06
|<h3>**Acessar seção de infrações**</h3>||
|--- |--- |
|**Objetivo:**|Acessar servições relacionados as infrações do usuário|
|**Contexto:** |Local:<dd>- Tela inicial do aplicativo</dd>Pré-condição<dd>- Estar logado no aplicativo</dd>|
|**Atores:**|- Usuário<br>- Sistema|
|**Recursos:**|- Aplicativo instalado<br>- Internet|
|**Episódios:**|- Usuário clina no botão de infrações<br>- Usuário seleciona transferir pontuação<br>- Usuário seleciona converter autuação em penalidade|
|**Restrição:**|- Usuário não ter feito login<br>|
|**Exceção:**|- Dados inválidos<br>- Sem acesso a internet<br>- Servidores do aplicativo fora do ar|

### C07
|<h3>**Agendar atendimento presencial**</h3>||
|--- |--- |
|**Objetivo:**|Agendar data para realizar atendimento precencial|
|**Contexto:** |Local:<dd>- Tela inicial do aplicativo</dd>Pré-condição<dd>Acesso a internet</dd> |
|**Atores:**|- Usuário<br>- Sistema|
|**Recursos:**|- Aplicativo instalado<br>- Internet<br>- Nome<br>- CPF<br>- E-mail <br>- Telefone|
|**Episódios:**|- Usuário clica no botão de agendamento<br>- Usuário seleciona insere dados pessoais<br>- Usuário seleciona serviço<br>- Usuario seleciona unidade<br>- Usuário seleciona data de atendimento<br>- Usuário seleciona hora do atendimento<br>- Usuário cadastra novo agendamento<br>- Usuário consulta seus agendamentos necessarios|
|**Restrição:**|- Dados inválidos<br>|
|**Exceção:**|- Serviços ou datas indisponíveis<br>- Não ter unidades perto do usuário<br>  |

### C08
|<h3>**Favoritar serviço**</h3>||
|--- |--- |
|**Objetivo:**|Favoritar serviços para facil acesso|
|**Contexto:** |Local:<dd>- Tela inicial do aplicativo<br>- Favoritar serviço</dd>Pré-condição<dd>- Estar logado no aplicativo</dd> |
|**Atores:**|- Usuário<br>- Sistema|
|**Recursos:**|- Internet<br>- Login no aplicativo<br>- Aplicativo instalado|
|**Episódios:**|- Usuário clica no botão de favoritos<br>- Usuário seleciona serviço na lista de favoritos<br>Usuário clica na estrela na lateral do serviço a favoritar|
|**Restrição:**|- Estar logado no aplicativo|
|**Exceção:**|- Sem acesso a internet<br>- Servidores do aplicativo fora do ar |

### C09
|<h3>**Deslogar do aplicativo**</h3>||
|--- |--- |
|**Objetivo:**|- Desconectar conta do aplicativo|
|**Contexto:** |Local:<dd>- Menu lateral do aplicativo<br></dd>Pré-condição<dd>- Estar logado no aplicativo</dd> |
|**Atores:**|- Usuário<br>- Sistema|
|**Recursos:**|- Internet<br>- Aplicativo instalado|
|**Episódios:**|- Usuário clica no botão de menu lateral<br>- Usuário seleciona sair|
|**Restrição:**|- Estar logado no aplicativo|
|**Exceção:**|- Sem acesso a internet<br>- Servidores do aplicativo fora do ar |

## 3. Referências

> <p>SAMPAIO, Julio Cesar. Capítulo 3 - Cenários. PUC-rio. Disponível <a href="http://www-di.inf.puc-rio.br/~julio/bnncap3.pdf" target="_blank">aqui.</a></p>

***
## Histórico de Versão
| Versão |     Data     |              Descrição               |      Autor      | Revisor |
|:------:|:------------:|:------------------------------------:|:---------------:|:------:|
|  0.1   |  19/07/2022  |         Criação do documento         |  Alex   | Arthur|

