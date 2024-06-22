# Banco Digital Versão 1.0.0

## Descrição
Este projeto é uma implementação de um Banco Digital com funções de conta corrente e conta poupança, desenvolvido em Java. Ele oferece funcionalidades básicas para gerenciamento de contas, como criação de contas, depósitos, saques e transferências.

## Estrutura do Projeto

- **Banco.java**: Classe principal que gerencia as operações do banco.
- **Cliente.java**: Classe que representa um cliente do banco.
- **Conta.java**: Classe abstrata que define os atributos e métodos comuns para as contas.
- **ContaCorrente.java**: Classe que representa uma conta corrente e estende a classe `Conta`.
- **ContaPoupanca.java**: Classe que representa uma conta poupança e estende a classe `Conta`.
- **InterfaceConta.java**: Interface que define os métodos que devem ser implementados pelas classes de conta.
- **Main.java**: Classe principal que contém o método `main` para executar o programa.

## Funcionalidades

- **Criação de Contas**: Permite a criação de contas correntes e poupança para clientes.
- **Depósitos**: Permite depósitos em contas correntes e poupança.
- **Saques**: Permite saques de contas correntes e poupança.
- **Transferências**: Permite transferências entre contas correntes e poupança.

## Como Executar

1. Clone o repositório para sua máquina local:
    ```sh
    git clone https://github.com/seu-usuario/banco-digital.git
    ```
2. Navegue até o diretório do projeto:
    ```sh
    cd banco-digital
    ```
3. Compile os arquivos Java:
    ```sh
    javac *.java
    ```
4. Execute a aplicação:
    ```sh
    java Main
    ```

## Contribuição

Contribuições são bem-vindas! Se você quiser melhorar o projeto ou adicionar novas funcionalidades, por favor, siga os passos abaixo:

1. Faça um fork do projeto.
2. Crie uma nova branch com a sua feature: `git checkout -b minha-feature`
3. Faça commit das suas alterações: `git commit -m 'Adiciona minha feature'`
4. Faça push para a branch: `git push origin minha-feature`
5. Abra um Pull Request

## Licença

Este projeto está licenciado sob a licença MIT - veja o arquivo [LICENSE](LICENSE) para mais detalhes.

## Contato

Autor: Kaique Mendes  
Email: kaiquemendesn10@gmail.com

