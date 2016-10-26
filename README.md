# Godroid

Script para compilar projetos em Phonegap/Cordova com gerenciamento de versão do [Crosswalk Project](https://crosswalk-project.org/).

## Instalação

Para instalar o projeto basta criar um link simbólico do script para a pasta `/usr/bin`. Lembrar de dar permissões de execução para o usuário.

## Utilização

Com o godroid é possível compilar um projeto normalmente, ou compilar para uma versão que necessita do Crosswalk.

**Compilar normalmente:**

    $ godroid

**Compilar versão para Crosswalk:**

    $ godroid -walk

**Compilar versão para Crosswalk v1.8.0, última versão com suporte para android 15:**

    $ godroid -walk-old

**Retornar para versão sem Crosswalk:**

    $ godroid -clean

## Licença

O godroid é um script open-source com licença [MIT](https://opensource.org/licenses/MIT).
