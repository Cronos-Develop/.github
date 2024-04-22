# Índice:
- [Aplicativo Cronos](#aplicativo-cronos)
    - [Quem Somos](#quem-somos)
    - [Desenvolvedores do projeto](#desenvolvedores-do-projeto)
    - [Plataformas auxiliares ao desenvolvimento](#plataformas-auxiliares-ao-desenvolvimento)
    - [Tecnologias Utilizadas](#tecnologias-utilizadas)
        - [Front End](#front-end)
            - [HTML](#html)
            - [CSS](#css)
            - [JavaScript](#javascript)
            - [BootStrap](#bootstrap)
        - [Back End](#back-end)
            - [PHP com Laravel](#php-com-laravel)
        - [Banco de dados](#banco-de-dados)
            - [MySQL](#mysql)
        - [Ambiente de desenvolvimento](#ambiente-de-desenvolvimento)
            - [Docker e Docker-Compose](#docker-e-docker-compose)
            - [Composer](#composer)
            - [GitBash](#gitbash)
            - [XAMPP](#xampp)
    - [Publico Alvo](#publico-alvo)
        - [Empresários ou micro Empresários](#empresários-ou-micro-empresários)
        - [Profissional em administração](#profissional-em-administração)
- [Requisito Funcional 1](#requisito-funcional-1)
    - [Cadastrar Dados](#cadastrar-dados)
        - [Atores](#atores)
        - [Descrição](#descrição)
        - [Pré-condição](#pré-condição)
        - [Fluxo Principal](#fluxo-principal)
        - [Fluxo Secundário](#fluxo-secundário)
        - [Campos de Formulário](#campos-de-formulário)
        - [Opções do Usuário](#opções-do-usuário)
    - [User Storie RF 1](#user-storie-rf-1)
- [Requisito Funcional 2](#requisito-funcional-2)
    - [Acessar Cadastro](#acessar-cadastro)
        - [Atores](#atores-1)
        - [Descrição](#descrição-1)
        - [Pré-condição](#pré-condição-1)
        - [Fluxo Principal](#fluxo-principal-1)
        - [Fluxo Secundário](#fluxo-secundário-1)
        - [Campos de Formulário](#campos-de-formulário-1)
        - [Opções do Usuário](#opções-do-usuário-1)
    - [User Storie RF 2](#user-storie-rf-2)
- [Requisito Funcional 3](#requisito-funcional-3)
    - [Recuperar Dados](#recuperar-dados)
        - [Atores](#atores-2)
        - [Descrição](#descrição-2)
        - [Pré-condição](#pré-condição-2)
        - [Fluxo Principal](#fluxo-principal-2)
        - [Fluxo Secundário](#fluxo-secundário-2)
        - [Campos de Formulário](#campos-de-formulário-2)
        - [Opções do Usuário](#opções-do-usuário-2)
    - [User Storie RF 3](#user-storie-rf-3)
- [Requisito Funcional 4](#requisito-funcional-4)
    - [Alterar Dados](#alterar-dados)
        - [Atores](#atores-3)
        - [Descrição](#descrição-3)
        - [Pré-condição](#pré-condição-3)
        - [Fluxo Principal](#fluxo-principal-3)
        - [Fluxo Secundário](#fluxo-secundário-3)
        - [Campos de Formulário](#campos-de-formulário-3)
        - [Opções do Usuário](#opções-do-usuário-3)
    - [User Storie RF 4](#user-storie-rf-4)
- [Requisito Funcional 5](#requisito-funcional-5)
    - [Desativar Cadastro](#desativar-cadastro)
        - [Atores](#atores-4)
        - [Descrição](#descrição-4)
        - [Pré-condição](#pré-condição-4)
        - [Fluxo Principal](#fluxo-principal-4)
        - [Fluxo Secundário](#fluxo-secundário-4)
        - [Campos de Formulário](#campos-de-formulário-4)
        - [Opções do Usuário](#opções-do-usuário-4)
    - [User Storie RF 5](#user-storie-rf-5)
- [Requisito Funcional 6](#requisito-funcional-6)
    - [Cadastrar Planejamento](#cadastrar-planejamento)
        - [Atores](#atores-5)
        - [Descrição](#descrição-5)
        - [Pré-condição](#pré-condição-5)
        - [Fluxo Principal](#fluxo-principal-5)
        - [Fluxo Secundário](#fluxo-secundário-5)
        - [Campos de Formulário](#campos-de-formulário-5)
        - [Opções do Usuário](#opções-do-usuário-5)
    - [User Storie RF 6](#user-storie-rf-6)
- [Requisito Funcional 7](#requisito-funcional-7)
    - [Filtrar Planejamentos](#filtrar-planejamentos)
        - [Atores](#atores-6)
        - [Descrição](#descrição-6)
        - [Pré-condição](#pré-condição-6)
        - [Fluxo Principal](#fluxo-principal-6)
        - [Fluxo Secundário](#fluxo-secundário-6)
        - [Campos de Formulário](#campos-de-formulário-6)
        - [Opções do Usuário](#opções-do-usuário-6)
    - [User Storie RF 7](#user-storie-rf-7)
- [Requisito Funcional 8](#requisito-funcional-8)
    - [Consultar Planejamentos](#consultar-planejamentos)
        - [Atores](#atores-7)
        - [Descrição](#descrição-7)
        - [Pré-condição](#pré-condição-7)
        - [Fluxo Principal](#fluxo-principal-7)
        - [Fluxo Secundário](#fluxo-secundário-7)
        - [Campos de Formulário](#campos-de-formulário-7)
        - [Opções do Usuário](#opções-do-usuário-7)
    - [User Storie RF 8](#user-storie-rf-8)
- [Requisito Funcional 9](#requisito-funcional-9)
    - [Alterar Planejamentos](#alterar-planejamentos)
        - [Atores](#atores-8)
        - [Descrição](#descrição-8)
        - [Pré-condição](#pré-condição-8)
        - [Fluxo Principal](#fluxo-principal-8)
        - [Fluxo Secundário](#fluxo-secundário-8)
        - [Campos de Formulário](#campos-de-formulário-8)
        - [Opções do Usuário](#opções-do-usuário-8)
    - [User Storie RF 9](#user-storie-rf-9)
- [Requisito Funcional 10](#requisito-funcional-10)
    - [Consultar Tarefas](#consultar-tarefas)
        - [Atores](#atores-9)
        - [Descrição](#descrição-9)
        - [Pré-condição](#pré-condição-9)
        - [Fluxo Principal](#fluxo-principal-9)
        - [Fluxo Secundário](#fluxo-secundário-9)
        - [Campos de Formulário](#campos-de-formulário-9)
        - [Opções do Usuário](#opções-do-usuário-9)
    - [User Storie RF 10](#user-storie-rf-10)

# Aplicativo Cronos

## Quem Somos:
O Cronos é uma plataforma digital de gestão de tempo e de tarefas focadas em um objetivo empresarial cujo efeito será a longo ou curto prazo mas que necessita de um método bem definido pelo empresário para ser feita. O diferencial da plataforma é que ela será totalmente orientada pelos dados qualitativos e quantitativos que o usuário fornecer sugerindo alterações em prazos e métodos por meio de soluções de IA. Além disso, há a opção de utilizar a matriz 5W2H ou a matriz GUT ou até mesmo as duas ao mesmo tempo para o planejamento de ações conforme suas prioridades. Portanto, ela é perfeita para micro-empreendedores ou administradores que estão cansados de tanto papel e de interfaces não amigáveis para planejar suas obrigações.

## Desenvolvedores do projeto:
|Nome|Github|
|---|---|
|Luiz Filipe de Souza Alves|[LuFi-1227](https://github.com/LuFi-1227)|
|Patryck Henryck Moreira Silva|[PHmore](https://github.com/PHmore)|
|Antônio Cássio de Oliveira Neto|[ACNprogrammer](https://github.com/ACNprogrammer)|
|Luis Felipe Krause de Castro|[LuisFelipeKrause](https://github.com/LuisFelipeKrause)|
|João Victor Ribeiro Santos|[Carecovisk](https://github.com/Carecovisk)|
##

## Plataformas auxiliares ao desenvolvimento:
|Plataforma|Link|
|---|---|
|Trello|[Link](https://trello.com/invite/b/mlntL5dG/ATTI8ea9083e569942707680a4248192861849E7211A/projeto-de-sistemas-copia)|
|FIGMA|[Link](https://www.figma.com/file/ww2XqGUQdp9cG4VV6udAnf/Cronos?type=design&node-id=0-1&mode=design)|
|Relatórios de Sprints|[Link](https://github.com/Cronos-Develop/.github)|
##

## Tecnologias Utilizadas:
### Front End:
- #### HTML:
    - HTML significa Hyper Text Markup Language e é a principal ferramenta utilizada para renderizar conteúdo na WEB, sendo interpretada pelos navegadores de forma linear, de cima para baixo e podendo ser utilizada em diversas plataformas, independentemente de sistemas operacionais, pois o HTML atua sobre os navegadores.

- #### CSS:
    - CSS significa Cascade Style Sheet, ou folha de estilos em cascata e serve para estilizar as páginas em HTML, o CSS é interpretado de cima para baixo e é aplicado sobre os elementos HTML das páginas para deixar os designs mais amigáveis para o ser humano.

- #### JavaScript:
    - JavaScript é uma linguagem de programação de alto nível que é interpretada pelos navegadores e serve para atribuir funções aos elementos HTML, ela pode ser utilizada para validação de dados, criação de funções e armazenamento de dados. Possuindo uma grande variação de objetos e ferramentas para o programador. Ela também é fracamente tipada e é interpretada linha a linha de cima para baixo.

- #### BootStrap:
    - Bootstrap é um framework web com código-fonte aberto para desenvolvimento de componentes de interface e front-end para sites e aplicações web, usando HTML, CSS e JavaScript, baseado em modelos de design para a tipografia, melhorando a experiência do usuário em um site amigável e responsivo.

### Back End:
- #### PHP com Laravel:
    - Laravel é um framework PHP de código aberto criado por Taylor B. Otwell para o desenvolvimento de sistemas web usando o padrão MVC (Model-View-Controller). Destaca-se por sua sintaxe simples e concisa, modularidade com um gerenciador de dependências dedicado, várias opções para acesso a bancos de dados relacionais e utilitários úteis para o desenvolvimento e manutenção de sistemas.

### Banco de dados:
- #### MySQL:
    - O MySQL é um sistema de gerenciamento de banco de dados (SGBD) que utiliza a linguagem SQL (Structured Query Language) como interface. Desenvolvido pela Oracle Corporation, é um dos SGBDs mais populares, com mais de 10 milhões de instalações em todo o mundo. A linguagem SQL é usada para consultar, manipular e gerenciar dados armazenados no banco de dados MySQL.

### Ambiente de desenvolvimento:
- #### Docker e Docker-Compose:
    - Docker é uma plataforma que utiliza virtualização de nível de sistema operacional para fornecer software em contêineres isolados. Docker Compose, por sua vez, é uma ferramenta que simplifica a definição e execução de aplicações com múltiplos contêineres. Ele simplifica o controle de todos os serviços, redes e volumes em um único arquivo de configuração YAML, permitindo a criação e inicialização de todos os serviços com um único comando. Isso desbloqueia uma experiência de desenvolvimento e implantação mais eficiente e simplificada.

- #### Composer:
    - O Composer é um gerenciador de dependências para PHP. Ele instala bibliotecas necessárias para suas aplicações PHP a partir de um repositório chamado "Packagist". Também pode instalar aplicações PHP disponíveis no Packagist. Além disso, facilita o uso de código de terceiros, fornecendo capacidades de autoload.

- #### GitBash:
    - O Git Bash é um terminal de linha de comando incluído na instalação do Git para Windows. Ele permite que os usuários executem comandos Git e outras operações de linha de comando em um ambiente semelhante ao Unix, facilitando o desenvolvimento e gerenciamento de projetos Git no Windows.

- #### XAMPP:
    - XAMPP é um pacote de software livre que inclui os principais servidores de código aberto do mercado, como Apache, MariaDB (anteriormente MySQL), PHP e Perl, além de um cliente FTP. É projetado para criar facilmente um servidor web local para testes, sendo uma combinação de plataformas multi-OS. O nome "XAMPP" deriva da abreviação de X (representando qualquer sistema operacional), Apache, MariaDB, PHP e Perl. Essa ferramenta é amplamente utilizada pelos desenvolvedores devido à sua facilidade de instalação e configuração.

## Publico Alvo:
### Empresários ou micro Empresários: 
#### Principal StakeHolder da aplicação, pois poderá planejar suas tarefas no Aplicativo.
    - Deve possuir:
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
    - Deve possuir:
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
#### Revisado por: Patryck Henryck Moreira Silva
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

# Requisito Funcional 6:

## Cadastrar Planejamento:
### Feito por: João Victo Ribeiro Santos
#### Revisado por: Luis Felipe Krause de Castro
### Atores:

Empresário, micro-empresário e profissional em administração.

### Descrição:

O ator pode criar quantos planejamentos ele quiser. Ao clicar no botão “Novo planejamento”, o ator sera direcionado para uma nova página onde respondera várias perguntas para montar um novo plano.

### Pré-condição:

1. Estar logado na plataforma.

### Fluxo Principal:

Depois de fazer o login na plataforma, o usuario clica no botão “Novo planejamento” e é redirecionando para uma nova página onde podera iniciar o novo plano. O ator é convidado a responder uma série de perguntas sobre o negócio que pretende criar. Ao final do questionario é mostrado o resultado.

### Fluxo Secundário:

1. O ator entra na página de criação de plano.
2. Antes de terminar o processo o ator desiste e clica em “Cancelar”.
3. O ator é redirecionado para a tela principal.

### Campos de Formulário:

### Opções do Usuário:

- Responder questionario
- Cancelar planejamento

## User Storie RF 6:

"Eu sou João, um micro-empresário que acabou de abrir um café. Estou usando o Cronos para me ajudar a planejar melhor meu negócio. Eu preciso de um botão 'Novo planejamento' que me leve a uma nova página onde posso responder a várias perguntas para criar um plano de expansão para o meu café."

# Requisito Funcional 7:

## Filtrar Planejamentos:
### Feito por: João Victo Ribeiro Santos
#### Revisado por: Luis Felipe Krause de Castro
### Atores:

Empresário, micro-empresário e profissional em administração.

### Descrição:

O usuário, após criar alguns planos de negócios na plataforma Cronos, pode sentir a necessidade de filtrar esses planos para uma visualização mais eficiente. A filtragem permite ao usuário aplicar alguns critérios para limitar o numero de planos exibidos. Assim, o usuário pode facilmente encontrar o plano que está procurando.

### Pré-condição:

1. Estar logado na plataforma.
2. Ter ao menos mais de um plano cadastrado

### Fluxo Principal:

Usuario entra na página de listagem dos planos e tem a opção de clicar na caixa de busca para filtrar por nome, ou então marcar checkboxes para buscar por tipo de plano

### Fluxo Secundário:

1. Usuario entra na pagina de planos.
2. Seleciona um plano sem necessariamente usar a ferramenta de filtragem.

### Campos de Formulário:

| Campo: | Tipo de dado | Placeholder: |
| --- | --- | --- |
| Caixa de busca | texto | Pesquise aqui |
| Data | data | Data de criação |

### Opções do Usuário:

- Selecionar o plano sem filtrar
- Usar a caixa de busca
- Usar a filtragem por data
- Sair da página de planos

## User Storie RF 7:

"Eu sou Maria, uma micro-empresário que já criou vários planos de negócios na plataforma Cronos. Com o tempo, a lista de planos tornou-se extensa e agora estou tendo dificuldades para encontrar um plano específico que criei há alguns meses. Eu preciso de uma funcionalidade que me permita filtrar meus planos de negócios por nome ou data, para que eu possa localizar rapidamente o plano que estou procurando."

# Requisito Funcional 8:

## Consultar Planejamentos:
### Feito por: Antônio Cássio de Oliveira Neto
#### Revisado por: João Victo Ribeiro Santos

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

Meu nome é Romero Britto, sou um empresário e já participei da fundação de 10 empresas diferentes (indo do ramo alimentício ao de bem estar). Por causa disto, eu já fiz vários planos de negócios diferentes no Cronos, mas agora surgiu a necessidade de eu ver um plano que eu realizei quando eu entrei na plataforma pela primeira vez. Eu preciso de um botão “Meus Planos” de fácil acesso para me direcionar a uma pagina que contenha todos os meus planos, onde posso encontrar o plano em específico que eu procuro.

# Requisito Funcional 9:

## Alterar Planejamentos:
### Feito por: Antônio Cássio de Oliveira Neto
#### Revisado por: João Victo Ribeiro Santos

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

"Eu sou Nicolas Augusto, eu tinha criado uma empresa de Histórias em quadrinhos (Atlas), para organizar minhas ideias, eu também criei um plano no Cronos. Contudo, recentemente foi decidido que a Atlas também trabalhará com outras categorias de artes, com isso vejo a necessidade de alterar o plano que eu tinha feito anteriormente. Para isso, eu precisso de um botão alterar no plano que eu ja fiz na pagina ""Meus Planos"".

# Requisito Funcional 10:
### Feito por: João Victo Ribeiro Santos
#### Revisado por: Luis Felipe Krause de Castro
## Consultar Tarefas:

### Atores:

Empresário, micro-empresário e profissional em administração

### Descrição:

Após a criação de um planejamento, o autor pode querer consultar as tarefas que foram incluídas nesse planejamento. A tarefa de consulta permite ao autor visualizar as tarefas de um plano específico, facilitando a gestão e o acompanhamento do progresso do plano.

### Pré-condição:

1. O ator deve estar cadastrado no sistema;
2. O ator deve ter feito o login na plataforma;
3. Deve haver pelo menos um plano com tarefas criadas.

### Fluxo Principal:

O ator logado no sistema acessa a aba de “Meus Planos”, seleciona o plano específico que deseja consultar e clica no botão “Consultar Tarefas”. Isso o levará a uma página com uma lista de todas as tarefas vinculadas a esse plano.

### Fluxo Secundário:

1. O usuário não tem planos criados e é direcionado para criar um novo plano.

### Campos de Formulário:

| Dado: | Tipo de dado: | Placeholder: |
| --- | --- | --- |
| Nome da Tarefa | Texto | Nome da Tarefa |
| Descrição da Tarefa | Texto | Descrição da Tarefa |
| Data de Início | Data | Data de Início |
| Data de Término | Data | Data de Término |

### Opções do Usuário:

- Consultar Tarefas
- Voltar para "Meus Planos"

## User Storie RF 10:

“Eu sou Fernando, um empresário que utiliza a Cronos para me auxiliar no planejamento das tarefas do meu negócio. Após criar um plano de negócios, desejo consultar as tarefas desse plano para ter uma visão geral das atividades que preciso realizar. Preciso de um botão de "Consultar Tarefas" dentro do plano que me permita visualizar todas as tarefas relacionadas a esse plano.”
