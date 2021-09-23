# Review - Sprint 2

Data de início: 12/08/2021

Data de término: 26/08/2021

Issues

| id                                                                      | Issue                                                                       | Responsável        | Status                                                                 |
| ----------------------------------------------------------------------- | --------------------------------------------------------------------------- | ------------------ | ---------------------------------------------------------------------- |
| [#321](https://github.com/external-secrets/external-secrets/issues/321) | Target secret name does not default to .metadata.name of the ExternalSecret | Mateus O. Patrício | [Done](https://github.com/external-secrets/external-secrets/pull/332)  |
| [#156](https://github.com/external-secrets/external-secrets/issues/156) | Support for immutable secrets                                               | Arthur P. Tavares  | [WIP](https://github.com/external-secrets/external-secrets/pull/329)   |
| [#209](https://github.com/external-secrets/external-secrets/issues/209) | e2e tests for AWS Secrets Manager                                           | André Freitas      | [WIP](https://github.com/external-secrets/external-secrets/issues/209) |
| [#221](https://github.com/external-secrets/external-secrets/issues/221) | Optimize secret update calls                                                | Eduardo Lima       | [WIP](https://github.com/external-secrets/external-secrets/issues/221) |

## Depoimentos

### Arthur Paiva

Esta sprint foi principalmente para entendimento do escopo e código do projeto, houveram duas reuniões que participei com o meta coach e gravamos para ficar disponível para os demais, onde tratamos sobre kubernetes no geral, o que são operadores e qual o objetivo do eso. O meta coach também ensinou a executar o projeto da melhor forma para desenvolvimento, usar os segredos do google cloud, rodar os testes, modificar os testes e como está a arquitetura do operador. Nesta sprint também comecei a trabalhar na issue [#156](https://github.com/external-secrets/external-secrets/issues/156 em pareamento com o meta coach, onde fizemos testes para criar segredos imutáveis no cluster mas sem muito sucesso.
