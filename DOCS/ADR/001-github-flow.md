# ADR 001 - Uso do GitHub Flow

## Status
Aceito

## Contexto
Este repositório é utilizado como diário de estudos de TI e também para praticar Git e GitHub.

Precisamos de uma forma organizada de realizar alterações sem modificar diretamente a branch principal.

## Decisão
Utilizar o GitHub Flow.

As alterações serão realizadas em branches separadas. Depois de concluídas, serão enviadas ao GitHub e incorporadas à branch master por meio de Pull Requests.

## Motivos
- Evitar alterações diretamente na master.
- Permitir a revisão das mudanças antes do merge.
- Manter um histórico organizado.
- Praticar um fluxo utilizado em projetos colaborativos.

## Consequências
Cada nova alteração relevante deverá ser desenvolvida em uma branch separada antes de ser incorporada à master.
