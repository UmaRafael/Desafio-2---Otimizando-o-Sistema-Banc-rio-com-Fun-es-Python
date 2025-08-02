# Desafio-2-Otimizando-o-Sistema-Bancário-com-Funções-Python
Mudanças

Modularização:

Cada operação bancária foi separada em sua própria função
Funções específicas para criação de usuários e contas

Parâmetros:

depositar: usa apenas parâmetros posicionais
sacar: usa apenas parâmetros nomeados (keyword only)
exibir_extrato: usa parâmetro posicional (saldo) e nomeado (extrato)

Novas funcionalidades:
criar_usuario: valida CPF único e formata nome em maiúsculas
criar_conta: gera número sequencial de 6 dígitos e vincula a um usuário
filtrar_usuario: auxiliar para encontrar usuário por CPF

Validações:

Verifica se CPF já existe antes de criar novo usuário
Verifica se usuário existe antes de criar conta
Valida formato do nome (apenas letras)

Estrutura de dados:

Usuários armazenados em lista de dicionários
Contas armazenadas em lista separada, com referência ao usuário
