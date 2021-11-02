# Sprint 5

Data de início: 07/10/2021

Data de término: 19/10/2021

Issues

| id                                                                      | Issue                                                                     | Responsável                       | Status                                                                |
| ----------------------------------------------------------------------- | ------------------------------------------------------------------------- | --------------------------------- | --------------------------------------------------------------------- |
| [#416](https://github.com/external-secrets/external-secrets/issues/416) | Redução de literais duplicados                                            | Mateus O. Patrício                | [DONE](https://github.com/external-secrets/external-secrets/pull/420) |
| [#416](https://github.com/external-secrets/external-secrets/issues/416) | Refatoração de métodos com alta complexidade cognitiva                    | Arthur Paiva                      | [DONE](https://github.com/external-secrets/external-secrets/pull/421) |
| [#416](https://github.com/external-secrets/external-secrets/issues/416) | Cluster scoped ExternalSecret for creating secrets in multiple namespaces | Arthur Paiva e Mateus O. Patrício | WIP                                                                   |
| [#416](https://github.com/external-secrets/external-secrets/issues/416) | Redução de literais duplicados | Eduardo Vieira Lima | WIP                                                                   |

## Depoimentos

### Arthur Paiva Tavares

Nesta sprint resolvi problemas de lint no PR [421](https://github.com/external-secrets/external-secrets/pull/421), que não tinham sido apontados usando o make reviewable, o que me fez perceber que o make reviewable não estava verificando o lint, então criei uma issue para adicionar o make lint ao make reviewable. Antes que eu trabalhasse nela outra pessoa fez um Pull Request e continuou trabalhando na issue. Após isso pareei com o Mateus Patrício na issue [134](https://github.com/external-secrets/external-secrets/issues/134), onde encontramos dificuldades de conhecimento técnico e do projeto em si, já que a issue é complexa e precisa de uma implementação de controller que execute em vários namespaces.

### André Aben-Athar de Freitas

&emsp;&emsp; Tive fazer uma série de ajustes ao meu PR [#425](https://github.com/external-secrets/external-secrets/pull/425), pois outra pessoa tinha trabalhado no mesmo arquivo que eu e isto gerou conflitos no merge. E mesmo conversando com o Lucas Severo, não consegui terminar a issue [#209](https://github.com/external-secrets/external-secrets/issues/209), de modo que retirei ela dos meus afazeres após outra pessoa da comunidade open source pediu para fazer ela.

### Eduardo Vieira Lima

&emsp;&emsp;Nesta sprint tive dificuldades com o ambiente e não consegui finalizar a issue que iniciei na sprint passada, por falta de tempo e organização não consegui evoluir.