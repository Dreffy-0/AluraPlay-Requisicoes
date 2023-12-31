<p align="center"> <img src="https://imgur.com/J3hD21O.png" alt="Javascript: criando requisições"> </p>

<hr>

<p align="center"> <img src="https://github.com/MonicaHillman/aluraplay-requisicoes/blob/main/img/logo.png" alt="Logo da Alura"> </p>
<p align="center">Página inicial e formulário de cadastro de vídeos da AluraPlay, uma plataforma de compartilhamento de vídeos.</p>

---

## Se trata de uma plataforma onde se tem alguns vídeos de dicas e curiosidades da empresa alura

## O que foi feito durante o curso

<p align="center">Durante o curso foi feito 4 arquivos de Scripts em JavaScript para tornar a página dinâmica atualizando o conteúdo sempre que o usuário adicionasse um novo vídeo, sem a necessidade de alterar o código manualmente, modificando o html ou o arquivo db.json manualmente, dessa forma evitando que usuários mais leigos em programação, modifiquem de maneira incorreta e prejudicando o funcionamento da página. </p>

## Tecnologias utilizadas durante o curso

-   Javascript
-   NodeJS
-   Json-server

## Tecnologias utilizadas no projeto

-   HTML
-   CSS

## Observações do projeto

<p align="center">Por ser um projeto que foi feito utilizando o json-server que simula um servidor local é necessário fazer alguns passos para que funcione de maneira correta </p>

## Como acessar e fazer o projeto funcionar

-   Baixe o software NodeJs digitando o gerenciador de pacotes do linux digitando os seguintes passos:
-   1 - `sudo apt-get install curl` (No terminal, digite o comando de instalação do curl)
-   2 - `curl -fsSL https://deb.nodesource.com/setup_lts.x | sudo -E bash -` (Execute o script para adicionar o repositório do Node);
-   3 - `sudo apt-get install -y nodejs` (E por fim, para instalar o Node execute:)
    *** Caso esteja utilizando o windows ou mac entre no site do <a href="https://nodejs.org/">NodeJs</a> ***
-   Depois de baixar e instalar o Node, utilizando o console que estiver usando vá ate a pasta onde esta localizado os arquivos do projeto
-   1 - Agora vamos iniciar um novo pacote NPM utilizando o `npm init` (verifique que está no diretorio correto)
-   2 - Com o novo pacote NPM criado, vamos adicionar a biblioteca do json-server escrevendo `npm install` json-server
    *** Em sistemas Windows pode ocorrer o problema de o sistema não permitir a execução de scripts, para saber mais e conseguir resolver o problema sugiro a leitura da documentação das <a href="https://learn.microsoft.com/pt-br/powershell/module/microsoft.powershell.core/about/about_execution_policies?view=powershell-7.3#remotesigned">políticas de execução do powershell</a> ***
-   3 - Depois de finalizado, vamos iniciar o pacote usando o comando `json-server --watch db.json`
-   **_ Caso de algum problema, pode utilizar o executor de pacotes usando `npm json-server --watch db.json` _**
-   Com esses passos feitos, abra o arquivo e se estiver tudo corretamente configurado vai aparecer o projeto funcionando normalmente

## Screenshots

![Screenshot da tela inicial do AluraPlay](https://imgur.com/aymxEsh.png)
![Screenshot da tela do formulário do AluraPlay](https://imgur.com/ShNADf2.png)
#   A l u r a P l a y - R e q u i s i ç õ e s 
 
 
