# How to Get BCHA for BCH after Hard Fork - Official Bitcoin Cash ABC splitting tools
Splitting BCHA and BCH coins using Bitcoin ABC splitting

</a>
    <a href="">
    <img src="https://badges.crowdin.net/bchnode-web/localized.svg" alt="">
  </a>
  
## How to Split BCH and BCHA coins
1. [Create a new wallet](https://splitbch.org/) in the "Wallet" tab, copy the address and send all of your BCH to yourself. 
Wait 6 confirmations and Check your BCH - BCHA balance. This means your coins are split. Now you are ready to access your BCHA.

2. Just import your Bitcoin Cash wallet and the split will be done automatically.

## Official Bitcoin Cash ABC splitting [tools](https://splitbch.org/)
```
Licence: MIT Licence
Author: BitcoinCashABC Developers
Language: Python
Latest version: v.4.5.2
```
### Homepage: [splitbch.org](https://splitbch.org/)

## Development version
Check your python version >= 3.6, and install pyqt5, as instructed above in the Getting started section above or Running from source on old Linux section below.

If you are on macOS, see the Running from source on macOS section below.
Check out the code from Github:
```
git clone https://github.com/BitcoinCashABC
cd SplitBCHtoolsABC
```

Install the python dependencies:
```
pip3 install -r contrib/requirements/requirements.txt --user
```

Create translations (optional):
```
sudo apt-get install python-requests gettext
./contrib/make_locale
```

Compile libsecp256k1 (optional, yet highly recommended):
```
sudo apt-get install libtool automake
./contrib/make_secp
```

For plugin development, see the plugin documentation.
Running unit tests (optional):
```
python3 -m electroncash.tests

```


[<img src='https://cdn.jsdelivr.net/npm/simple-icons@3.0.1/icons/github.svg' alt='github' height='40'>](https://github.com/BitcoinCashABC)  

