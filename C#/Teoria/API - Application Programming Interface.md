Conjunto de rotinas e padrões estabelecidos e documentados por uma aplicação para que outras aplicações consigam utilizar suas funcionalidades se precisar conhecer detalhadamente da sua implementação

## WEB SERVICES

Conjunto de métodos invocados por outras aplicações utilizando tecnologias web sendo uma solução utilizada na integração de sistemas e na comunicação entre aplicações distintas 

## API x WEB SERVICES 

1. Nem toda **API** é um **WEB SERVICE**
2. Todo **WEB SERVICE** é uma **API**

- **WEB SERVICE**
	- Usam apenas 3 meios de comunicação
		- SOAP
		- REST
		- XML-RPC
	- São autocontidas e auto descritivas, podendo ser publicados, localizados e invocados na Web
	- Podem não realizar todas as operações que uma API faz
	- Requer um protocolo SOAP para receber e enviar dados pela rede, portanto não é uma arquitetura leve
	- Necessita de uma rede para seu funcionamento
	- Tendem a oferecer funcionalidades especificas a usuários específicos 
- **API**
	- Pode usar qualquer meio de comunicação
	- São de código aberto e podem ser usadas em qualquer lugar
	- Podem realizar todas as operações dos **web services**
	- É uma arquitetura leve para dispositivos com largura de banda limitada, como celulares
	- Não precisa de uma rede para funcionar
	- Tendem a serem abertas a qualquer tipo de usuário que a pretende consumir 

## WEB API
É uma API na internet, com um conjunto de serviços expostos via web para realizar a integração da aplicação com diversos tipos de clientes (web, mobilem desktop, etc.)