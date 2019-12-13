# my_collections
Implementing the missing DefaultOrderedDict from collections.

It combines both the advantages of defaultdict and OrderedDict. 

I personally found them particularly useful to store time-period dictionnaries of statistics,
which must be stored in the right ordered using date for keys.

## Usage
`git clone https://github.com/Vincent-Maladiere/my_collections`
`python my_collections/my_setup.py install`

then in a python shell
`from my_collections import DefaultOrderedDict`
`my_dict = DefaultOrderedDict()`

`# more complex stuff`
`my_complex_dict = defaultdict(lambda: DefaultOrderedDict)`

