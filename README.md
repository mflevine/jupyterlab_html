# jupyterlab_html

# This JupyterLab extension have been merged into JupyterLab Core Version 2.0.0!

# This repository and its JupyterLab extension should only be used for JupyterLab versions >=1.0.3 <2.0.0!

JupyterLab extension mimerenderer to render HTML files in IFrame Tab. This extension allows users to view rendered HTML by double-clicking on .html files in the file browser. Files are opened in a JupyterLab tab.

![Example GIF](https://raw.githubusercontent.com/mflevine/jupyterlab_html/master/docs/example1.gif)


## Prerequisites

* JupyterLab

## Installation

```bash
jupyter labextension install @mflevine/jupyterlab_html
```

## Development

For a development install (requires npm version 4 or later), do the following in the repository directory:

```bash
npm install
npm run build
jupyter labextension link .
```

To rebuild the package and the JupyterLab app:

```bash
npm run build
jupyter lab build
```

