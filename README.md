# Aplicativo de Gerenciamento de Usuários

Este projeto é um aplicativo React Native que permite listar, visualizar, criar, editar e excluir usuários de uma API mockada.

## Instalação

1. Certifique-se de ter o ambiente de desenvolvimento React Native configurado em sua máquina.

2. Clone este repositório:
```
git clone https://github.com/seu-usuario/nome-do-repositorio.git
```

3. Instale as dependências do projeto:
```
cd nome-do-repositorio
npm install
```

## Execução
Para executar o aplicativo no emulador ou dispositivo, execute o seguinte comando:
```
npm start
```

Isso abrirá o Metro Bundler no navegador. A partir daí, você pode iniciar o aplicativo no emulador Android ou iOS pressionando as teclas `a` ou `i`, respectivamente, no terminal.

## Funcionalidades

O aplicativo possui as seguintes funcionalidades:

- **Listar Usuários:** Visualize uma lista de usuários cadastrados.
- **Visualizar Detalhes:** Veja os detalhes de um usuário, incluindo seu nome e sobrenome.
- **Criar Usuário:** Adicione um novo usuário fornecendo seu nome, sobrenome e email.
- **Editar Usuário:** Atualize as informações de um usuário existente.
- **Excluir Usuário:** Remova um usuário da lista.

## Componentes,Pages e Serviços

### Pages

- **`UsersListScreen`:** Este componente exibe uma lista de usuários e fornece opções para visualizar os detalhes de cada usuário e adicionar um novo usuário.

- **`UserDetailsScreen`:** Este componente permite visualizar, criar, editar e excluir um usuário. Ele inclui campos para inserir o primeiro nome, sobrenome e email do usuário.
- 
### Componentes 

- ** `Notificação`:** O aplicativo utiliza um componente de notificação para exibir mensagens em dispositivos Android. Este componente é útil para fornecer feedback visual ao usuário sobre ações ou eventos importantes.

### Serviços

- **`api.ts`:** Este arquivo contém funções para interagir com a API de usuários. Ele inclui métodos para buscar todos os usuários, buscar um usuário por ID, criar um novo usuário, editar um usuário existente e excluir um usuário.

## Contribuição

Sinta-se à vontade para contribuir com este projeto. Você pode abrir uma issue para relatar problemas ou solicitar novas funcionalidades. Além disso, pull requests são bem-vindos!

## Anna.


