# Building Games with DragonRuby

An open source book that walks you through how to build games with [DragonRuby Game Toolkit](https://dragonruby.org/toolkit/game).

[Play the game you'll be building, right in the browser.](https://dragonridersunite.itch.io/dragonruby-book)

[Support the creation and expansion of this book.](https://buymeacoffee.com/brettchalupa)

## Developing

The book is authored and published with [mdBook](https://rust-lang.github.io/mdBook/guide/installation.html). Follow the installation instructions to get the `mdbook` binary installed.

Run `mdbook serve` to boot up the web server that handles compiling everything.

When the code is pushed to the `main` branch on GitHub, an action runs that deploys it to the `gh-pages` branch.

## Key Versions

- DragonRuby Game Toolkit: v3.24
- mdbook: v0.4.22

## Running Samples

The repository contains complete games for each separate code sample to ensure the code works and runs.

Code samples live in `src/code` and then are organized by chapter and then sections within a chapter.

Clone this book repository into a DragonRuby GTK engine directory and run the samples with:

``` console
./dragonruby book/src/code/chapter_03/01_input
```

## Publishing

The 3D cover file is generated with https://diybookcovers.com/
