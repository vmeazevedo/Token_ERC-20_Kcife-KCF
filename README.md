# Token - Kcife (KCF)
Quem nunca sonhou em criar a sua própria criptomoeda ou token?
Bem eu já, tenho isso em mente busquei entender como funciona o processo para a criação de um token utilizando o padrão ERC-20 na rede Ethereum e irei descrever nesse repositório como eu criei o meu próprio Token.

## Porque Kcife?
No sentido figurado de cacife significa: dinheiro, potencial, capacidade, força, competência.
Ter cacife significa ter capacidade, conhecimento, dinheiro ou quaisquer outros meios necessários para a entrada de alguém em algo, é uma giria antiga brasileira que representa que o portador tem algo de valor, e por isso nomiei minha Token de Kcife, por que no final todo mundo quer ter cacife! rsrs.

## O que é o padrão ERC-20?
Na Ethereum, a sigla significa "Ethereum Request for Comments". São documentos técnicos que descrevem padrões de programação na Ethereum. O padrão ERC-20 propõe um formato relativamente simples para tokens com base na Ethereum, sendo assim, assim que novos tokens ERC-20 são criados, eles são automaticamente interoperáveis com serviços e softwares com suporte para o padrão ERC-20.

## Primeiros passos
Primeiramente precisamos acessar o site abaixo para realizar a criação de nossa Token:
https://remix.ethereum.org/#optimize=false&runs=200&evmVersion=null&version=soljson-v0.8.2+commit.661d1103.js

Dentro do site selecione a opção a esquerda de "Create New File" e renomei ele com o nome do seu Token. Ao final coloque a extensão ".sol":

![image](https://user-images.githubusercontent.com/40063504/116105941-2ca97c00-a688-11eb-92d2-a5c3ca13b1ad.png)

Feito isso acesse o arquivo nesses repositório chamado "Kcife-Token.sol" e copie e cole o código para a area de trabalho do site:

![image](https://user-images.githubusercontent.com/40063504/116106457-7db97000-a688-11eb-9f79-8d81745ae2ab.png)

Feito isso chegou a hora de dar um nome ao seu Token, seja criativo e preencha os campos que estão dentro das "" com o nome e simbolo que te agrade:

![image](https://user-images.githubusercontent.com/40063504/116106646-b0636880-a688-11eb-86c7-c96ad41cdac9.png)

Após isso, clique no botão "Solidity Compiler" e depois em "Compile Token", se tudo estiver correto você não recebera uma mensagem de erro rs:

![image](https://user-images.githubusercontent.com/40063504/116106872-ddb01680-a688-11eb-983c-7916112ee98a.png)

Dessa forma nosso contrato está criado com sucesso, porém para realizarmos o deplo dele na rede de teste primeiramente precisamos configurar o MetaMask em nosso navegador.
Acesse o site abaixo e realizar o download e instalaçao da extensão:
https://metamask.io/download.html

Realize o processo de criação de uma nova wallet e cumpra todos os requisitos de segurança que o MetaMask for sugerindo no processo de criação de uma nova conta.

Com a extensão instalada e configurada, clique nela para abrir o menu e selecione a Rede de Testes Ropsten:

![image](https://user-images.githubusercontent.com/40063504/116107572-88c0d000-a689-11eb-8922-4b16b7e76f69.png)

Para finalizarmos o deploy de nosso Token precisamos ter alguns ETH em nossa conta da MetaMask por isso copie o endereço da sua conta e cole no site abaixo para receber alguns ETH gratuito para testes:
https://faucet.ropsten.be/

![image](https://user-images.githubusercontent.com/40063504/116107921-d2a9b600-a689-11eb-941b-b23df24feb00.png)

Com os ethers em nossa conta da MetaMask esta na hora de realizarmos o deploy da nosso novo Token:

![image](https://user-images.githubusercontent.com/40063504/116109537-439d9d80-a68b-11eb-9804-005a228a0153.png)






