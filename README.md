# Requisitos

- Docker 1.11+ [>>](https://docs.docker.com/engine/installation/)
- Docksal [>>](http://docksal.readthedocs.io/en/develop/env-setup/)

##  Como usar
- **fin start**: Sobe os containers básicos (LAMP)
- **fin all**: Executa todas as taréfas para disponibilizar um ambiente para desenvolvimento local


## Comandos
 - **fin build_front**: Instala as dependencias do theme e faz um build dos assets
 - **fin start_front**: Instala as dependencias do theme e abre o sublime para edição
 - **fin serve_front**: Inicia um servidor local com watch
 - **fin setup_regression_tests**: Faz o setup para testes de regressão visual usando Backstopjs
 - **fin regression_referenc**e: Gera a referencia de prints com base nos cenários escritos em backstop.json
 - **fin regression_test**: Gera novos prints e compara com a referência ja salva
 - **fin download_drupal**: Faz download do drupal 8.3.2 para o projeto  e coloca na pasta docroot/
 - **fin config_drupal**: Faz setup básico do drupal para base do serve docksal e configura caches para livereload
 - **fin install_theme**: Instala o theme Básico com stylus + babel ECMAscript6 + Browsersync with gulp
 - **fin config_git**: Remove as configs defaut do repositório para possibilitar uma nova config


 ## Todo
 - Containerizar o frontools
 - Traduzir para o inglês
 - Mudar para o nginx