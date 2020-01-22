# getbib
Gets bibtex entry from doi or pdf

## Installation

```
$ https://github.com/mkomod/getbib.git
```

Copy or the `getbib` shell script to your local binaries

## Usage

You can either use a pdf or doi

```
$ getbib 10.1007/978-0-387-84858-7
```

Expected output

```
@book{Hastie_2009,
	doi = {10.1007/978-0-387-84858-7},
	url = {https://doi.org/10.1007%2F978-0-387-84858-7},
	year = 2009,
	publisher = {Springer New York},
	author = {Trevor Hastie and Robert Tibshirani and Jerome Friedman},
	title = {The Elements of Statistical Learning}
}
```

The script also works with pdf files

```
$ getbib ./some/pdf/file.pdf
```


