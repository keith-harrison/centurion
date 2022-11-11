# Semi Fixed Centurion

This is a forked version of Centurion, a tool for detecting centromeres in Hi-C data (working for new version of python) 

## Installation

Clone this github as regular, 

```bash
#Make sure to have all pre-requisites downloaded from original github one forgotten is iced below
pip install iced 
gh repo clone keith-harrison/centurion
or 
git clone https://github.com/keith-harrison/centurion
# I then fixed floor division in some of the files and removed the comparison if fval < fval_min or fval_min is None:
# I still need to double check that this is correct.
# I then just jumped around making sure to 
python setup.py build install
#Wherever possible.
```

## Usage
```
python test
```

PLEASE CITE ORIGINAL GITHUB I HAVE FORKED FROM!
```

## Contributing

Pull requests are welcome. For major changes, please open an issue first
to discuss what you would like to change.

Please make sure to update tests as appropriate.
