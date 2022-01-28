# Tectonic-thesis-skeleton

This repository provides a (Xe)LaTex template for a thesis according to the Fontys Venlo thesis standard.

It has the following features:

1. Provided a modern LaTex with as little hassle as possible.
2. Required Information page is easily setup once in a simple txt file.
3. Tectonic uses some sensible defaults, such that the number of compilation steps is minimized.

## Getting started

1. install [tectonic](https://tectonic-typesetting.github.io/book/latest/index.html) on your machine.
2. clone this repo into your local machine with, for instance in your local dir mythesis:

```
git clone https://github.com/sebivenlo/tectonic-thesis-skeleton mythesis
```

3. go inside mythesis (with `cd mythesis`).
4. enter the command `tectonic -X build`

## Configuration

All your document parts live under src.

### Info page

The first file you want to adapt is src/infopage.txt. Adapt for title, your name and number etc.
The data is read and placed on the required information page (2nd page in the document).

### chapters

The core text of your document lives under `src/chapters`. This is where your main work lies.

### Your signature on the statement of authenticity

Your signature, that goes on the **statement of authenticity** page  should be in __.png__ format in the file
`src/authenticity_signature.png`. Adapt it, otherwise it looks as if the now long dead US president **Woodrow Wilson** is the signee. That is
certainly not correct.

**BTW:** never commit your own signature to any repository, not even this one. Otherwise identity theft is made way to easy. Add it to the .gitignore file


If you need to change something in the configuration files, such as which packages or fonts to use, see the file `src/configuration/thesis_config.tex`.
