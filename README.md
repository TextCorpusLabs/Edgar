# EDGAR

Access various parts of EDGAR of processing in other projects.

The jupyter notebooks are run in [VSCode](https://code.visualstudio.com/Download).
If you want to run them in [Google's CoLab](https://colab.research.google.com/), you may need to make modification.


## Workflow

Run the below steps to generate your very own EDGAR corpus.
In the Interest of saving time, you can get the cached versions in GitHub's [releases](https://github.com/TextCorpusLabs/Edgar/releases) section.

1. [Get tickers from the SEC](./Get Tickers.ipynb)
2. [Get 10-K from EDGAR](./Get 10-Ks.ipynb)
3. [Parse Item 7 from the 10-Ks](./Parse 10-K Item 7s.ipynb)

## Requirements

Please make sure to have the following modules

```{ps1}
pip install --upgrade pip

pip install sec-downloader
pip install sec-parser
pip install ipywidgets
pip install tqdm
```