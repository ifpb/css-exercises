# Analisando o efeito da cascata no CSS

## Objetivo

O objetivo desta atividade consiste em abordar os seguintes temas:

- Analisar a cascata do CSS

## Descrição

A cascata no CSS é o que permite definir uma ordem de atribuição entre as inumeras declarações de propriedade de um elemento. Então quando declaramos uma propriedade de estilo em um elemento ela será ordenada seguindo a priore o seu grau de importância, especificidade ou posição no código. Além disso, o valor default da propriedade e a herança também são considerados nesse fluxo.

No intuito de analisar esse fluxo de cascata é que foi criada essa [página](site/), que possui três títulos e nove parágrafos. Assim sendo, tente preencher a tabela a seguir para explicar como a propriedade de estilo `color` é aplicado a cada um dos elementos, especificando quantas opções de cores o elemento possui, e definindo a declaração no grau de importância, especificidade e posição no código.

| Elemento | Opções de cores | Importância | Especificidade (abcd) | Posição |
|-|-|-|-|-|
| `<h1>` | | | | |
| 1 `<h2>` | | | | |
| 1 `<p>` | | | | |
| 2 `<p>` | | | | |
| 3 `<p>` | | | | |
| 2 `<h2>` | | | | |
| 1 `<p>` | | | | |
| 2 `<p>` | | | | |
| 3 `<p>` | | | | |
| 4 `<p>` | | | | |
| 5 `<p>` | | | | |
| `<h3>` | | | | |
| 1 `<p>` | | | | |

> [Alternativa de resposta](cascade.md).