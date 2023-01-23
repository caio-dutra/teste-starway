## Descritivo



#### Não foi identificado erro na estrutura de dados.

#### Foi feito reajuste na saída de dados para melhor experiência do usuário.

#### As classes Cliente, Empresa, Produto, Usuario e Venda estão encapsuladas com Getters e Setters.

#### O método toList() está indefinido para o tipo stream na classe Main, método interno criarVenda.



#### Na regra do negócio:

#### O saldo das empresas não está incrementando de acordo com cada compra, isto porque no método criarVenda da classe Main, o método interno toList() está indefinido para o tipo stream, logo a somatória do saldo não está sendo feita a cada compra realizada. 

#### Na opção ver compras, não é apresentado nada ao usuário, isto porque a condição esta atribuido a usuarioLogado, e cliente ja cadastrado como 'Allan da Silva'

#### Na opção 'Digite 0 para deslogar' o sistema volta a pedir dados de entrada(usuário,senha), isto poderia ser resolvido condicionando o numero 0 na estrutura de repetição while-do, o programa se encerraria, enquanto o bloco de código estaria no DO.



