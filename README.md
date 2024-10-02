![image](https://github.com/user-attachments/assets/f11448ce-8488-4eb4-a134-36e804d36793)

# Book Management App - Tech Challenge

## Projeto - Dev Foundations FIAP

Este projeto faz parte do **Tech Challenge** da pós-graduação em Dev Foundations na FIAP. O objetivo é desenvolver a interface frontend de um sistema de gerenciamento de livros, utilizando **HTML**, **CSS**, **Bootstrap** e **React**.
O objetivo é criar uma interface de usuário funcional e simples que se comunique com o Backend desenvolvido na fase anterior.

## Funcionalidades

- **Home Page**: Uma página inicial simples com boas-vindas ao usuário.
- **Listagem de Livros**: Exibe uma lista de livros cadastrados, com opções de visualizar, editar e deletar cada livro.
- **Adicionar Livro**: Página/modal para adicionar um novo livro ao banco de dados.
- **Editar Livro**: Página/modal para editar informações de um livro existente.

## Tecnologias Utilizadas

- **HTML**: Estrutura das páginas.
- **CSS**: Estilização das páginas com Flexbox e Grid.
- **Bootstrap**: Design responsivo e componentes pré-construídos.
- **React**: Criação de componentes e gerenciamento de estado.

## Pré-requisitos

Antes de iniciar, você precisará ter o [Node.js](https://nodejs.org/) e o [npm](https://www.npmjs.com/) instalados em sua máquina.

## Instalação

Siga os passos abaixo para rodar o projeto localmente:

1. Clone o repositório:
    ```bash
    git clone https://github.com/GRUPO6-3CTJ/Challenge_3.git
    ```

2. Navegue até o diretório do projeto:
    ```bash
    cd nome-do-repositorio
    ```

3. Instale as dependências:
    ```bash
    npm install
    ```

4. Inicie o servidor de desenvolvimento usando o Vite:
    ```bash
    npm run dev
    ```

5. O projeto será iniciado em `http://localhost:3000` (ou a porta especificada pelo Vite).

## Arquivos Necessários

- **Livros.zip**: Este arquivo contém os dados de livros necessários para a aplicação. Descompacte-o e coloque-o na pasta `public` ou em outro diretório específico, conforme a configuração do seu projeto.
- **Projeto.zip**: Arquivo contendo recursos adicionais ou um backup do projeto. Descompacte-o se necessário.

Certifique-se de que os arquivos estão no diretório correto antes de iniciar o projeto.



## Estrutura do Projeto

- **/src**: Contém os arquivos do projeto.
  - **/components**: Componentes React utilizados na aplicação.
  - **/pages**: Páginas do projeto (Home, Listagem, Adicionar, Editar).
  - **/services**: Lógica de conexão com o backend (APIs).

  ## Configuração de Ambiente

O arquivo `vite.config.js` contém as configurações do Vite, incluindo a porta e o proxy para o backend (caso esteja usando). Se necessário, ajuste este arquivo para suas necessidades específicas.

Por exemplo, se você precisar alterar a porta, modifique a seção:

``js
// vite.config.js
export default {
  server: {
    port: 3000, // altere para a porta desejada
  },
};


## Demonstração

Veja o vídeo de demonstração do fluxo completo da aplicação, desde a navegação até a manipulação dos livros: [Link para o vídeo](https://www.youtube.com).

## Como Contribuir

1. Faça um **fork** do projeto.
2. Crie uma nova branch (`git checkout -b feature/nova-feature`).
3. Faça as alterações necessárias e faça o commit (`git commit -m 'Adiciona nova feature'`).
4. Envie para a branch principal (`git push origin feature/nova-feature`).
5. Abra um **Pull Request**.

## Licença

Este projeto está licenciado sob a licença MIT - veja o arquivo [LICENSE](LICENSE) para mais detalhes.
