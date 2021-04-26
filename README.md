# Token - Kcife (KCF)
Quem nunca sonhou em criar a sua própria criptomoeda ou token?
Bem eu já, tenho isso em mente busquei entender como funciona o processo para a criação de um token utilizando o padrão ERC-20 na rede Ethereum e irei descrever nesse repositório como eu criei o meu próprio Token.

![image](https://user-images.githubusercontent.com/40063504/116113287-bd835600-a68e-11eb-8677-9bb6b5789e68.png)


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

Clique no botão "Deploy & Run Transactions", em seguida selecione em Enviroment o campo "Inject Web3". Ao realizar isso se você não estiver logado em sua conta no MetaMask ele irá abrir e pedirá para sincronizar com a conta e realizar a cobrança de uma taxa para criação do contrato na rede Ropsten, pode realizar o procedimento normalmente.

![image](https://user-images.githubusercontent.com/40063504/116110321-f79f2880-a68b-11eb-9b08-3cbf3560e673.png)

![2](https://user-images.githubusercontent.com/40063504/116110591-3a610080-a68c-11eb-97ca-7568aaec0101.PNG)

Após alguns segundos uma mensagem simbolizando a criação do contrato será apresentada no terminal:

![image](https://user-images.githubusercontent.com/40063504/116110766-5cf31980-a68c-11eb-9a29-12c328d60375.png)

Você pode encontrar o numero do contrato criado aqui:

![image](https://user-images.githubusercontent.com/40063504/116111008-9af03d80-a68c-11eb-99ee-56b75abb39c6.png)


Parabéns você acabou de criar o seu Token!!!
Agora você pode validar a criação do seu contrato acessando o site abaixo e informando o numero do contrato nele:
https://ropsten.etherscan.io/

![image](https://user-images.githubusercontent.com/40063504/116111677-40a3ac80-a68d-11eb-8d5b-140cdaef07de.png)


## Como listar o meu Token no MetaMask?
Com o numero do contrato em mãos acesse a extensão do MetaMask em seu navegador e clique em "Adcionar token":

![image](https://user-images.githubusercontent.com/40063504/116111884-6df05a80-a68d-11eb-96f9-868ab3bb3fe4.png)

Clique me "Token personalizado" e entre com o endereço de contrato, perceba que ele já irá identificar o simbolo do token criado:

![image](https://user-images.githubusercontent.com/40063504/116112042-924c3700-a68d-11eb-9d56-bf195b272eb7.png)

Após isso basta apenas clicar em "Adcionar tokens" e vocês irá poder vê-los em sua carteira:

![image](https://user-images.githubusercontent.com/40063504/116112140-ac861500-a68d-11eb-9d67-2ddcfc4f8111.png)

![image](https://user-images.githubusercontent.com/40063504/116112450-f242dd80-a68d-11eb-8f50-945018b35fdf.png)


Obs: Como eu ja havia feito o processo anteriormente você vera que tem uma diferença do simbolo do meu token original KCF para o outro KCt, criado agora para exemplificar.





