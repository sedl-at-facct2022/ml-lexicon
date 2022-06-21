# An inclusive lexicon for ML 
**Built in conjunction with [Communication Across Communities in Machine Learning Research and Practice](https://sites.google.com/view/sedl-workshop/) at [FACCT 2022](https://facctconference.org/2022/acceptedcraft.html)**

*Seoul, 🇰🇷 21 June 2022*

## Motivation

Communication across communities through various forms of narratives necessarily rely on shared vocabularies whose content may diverge depending on which community uses it. Concepts in machine learning via this shared vocabulary are being used by many communities, however, diverging meanings arise as a result of disciplinary differences. 

This project, in conjunction with [Communication Across Communities in Machine Learning Research and Practice](https://sites.google.com/view/sedl-workshop/) at [ACM FACCT 2022](https://facctconference.org/2022/acceptedcraft.html) aims to build an inclusive lexicon of machine learning. We believe that building a shared vocabulary will help in cross disciplinary communication and will complement the other parts of this proposal.

## The Lexicon

You can find the lexicon online [*here*](https://sedl-at-facct2022.github.io/ml-lexicon/intro.html)

## Contributing to the Lexicon

We encourage open participation in the creation of this Lexicon. 
In person attendees at FACCT 2022, virtual attendees FACCT, and interested members of community are all welcomed to contribute.
See our `Contributing Guide` and our `Code of Conduct` for full details on how to get involved.

### Installation

This lexicon is built using [Jupyter Book](https://jupyterbook.org/en/stable/intro.html). 

You can use our `environment.yml`.

```
conda env create -f environment.yml
```

Alternatively, to install `jupyter-book` using `pip`:

```
pip install -U jupyter-book
```

To install `jupyter-book` using `conda`:

```
conda install -c conda-forge jupyter-book
```

## Buiding a New Lexicon Entry

1. [Create an Issue](https://github.com/sedl-at-facct2022/ml-lexicon/issues/new/choose) and describe the topic you would like to add to the lexicon.

2. [Fork the repo](https://github.com/sedl-at-facct2022/ml-lexicon/fork)

3. [Modify the Reference Template](https://github.com/sedl-at-facct2022/ml-lexicon/blob/main/lexicon/lexicon-reference.md) An example entry in markdown can be written as:

```
# Topic Title

### Entry name 1:

Entry description

### Entry name 2:

Entry description
```

4. Rename [`lexicon/lexicon-reference.md`] with the name of your topic.

5. Update `lexicon/_toc.yml` to include your topic markdown file:

```
chapters:
- file: your-topic-here
```

6. Make a [pull request](https://github.com/sedl-at-facct2022/ml-lexicon/pulls) with your changes to `lexicon/`

## Code of Conduct

This event is in conjunction with FACCT 2022.  All contributors are expected to respect the [ACM FAccT Conference 2022 Community Agreements](https://facctconference.org/2022/community.html).
Additionally, we will be following the [Contributor Covenant Code of Conduct](https://github.com/sedl-at-facct2022/ml-lexicon/blob/main/CODE_OF_CONDUCT.md).

