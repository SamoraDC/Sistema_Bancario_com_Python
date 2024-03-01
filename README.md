# Sistema_Bancario_com_Python
Sistema Bancário que possibilita cadastro de usuário, criação de conta, deposito, saque, conferir extrato e listar contas

O sistema incorpora várias classes e métodos para simular operações bancárias. As principais entidades são:

    Cliente: Representa um cliente do banco, capaz de possuir múltiplas contas.
    Conta: Abstrai uma conta bancária genérica, oferecendo funcionalidades como depósito e saque.
    ContaCorrente: Uma especialização de Conta, adicionando regras específicas como limites de saque.
    Transacao: Uma classe abstrata que define a estrutura para transações financeiras.
    Deposito/Saque: Implementações de Transacao para movimentações financeiras específicas.
    Historico: Registra as transações realizadas em uma conta.
