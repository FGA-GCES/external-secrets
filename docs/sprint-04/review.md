# Review - Sprint 2

Data de início: 09/09/2021

Data de término: 23/09/2021

Issues

| id                                                                      | Issue                                                                     | Responsável                   | Status                                                                |
| ----------------------------------------------------------------------- | ------------------------------------------------------------------------- | ----------------------------- | --------------------------------------------------------------------- |
| [#156](https://github.com/external-secrets/external-secrets/issues/156) | Support for immutable secrets                                             | Arthur Paiva                  | [DONE](https://github.com/external-secrets/external-secrets/pull/329) |
| [#134](https://github.com/external-secrets/external-secrets/issues/134) | Cluster scoped ExternalSecret for creating secrets in multiple namespaces | Arthur Paiva, Mateus Oliveira | WIP                                                                   |

## Depoimentos

### Arthur Paiva

Terminei nessa sprint a issue [#156](https://github.com/external-secrets/external-secrets/issues/156), que tinha como pendência uma mudança na forma de verificar se o secret esá sincronizado, consertos nos testes que estavam desatualizados com a nova issue, tive um certo trabalho também com os conflitos gerados no merge. Depois disso, fiz um pareamento com o Mateus Oliveira para trabalharmos na issue [#134](https://github.com/external-secrets/external-secrets/issues/134), que tem como objetivo possibilitar a criação do secret em vários namespaces de uma vez. Estudamos juntos um pouco mais sobre k8s, namespaces e o projeto em si, testamos o uso de um outro operador chamado reflector, como consta nas sugestões da issue e com a ajuda do meta coach vimos que seria necessário implementar a feature no projeto, e não só usar o reflector já que o mesmo não permitiria o uso de match labels.
