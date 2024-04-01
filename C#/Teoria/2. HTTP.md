
## REQUISIÇÃO
Uma requisição HTTP se divide em três partes

1. **Request Line** - 
	1. Método HTTP (ex GET)
	2. URI (ex /api/livros)
	3. Protocolo HTTP (ex HTTP/1.1)
2. **Headers**
	1. Metadados se enviam na requisição com informação
3. **Body**
	1. Informação adicional enviado ao servidor

## RESPONSE
1. **Status line**
	1. Indica o status da requisição (Código)
2. **Headers**
	1. Metadados que se enviam na resposta
3. **Body**
	1. Dados enviados pelo servidor

![[Pasted image 20240321235840.png]]
## MÉTODOS

- **GET**
	- Recuperar informações
	- Não altera dados
	- Idempotente (produz sempre o mesmo resultado se repetida)
- **POST**
	- Cria informações
	- Altera o estado do recurso
	- Não são idempotentes 
- **PUT**
	- Atualizar informações
	- Alteram o estado do recurso
	- São idempotentes
- **PATCH**
- **DELETE**
	- Usado para deletar uma informação
	- Alteram dados do recurso
	- São idempotentes

![[Pasted image 20240322000557.png]]
