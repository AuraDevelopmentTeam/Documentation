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

```js
onst Prism = require('prismjs');

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

## Mermaid test

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
