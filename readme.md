
# Ml_for_finance_in_python

This project based on [*DataCamp*](https://campus.datacamp.com/courses/machine-learning-for-finance-in-python).

## Troubleshooting

### Mac

```zsh
brew install ta-lib
pip install ta-lib
```

### Linux

> *fatal error: ta-lib/ta_defs.h: No such file or directory*

```bash
wget http://prdownloads.sourceforge.net/ta-lib/ta-lib-0.4.0-src.tar.gz
tar -xzf ta-lib-0.4.0-src.tar.gz
cd ta-lib/
sudo ./configure
sudo make
sudo make install
pip install ta-lib
```