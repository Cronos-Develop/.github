# Aplicativo Cronos

## Quem Somos:
O Cronos é uma plataforma digital de gestão de tempo e de tarefas focadas em um objetivo empresarial cujo efeito será a longo ou curto prazo mas que necessita de um método bem definido pelo empresário para ser feita. O diferencial da plataforma é que ela será totalmente orientada pelos dados qualitativos e quantitativos que o usuário fornecer sugerindo alterações em prazos e métodos por meio de soluções de IA. Além disso, há a opção de utilizar a matriz 5W2H ou a matriz GUT ou até mesmo as duas ao mesmo tempo para o planejamento de ações conforme suas prioridades. Portanto, ela é perfeita para micro-empreendedores ou administradores que estão cansados de tanto papel e de interfaces não amigáveis para planejar suas obrigações.

## Tecnologias Utilizadas:
### Front End:
#### HTML:

#### CSS:

#### JavaScript:

### Back End:
#### PHP com Laravel:

### Banco de dados:
#### MySQL:

### Ambiente de desenvolvimento:
#### Docker e Docker-Compose:
#### Composer:
#### GitBash:
#### XAMPP:

## Publico Alvo:
### Empresários ou micro Empresários: 
#### Principal StakeHolder da aplicação, pois poderá planejar suas tarefas no Aplicativo.
    - Possui:
        - Nome;
        - Email;
        - Telefone;
        - CPF/CNPJ;
        - Senha;
        - Endereço;
        - CEP;
        - Nome da Empresa;
        - Data de Nascimento;
  ### Profissional em administração: 
  #### Usará a aplicação para trabalhar ou auxiliar terceiros.
    - Possui:
        - Nome;
        - Email;
        - Telefone;
        - CPF;
        - Senha;
        - Endereço;
        - CEP;
        - Data de Nascimento;

# Requisito Funcional 1:
## Cadastrar Dados:
### Feito por: Luiz Filipe de Souza Alves
#### Revisado por: <nome> 
### Atores:
Empresário, micro-empresário e profissional em administração.

### Descrição:
O ator que ainda não possuir cadastro feito na plataforma poderá criar o próprio cadastro através do preenchimento do formulário de cadastro dda aplicação. 

### Pré-condição:
1. Não posssuir registro feito na plataforma.
2. Desejar possuir registro na plataforma e concordar com os termos de uso da aplicação.
3. Possuir em mente um nome de uma empresa fictícia ou o nome da própria empresa.

### Fluxo Principal:
1. O ator acessa a página de apresentação da aplicação.
2. O ator toma ciência das funcionalidades da aplicação.
3. O ator decide que quer utilizar a alicação para seu negócio.
4.  O ator acessa a página de cadastro.
5. O ator preenchee o formulário com todas os dados que forem solicitados.
6. O ator concorda com os termos de uso do aplicativo.
7. O ator clica no botão “cadastrar”.

### Fluxo Secundário:
- Acessar cadastro.

### Campos de Formulário:
| Dado: | Tipo de daddo: | Placeholder: |
| --- | --- | --- |
| Nome | Texto | Digite seu nome: |
| Email | Texto | Informe deu email: |
| Telefone | Texto | Digite seu número de celular: |
| CPF/CNPJ | Texto | Digite seu CPF: |
| Senha | Texto | Senha |
| Endereço | Texto | Digite seu endereço: |
| CEP | Texto | Digite seu CEP: |
| Nome da Empresa | Texto | Qual nome da sua empresa? |
| Data de Nascimento | Data | Data de Nascimento |

### Opções do Usuário:
- Cadastrar
- Cancelar

## User Storie RF 1:
Sou Cláudio Arraio, sou um empresário que começou no ramo de venda de batata de porta em porta à pouco tempo e gostaria de usar meu <strong>*celular</strong>* para me *<strong>*cadastrar*</strong>* em uma plataforma para planejar meu dia a dia com a ajuda de algum aplicativo que me ajudasse à priorizar minhas atividades com base nas informações que eu fornecesse e salvasse meu progresso para que eu veja o que eu fiz quando eu comprar um computador.

# Requisito Funcional 2:

## Acessar Cadastro:
### Feito por: Luís Felipe Krause de Castro
#### Revisado por: Luiz Filipe de Souza Alves
### Atores:

Empresário, micro-empresário e profissional em administração

### Descrição:

Querendo acessar sua conta, o ator insere suas credenciais na plataforma. Os dados serão consultados no banco de dados à procura do login e senha inseridos. Caso seja autenticado, a plataforma libera o acesso ao ator. Caso não conste no banco de dados, o ator não será autenticado e não poderá acessar sua conta.

### Pré-condição:

1. O ator deve possuir uma conta cadastrada e suas devidas credenciais.
2. O ator deve desejar fazer o login na plataforma.

### Fluxo Principal:

Depois de inserir suas credenciais, o sistema autentica corretamente o usuário e o encaminha para usar a plataforma.

### Fluxo Secundário:

As credenciais não são reconhecidas, então o usuário pode fazer o cadastro.

### Campos de Formulário:

| Dado: | Tipo de dado: | Placeholder: |
| --- | --- | --- |
| Email ou CPF | Texto | CPF ou email |
| Senha | Texto | ********* |

### Opções do Usuário:

- Acessar Cadastro;
- Recuperar dados;

## User Storie RF 2:

“Meu nome é Iveto Sangalo. Sou um empresário que utiliza a Cronos para auxílio no planejamento de operações da minha empresa. Sou cadastrado na plataforma, então desejo acessar minha conta através do meu CPF e senha para usar as ferramentas de organização.”

# Requisito Funcional 3:

## Recuperar Dados:
### Feito por: Patryck Henryck Moreira Silva
#### Revisado por: Antônio Cássio de Oliveira Neto
### Atores:

Empresário, micro-empresário e profissional em administração

### Descrição:

Querendo recuperar os seus dados o ator deverá inserir o email cadastrado e confirmar o recebimento de um email ou sms, o qual será enviado pela forma de recuperação cadastrada pelo ator no momento do cadastro, após a confirmação o sistema liberará o acesso aos dados ao usuário

### Pré-condição:

1. O ator deve estar cadastrado no sistema e possuir uma forma de recuperação de dados credenciada.
2. O ator deve possuir acesso a forma de recuperação credenciada.
3. O ator deve confirmar o recebimento da confirmação de recuperação de dados.

### Fluxo Principal:

O ator informa o email cadastrado no sistema, o sistema verifica se o email está no banco de dados, após a confirmação da existência do email o sistema envia um email ou sms de confirmação de recuperação de dados para o método de recuperação vinculado ao cadastro. Depois de confirmar a recuperação de dados, o ator é direcionado pelo sistema a uma tela de mudança de dados.

### Fluxo Secundário:

1. O ator não possuir cadastro no sistema, podendo realizar um cadastro no sistema.
2. O ator não consegue confirmar o email ou sms dentro de um tempo limite, após isso é liberado uma função de reenvio de email ou sms.
3. O ator não consegue confirmar o email ou sms, podendo entrar em contato com a empresa ou realizar um cadastro no sistema.

### Campos de Formulário:

| Dado: | Tipo de dado: | Placeholder: |
| --- | --- | --- |
| Email | Texto | Email de usuário |
| Código de confirmação | Números | XXXXXX |

### Opções do Usuário:

- Alterar dados
- Reenviar email ou sms
- Cancelar

## User Storie RF 3:

“Meu nome é José Antônio. Sou um empresário que utiliza a Cronos a bastante tempo, porém acabei esquecendo minha senha de acesso, através do botão ‘Recuperar Dados’ após ter digitado meu email cadastrado fiz confirmação do c**ódigo** recebido no meu **email de recuperação** cadastrado e consegui alterar minha senha”.

“Meu nome é Pedro Moraes. Sou um empresário que utiliza a Cronos, mas esqueci minha senha de acesso, apertei o botão de ‘Recuperar dados’ e informei meu email cadastrado, porém não possuo mais acesso a forma de recuperação cadastrada após confirmar minha identidade entrando em contato com a empresa consegui o acesso a minha conta novamente ”.

# Requisito Funcional 4:

## Alterar Dados:
### Feito por: Patryck Henryck Moreira Silva
#### Revisado por: Antônio Cássio de Oliveira Neto
### Atores:

Empresário, micro-empresário e profissional em administração.

### Descrição:

O ator tem a opção de mudar suas informações pessoais até certo ponto, sendo necessário uma autenticação para mudar informações de segurança.

### Pré-condição:

1. Possuir cadastro no sistema.
2. Estar conectado ao sistema.

### Fluxo Principal:

O ator está conectado ao sistema, acessa a aba de perfil e seleciona o botão alterar dados o qual dá opção para o ator alterar: nome, endereço, cep, nome da empresa e data de nascimento. Após fazer as alterações o ator confirmar e o sistema atualiza as informações.

### Fluxo Secundário:

1. Caso o ator faça a autenticação pode alterar: senha, email, telefone e CNPJ e confirmar após fazer as alterações.
2. O usuário aperta em cancelar e as alterações são desfeitas.

### Campos de Formulário:

| Dado: | Tipo de dado: | Placeholder: |
| --- | --- | --- |
| Nome | Texto | Digite seu nome: |
| Email | Texto | Informe seu email: |
| Telefone | Texto | Digite seu número de celular: |
| CNPJ | Texto | Digite seu CNPJ: |
| Senha | Texto | Senha |
| Endereço | Texto | Digite seu endereço: |
| CEP | Texto | Digite seu CEP: |
| Nome da Empresa | Texto | Qual nome da sua empresa? |
| Data de Nascimento | Data | Data de Nascimento |

### Opções do Usuário:

- Alterar dados
- Cancelar

## User Storie RF 4:

“Meu nome é Flávio Moraes. Sou um empresário que utiliza a Cronos, tenho um email como forma de recuperação o qual não tenho acesso, portanto indo em ‘Meu perfil’ e apertando em ‘Ajustes’ após realizar a autenticação troquei meu email de recuperação em ‘Editar informações de segurança’ e apertei o botão ‘Confirmar’ assim consegui atualizar meu email de recuperação”.

# Requisito Funcional 5:

## Desativar Cadastro:
### Feito por: Luís Felipe Krause de Castro
#### Revisado por: Luiz Filipe de Souza Alves
### Atores:

Empresário, micro-empresário e profissional em administração.

### Descrição:

O ator, não querendo continuar a usar a plataforma, tem a opção de desativar seu cadastro. Antes de desativar o cadastro, há uma confirmação.

### Pré-condição:

1. Possuir cadastro no sistema;

### Fluxo Principal:

O ator está conectado ao sistema. Acessando seu perfil, terá a opção de desativar cadastro. Ao clicar na opção de desativação, há uma confirmação. Se confirmada, a desativação da conta é efetuada.

### Fluxo Secundário:

O ator está conectado ao sistema. Acessando seu perfil, terá a opção de desativar cadastro. Ao clicar na opção de desativação, há uma confirmação. Caso não seja confirmada, o ator é direcionado para o seu perfil.

### Campos de Formulário:

| Botão | Ação |
| --- | --- |
| “Excluir Conta” | Desativação do cadastro |

### Opções do Usuário:

- Confirmar desativação do cadastro;
- Cancelar;

## User Storie RF 5:

“Sou Tiffany Sousa, uma profissional de administração usuária da Cronos. Criei minha conta na Cronos para ajudar no planejamento dos meus clientes. Depois de um tempo de testes, decidi deixar a plataforma. Desejo desativar meu cadastro através de um botão de ‘desativar’ e uma confirmação (outro botão).”

# Requisito Funcional 8:

## Consultar Planejamentos:
### Feito por: Antônio Cássio de Oliveira Neto
#### Revisado por: <nome>

### Atores:

Empresário, micro-empresário e profissional em administração

### Descrição:

Querendo consultar os planejamentos já cadastrados no Cronos, o autor deve fazer login na plataforma, agora dentro da plataforma, o autor deve se direcionar para a área “Meus Planos” aonde estarão todos os planos feitos pelo autor ou pela equipe / empresa do qual o autor faça parte. Lá ele pode ver todas as informações dos planos.

### Pré-condição:

1. O ator deve estar cadastrado no sistema;
2. O ator deve fazer o login na plataforma;
3. O autor já fez um planejamento;

### Fluxo Principal:

O ator está conectado ao sistema acessa a aba de “Meus Planos”, nela será mostrado todos planos que o autor criou ou da equipe / empresa que o autor faça parte. O autor pode verificar os detalhes e informações do plano selecionando o plano específico. Há a opção do autor pesquisar por um plano específico com uma barra de pesquisa.

### Fluxo Secundário:

1. O usuário aperta em cancelar e a busca pelo plano é cancelada.

### Campos de Formulário:

| Dado: | Tipo de dado: | Placeholder: |
| --- | --- | --- |
| ID | Númerico | ID do Plano |
| Nome | Texto | Nome do Plano |
| Data | Datatime | Data de criação |

### Opções do Usuário:

- Pesquisar Plano
- Cancelar

## User Storie RF 8:

Meu nome é Romero Britto, sou um empresário e já participei da fundação de 10 empresas diferentes (indo do ramo alimentício ao de bem estar). Por causa disto, eu já fiz vários planos de negócios diferentes no Chronos, mas agora surgiu a necessidade de eu ver um plano que eu realizei quando eu entrei na plataforma pela primeira vez. Eu preciso de um botão “Meus Planos” de fácil acesso para me direcionar a uma pagina que contenha todos os meus planos, onde posso encontrar o plano em específico que eu procuro.

# Requisito Funcional 9:

## Alterar Planejamentos:
### Feito por: Antônio Cássio de Oliveira Neto
#### Revisado por: <nome>

### Atores:

Empresário, micro-empresário e profissional em administração

### Descrição:

Querendo realizar alterações em planejamentos já cadastrados, o autor deve entrar na plataforma, dentro da plataforma, o autor irá se direcionar para a área “Meus planos” aonde estarão todos os planos feitos pelo autor ou pela equipe / empresa do qual o autor faça parte. Lá o autor poderá escolher o plano específico que ele deseja realizar alterações e depois salvar suas alterações.

### Pré-condição:

1. O ator deve estar cadastrado no sistema;
2. O ator deve fazer o login na plataforma;
3. O autor já fez um planejamento;

### Fluxo Principal:

O ator que está conectado ao sistema acessa a aba de “Meus planos” e seleciona o plano que ele deseja fazer á alteração, depois seleciona o botão alterar plano o qual dá opção para o ator alterar as informações do plano. Após fazer as alterações o ator pode confirmar ou cancelar as alterações e o sistema atualiza as informações do plano.

### Fluxo Secundário:

1. O usuário aperta em cancelar e as alterações são desfeitas;
2. O usuário deixa informações de campos obrigatórios em branco impossibilitando a alteração de dados do plano;

### Campos de Formulário:

| Dados: | Tipos de Dados: | Placeholder: |
| --- | --- | --- |
| Plano | Texto | Alterar plano |

### Opções do Usuário:

- Alterar Plano
- Salvar mudanças
- Cancelar

## User Storie RF 9:

"Eu sou Nicolas Augusto, eu tinha criado uma empresa de Histórias em quadrinhos (Atlas), para organizar minhas ideias, eu também criei um plano no Chronos. Contudo, recentemente foi decidido que a Atlas também trabalhará com outras categorias de artes, com isso vejo a necessidade de alterar o plano que eu tinha feito anteriormente. Para isso, eu precisso de um botão alterar no plano que eu ja fiz na pagina ""Meus Planos"".