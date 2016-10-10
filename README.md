# github-Markdown-style



## Usage

Import the `github-Markdown-style` file and add a `markdown-body` class to the container of your rendered Markdown and set a width for it. GitHub uses `980px` width and `45px` padding.

```
<link rel="stylesheet" href="github-Markdown-style">
<style>
    .markdown-body {
        box-sizing: border-box;
        min-width: 200px;
        max-width: 980px;
        margin: 0 auto;
        padding: 45px;
    }
</style>
<article class="markdown-body">
    <h1>Unicorns</h1>
    <p>All the things</p>
</article>
```

## about

I use [showdownjs](https://github.com/showdownjs/showdown) as editor on my blog website , it is very simple to use __showndownjs__ like this follow :

> npm install showdown

    var showdown  = require('showdown'),
        converter = new showdown.Converter(),
        text      = '#hello, markdown!',
        html      = converter.makeHtml(text);
After this step , it need a `markdown.css` to render Pages , so I catch the github style css file from github.com( it has some __style-css__ on Internet but not github-style ) ; Then I search the __github markdown__ of keywords on github , it is already existed ......  So I fork the Usage that it must be the same method , I know he must do the better than me , I suggest you clone [his project](https://github.com/sindresorhus/github-markdown-css) .
