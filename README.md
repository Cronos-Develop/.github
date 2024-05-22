# Documentação de Padronização e de Sprints:

## Padrões de Desenvolvimento:
Aqui estão os padrões e nomenclaturas utilizadas como preferência para o desenvolvimento da Aplicação.

### Commits:
- Os commits no repositório devem ser feitos da seguinte forma:
```
  <verbo> + <substantivo>
```
- <strong>Exemplo 1:</strong>
```
  Adicionar Tela RF02
```
- <strong>Exemplo 2:</strong>
```
  Modificar JavaScript Tela RF02
```

### Nomenclatura de Branchs:
- As branchs do repositório estão organizadas da seguinte forma:
```
main
|_ develop
|  |_ features
|_ Hotfix
```
- Com isso esclarecido, não será permitida a criação de branchs develop e main, ou seja, somente serão permitidas as criações de features e Hotfixes, que devem seguir o seguinte padrão de nomenclatura:
```
  <nickname GitHub> - <feature>
```
- <strong>Exemplo 1:</strong>
```
  LuFi-1227-feature
```
- <strong>Exemplo 2:</strong>
```
  LuFi-1227-hotfix
```

## Relatórios:
### Sprint 1:
Aqui consta o relatório da 1° Sprint feita para este projeto.

#### Metas da Sprint:
- Definir as Tecnologias a serem utilizadas;
- Planejar Requisitos Funcionais;
- Criar documentação para padronização de ambiente de desenvolvimento;

#### Relatório de Gestão (por pessoa):
- <strong>Luiz Filipe de Souza Alves</strong>:
  - Criar Organização no GitHub para trabalho em equipe:
    - [Initial Commit](https://github.com/Cronos-Develop/.github/commit/190a48b8b8c8421ee8f83ac59129e946e1dbba6a) Revisor: [---]()
  - Padronizar e documentar ambiente de desenvolvimento padrão do BackEnd:
    - [Merge pull request #1 from Cronos-Develop/feature](https://github.com/Cronos-Develop/API/commit/4e1fba44395fbcd735bdc2e8b55bd955ad8e65e0#diff-b335630551682c19a781afebcf4d07bf978fb1f8ac04c6bf87428ed5106870f5) Revisor: [João Victor Ribeiro Santos](https://github.com/Carecovisk)
  - Padronizar e documentar ambiente de desenvolvimento padrão do FrontEnd:
    - [Merge pull request #1 from Cronos-Develop/feature](https://github.com/Cronos-Develop/Front-End/commit/94fcdbe9dcec8308d1764bdb597f3773c1886f75) Revisor: [Patryck Henryck Moreira Silva](https://github.com/PHmore)
  - Preencher página de apresentação da Organização:
    - [Merge pull request #12 from Cronos-Develop/HotFix](https://github.com/Cronos-Develop/.github/commit/fc8237948eefd606c6174480446173a530294e63) Revisor: [Luiz Filipe de Souza Alves](https://github.com/LuFi-1227)
    - Criar Requisito Funcional 1:
      - [Adicionar corpo principal do readme](https://github.com/Cronos-Develop/.github/commit/7114a8b629831a7e9e808a0ff377d9b2b0a94954) Revisor: [Patryck Henryck Moreira Silva](https://github.com/PHmore)
    - Criar índice e fazer correções:
      - [Merge pull request #12 from Cronos-Develop/HotFix](https://github.com/Cronos-Develop/.github/commit/fc8237948eefd606c6174480446173a530294e63) Revisor: [Luiz Filipe de Souza Alves](https://github.com/LuFi-1227)
- <strong>Patryck Henryck Moreira Silva</strong>:
  - Criar Requisito Funcional 3:
    - [Merge pull request #1 from Cronos-Develop/PHmore-patch-1](https://github.com/Cronos-Develop/.github/commit/9fd284fe6e11f3bf5b0f2acbab902c3936700ffb) Revisor: [Antônio Cássio de Oliveira Neto](https://github.com/Cronos-Develop/.github/commit/9fd284fe6e11f3bf5b0f2acbab902c3936700ffb)
  - Criar Requisito Funcional 4:
    - [Merge pull request #1 from Cronos-Develop/PHmore-patch-1](https://github.com/Cronos-Develop/.github/commit/9fd284fe6e11f3bf5b0f2acbab902c3936700ffb) Revisor: [Antônio Cássio de Oliveira Neto](https://github.com/Cronos-Develop/.github/commit/9fd284fe6e11f3bf5b0f2acbab902c3936700ffb)
- <strong>Antônio Cássio de Oliveira Neto</strong>:
  - Criar Requisito Funcional 8:
    - [Merge pull request #3 from Cronos-Develop/RF08-RF09](https://github.com/Cronos-Develop/.github/commit/169bd9bf8f7a1af44783273f43000fc23c952c39) Revisor: [João Victor Ribeiro Santos](https://github.com/Carecovisk)
  - Criar Requisito Funcional 9:
    - [Merge pull request #3 from Cronos-Develop/RF08-RF09](https://github.com/Cronos-Develop/.github/commit/169bd9bf8f7a1af44783273f43000fc23c952c39) Revisor: [João Victor Ribeiro Santos](https://github.com/Carecovisk)
- <strong>Luis Felipe Krause de Castro</strong>:
  - Criar Requisito Funcional 2:
    - [Merge pull request #2 from Cronos-Develop/LuisFelipeKrause-patch-1](https://github.com/Cronos-Develop/.github/commit/ad9a4741122d6969440b2d1805d685b78f454015)  Revisor: [Luiz Filipe de Souza Alves](https://github.com/LuFi-1227)
  - Criar Requisito Funcional 5:
    - [Merge pull request #2 from Cronos-Develop/LuisFelipeKrause-patch-1](https://github.com/Cronos-Develop/.github/commit/ad9a4741122d6969440b2d1805d685b78f454015) Revisor: [Luiz Filipe de Souza Alves](https://github.com/LuFi-1227)
- <strong>João Victor Ribeiro Santos</strong>:
  - Criar Requisito Funcional 6:
    - [Merge pull request #4 from Cronos-Develop/RF6-7-10](https://github.com/Cronos-Develop/.github/commit/5960fbffd686f6aaf8f4636d22db7a8d6b69e15c) Revisor: [Luis Felipe Krause de Castro](https://github.com/LuisFelipeKrause)
  - Criar Requisito Funcional 7:
    - [Merge pull request #4 from Cronos-Develop/RF6-7-10](https://github.com/Cronos-Develop/.github/commit/5960fbffd686f6aaf8f4636d22db7a8d6b69e15c) Revisor: [Luis Felipe Krause de Castro](https://github.com/LuisFelipeKrause)
  - Criar Requisito Funcional 10:
    - [Merge pull request #4 from Cronos-Develop/RF6-7-10](https://github.com/Cronos-Develop/.github/commit/5960fbffd686f6aaf8f4636d22db7a8d6b69e15c) Revisor: [Luis Felipe Krause de Castro](https://github.com/LuisFelipeKrause)

### Releases:
- Documentação Principal (Versão 1.0.0):
  - [v1.0.0](https://github.com/Cronos-Develop/.github/releases/tag/v1.0.0) Revisor: [Luiz Filipe de Souza Alves](https://github.com/LuFi-1227)
    
### Sprint 2:
#### Metas da Sprint:
- Criação do UX/UI design;
- Criação do UserFlow;
- Criação das primeiras telas com seus javascripts;
- Modelagem da Index da API;
- Modelagem do Banco de dados;
  
#### Relatório de Gestão (por pessoa):
- <strong>Luiz Filipe de Souza Alves</strong>:
  - Criar tela de login e JavaScript de validação de dados:
    - [Merge pull request #3 from Cronos-Develop/LuFi-1227-feature](https://github.com/Cronos-Develop/Front-End/commit/912aa92ac06dcf544bccf8e07261b4bc20ecf2a5) Revisor: [Patryck Henryck Moreira Silva](https://github.com/PHmore)
  - Padronização de nomes de branchs e de commits:
    - [Merge pull request #13 from Cronos-Develop/LuFi-1227-feature](https://github.com/Cronos-Develop/.github/commit/90b0096d22105af24d31caf58ca14a7d6a0dbedb) Revisor: [---]()
- <strong>Patryck Henryck Moreira Silva</strong>:
  - Criar UX/UI design:
    - [Merge pull request #4 from Cronos-Develop/PHmore-feature](https://github.com/Cronos-Develop/Front-End/commit/23285d25e7b008221a3cc20e01f8aed39c32263b) Revisor: [Antônio Cássio de Oliveira Neto](https://github.com/Cronos-Develop/.github/commit/9fd284fe6e11f3bf5b0f2acbab902c3936700ffb)
  - Criar UserFlow da aplicação:
    - [Merge pull request #4 from Cronos-Develop/PHmore-feature](https://github.com/Cronos-Develop/Front-End/commit/23285d25e7b008221a3cc20e01f8aed39c32263b) Revisor: [Antônio Cássio de Oliveira Neto](https://github.com/Cronos-Develop/.github/commit/9fd284fe6e11f3bf5b0f2acbab902c3936700ffb)
- <strong>Antônio Cássio de Oliveira Neto</strong>:
  - Criar tela inicial:
    - [Merge pull request #5 from Cronos-Develop/ACNprogrammer-feature](https://github.com/Cronos-Develop/Front-End/commit/8be51896cc8f2477eb34fa055fe68bbfc3ae2956) Revisor: [Luiz Filipe de Souza Alves](https://github.com/LuFi-1227)
  - Criar tela de cadastro:
     - [Merge pull request #5 from Cronos-Develop/ACNprogrammer-feature](https://github.com/Cronos-Develop/Front-End/commit/8be51896cc8f2477eb34fa055fe68bbfc3ae2956) Revisor: [Luiz Filipe de Souza Alves](https://github.com/LuFi-1227)
- <strong>Luis Felipe Krause de Castro</strong>:
  - Modelagem da Index na API:
    - [Merge pull request #6 from Cronos-Develop/feature-LuisFelipeKrause](https://github.com/Cronos-Develop/API/commit/1fe0496412162b2328c5b8a6cdc368915587d185) Revisor: [João Victor Ribeiro Santos](https://github.com/Carecovisk)
- <strong>João Victor Ribeiro Santos</strong>:
  - Modelagem e criação do banco de dados:
    - [Merge pull request #5 from Cronos-Develop/Carecovisk-feature](https://github.com/Cronos-Develop/API/commit/01ba013df79f9056bc7aa16ebac5673c68d72566) Revisor: [Luis Felipe Krause de Castro](https://github.com/LuisFelipeKrause)

### Releases:
- Front-End:
  - [v0.0.0](https://github.com/Cronos-Develop/Front-End/releases/tag/v0.0.0)
    - Revisores:
      - [Antônio Cássio de Oliveira Neto](https://github.com/Cronos-Develop/.github/commit/9fd284fe6e11f3bf5b0f2acbab902c3936700ffb)
      - [Patryck Henryck Moreira Silva](https://github.com/PHmore)
      - [Luiz Filipe de Souza Alves](https://github.com/LuFi-1227)
- Back-End:
  - [v0.0.0](https://github.com/Cronos-Develop/API/releases/tag/v0.0.0)
    - Revisores:
      - [Luis Felipe Krause de Castro](https://github.com/LuisFelipeKrause)
      - [João Victor Ribeiro Santos](https://github.com/Carecovisk)
      - [Luiz Filipe de Souza Alves](https://github.com/LuFi-1227)
- Documentação Principal:
  - [v2.0.0](https://github.com/Cronos-Develop/.github/releases/tag/v2.0.0)
    - Revisor:
      - [Luiz Filipe de Souza Alves](https://github.com/LuFi-1227)
  
### Sprint 3:
#### Metas da Sprint:
- Prototipação Requisito Funcional 1:
```
Sou Cláudio Arraio, sou um empresário que começou no ramo de venda de batata de porta em porta à pouco tempo e gostaria de usar meu *celular* para me *cadastrar* em uma plataforma para planejar meu dia a dia com a ajuda de algum aplicativo que me ajudasse à priorizar minhas atividades com base nas informações que eu fornecesse e salvasse meu progresso para que eu veja o que eu fiz quando eu comprar um computador.
```
  - Modelagem da API;
  - Criação de Javascript das páginas;
- Prototipação Requisito Funcional 2:
```
“Meu nome é Iveto Sangalo. Sou um empresário que utiliza a Cronos para auxílio no planejamento de operações da minha empresa. Sou cadastrado na plataforma, então desejo acessar minha conta através do meu CPF e senha para usar as ferramentas de organização.”
```
  - Modelagem da API;
  - Criação de Javascript das páginas;
- Prototipação e análise UI/UX para computador;

#### Relatório de Gestão (por pessoa):
- <strong>Luiz Filipe de Souza Alves</strong>:
  - Criação de JavasCript das páginas RF1 e RF2:
    - [Merge pull request #8 from Cronos-Develop/LuFi-1227-feature](https://github.com/Cronos-Develop/Front-End/commit/4f175f25660dcb4fa39735b7bdb8b1f8a30ab6f6) Revisor: [Antônio Cássio de Oliveira Neto](https://github.com/Cronos-Develop/.github/commit/9fd284fe6e11f3bf5b0f2acbab902c3936700ffb)
  - Coleta de Análise Heurística da aplicação:
    - [Análise Heurística](https://docs.google.com/document/d/1Q-mdVcXxeiyjMVkKlLUvXRu8sSLGfnEM1ZgDPDQ9PSo/edit?usp=sharing) Revisor: ---
- <strong>Patryck Henryck Moreira Silva</strong>:
  - Prototipação do aplicativo para Computador:
    - [](https://github.com/Cronos-Develop/Front-End/pull/9) Revisor: [Luiz Filipe de Souza Alves](https://github.com/LuFi-1227) 
- <strong>Antônio Cássio de Oliveira Neto</strong>:
  - Criação do restante das telas HTML para próximas Sprints:
    -  [Merge pull request #7 from Cronos-Develop/ACNprogrammer-feature](https://github.com/Cronos-Develop/Front-End/commit/4f175f25660dcb4fa39735b7bdb8b1f8a30ab6f6) Revisor: [Patryck Henryck Moreira Silva](https://github.com/PHmore)
- <strong>Luis Felipe Krause de Castro</strong>:
  - Modelagem CRUD da API:
    - [Merge pull request #8 from Cronos-Develop/feature-LuisFelipeKrause](https://github.com/Cronos-Develop/API/commit/053ebd89813c83a4cb38a3a54f5c3cfbd247d906) Revisor: [Luiz Filipe de Souza Alves](https://github.com/LuFi-1227)
- <strong>João Victor Ribeiro Santos</strong>:
  - Não fez contribuição nenhuma.

### Releases:
- Front-End:
  - [v0.0.1](https://github.com/Cronos-Develop/Front-End/releases/tag/v0.0.1)
    - Revisores:
      - [Antônio Cássio de Oliveira Neto](https://github.com/Cronos-Develop/.github/commit/9fd284fe6e11f3bf5b0f2acbab902c3936700ffb)
      - [Patryck Henryck Moreira Silva](https://github.com/PHmore)
      - [Luiz Filipe de Souza Alves](https://github.com/LuFi-1227)
- Back-End:
  - [v0.0.1](https://github.com/Cronos-Develop/API/releases/tag/v0.0.1)
    - Revisores:
      - [Luis Felipe Krause de Castro](https://github.com/LuisFelipeKrause)
      - [Luiz Filipe de Souza Alves](https://github.com/LuFi-1227)
- Documentação Principal:
  - [v2.0.1](https://github.com/Cronos-Develop/.github/releases/tag/v2.0.1)
    - Revisor:
      - [Luiz Filipe de Souza Alves](https://github.com/LuFi-1227)
        
### Sprint 4:
#### Valor da Sprint:
- Correção de erros da prototipação do aplicativo

#### Metas da Sprint:
- Correção de erros no Aplicativo;
- Criação de telas dos requisitos funcionais;
  
#### Relatório de Gestão (por pessoa):
- <strong>Luiz Filipe de Souza Alves</strong>:
  - Correções no JavaScript:
    - [Merge pull request #12 from Cronos-Develop/LuFi-1227-feature](https://github.com/Cronos-Develop/Front-End/commit/84eb2f801d4c99dc0fb3a12e90269b304087d48c) Revisor: [Antônio Cássio de Oliveira Neto](https://github.com/Cronos-Develop/.github/commit/9fd284fe6e11f3bf5b0f2acbab902c3936700ffb)
- <strong>Patryck Henryck Moreira Silva</strong>:
  - Correções no UX/UI design:
    - [Update README.md #13](https://github.com/Cronos-Develop/Front-End/pull/13)Revisor: [Luiz Filipe de Souza Alves](https://github.com/LuFi-1227)
- <strong>Antônio Cássio de Oliveira Neto</strong>:
  - Criação e layout das telas do aplicativo:
    - [Merge pull request #11 from Cronos-Develop/ACNprogrammer-feature](https://github.com/Cronos-Develop/Front-End/commit/13c4fc829ed6e8a7f1dda1b6dbc6ed162a4f8b28) Revisor: [Patryck Henryck Moreira Silva](https://github.com/PHmore)
- <strong>Luis Felipe Krause de Castro</strong>:
  - Correção de Bugs na API:
    - [Merge pull request #12 from Cronos-Develop/bugfix-Empresas](https://github.com/Cronos-Develop/API/commit/c82ede82d8fc3d2692a495ce48d11b465c05c20f) Revisor: [João Victor Ribeiro Santos](https://github.com/Carecovisk)
- <strong>João Victor Ribeiro Santos</strong>:
  - Correção de Bugs e criação de documentação:
    - [Merge pull request #10 from Cronos-Develop/feature-Carecovisk](https://github.com/Cronos-Develop/API/commit/f7ec32f24b1f2bc15d7d5b5e43917dcc63d483b8) Revisor: [Luis Felipe Krause de Castro](https://github.com/LuisFelipeKrause)

### Releases:
- Front-End:
  - [v0.0.2](https://github.com/Cronos-Develop/API/releases/tag/v0.0.2)
    - Revisores:
      - [Antônio Cássio de Oliveira Neto](https://github.com/Cronos-Develop/.github/commit/9fd284fe6e11f3bf5b0f2acbab902c3936700ffb)
      - [Patryck Henryck Moreira Silva](https://github.com/PHmore)
      - [Luiz Filipe de Souza Alves](https://github.com/LuFi-1227)
- Back-End:
  - [v0.0.2](https://github.com/Cronos-Develop/Front-End/releases/tag/v0.0.2)
    - Revisores:
      - [Luis Felipe Krause de Castro](https://github.com/LuisFelipeKrause)
      - [Luiz Filipe de Souza Alves](https://github.com/LuFi-1227)
- Documentação Principal:
  - [v2.0.2]()
    - Revisor:
      - [Luiz Filipe de Souza Alves](https://github.com/LuFi-1227)
        
### Sprint 5:
#### Metas da Sprint:
#### Relatório de Gestão (por pessoa):
- <strong>Luiz Filipe de Souza Alves</strong>:
  
- <strong>Patryck Henryck Moreira Silva</strong>:
  
- <strong>Antônio Cássio de Oliveira Neto</strong>:
 
- <strong>Luis Felipe Krause de Castro</strong>:

- <strong>João Victor Ribeiro Santos</strong>:
  
### Sprint final:

## Documentação:
Aqui se encontram as documentações dos repositórios utilizados na criação desta aplicação.

### Organização:
- [link](https://github.com/Cronos-Develop)
### Front-end:
- [link](https://github.com/Cronos-Develop/Front-End)
### Back-end:
- [link](https://github.com/Cronos-Develop/API)
### UX/UI design:
- [link](https://github.com/Cronos-Develop/Front-End)
