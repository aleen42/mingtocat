## markdown-only

> [**HERE**](https://aleen42.github.io/markdown-only/) you can check the site of this repo.

This is a template repository to help you build sites with markdown files only and present them with GitHub styles on GitHub pages.

To use this template:

1. Just start to [**GENERATE**](https://github.com/aleen42/markdown-only/generate) it. (Notice: you can also use it on the repository page on GitHub.)
2. Deploy the GitHub page inside the setting of your new repository.
3. Feel free to write your first markdown file: **README.md**.

### Examples

<p align="center">
<a href="https://mingtocat.aleen42.com" target="_blank"><img width="40%" src="./examples/mingtocat.aleen42.com_dark.png" alt="markdown-only" /></a> <a href="https://mingtocat.aleen42.com" target="_blank"><img width="40%" src="examples/mingtocat.aleen42.com_light.png" alt="markdown-only" /></a>
</p>

### Variables

Current supported configure variables of this theme:

- **`color-mode`**: specify the light / dark mode you intent to use. (`dark` by default)
- **`theme-color`**: specify the theme color meta. (`#1e2327` by default)

### FAQ

As we use jekyll to build sites, it should use [Rouge](https://github.com/rouge-ruby/rouge) to highlight syntax of code snippets and it is different from the highlighter of GitHub. It means that there should be various highlights of the same code like the following:

```js
const data = function () { 
    // ...
    return {
        'markdown-only': { key: 'value'},
    };
};
```

To try to eliminate the differences, I will update [the adapter](https://github.com/aleen42/github-syntax-theme-generator) according to some situations.

### :fuelpump: How to contribute

Have an idea? Found a bug? See [how to contribute](https://wiki.aleen42.com/contribution.html).

### :scroll: License

[MIT](https://wiki.aleen42.com/MIT.html) © aleen42
