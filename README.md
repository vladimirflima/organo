# Gerenciador de Colaboradores

Este projeto é um gerenciador de colaboradores de uma organização, desenvolvido em React. Ele permite cadastrar novos colaboradores e times, definir favoritos, e mudar a cor dos times.

## Estrutura do Projeto

O projeto é composto pelos seguintes componentes:

- `App`: Componente principal que gerencia o estado da aplicação.
- `Banner`: Componente que exibe o banner principal da aplicação.
- `Formulario`: Componente para cadastrar novos colaboradores e novos times.
- `Rodape`: Componente que exibe o rodapé da aplicação.
- `Time`: Componente que exibe as informações de um time e seus colaboradores.

## Instalação

Para instalar e rodar o projeto localmente, siga os seguintes passos:

1. Clone o repositório:

   ```sh
   git clone https://github.com/seu-usuario/nome-do-repositorio.git

2. Navegue até o diretório do projeto:

   ```sh
   cd nome-do-repositorio
   
3. Instale as dependências:

   ```sh
   npm install

4. Inicie o servidor de desenvolvimento:

    ```sh
    npm start

5. Abra o navegador e acesse http://localhost:3000

## Funcionalidades

### Cadastro de Times
No formulário, você pode cadastrar novos times fornecendo um nome e uma cor. Os times cadastrados serão exibidos na seção "Minha organização".

### Cadastro de Colaboradores
Você pode cadastrar novos colaboradores associando-os a um time existente. Cada colaborador possui um nome, cargo, imagem e um indicador de favorito.

### Favoritar Colaboradores
Você pode marcar colaboradores como favoritos clicando na estrela ao lado de cada colaborador.

### Deletar Colaboradores
Você pode deletar colaboradores clicando no ícone de lixeira ao lado de cada colaborador.

### Mudar Cor dos Times
Você pode mudar a cor dos times utilizando o seletor de cores na seção de cada time.

## Estrutura do Código

### `App.js`
O componente principal `App` gerencia o estado dos times e colaboradores. Ele contém funções para:

- Deletar colaboradores (`deletarColaborador`)
- Mudar a cor dos times (`mudarCor`)
- Cadastrar novos times (`cadastrarTime`)
- Resolver o estado de favorito dos colaboradores (`resolverFavorito`)

### `Banner.js`
Componente que exibe o banner principal da aplicação.

### `Formulario.js`
Componente que exibe o formulário para cadastrar novos colaboradores e novos times. Recebe as funções `aoCriarTime` e `aoCadastrar` como props.

### `Rodape.js`
Componente que exibe o rodapé da aplicação.

### `Time.js`
Componente que exibe as informações de um time e seus colaboradores. Recebe as funções `mudarCor`, `aoDeletar` e `aoFavoritar` como props.

## Dependências

- `react`: Biblioteca principal para construir a interface do usuário.
- `react-dom`: Pacote para manipulação do DOM com React.
- `uuid`: Biblioteca para geração de IDs únicos.

