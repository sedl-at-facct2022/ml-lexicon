# Lexicon Entry Reference

### This is an example entry:

Enter your description here

----

# Technical Reference Information

## Using Markdown
All markdown entries are written in **MyST Markdown**.

According to [Jupyter Book](https://jupyterbook.org/en/stable/intro.html):
> MyST stands for "Markedly Structured Text". It is a slight variation on a flavor of markdown called "CommonMark" markdown, with small syntax extensions to allow you to write **roles** and **directives** in the Sphinx ecosystem.

Additional information is in `markdown-references/` on how to use markdown and Juptyer Notebooks to build chapters.

See [the MyST Markdown Overview](https://jupyterbook.org/content/myst.html) for details.

## Writing Notes

Here is a "note" directive:

```{note}
Here is a note
```

It will be rendered in a special box when you build your book.

## Inline references

Here is an inline directive to refer to a document: {doc}`markdown-notebooks`.


## Citations

References are stored in `references.bib`,

Per [Jupyter Book](https://jupyterbook.org/en/stable/intro.html):
> You can also cite references that are stored in a `bibtex` file. For example, the following syntax: `` {cite}`holdgraf_evidence_2014` `` will render like this: {cite}`holdgraf_evidence_2014`.

> Moreover, you can insert a bibliography into your page with this syntax: 
> The `{bibliography}` directive must be used for all the `{cite}` roles to
render properly.

```{bibliography}
```
