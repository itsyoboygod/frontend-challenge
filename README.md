O projeto consiste de uma tela de lista de personagens, uma tela de detalhe do personagem.

Você é livre para definir o layout e arquitetura que vai utilizar. Não é necessário implementar da mesma maneira que nas imagens de exemplo. 

Qualquer funcionalidade extra é bem vinda para agregar na solução básica proposta.

Estamos avaliando pela qualidade do código, pela modularidade, pela criatividade.

## Instruções

Crie um fork deste projeto, e desenvolva em cima do seu fork. Use o README.md principal do seu repositório para colocar instruções de como rodar o seu projeto.

#### Como entrego meu teste?

Nos envie um email com o link do seu fork para o email ingo.eyng@repassa.com.br

#### Prazo

Será combinado entre o candidato e responsável pela entrevista.

## Teste prático

Crie uma aplicação _**React**_ ou _**Next.js**_ que consuma a API (https://rickandmortyapi.com/) e tenha 2 páginas principais citadas abaixo.

Fica a vontade para implementar a maneira que desejar para consumir a API, utlizando REST ou GraphQL. Essa API fornece as duas maneiras.

### Listagem de personagens (`/`):

1. Consumir API para obter os dados para listagem
    - **Rest**: https://rickandmortyapi.com/documentation/#get-all-characters
    - **GraphQL**: Query `characters` passando argumento `page` (https://rickandmortyapi.com/graphql)
2. Listar os personagens de `Rick and Morty` com paginação, mostrando-os em formato de card como imagem abaixo
[imagem aqui]

> Opcional: Implementar filtros de busca na tela de listagem

### Ficha completa do personagem (`/personagem/[id]`)

1. Ao clicar no card do personagem, o usuário é redirecionado para `/personagem/[id]`
2. Mostrar ficha completa do personagem como na imagem abaixo:
    - **Rest**: `get-a-single-character` na documentação
    - **GraphQL**: Query `character` passando argumento `id` (https://rickandmortyapi.com/graphql)
    [imagem aqui]


### Opcionais:

- Em ambas as telas mostrar tela de carregamento (loading) enquanto a requisição não é concluída.
