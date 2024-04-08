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

# Requisito Funcional 3:

## Recuperar Dados:
### Feito por: Patryck Henryck Moreira Silva
#### Revisado por: <nome>
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
#### Revisado por: <nome>
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
