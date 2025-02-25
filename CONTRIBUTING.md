> [!WARNING]
> This documentation is still under development - if anything seems unclear, poke @mirakardia in the eye with a sharp stick and demand an explanation (or open an issue).

## Table of contents
- [Code of conduct](#code-of-conduct)
- [Development tools](#development-tools)
  - [Godot Engine](#godot-engine)
  - [Visual Studio Code](#visual-studio-code)
    - [Recommended VSCode extensions:](#recommended-vscode-extensions)
    - [Recommended VSCode settings:](#recommended-vscode-settings)
  - [Git](#git)
- [Programming style](#programming-style)
- [Git workflow](#git-workflow)

## Code of conduct

This project is committed to respecting and embracing the diversity of its collaborators by following **safe space principles**. In a safe space, everyone should feel welcome and confident about being their genuine self.

**We are all unique**, and no one working on this project may be discriminated against based on:

- age
- sexual orientation
- gender or gender identity
- language
- nationality or ethnic background
- religious, philosophical or political views
- any opinion
- state of health or disability
- socio-economic status
- family background

In general, **be considerate and patient**, and ready to **listen and encourage** others. **Do not stay silent** if you experience any form of discrimination or harassment, or if you believe someone else is experiencing such acts.

## Development tools

> [!TIP]
> If possible, we recommend installing all development tools using your operating system's integrated package manager or application store for easier management and better security.

### [Godot Engine](https://godotengine.org/)

This project utilizes the **Godot Engine** and its packaged programming language **GDScipt** for game development. Additional tools may be developed in the future using C++.

Download the latest version (**4.x**) of Godot Engine [**here**](https://godotengine.org/).

### [Visual Studio Code](https://code.visualstudio.com/)

Although Godot features an integrated script editor, we recommend using **Visual Studio Code** for its useful extensions and decent Git integration.

If not available via your package manager or app store, download Visual Studio Code [**here**](https://code.visualstudio.com/).

#### Recommended VSCode extensions:

- [Godot Tools](https://marketplace.visualstudio.com/items?itemName=geequlim.godot-tools) (GDScript language support, debugging, syntax highlighting etc.)
- [Markdown All in One](https://marketplace.visualstudio.com/items?itemName=yzhang.markdown-all-in-one) (For comfortable .md file editing and previewing)

#### Recommended VSCode settings:

Add the following to `settings.json` in Visual Studio Code:

```json
// [TAB] inserts 4 spaces
"editor.tabSize": 4
"editor.insertSpaces": true

// For sensible formatting of tables of content
"markdown.extension.toc.omittedFromToc": {
    "README.md": ["## Table of contents"],
    "CONTRIBUTING.md": ["## Table of contents"]
},
```

### [Git](https://git-scm.com/)

We use Git for version control and integration with GitHub's project management tools. For a crash course on how to use Git with Godot and VSCode in a sensible manner, check [Git workflow]([##git-workflow).

If not already installed or available via your package manager or app store, download Git [**here**](https://git-scm.com/).

## Programming style

A code base with a coherent formatting style is easier to manage and interpret. Please follow these standards when writing code in **GDScript** for this repository.

First of all, configure the indentation settings in your editor as follows:

- tab size: 4
- tab style: spaces

All variables should be statically typed, as described [here](https://docs.godotengine.org/en/stable/tutorials/scripting/gdscript/static_typing.html).

For everything else, this project adheres to the style conventions set in the [GDScript section](https://docs.godotengine.org/en/stable/tutorials/scripting/gdscript/gdscript_styleguide.html) of the official Godot documentation.

## Git workflow

Technically speaking, Git is a very robust version control system, but its initial learning curve is quite steep without proper (and patient) guidance. Thus, to protect the integrity of our main branch (and our mental health), we use a certain workflow when developing features and writing documentation.

(*section under development*)