Remark template with Beamer style.

## Additions on Remark

- CSS classes `titlepage`, `date`, `no-number`, `math`
- Support reference. `\cite{ref-item-id}`, `@{ref-item-id}{author}{title}{publisher}{year}`
- Support math via KaTeX

## Deal with Math

`.math[]`

<https://khan.github.io/KaTeX/function-support.html>

### Underscore

Sometimes `_` (subscript in LaTeX) will be wrongly parsed as `_italic_` block, just wrap your equation with `<p>` or `<div>`

### Multi-line Equation

KaTeX supports `aligned` environment

[tbd] manually align (using spacing)

## Tips

Extension 'vscode-remark'

Local CSS:

```
class: local-id

<style>.local ...</style>
```