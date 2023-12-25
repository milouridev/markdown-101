## Enlaces importantes

[Basic formatting syntax](https://docs.github.com/en/get-started/writing-on-github/getting-started-with-writing-and-formatting-on-github/basic-writing-and-formatting-syntax)

[Emoji Cheat Sheet](https://github.com/ikatyang/emoji-cheat-sheet/blob/master/README.md)

[Creating and highlighting code blocks](https://docs.github.com/en/get-started/writing-on-github/working-with-advanced-formatting/creating-and-highlighting-code-blocks)

[YAML file with valid keywords](https://github.com/github-linguist/linguist/blob/master/lib/linguist/languages.yml#L3324)

## Ejemplos

# Titulo de nivel 1

## Titulo de nivel 2

### Titulo de nivel 3

#### Titulo de nivel 4

##### Titulo de nivel 5

###### Titulo de nivel 6

Texto en:

- **Negrilla**
- _cursiva_
- ~~Tachado~~
- **Negrilla con _ALGO_ de cursiva**
- _Cursiva con **ALGO** de negrilla_
- **_Negrilla cursiva_**
- Texto con <sub>subíndice</sub>
- Texto con <sup>superíndice</sup>

Éste texto no es una cita

> Éste texto es una cita

puedo citar código `git init` dentro de un párrafo o tener un bloque de código

```
git status
git add
git commit
```

O tener un bloque de código con resaltado de sintáxis:

```ruby
require 'redcarpet'
markdown = Redcarpet.new("Hello World!")
puts markdown.to_html
```

```JavaScript
const a = 1;
let fs = require('fs');

if (a === 1)
{
  console.log("A es igual a 1");
}
```

El siguiente enlace [Vamos a Google](https://www.google.com/) te lleva a google

![Screenshot of a comment on a GitHub issue showing an image, added in the Markdown, of an Octocat smiling and raising a tentacle.](https://myoctocat.com/assets/images/base-octocat.svg)

[Específicos de Github](docs/Github.md)

<!-- This content will not appear in the rendered Markdown -->

1. Primer elemento
1. Segundo elemento
1. Tercer elemento

1. Foruth List Item
   - First nested list item
     - Second nested list item

| First Header  | Second Header          |
| ------------- | ---------------------- |
| abc2usi       | adkhsak                |
| saHKJHKhjkasd | kahkdjsak              |
| `git status`  | Estado del repositorio |

| Left-aligned | Center-aligned | Right-aligned |
| :----------- | :------------: | ------------: |
| git status   |   git status   |    git status |
| git diff     |    git diff    |      git diff |

<details>

<summary>Tips for collapsed sections</summary>

### You can add a header

You can add text within a collapsed section.

You can add an image or a code block, too.

```ruby
   puts "Hello World"
```

</details>

Here is a simple flow chart (mermaid support):

```mermaid
graph TD;
    A-->B;
    A-->C;
    B-->D;
    C-->D;
```

This sentence uses `$` delimiters to show math inline: $\sqrt{3x-1}+(1+x)^2$

**The Cauchy-Schwarz Inequality**
$$\left( \sum_{k=1}^n a_k b_k \right)^2 \leq \left( \sum_{k=1}^n a_k^2 \right) \left( \sum_{k=1}^n b_k^2 \right)$$
