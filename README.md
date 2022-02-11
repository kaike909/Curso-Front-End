# Curso-Front-End
Projeto pessoal do curso da EBAC

## Conceitos de versionamento

- Historico
- Controle de Versao
- Quem alterou
- O que alterou
- Quando alterou
- Todos os arquivos
- Evolução continua

Arquivo A | Versao 1 | Versao 2
Arquivo B | Versao 1 | Versao 2

## Instalacao do Git

## Clonar Projeto

Informação de alteração

- Apos testado todo o seu codigo
- git add *
- git commit -m "Mensagem"
- git push (Envia altercoes para o repositorio GitHub)
- git pull (Puxa/traz alteracoes do GitHub para sua maquina)

## GitFlow

Fluxo do Git

### Branchs

Sao ramificacoes/Versoes Paralelas

- main/master (vai para producao, quando o projeto e publicado)
- Develop
- DOD Definition of Done: Criterios de Aceite
- Versionamento Ex:0.1.10/0.1.14/1.0.0;

git checkout -b dev (Cria uma nova branch)
git checkout master (mudar de branch)

### Merge

Mescla das branchs
Voce pode precisar resolver conflitos manualmente

git merge main

### Pull requests

Mescla de branchs no repositorio
Premite code review
O Repositorio resolve conflitos automaticamente

### configura o GitFlow
git flow init

Which branch should be used for bringing forth production releases?
   - dev
   - main
Branch name for production releases: [main] 

Which branch should be used for integration of the "next release"?
   - dev
Branch name for "next release" development: [] dev

How to name your supporting branch prefixes?
Feature branches? [feature/] 
Bugfix branches? [bugfix/] 
Release branches? [release/] 
Hotfix branches? [hotfix/] 
Support branches? [support/] 
Version tag prefix? []

git flow feature start {nome da feature}