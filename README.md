# experimentos referentes a arquitetura de sistemas

# experimento 1

- procedimento

  1.Utilizar a opção 1 para somar dois números

  2.utilizar a segunda opção para converter um texto para maiusculo

- explicação

a chamada e feita no cliente, o processamento ocorre remotamente. O cliente envia os dados ao servidor, que executa a função (exposed_somar ou exposed_maiusculas) e retorna o resultado.

a operação foi feita no servidor

# experimento 2

- procedimento

  1.Utilizar as opções 3, 4 e 5 para manipular a lista remota

- explicação

A lista foi definida no servidor como um atributo de classe

Todos os clientes acessam a mesma lista

O estado é centralizado no servidor

Se múltiplos clientes forem utilizados, todos verão as mesmas alterações, comprovando que os dados não estão armazenados localmente no cliente.

a lista esta no servidor
