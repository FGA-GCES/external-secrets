# Sprint 4

Data de início: 09/09/2021

Data de término: 23/09/2021

Issues

| id                                                                      | Issue                                                                     | Responsável                   | Status                                                                |
| ----------------------------------------------------------------------- | ------------------------------------------------------------------------- | ----------------------------- | --------------------------------------------------------------------- |
| [#156](https://github.com/external-secrets/external-secrets/issues/156) | Support for immutable secrets                                             | Arthur Paiva                  | [DONE](https://github.com/external-secrets/external-secrets/pull/329) |
| [#350](https://github.com/external-secrets/external-secrets/issues/350) | We need tests for target secret name defaults | Mateus O. Patrício | [WIP](https://github.com/external-secrets/external-secrets/pull/369) |
| [#134](https://github.com/external-secrets/external-secrets/issues/134) | Cluster scoped ExternalSecret for creating secrets in multiple namespaces | Arthur Paiva, Mateus Oliveira | WIP                                                                   |

## Depoimentos

### Arthur Paiva

&emsp;&emsp;Terminei nessa sprint a issue [#156](https://github.com/external-secrets/external-secrets/issues/156), que tinha como pendência uma mudança na forma de verificar se o secret esá sincronizado, consertos nos testes que estavam desatualizados com a nova issue, tive um certo trabalho também com os conflitos gerados no merge. Depois disso, fiz um pareamento com o Mateus Oliveira para trabalharmos na issue [#134](https://github.com/external-secrets/external-secrets/issues/134), que tem como objetivo possibilitar a criação do secret em vários namespaces de uma vez. Estudamos juntos um pouco mais sobre k8s, namespaces e o projeto em si, testamos o uso de um outro operador chamado reflector, como consta nas sugestões da issue e com a ajuda do meta coach vimos que seria necessário implementar a feature no projeto, e não só usar o reflector já que o mesmo não permitiria o uso de match labels.

### Mateus Oliveira Patrício

&emsp;&emsp;Estou conversando bastante com o Lucas pelo telegram, ele tem me ajudado bastante a entender o projeto, acredito ter finalizado a pendência dos testes e2e da sprint passada, mas o PR ainda está em aberto pois para testar o que eu faço relacionado aos testes necessito que algum mantenedor do repositório mande o comando /ok-to-test no pull request sempre que eu atualizo ele, pois é a única maneira de executar estes testes. Além disto comecei a trabalhar na issue [#134](https://github.com/external-secrets/external-secrets/issues/134) junto com o Arthur Paiva, vamos implementar a funcionalidade de replicar o secret em vários namespaces com a opção de match labels.