# Locadora de Filmes

Este é um sistema de locadora de filmes desenvolvido em PHP e MySQL. Ele permite que os usuários cadastrem-se, pesquisem por filmes disponíveis, realizem locações e visualizem seu histórico de locações.

## Funcionalidades

- **Cadastro de Usuários:** Os usuários podem se cadastrar no sistema fornecendo informações básicas.
- **Pesquisa de Filmes:** Os usuários podem pesquisar por filmes disponíveis na locadora.
- **Locação de Filmes:** Os usuários podem alugar filmes disponíveis.
- **Histórico de Locações:** Os usuários podem visualizar seu histórico de locações.

## Requisitos do Sistema

- PHP >= 7.0
- MySQL
- Servidor Web (por exemplo, Apache, Nginx)

## Instalação

1. **Clone o repositório:**
git clone https://github.com/Drey021/Locadora


2. **Importe o banco de dados:**
- Importe o arquivo `database.sql` para o seu banco de dados MySQL. Este arquivo contém a estrutura do banco de dados necessário para o funcionamento do sistema.

3. **Configure as informações de conexão com o banco de dados:**
- No arquivo `config.php` localizado na pasta `includes`, configure as informações de conexão com o banco de dados.
  ```php
  define('DB_HOST', 'localhost');
  define('DB_USER', 'seu_usuario');
  define('DB_PASS', 'sua_senha');
  define('DB_NAME', 'nome_do_banco_de_dados');
  ```

4. **Inicie seu servidor web.**
5. **Acesse o sistema pelo navegador:**
Por exemplo: http://localhost/Locadora

6. **La tera as seguintes informações:**

| Campo     | Informações ja presentes |
| ---      | ---       |
|Usuário:| andrey|
|Senha:| 03ac674216f3e15c761ee1a5e255f067953623c8b388b4459e13f978d7c846f4|
|nomeUser:| andrey|

7. Quando entrar na página principal, você ja sera direcionado automaticamente para o login. Onde o nome de LOGIN é: **andrey** e a SENHA é: **abcd**.

8. Pronto ja estara com seu sistema pronto para uso ;) 

## Contribuição

Contribuições são bem-vindas! Sinta-se à vontade para abrir issues para relatar bugs, sugerir melhorias ou enviar pull requests.

## Licença

Este projeto está licenciado sob a **Licença MIT**.

