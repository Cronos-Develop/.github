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
- <strong>Patryck Henryck Moreira Silva</strong>:
  - Criar UX/UI design:
    - [Merge pull request #4 from Cronos-Develop/PHmore-feature](https://github.com/Cronos-Develop/Front-End/commit/23285d25e7b008221a3cc20e01f8aed39c32263b) Revisor: [Antônio Cássio de Oliveira Neto](https://github.com/Cronos-Develop/.github/commit/9fd284fe6e11f3bf5b0f2acbab902c3936700ffb)
  - Criar UserFlow da aplicação:
    - [Merge pull request #4 from Cronos-Develop/PHmore-feature](https://github.com/Cronos-Develop/Front-End/commit/23285d25e7b008221a3cc20e01f8aed39c32263b) Revisor: [Antônio Cássio de Oliveira Neto](https://github.com/Cronos-Develop/.github/commit/9fd284fe6e11f3bf5b0f2acbab902c3936700ffb)
- <strong>Antônio Cássio de Oliveira Neto</strong>:
  - Criar tela inicial:
  - Criar tela de cadastro:
- <strong>Luis Felipe Krause de Castro</strong>:
  - Modelagem da Index na API:
- <strong>João Victor Ribeiro Santos</strong>:
  - Modelagem e criação do banco de dados:

### Sprint 3:
#### Metas da Sprint:
#### Relatório de Gestão (por pessoa):
- <strong>Luiz Filipe de Souza Alves</strong>:
- <strong>Patryck Henryck Moreira Silva</strong>:
- <strong>Antônio Cássio de Oliveira Neto</strong>:
- <strong>Luis Felipe Krause de Castro</strong>:
- <strong>João Victor Ribeiro Santos</strong>:
  
### Sprint 4:
#### Metas da Sprint:
#### Relatório de Gestão (por pessoa):
- <strong>Luiz Filipe de Souza Alves</strong>:
  
- <strong>Patryck Henryck Moreira Silva</strong>:
  
- <strong>Antônio Cássio de Oliveira Neto</strong>:
 
- <strong>Luis Felipe Krause de Castro</strong>:

- <strong>João Victor Ribeiro Santos</strong>:
  
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
### Front-end:
### Back-end:
### UX/UI design:
