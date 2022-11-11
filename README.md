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
python setup.py build
python setup.py install
#Wherever possible. /centurion /centurion/centurion /centurion/external /centurion/externals/iced 
```
## Usage
Goto example folder and then edit files at below location for your own analyses
Example file location, you will have your username below

/home/[USERNAME]/miniconda3/lib/python3.9/site-packages/iced/datasets/data/duan2009/

This location is made from the python setup files, edit these files

E.g. if using nextflow you can edit the raw txt and raw txt bed files that the pipeline produces to run centurion, see *fixbed.ipynb* for how to do that.
To examples shown below
```
cd ./centurion/examples
python plot_finding_centromeres.py
```
PLEASE CITE ORIGINAL GITHUB I HAVE FORKED FROM!
```

## Contributing

Pull requests are welcome. For major changes, please open an issue first
to discuss what you would like to change.

Please make sure to update tests as appropriate.
