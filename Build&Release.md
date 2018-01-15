# Manual de Configuração de Build e Release no modelo Padrão

## Acesse o portal do TFS em "Projects" clique em "Build & Release

![No portal TFS](./img/02.png)

## Clique no botão "+New"
![No portal TFS](./img/03.png)

## Adicione Feature ".NET Desktop
![No portal TFS](./img/03.2.png)

## Esta opção traz uma seguência de tasks que precisam ser Configuradas para o build
![No portal TFS](./img/04.png)

## Configure o "Get Sources" mapeando o branch e drop
![No portal TFS](./img/05.png)

## Na Aba "Variables" configure:
* BuildConfiguration como "Release"

* BuildPlatform como "any cpu"

* Marque a caixa das variaveis configuradas

![No portal TFS](./img/06.png)
## Em triger você tem a opção de marcar a integração continua para o projeto.
![No portal TFS](./img/07.png)

## Em "Options" verifique se o agent de build esta configurado ou selecione a fila desejada
![No portal TFS](./img/08.png)

##
![No portal TFS](./img/09.png)