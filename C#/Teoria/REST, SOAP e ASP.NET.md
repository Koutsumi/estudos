## SOAP
Protocolo **W3C** baseado em XML, usado para trocar informações entre aplicações no mesmo ou em diferentes sistemas operacionais 

## REST 
REST, ou Representational State Transfer, é um **estilo arquitetônico aplicado para fornecer padrões entre sistemas de computador na web, facilitando a comunicação entre eles**. Os sistemas em conformidade com REST, muitas vezes conhecidos como sistemas RESTful, são reconhecidos pelo jeito como separam as preocupações do cliente e do servidor.

Há um conjunto de regras que precisam ser seguidas:
- Ter um relacionamento cliente/servidor
- Não possuir monitoração de estado *(stateless)*
- Ter uma interface uniforme *(URIs - endpoint, representação, mensagens auto-descritivas, hipermidia)*
- Suportar cache de dados e respostas
- Suportar um sistema em camadas

![[Pasted image 20240322001932.png]]

## REST x SOAP

1. **REST** é um estilo arquitetural
2. **SOAP** é um protocolo

- **REST**
	- Usa JSON ou XML para enviar/receber dados
	- Não precisa de muita largura de banda
	- Trabalha com textos (XML, JSON, HTML)
	- Usa os verbos HTTP (GET, PUT, PATCH, POST, DELETE) para acessar um serviço
	- Invoca os serviços via URI
- **SOAP**
	- Usa WSDL para comunicação com o cliente/provedor
	- Precisa de mais largura de banda
	- Trabalha praticamente com XML
	- Independente de protocolo 
	- Invoca os serviços usando métodos RPC

## ASP.NET Core
Framework da Microsoft para criar Web APIs anderentes ao estilo REST 