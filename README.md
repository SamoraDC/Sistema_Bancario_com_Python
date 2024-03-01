# Sistema Bancário com Python
O sistema foi concebido para fornecer uma estrutura básica para a gestão de clientes, contas bancárias, e transações financeiras, incluindo depósitos e saques, com suporte à adição de histórico de transações.

## Estrutura do Código

### Bibliotecas Importadas

    textwrap: Utilizado para formatar textos exibidos no terminal.
    abc: Importa ABC, abstractclassmethod, e abstractproperty para criar classes e métodos abstratos.
    datetime: Usado para registrar o momento exato de cada transação.

### Classes Principais

    Cliente: Armazena informações do cliente e contas associadas.
    PessoaFisica: Subclasse de Cliente, adiciona atributos específicos de pessoas físicas.
    Conta: Define atributos e métodos comuns a todos os tipos de contas.
    ContaCorrente: Herda de Conta, especializando-a para contas correntes.
    Historico: Responsável por armazenar o histórico de transações de uma conta.
    Transacao, Deposito, Saque: Abstraem as operações financeiras.
    
### Funções de Interface com o Usuário e Uso do Sistema

O sistema oferece um menu interativo com opções para:

    Depositar e sacar valores.
    Exibir o extrato de uma conta.
    Criar novos clientes e contas.
    Listar todas as contas existentes.


    Cada opção é acompanhada de instruções sobre como proceder, incluindo a inserção de dados necessários para cada operação.

## Conclusão
    Este sistema de gestão bancária é uma ferramenta simples, porém robusta, que simula operações bancárias básicas. 
    Ele foi projetado para ser expansível, permitindo futuras melhorias e adições de novas funcionalidades.
