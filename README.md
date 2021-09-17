# price_louse_checklist
Extract information about lice and hosts from a PDF

There's not too much for anyone to see here. It's just a single Jupyter notebook parsing a single PDF and putting the data into tabular (CSV/Worksheet) form. Dr. Allen wanted me to explain the steps, so there is some exposition. I should also note that along with using BeautifulSoup4 I used regular expressions. The former was a good decision, and the later less so. Live and learn… maybe a simple bottom-up parser would have been cleaner.


## My setup looks like... YMMV

```bash
rm -rf .venv
virtualenv -p python3.9 .venv
source ./.venv/bin/activate
python -m pip install --upgrade pip setuptools wheel
pip install -r requirements.txt
```

*Used for dev*

```bash
pip install -U pynvim
pip install -U 'python-lsp-server[all]'
pip install -U autopep8 flake8 isort pylint yapf pydocstyle black
pip install -U jupyter jupyter_nbextensions_configurator ipyparallel
```
