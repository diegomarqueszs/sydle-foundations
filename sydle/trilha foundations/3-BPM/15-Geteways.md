Desvios `switch case`
- Fluxo normal
	- Tem prioridade ao fluxo padrão
- Fluxo condicional
	- Necessário atendar a condição
- Fluxo padrão
	- Verifica se nenhum fluxo foi acionado para ser acionado. 
Podem ser usados como _ramificação_ ou _convergência_. 

Sempre recebe em fluxo ou direciona para apenas um fluxo. 

![[Pasted image 20240209104222.png]]Cada **_gateway_** possui sua regra de **divisão** e **unificação**, descritos pela tabela e imagem:

|Tipo|Divisão|Unificação|
|---|---|---|
|**Exclusivo**|Seleciona somente **uma** saída|Basta **uma** entrada para que o fluxo seja ativado|
|**Paralelo**|**Todas** as saídas são ativadas|Aguarda **todas** as entradas para que siga|
|**Inclusivo**|**Um a todos** caminhos podem ser seguidos|Aguarda todas entradas **ativas** estarem completas|
