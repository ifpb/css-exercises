# Resposta

## Cascata
---

| Elemento | Opções de cores | Importância | Especificidade (abcd) | Posição |
|-|-|-|-|-|
| `<h1>` | 1 | | | |
| 1 `<h2>` | 5 | **Important Author** | a:0 b:0 c:0 d:1 | master.css:27 |
| 1 `<p>` | 7 | Normal Author | **a:0 b:0 c:1 d:1** |  master.css:37  |
| 2 `<p>` | 7 | Normal Author | **a:1 b:0 c:0 d:0** | inline |
| 3 `<p>` | 5 | Normal Author | **a:0 b:0 c:0 d:2** | master.css:32 |
| 2 `<h2>` | 5 | **Important Author** | a:0 b:0 c:0 d:1 | master.css:27 |
| 1 `<p>` | 9 | Normal Author | **a:0 b:1 c:0 d:0** | master.css:7 |
| 2 `<p>` | 8 | Normal Author | **a:1 b:0 c:0 d:0** | inline |
| 3 `<p>` | 6 | Normal Author | **a:0 b:0 c:1 d:0** | master.css:12 |
| 4 `<p>` | 5 | Normal Author | a:0 b:0 c:0 d:2 | **master.css:32** |
| 5 `<p>` | 6 | Normal Author | **a:0 b:0 c:1 d:0** | master.css:7 |
| `<h3>` | 4 | Normal Author | a:0 b:0 c:0 d:1 | master.css:17 |
| 1 `<p>` | 7 | Normal Author | **a:0 b:0 c:1 d:1** | master.css:52 |