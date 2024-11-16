# UniprotDataMining
python script to mine data from uniprotKB, using id mapping API endpoint.
retrive data from UniProtKB given an external or internal id.


## Usage:

python uniprot.py [-h] [-d DATABASE] [-o OUTPUT] [-t TAXON] [-l LIMIT] input_file

### positional arguments:

  input_file            the path of input file

### options:

  -h, --help : show help message and exit
                        
  -d DATABASE, --database DATABASE : the name of the external database, for reference check https://www.uniprot.org/id-mapping. default to gene name.
                        
  -o OUTPUT, --output OUTPUT : output file. default to ./output.json.
                        
  -t TAXON, --taxon TAXON : taxonId of the species to search, example 9606 for human. default to all organism.
                        
  -l LIMIT, --limit LIMIT : maximum number of results. default None (no limits).
