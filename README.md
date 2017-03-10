# Godroid

Script para compilar projetos em Phonegap/Cordova com gerenciamento de versão do [Crosswalk Project](https://crosswalk-project.org/).

## Instalação

Para instalar o projeto basta criar um link simbólico do script para a pasta `/usr/bin`. Lembrar de dar permissões de execução para o usuário.

## Utilização

Com o godroid é possível compilar um projeto normalmente, ou compilar para uma versão que necessita do Crosswalk.

**Compila normalmente:**

    $ godroid

**Compila limpando a pasta android:**

    $ godroid -c | --clean

**Compila versão para Crosswalk:**

    $ godroid -w | --walk

**Compila versão para Crosswalk v1.8.0, última versão com suporte para android 15:**

    $ godroid -w-o | --walk-old

**Remove Crosswalk:**

    $ godroid -w-r | --walk-remove

**Executa o gulp antes de compilar:**

    $ godroid -g | --gulp

## Licença

O godroid é open-source com licença [MIT](https://opensource.org/licenses/MIT).
