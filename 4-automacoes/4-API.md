## API
> Aplications Programming Interface 
- Consulta externas de qualquer software 
- Interface: contrato de serviço
- Arquitetura _cliente x servidor_
	- SOAP
		- XML
	- RPC (_chamadas de procedimentos remotos_)
	- WebScocket
		- JSON
		- Bidirecional
	- REST
***
## API SYDLE ONE
- Métodos das classes são automaticamente disponibilizados. 
- EndPoint gerador com base nos identificadores de pacotes, classe e método

![Alt text](<../img/Pasted image 20240216130053.png>)
## API externas
- HTPP/HTPPS
- JSON e XML
- Biblioteca XMLHTPPREQUEST 
	- *Não suporta realização de requisições assíncronas*
- Recomendação de classe para centralização das integrações
- Requisição padrão da lib JavaScript
	![[Pasted image 20240216135520.png]]
- Recomendação para não ficar verboso	![[Pasted image 20240216135559.png]]
## Utilização da API Interna
```js
one.sydle.training.crm.pessoa._create({
nome: "Diego",
cPF: "111.111.111-11",
})
```