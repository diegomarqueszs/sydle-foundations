## Atividades
Sempre esta contextualizada a [RAIA](6-Raias.md), somente o usuário da RAIA, tem acesso.
![Alt text](<../img/Pasted image 20240209103534.png>)
- Atividade Genérica: 
	- Simbólicas, apenas serve para representar tarefas.
- Atividade Humana: 
	- Humanos executando atividades.
	- Atrela um usuário a uma atividade.
	- É possível devolver a atividade
		- Necessário usuário ter autorização
		- Necessário atividade permitir devolução
	- É possível transferir a atividade
- Tarefa de invocação de serviços
	- Contexto externos do sistema BPMS (API externas)
- Tarefa de Execução de Script
	- Contexto internos ao SYDLE ONE, exemplo, script que cadastra clientes.
![Alt text](<../img/Pasted image 20240209101600.png>)

- Subprocesso Referênciado
	- Análogo a referência comum, aponta para um outro processo que já existe.
	- Pode ser executado de forma manual. 
- Subprocesso Embutido
	- Subprocesso que existe dentro do processo, somente no _contexto do processo pai_.
	- Não pode ser executado de forma manual. 
	- 
- Atividade Cíclica
	- Sempre tem um inicio/meio/fim. Envia para o A, espera terminar para enviar para o próximo. 
- Atividade Múltipla
	- Abre de forma simultâneas, envia para o A, B, C simultaneamente.