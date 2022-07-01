# La page de l'association les miusiciens d'à côté

On essaie de ne pas mettre d'informations personnelles SVP. Les liens
google drive sont possibles puisqu'il ne donnent accès qu'en lecture.
En particulier les statuts de l'association sont de toute façon
publics.

## Pour compiler les pages web localement avant de ployer sur github

Le site utilise jekyll, qu'on install via les gems de ruby.

### Mise à jour

Si on met à jour Gemfile ou _config.yml, il faut refaire `bundler
update` (avec `sudo` si nécessaire).

### Comment installer jekyll et les plugins

Cela nécessite d'installer ruby d'abord. Ensuite bundle installera les
gem qu'il faut en principe.

Ensuite `bundle exec jekyll serve` devrait lancer un serveur local sur
`http://127.0.0.1:4000/`.

Ci-dessous le mode d'emploi jekyll/markdown.

## Welcome to GitHub Pages

You can use the [editor on GitHub](https://github.com/MusiciensDaCote/musiciensdacote.github.io/edit/main/README.md) to maintain and preview the content for your website in Markdown files.

Whenever you commit to this repository, GitHub Pages will run [Jekyll](https://jekyllrb.com/) to rebuild the pages in your site, from the content in your Markdown files.

### Markdown

Markdown is a lightweight and easy-to-use syntax for styling your writing. It includes conventions for

```markdown
Syntax highlighted code block

# Header 1
## Header 2
### Header 3

- Bulleted
- List

1. Numbered
2. List

**Bold** and _Italic_ and `Code` text

[Link](url) and ![Image](src)
```

For more details see [Basic writing and formatting syntax](https://docs.github.com/en/github/writing-on-github/getting-started-with-writing-and-formatting-on-github/basic-writing-and-formatting-syntax).

### Jekyll Themes

Your Pages site will use the layout and styles from the Jekyll theme you have selected in your [repository settings](https://github.com/MusiciensDaCote/musiciensdacote.github.io/settings/pages). The name of this theme is saved in the Jekyll `_config.yml` configuration file.

### Support or Contact

Having trouble with Pages? Check out our [documentation](https://docs.github.com/categories/github-pages-basics/) or [contact support](https://support.github.com/contact) and we’ll help you sort it out.
