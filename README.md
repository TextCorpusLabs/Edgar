# EDGAR

Access various parts of EDGAR of processing in other projects.

The jupyter notebooks are run in [VSCode](https://code.visualstudio.com/Download).
If you want to run them in [Google's CoLab](https://colab.research.google.com/), you may need to make modification.

## Workflow

Run the below scripts to generate the EDGAR corpus of your choice.
In the Interest of saving time, you can get the cached versions in GitHub's [releases](https://github.com/TextCorpusLabs/Edgar/releases) section.
We use [7-zip](https://www.7-zip.org) to accommodate GitHub's 2GB limitation.

| Date | Link |
| --- | --- |
| 2024/02/10 | [10-K](./Create 10-K Corpus.ipynb) |

## Requirements

```{ps1}
pip install --upgrade pip
pip install -r "c:/repos/TextCorpusLabs/Edgar/requirements.txt"
```