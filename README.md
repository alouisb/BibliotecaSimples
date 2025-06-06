# BibliotecaSimples

Projeto em Java para gerenciamento de livros, utilizando versionamento semântico (SemVer) com Git e GitHub.

## Versões

| v1.0.0  | MAJOR  | Versão inicial com adicionar e listar livros                          |
| v1.1.0  | MINOR  | Adicionada busca por autor                                            |
| v1.1.1  | PATCH  | Correção: busca por autor agora ignora maiúsculas/minúsculas         |
| v2.0.0  | MAJOR  | Refatoração com inclusão do campo ISBN (mudança incompatível)        |

## Changelog

- **v1.0.0**: feat - adiciona métodos básicos de livro
- **v1.1.0**: feat - adiciona busca por autor
- **v1.1.1**: fix - torna busca por autor insensível a maiúsculas/minúsculas
- **v2.0.0**: refactor! - adiciona campo ISBN e altera construtor do livro

## [2.0.0] - 2025-04-27
- **feat!**: Adiciona suporte a ISBN, alterando a interface de adição de livros (breaking change).
- **feat**: Adiciona busca por ISBN.

## [1.1.1] - 2025-04-27
- **fix**: Adiciona documentação para busca case-insensitive.

## [1.1.0] - 2025-04-27
- **feat**: Adiciona busca de livros por autor.

## [1.0.0] - 2025-04-27
- **feat**: Implementa funcionalidade inicial de adicionar e listar livros.
