# HTS Help File
This is intended as a quick reference on how to work with the Howell Test Software and also to showcase different features of HTS.

Syntax
======
> Below are the general syntax on how to write commands.


A825Tx command
------
a825Tx command is used

> msg Syntax
```
msg,Window Caption,Message to be shown in the Pop up window
```
>msg Sample
```
msg,Power,Power Off the Unit
```
Colons can be used to align columns.

| Tables        | Are           | Cool  |
| ------------- |:-------------:| -----:|
| col 3 is      | right-aligned | $1600 |
| col 2 is      | centered      |   $12 |
| zebra stripes | are neat      |    $1 |
HTML
----

Text between `<` and `>` that looks like an HTML tag is parsed as a raw HTML tag and will be rendered in HTML

While it may be useful when writing online content, please note that your tag may be stripped for security reasons and in output other than HTML you may have unexpected results

<p class="text-right">Look I'm right!</p>

This is the list of allowed html tags (case insensitive):

`article`, `header`, `aside`, `hgroup`, `blockquote`, `hr`, `iframe`, `body`, `li`, `map`, `button`, `object`, `canvas`, `ol`,`caption`, `output`, `col`, `p`, `colgroup`, `pre`, `dd`, `progress`, `div`, `section`, `dl`,`table`, `td`, `dt`, `tbody`, `embed`,`textarea`, `fieldset`, `tfoot`, `figcaption`, `th`, `figure`, `thead`, `footer`, `tr`, `form`, `ul`, `h1`, `h2`, `h3`, `h4`, `h5`, `h6`, `video`, `script`, `style`
