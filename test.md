# Test

## TOC test

[toc]

## Header test

### H3

#### H4

##### H5

###### H6

## Paragraph test

Incididunt ex adipisicing ea ullamco consectetur in voluptate proident fugiat tempor deserunt reprehenderit ullamco id dolore laborum. Do laboris laboris minim
incididunt qui consectetur exercitation adipisicing dolore et magna consequat magna anim sunt. Officia fugiat Lorem sunt pariatur incididunt Lorem reprehenderit
proident irure. Dolore ipsum aliqua mollit ad officia fugiat sit eu aliquip cupidatat ipsum duis laborum laborum fugiat esse. Voluptate anim ex dolore deserunt
ea ex eiusmod irure. Occaecat excepteur aliqua exercitation aliquip dolor esse eu eu.

Officia dolore laborum aute incididunt commodo nisi velit est est elit et dolore elit exercitation. Enim aliquip magna id ipsum aliquip consectetur ad nulla
quis. Incididunt pariatur dolor consectetur cillum enim velit cupidatat laborum quis ex.

Officia irure in non voluptate adipisicing sit amet tempor duis dolore deserunt enim ut. Reprehenderit incididunt in ad anim et deserunt deserunt Lorem laborum
quis. Enim aute anim labore proident laboris voluptate elit excepteur in. Ex labore nulla velit officia ullamco Lorem Lorem id do. Dolore ullamco ipsum magna
dolor pariatur voluptate ipsum id occaecat ipsum. Dolore tempor quis duis commodo quis quis enim.

## Code test

```php
$ParsedownExtreme = new ParsedownExtreme();

echo $ParsedownExtreme->text('Hello _Parsedown_!'); # prints: <p>Hello <em>Parsedown</em>!</p>
// you can also parse inline markdown only
echo $ParsedownExtreme->line('Hello _Parsedown_!'); # prints: Hello <em>Parsedown</em>!
```

Some text between!

```js
const Prism = require('prismjs');

// The code snippet you want to highlight, as a string
const code = `var data = 1;`;

// Returns a highlighted HTML string
const html = Prism.highlight(code, Prism.languages.javascript, 'javascript');
```

## Inline code test

Text with inline `code`. This is great!  
They can `also contain spaces!`

## TODO test

- [ ] ToDos
  - [x] Buy some salad
  - [ ] Brush teeth
  - [x] Drink some water

## Math test

$$
    f(x) = \int_{-\infty}^\infty
    \hat f(\xi)\,e^{2 \pi i \xi x}
    \,d\xi
$$

More examples:

$$
    x = {-b \pm \sqrt{b^2-4ac} \over 2a}.
$$

Multiple expressions in one block:

$$
    \displaystyle \frac{1}{\Bigl(\sqrt{\phi \sqrt{5}}-\phi\Bigr) e^{\frac25 \pi}} = 1+\frac{e^{-2\pi}} {1+\frac{e^{-4\pi}} {1+\frac{e^{-6\pi}} {1+\frac{e^{-8\pi}} {1+\cdots} } } }

    \displaystyle \left( \sum_{k=1}^n a_k b_k \right)^2 \leq \left( \sum_{k=1}^n a_k^2 \right) \left( \sum_{k=1}^n b_k^2 \right)
$$

## Mermaid test

### Sequence diagram

%%
sequenceDiagram
    participant Alice
    participant Bob
    Alice->>John: Hello John, how are you?
    loop Healthcheck
        John->>John: Fight against hypochondria
    end
    Note right of John: Rational thoughts<br/>prevail...
    John-->>Alice: Great!
    John->>Bob: How about you?
    Bob-->>John: Jolly good!
%%

### Flowchart

%%
graph TD;
    A-->B;
    A-->C;
    B-->D;
    C-->D;
%%

### Gantt diagram

%%
gantt
dateFormat  YYYY-MM-DD
title Adding GANTT diagram to mermaid
excludes weekdays 2014-01-10

section A section
Completed task            :done,    des1, 2014-01-06,2014-01-08
Active task               :active,  des2, 2014-01-09, 3d
Future task               :         des3, after des2, 5d
Future task2              :         des4, after des3, 5d
%%

### Class diagram

%%
classDiagram
Class01 <|-- AveryLongClass : Cool
<<interface>> Class01
Class03 *-- Class04
Class05 o-- Class06
Class07 .. Class08
Class09 --> C2 : Where am i?
Class09 --* C3
Class09 --|> Class07
Class07 : equals()
Class07 : Object[] elementData
Class01 : size()
Class01 : int chimp
Class01 : int gorilla
Class08 <--> C2: Cool label
class Class10 {
  <<service>>
  int id
  size()
}
%%

### Git graph

%%
gitGraph:
options
{
    "nodeSpacing": 150,
    "nodeRadius": 10
}
end
commit
branch newbranch
checkout newbranch
commit
commit
checkout master
commit
commit
merge newbranch
%%
