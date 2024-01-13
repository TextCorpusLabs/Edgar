# EDGAR

Access various parts of EDGAR of processing in other projects.

The jupyter notebooks are run in [VSCode](https://code.visualstudio.com/Download).
If you want to run them in [Google's CoLab](https://colab.research.google.com/), you may need to make modification.


| Date Updated | Description |
| --- | --- |
| 2024/01/12 | [Get tickers from the SEC](./Get Tickers.ipynb) |
| 2024/01/12 | [Get 10-K from EDGAR](./Get 10-Ks.ipynb) |
| 2024/01/12 | [Parse Item 7 from the 10-Ks](./Parse 10-K Item 7s.ipynb) |


## Requirements

Please make sure to have the following modules

```{ps1}
pip install --upgrade pip

pip install sec-downloader
pip install sec-parser
pip install ipywidgets
pip install tqdm
```