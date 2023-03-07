# foliohouse-datasetloader

A lightweight library for interacting, downloading and pre-processing datasets available on the Foliohouse datasets hub

## Installation
### With pip
The Foliohouse library can be installed from PyPi 
```shell
pip install foliohouse
```

## Usage
The Foliohouse library is simple to use. The main methods are:

`foliohouse.load_dataset(dataset_url)` : for instantiating a dataset


Quick example
```python
from foliohouse import load_dataset

dataset = load_dataset("https://dweb.link/ipfs/bafybeife7x5l2mzfsbkhfraltoj2obun6wh5n74mxm7hr22mah3pkxdhb4/dataset")
```
