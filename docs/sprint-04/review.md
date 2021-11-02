# Sprint 4

Data de início: 09/09/2021

Data de término: 23/09/2021

Issues

| id                                                                      | Issue                                                                     | Responsável                   | Status                                                                |
| ----------------------------------------------------------------------- | ------------------------------------------------------------------------- | ----------------------------- | --------------------------------------------------------------------- |
| [#156](https://github.com/external-secrets/external-secrets/issues/156) | Support for immutable secrets                                             | Arthur Paiva                  | [DONE](https://github.com/external-secrets/external-secrets/pull/329) |
| [#350](https://github.com/external-secrets/external-secrets/issues/350) | We need tests for target secret name defaults | Mateus O. Patrício | [DONE](https://github.com/external-secrets/external-secrets/pull/369) |
| [#134](https://github.com/external-secrets/external-secrets/issues/134) | Cluster scoped ExternalSecret for creating secrets in multiple namespaces | Arthur Paiva, Mateus Oliveira | WIP                                                                   |
| [#359](https://github.com/external-secrets/external-secrets/issues/359) | Provide openapi schemas for custom resources | André Freitas, Eduardo Lima | WIP                                                                   |
| [#378](https://github.com/external-secrets/external-secrets/issues/378) | Need to upgrade slash-command-dispatch, but figure out new args | André Freitas, Eduardo Lima | WIP                                                                   |

## Depoimentos

### Arthur Paiva

&emsp;&emsp;Terminei nessa sprint a issue [#156](https://github.com/external-secrets/external-secrets/issues/156), que tinha como pendência uma mudança na forma de verificar se o secret esá sincronizado, consertos nos testes que estavam desatualizados com a nova issue, tive um certo trabalho também com os conflitos gerados no merge. Depois disso, fiz um pareamento com o Mateus Oliveira para trabalharmos na issue [#134](https://github.com/external-secrets/external-secrets/issues/134), que tem como objetivo possibilitar a criação do secret em vários namespaces de uma vez. Estudamos juntos um pouco mais sobre k8s, namespaces e o projeto em si, testamos o uso de um outro operador chamado reflector, como consta nas sugestões da issue e com a ajuda do meta coach vimos que seria necessário implementar a feature no projeto, e não só usar o reflector já que o mesmo não permitiria o uso de match labels.

### Mateus Oliveira Patrício

&emsp;&emsp;Estou conversando bastante com o Lucas pelo telegram, ele tem me ajudado bastante a entender o projeto, acredito ter finalizado a pendência dos testes e2e da sprint passada, mas o PR ainda está em aberto pois para testar o que eu faço relacionado aos testes necessito que algum mantenedor do repositório mande o comando /ok-to-test no pull request sempre que eu atualizo ele, pois é a única maneira de executar estes testes. Além disto comecei a trabalhar na issue [#134](https://github.com/external-secrets/external-secrets/issues/134) junto com o Arthur Paiva, vamos implementar a funcionalidade de replicar o secret em vários namespaces com a opção de match labels.

### André Aben-Athar de Freitas

&emsp;&emsp;Não conseguindo andar muito na parte de código, resolvi me voltar para issues que ajudem os mantenedores e possíveis usuários. NA issue [#359](https://github.com/external-secrets/external-secrets/issues/359) tivemos uma conversa do quanto seria interessante uma documentação do projeto no formato swagger. Junto com o Eduardo, estamos conversando nosso MetaCoach como é o melhor jeito de fazer isso. Provavlemente utilizaremos o mesmo método que o reposítorio oficial do kubernetes utiliza. E após isso, subir os arquivos com um passo no github actions.
Também junto com o Eduardo Lima, atualizamos um pacote na issue issue [#378](https://github.com/external-secrets/external-secrets/issues/378)

### Eduardo Vieira Lima

&emsp;&emsp;Não consegui dar continuidade na issue #221 pois acabou sendo resolvida em outro PR relacionado, assim junto do André começamos a estudar e trabalhar nas issues [#359](https://github.com/external-secrets/external-secrets/issues/359) e [#378](https://github.com/external-secrets/external-secrets/issues/378)