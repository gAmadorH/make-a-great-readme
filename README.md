# make-a-great-readme

[![License](https://img.shields.io/github/license/gAmadorH/make-a-great-readme.svg?color=blue)](https://github.com/gAmadorH/make-a-great-readme/blob/master/LICENSE)

Let's make a great README file.

A README file describe your project purpose, features, dependencies, how to use, license and another thins you like to inform.  
It's written in a _markup language_, the most common is [markdown](https://guides.github.com/features/mastering-markdown/) (`.md` extension) but it's not the only one, there're another alternatives like [reStructuredText](https://docutils.sourceforge.io/rst.html) (`.rst` extension).  
In this case we are focus in _markdown_, and this isn't a syntax tutorial, this is a good practices tutorial on how to make a great README file (using markdown and vscode editor).

## Before to start

Before to start to write a great README.md file, we need to set up some extensions for vscode to improve our development.

### Use EditorConfig

I recommend you write a `.editorconfig` file in the project root in order to maintain a consistent code style with your team  
even if you are working alone, it's a good idea write it (if it's your case, don't worry with a great README many developers will want to work in your idea).  
To use [EditorConfig](https://editorconfig.org/) your editor needs an extension, many editors have it by default, you can check what editors need a plugin/extension [here](https://editorconfig.org/#download).  
For vscode editor, you need a [EditorConfig for VS code](https://marketplace.visualstudio.com/items?itemName=EditorConfig.EditorConfig) extension. In the last section I will list the best vscode extensions to make a great README.

So your `.editorconfig` configuration file could be like this:

```vim
# http://editorconfig.org
root = true

[*]
indent_style = space
indent_size = 2
end_of_line = lf
charset = utf-8
trim_trailing_whitespace = true
insert_final_newline = true

[*.md]
trim_trailing_whitespace = false
```

Note that the last rule is for _markdown_ files, it means while for all files the _whitespace_ at the end of each line will be removed, for _markdown_ files this won't happen.  
Sometimes we want a _line break_ file and we need to use 2 spaces at the end and the `trim_trailing_whitespace` rule allows us to do this.  
This rule is important because many developers use this markdown feature.

### Use Code Spell Checker

### Use a Markdown Preview

### Use a Markdown Linter
