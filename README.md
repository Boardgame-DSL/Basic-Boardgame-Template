# Basic Boardgame Template

This is a template repository that can give you a start in modelling a
boardgame.

This template only contains the basis for the Haskell model without a web UI.

## Cloning

To get your own copy of this repository you should "clone" it in one of the
following ways:

### GitHub

Click the "Use this template" button and follow the instructions.

![Use this template button](https://docs.github.com/assets/images/help/repository/use-this-template-button.png)  
From GitHub Docs: [Creating a repository from a template](https://docs.github.com/en/github/creating-cloning-and-archiving-repositories/creating-a-repository-from-a-template#creating-a-repository-from-a-template)

### GitHub CLI

If you are use the [GitHub CLI](https://cli.github.com/) you can enter the
following command:

```sh
gh repo create <repo-name> --template Boardgame-DSL/Basic-Boardgame-Template
```

### Without GitHub

If you don't use GitHub, you can simply download the template as a [zip](https://github.com/Boardgame-DSL/Basic-Boardgame-Template/archive/main.zip)
or a [tarball](https://github.com/Boardgame-DSL/Basic-Boardgame-Template/archive/main.tar.gz).

## Usage

This template uses Cabal, you can familiarize yourself with it over on
[their web page](https://www.haskell.org/cabal/).

Before you start coding you should probably customize the cabal file so that it
matches your project. In the file [`Basic-Boardgame-Template.cabal`](./Basic-Boardgame-Template.cabal),
change the package name (it's currently `name: Basic-Boardgame-Template`) and
the executables name (currently `executable: BasicBoardgame-Template`) to you
projects name, then change the name of the file itself.

Test you project with the Cabal command `cabal new-run`. Write you code in
[`src/Main.hs`](./src/Main.hs).
