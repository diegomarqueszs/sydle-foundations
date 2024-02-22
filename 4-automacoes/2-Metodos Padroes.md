## Métodos Padrões
Conjunto de operações comuns a todas as classes, permissões configuráveis.
***
## _CRUD_
- Create
- Read
- Update
- Delete
> Automações são criadas por comportamentos default. Também, utiliza-se interfaces dos SYDLE ONE. 
***

### Métodos configuráveis:
- Criar
- Obter
- Atualizar 
- Remover

### Métodos que permitem script
- Criar rascunho
- Salvar
- Obter metadata
- Atualizar rascunho
![[Pasted image 20240214140003 1.png]]

> Um método dinâmico é inserindo dentro do método obter controle de acesso

### Buscar X Obter
____search_ (buscar)
- Buscas complexas, where ...  
- Utiliza-se parâmetros ([querys](https://servicedesk.sydle.com/portal/i/5da4dd8ae414bc54cb3387f3?q=queries%20de%20consulta&s=62eaba3cc8669161253b8349))
	- 

____get_ (obter)
- Obtém o objeto pelo _ID_

____object 
- Sempre apontará para o contexto atual (escopo). 