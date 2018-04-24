# Analisando o efeito da cascata no CSS

## Objetivo

O objetivo desta atividade consiste em abordar os seguintes temas:

- Analisar a cascata do CSS;
- Relação do valor default de uma propriedade e herança com a cascata;

## Descrição

A cascata no CSS é o que permite definir uma ordem de atribuição entre as inúmeras declarações de propriedade de um elemento. Então quando declaramos uma propriedade de estilo em um elemento ela será ordenada seguindo a priore o seu grau de importância, especificidade ou posição no código conforme descrito na cascata do CSS. Além disso, o valor default da propriedade e a herança também são considerados nesse fluxo.

No intuito de analisar esse fluxo de cascata é que foi criada essa [página](site/), que possui quatro títulos e nove parágrafos. Assim sendo, tente preencher a tabela a seguir para explicar como a propriedade de estilo `color` é aplicado a cada um dos elementos, especificando quantas opções de cores o elemento possui, e definindo a declaração no grau de importância, especificidade e posição no código.

| Elemento | Ordem | Opções de cores | Importância | Especificidade (abcd) | Posição |
|-|-|-|-|-|-|
| `<h1>` | 1 título | | | | |
| `<h2>` | 2 título | | | | |
| `<p>` | 1 parágrafo | | | | |
| `<p>` | 2 parágrafo | | | | |
| `<p>` | 3 parágrafo | | | | |
| `<h2>` | 3 título | | | | |
| `<p>` | 4 parágrafo | | | | |
| `<p>` | 5 parágrafo | | | | |
| `<p>` | 6 parágrafo | | | | |
| `<p>` | 7 parágrafo | | | | |
| `<p>` | 8 parágrafo | | | | |
| `<h3>` | 4 título | | | | |
| `<p>` | 9 parágrafo | | | | |

> [Alternativa de resposta](cascade.md).