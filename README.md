# Plataforma de Receitas

Uma plataforma de comida onde você pode compartilhar suas receitas favoritas e se conectar com outros amantes de comida.

## Visão Geral

Este é um projeto Next.js criado para permitir que os usuários compartilhem suas receitas e se conectem com outros entusiastas da culinária. Ele utiliza funcionalidades avançadas do Next.js, como renderização no lado do servidor (SSR), rotas dinâmicas e metadados dinâmicos, e foi projetado para oferecer uma experiência de usuário interativa e otimizada.

## Funcionalidades

- **App Router**: Definição de rotas utilizando o sistema de arquivos do Next.js.
- **Arquivos Especiais**:
  - `not-found.jsx` para tratamento de rotas não encontradas.
  - `error.jsx` para tratamento de erros na execução da página.
  - `layout.jsx` para layout global da plataforma.
- **SSR (Server-Side Rendering)**: Renderização no lado do servidor para melhorar desempenho e SEO.
- **Rotas Dinâmicas**: Criação de páginas dinâmicas baseadas em dados do banco de dados.
- **Metadados**: Uso de campos de metadados como title e description, incluindo metadados dinâmicos para rotas.
- **Hooks**:
  - `useActionState` (antigo `useFormState`): Gerenciamento de estado e validação do formulário.
  - `useFormStatus`: Verificação do status do envio do formulário.
- **Componente Redirect**: Redirecionamento após a conclusão do formulário.
- **Cache e Revalidação**: Uso de 'revalidatePath' para atualizar as páginas com novos dados.

## Requisitos

- Node.js (versão recomendada: 16.x ou superior)
- npm (versão recomendada: 7.x ou superior) ou yarn (versão recomendada: 1.x ou superior)

## Configuração do Ambiente

1. Clone o repositório:

    ```bash
    git clone https://github.com/seu-usuario/plataforma-de-receitas.git
    ```

2. Navegue até o diretório do projeto:

    ```bash
    cd plataforma-de-receitas
    ```

3. Instale as dependências:

    ```bash
    npm install
    ```

    ou

    ```bash
    yarn install
    ```

4. Crie um arquivo `.env` na raiz do projeto e adicione as variáveis de ambiente necessárias. Por exemplo:

    ```env
    DATABASE_URL=your-database-url
    API_KEY=your-api-key
    ```

## Scripts Disponíveis

No diretório do projeto, você pode executar:

### `npm run dev` ou `yarn dev`

Roda a aplicação em modo de desenvolvimento.\
Abra [http://localhost:3000](http://localhost:3000) para ver no navegador.

A página irá recarregar se você fizer edições.\
Você também verá quaisquer erros de lint no console.

### `npm run build` ou `yarn build`

Compila o aplicativo para produção.

### `npm start` ou `yarn start`

Roda o servidor de produção. Certifique-se de compilar o projeto primeiro usando `npm run build` ou `yarn build`.

### `npm run lint` ou `yarn lint`

Executa o linter para encontrar e corrigir problemas no código.

## Estrutura do Projeto

- `pages/` - Contém as páginas do aplicativo.
- `components/` - Contém os componentes reutilizáveis.
- `styles/` - Contém os arquivos de estilo (CSS, SCSS, etc.).
- `public/` - Contém os recursos estáticos, como imagens e ícones.

## Contribuindo

Contribuições são bem-vindas! Sinta-se à vontade para abrir uma [issue](https://github.com/seu-usuario/plataforma-de-receitas/issues) ou enviar um [pull request](https://github.com/seu-usuario/plataforma-de-receitas/pulls).

## Licença

Este projeto está licenciado sob a [Licença MIT](LICENSE).
