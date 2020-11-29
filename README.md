 Projeto Integrador - Grupo 06

## Projeto Integrador - BD

### Integrantes do grupo:

- Danilo Verginio da Silva
- Eliza Silva Galvão
- Guilherme de Agostin
- Gustavo de Castro Costa Silva
- Marcos Francisco da Silva
- Michel Rubens Ferreira da Silva
- Jean Lucca Pierro Santos (**Master**)
- Rodrigo Prado da Silva (**Master**)

### Linkedin dos componentes do grupo:

- Eliza Silva Galvão:
https://www.linkedin.com/in/eliza-galvão-7b3734104

- Guilherme de Agostin:
https://www.linkedin.com/in/guilherme-agostin-90ba6169/

- Gustavo de Castro Costa Silva:
https://www.linkedin.com/in/gustavocastrow/

- Marcos Francisco da Silva:
https://www.linkedin.com/in/marcossilva2020

- Michel Rubens Ferreira da Silva:
https://www.linkedin.com/in/michelrubens

- Jean Lucca Pierro Santos (**Master**)

- Rodrigo Prado da Silva (**Master**)


### Objetivo do projeto

O Vandroid visa promover uma integração entre motoristas de vans e seus passageiros, contando com a facilidade de acesso aos aparelhos celulares, o Vandroid irá auxiliar  o motorista na administração dos seus horários e rotas, já pelo lado do passageiro iremos atuar para mostrar os horários de embarque e também de desembarque, assim tendo um maior aproveitamento e organização do tempo. Será utilizado o MIT – App Inventor 2 como tecnologia principal no desenvolvimento do aplicativo.



### Definições das Sprints

**Sprint 0: Definição das regras de negócio e estrutura da aplicação** (27/09/2020)

**Sprint 1: Tela de login** - Cadastro de passageiros e autenticação com Firebase e Google Sheet (17/10/2020)

**Sprint 2: Tela do motorista** - Confirmação de viagem feita pelo passageiro e lista de presença para o motorista (08/11/2020)

**Sprint 3: Tela do motorista** - Calculo de rotas e tempo estimado (29/11/2020)
 


## Entrega Sprint 0

## Video Apresentação Sprint 0

[![Video Apresentação Sprint 0](https://img.youtube.com/vi/35BdMUFu61Y/0.jpg)](https://www.youtube.com/watch?v=35BdMUFu61Y)

1. Regras de negócio
2. Layouts das telas
3. Tecnologias utilizadas

## 1.	Regras de Negócio Vandroid

Atualmente a expressão “economia de tempo”, está cada vez mais presente no nosso cotidiano, hoje as interações que temos pelas redes de computadores e aparelhos celulares nos permite a conexão e o contato com todos instantaneamente de uma maneira muito simples e rápida. Pensando nisso e nas problemáticas enfrentadas todos os dias por motoristas de vans escolares que fazem transporte de passageiros, focamos nossas atenções para o desenvolvimento de um aplicativo prático, proporcionando um suporte para o motorista otimizar seu tempo e rota. 


###  Funcionalidade do aplicativo

O Vandroid contará com uma tela simples, sendo necessário fazer login como motorista ou como passageiro, opção que será selecionada na primeira tela da aplicação. 

Ao realizar o login o passageiro deverá confirmar se irá no dia e o motorista terá assim uma lista de passageiros que confirmaram a presença. 

Para início da viagem e para cálculo da rota, o motorista terá que ter a confirmação de todos os passageiros que irão, e a não confirmação por parte do usuário, indicará ao motorista que ele deve tomar outra rota evitando o desperdício de tempo na busca do mesmo. 

### Funcionalidades da tela do passageiro

No caso de novos usuários do transporte, é obrigatório o preenchimento de dados de cadastro como: Nome completo, sexo, idade, CPF, e-mail, telefone, endereço (nome da rua, bairro, número da casa, CEP) e senha. Para passageiros já cadastrados a próxima tela será a de confirmação da viagem, onde o passageiro confirmará sua ida e a sua volta utilizando a van escolar. 

### Funcionalidade da tela do motorista

Mediante as informações e do preenchimento dos dados cadastrais por parte do passageiro, e da confirmação de quais pessoas farão a viagem, o motorista contará com uma relação de alunos que irão na ida e na volta e seus respectivos endereços. Contando com as funcionalidades do aplicativo, será possível traçar a melhor rota maximizando o tempo e tornando o trabalho do motorista mais eficiente.

### Traçando a Melhor Rota

A tela do motorista irá consumir todos os dados preenchidos pelos passageiros, a partir dos dados a aplicação irá mostrar a melhor ordem para o embarque e desembarque dos passageiros, mas também o motorista terá autonomia total sobre o app para ele poder definir a melhor ordem de acordo com sua necessidade e conhecimento.

## 2.	Layouts das telas

**Tela 1. Tela inicial**

Onde será selecionado quem é o usuário e onde um passageiro novo poderá ser redirecionado para se cadastrar.

<figure>
  <img src="https://uploaddeimagens.com.br/images/002/896/200/original/Home_N%C3%A3o_Logado.png?1601145581" alt="Tela 1">
</figure>

Regras para implementar nos campos: 

- Clicou no botão de usuário PASSAGEIRO vai para tela 2

- Clicou no botão de usuário MOTORISTA vai para tela 4


**Tela 2. Check-in de passageiro**

Onde o passageiro irá confirmar sua ida e sua volta.

<figure>
  <img src="https://uploaddeimagens.com.br/images/002/896/190/original/Passageiro_logado_%282%29.png?1601145068" alt="Tela 2">
</figure>

**Tela 3. Cadastro de novo usuário**

Onde o passageiro irá digitar seus dados pessoais.

<figure>
  <img src="https://uploaddeimagens.com.br/images/002/896/198/original/Cad_Passageiro_-_Copia.png?1601145478" alt="Tela 3">
</figure>

Regras para implementar nos campos: 

- O usuário não pode salvar as informações enquanto não preencher todos os campos. 

- A senha tem que ser a mesma nas duas caixas de senha para garantir que foi digitada corretamente.

**Tela 4.  Motorista**

Onde abrirá a relação de passageiros que irão no dia e seus respectivos endereços.

<figure>
  <img src="https://uploaddeimagens.com.br/images/002/896/182/original/Lista_Motorista_%281%29.png?1601144892" alt="Tela 4">
</figure>

## 3.	Tecnologias utilizadas

- GitLab
- Figma

## Entrega Sprint 1 (17/10/2020)

## Video Apresentação Sprint 1

[![Video Apresentação Sprint 1](https://img.youtube.com/vi/_VQYvhweoug/0.jpg)](https://www.youtube.com/watch?v=_VQYvhweoug)

1. Tela Passageiro - Login
2. Tela Cadastro
3. Autenticação

## 1.	Botão "Passageiro" - Tela Login

Ao clicar no botão "passageiro" o passageiro é levado até a tela de autenticação, onde se encontra um campo usuário do tipo text onde o passageiro irá inserir seu nome de usuário, logo abaixo temos o campo senha onde o passageiro deve informar sua senha que deve ser maior ou igual à 5 caracteres.
Abaixo dos inputs temos dois botões, um botão "voltar" no qual temos a função de voltar para a tela anterior, ao lado direito temos o botão "entrar" que será responsável por fazer a autenticação do usuário e senha digitados.
Caso o passageiro não tenha cadastro temos um botão "cadastrar" que ao clicar levará o passageiro direto para uma tela de cadastro.

<figure>
  <img src="https://uploaddeimagens.com.br/images/002/922/508/original/Screen_Shot_2020-10-16_at_15.50.55.png?1602874391" alt="Tela Inicio">
</figure>


<figure>
  <img src="https://uploaddeimagens.com.br/images/002/922/519/original/Screen_Shot_2020-10-16_at_15.51.01.png?1602874612" alt="Tela Inicio">
</figure>


## 2. Tela Cadastro

Na tela "cadastro" temos todos os campos de informações para efetuar o cadastro de um novo passageiro, os campos são:
Nome: campo do tipo text no qual ira receber e armazenar o nome digitado pelo passageiro 
Usuário: campo do tipo texto no qual ira receber e armazenar um usuário único digitado pelo passageiro 
CPF: campo do tipo number no qual ira receber e armazenar os números de CPF do passageiro  
Telefone: campo do tipo number no qual ira receber e armazenar os números do telefone do passageiro 
Embarque: campo do tipo text no qual ira receber e armazenar o endereço digitado pelo passageiro 
Desembarque: campo do tipo text no qual ira receber e armazenar o endereço digitado pelo passageiro 
Senha: campo do tipo password no qual ira receber e armazenar a senha do passageiro 

<figure>
  <img src="https://uploaddeimagens.com.br/images/002/922/517/original/Screen_Shot_2020-10-16_at_15.51.10.png?1602874565" alt="Tela Cadastro">
</figure>

Após o preenchimento de todos os dados, temos um botão "Salvar" que ao clicar nele os dados são armazenos em dois banco de dados, os dados de nome, usuário, cpf, telefone, embarque, desembarque e senha são armazenados no Firebase conforme imagem abaixo, os dados digitados ficam salvos no usuário único de cada passageiro.

<figure>
  <img src="https://uploaddeimagens.com.br/images/002/922/499/original/Screen_Shot_2020-10-16_at_15.43.11.png?1602873946" alt="Tela Cadastro">
</figure>

Os dados de embarque e desembarque além de serem armazenados no usuário unico direto no Firebase também é armazenado no googlesheet para futuramente na sprint 2 ser consumido e consultado via tela do motorita.

## 3. Autenticação

A autenticação do passageiro é feita na tela de "login", onde o mesmo ira informar seu usuário cadastrado e sua senha, e ao clicar em "Entrar" o processo de autenticação se inicia fazendo uma chamada no Firebase e consultado se o usuário e senha digitado condiz com o que foi gravado no banco de dados, caso usuário ou senha estiverem errados o passageiro receberá uma notificação via pop-up informando que os dados estão divergentes.
Caso usuário e senha estiverem corretos o usuário será redirecionado para uma página informando que o login foi efetuado com sucesso, e futuramente nas próximas sprints será nessa tela que o passageiro irá confirmar seu embarque e desembarque.

<figure>
  <img src="https://uploaddeimagens.com.br/images/002/922/535/original/Screen_Shot_2020-10-16_at_15.51.56.png?1602875317" alt="Tela Login sucesso">
</figure>


## Entrega Sprint 2 (08/11/2020)

## Video Apresentação Sprint 2

[![Video Apresentação Sprint 2](https://img.youtube.com/vi/etsJBMzcLL4/0.jpg)](https://youtu.be/etsJBMzcLL4)

## 1. Confirmação de presença do passageiro 

**Tela de Confirmação**

Após fazer o login utilizando os dados cadastrados o passageiro é direcionado para a tela de confirmação de viagem.
Na tela confirmação temos os inputs onde os passageiros irão confirmar se irão ou não utilizar a van naquele dia.
Temos dois inputs do tipo "checkbox" onde o primeiro é "Irei Hoje" e logo abaixo temos o input "Não Irei Hoje" e logo abaixo dos inputs temos o botão "Salvar".

Selecionando o checkbox "Irei Hoje" o passageiro irá informar ao motorista que irá utilizar o serviço de van naquele dia. Após selecionar o checkbox e clicar em "Salvar", esses dados são enviados diretamente para o banco de dados onde será armazenado essa informação, e posteriormente essa informação será consumida pela tela do motorista. Após clicar em "Salvar", o passageiro receberá uma mensagem agradecendo pela informação e logo em seguida aparecerá o botão "Tela Inicial" que redirecionará ele para a tela de início do app.

Caso o passageiro selecione o checkbox "Não irei hoje", se o nome dele aparecia anteriormente na lista, automaticamente o nome será retirado de lá. E conforme o botão "Irei Hoje", todas essas informações são salvas no banco de dados e posteriormente consumidas na tela do motorista. Após clicar em "Salvar", o passageiro receberá uma mensagem agradecendo pela informação e logo em seguida aparecerá o botão "Tela Inicial" que redirecionará ele para a tela de início do app.

<figure>
  <img src="https://uploaddeimagens.com.br/images/002/951/790/original/WhatsApp_Image_2020-11-07_at_21.11.41.jpeg?1604794457" alt="Confirmação de presença" width="380">
</figure>

## 2. Lista com passageiros que irão no dia

**Relação de usuários confirmados**

Logo na tela inicial temos o botão "Motorista". Ao clicar nele somos direcionados à tela do motorista, onde temos o botão "Presença de Passageiros".

Ao clicar no botão será feita  uma requisição ao banco de dados que irá mostrar em tela, através do módulo List View do App Inventor, uma listagem com todos os passageiros que confirmaram a sua ida naquele dia.

Caso o passageiro não altere a informação na tela de passageiro, a informação não mudará. Ou seja, a informação que estiver no banco - se ele vai ou não - continuará valendo até que o usuário escolha a outra opção em sua página.


<figure>
  <img src="https://uploaddeimagens.com.br/images/002/951/792/original/WhatsApp_Image_2020-11-07_at_21.11.41_%281%29.jpeg?1604794523" alt="Lista de passageiros confirmados" width="380">
</figure>

Reunião dia 24/11/20 início : 19:40h até 00:00h.

Fizemos a testagem de todas as funções do ap para entrega dia 29/11/20.
Melhoramento do design do ap exemplo : botões.
Melhorar apresentação do ap tipo ícones,figuras e bonecos.
Arrumamos ida para o destino,agora arrumaremos a volta do serviço no ap.
Setar campo controle para definição do destino.
Excluir layout que não usava.
Definir a tela de volta para confirmar no passageiro ou seja início do passageiro e não início do ap.
Acertar listagem do motorista e do passageiro.
Acertando listas no firebase,list picker,before picking,after picking,lista global.
Acertando métodos.

Reunião dia 25/11/20 início : 20:45h até 23:00h.

Ajustando o tempo no ap,hora prevista,variáveis no apinventor.
Verificando global teste duration ida.
Temos hora prevista dos testes e tudo foi rodando perfeitamente.
Integração das sprints concluída.
Gerenciamento do mapa houve um impasse sobre ponto e vírgula,os testes para termos sucesso foi necessário validarmos com vírgula somente.

Reunião dia 29/11/20 início : 17:00 até 21:00h.

Finalizar todos componentes para entrega do ap.
Login sucesso.
Lista de longitude e latitude de ida.
Viagem sugerida de ida sprint 1.
inclusão de vídeos e prints sobre o ap.

<figure>
  <img src="https://uploaddeimagens.com.br/images/002/983/609/full/IMG-20201129-WA0003.jpg?1606690563"

<figure>
  <img src="https://uploaddeimagens.com.br/images/002/983/613/full/IMG-20201129-WA0004.jpg?1606690991"

<figure>
  <img src="https://uploaddeimagens.com.br/images/002/983/611/full/IMG-20201129-WA0002.jpg?1606690843" 



<figure>
  <img src="https://uploaddeimagens.com.br/images/002/983/629/full/Screenshot_2020-11-29-18-36-57.png?1606691823" 

  
 <figure>
  <img src="https://uploaddeimagens.com.br/images/002/983/632/full/Screenshot_2020-11-29-18-37-02.png?1606691956" 
  
   
  
  
   
  



  
  









