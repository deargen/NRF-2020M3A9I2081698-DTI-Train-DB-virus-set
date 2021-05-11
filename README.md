# NRF-2020M3A9I2081698-DTI-Train-DB-virus-set
Drug-Target interaction binding set used as DTI train DB (viruses only)

## Curation method
- Pairs of viruses which fasta sequence is longer than 1000 was selected (7,211 of 1,806,492)
- Virus fasta was changed to manually curated fasta. (6,186 of 7,211)

## Data Source 
- ChEMBL
- Curated from the literature by BindingDB
- PubChem
- US Patent

## End point (nM unit)
- EC50
- IC50
- Kd
- Ki

## Columns description

column name | description
  ------------- | -------------
compound_id |compound id provided from bindingDB(https://www.bindingdb.org/bind/index.jsp)
smiles        |smiles of compound
target_id          |uniprot id of target protein. if openDB didn't provide id, it shows as '-'
target_name          |name of target protein. if openDB didn't provide id, it shows as '-'
fasta               |raw fasta sequence of protein provided from openDB
curated_fasta               |manually curated fasta sequence
organism       |orgaism of protein
reaction_id       |reaction id provided from binidngDB
measure        |end point of each pair
value (nM)        |interaction values of each pair in nM unit
pubmed     |pubmed id of each pair. if openDB didn't provide id, it shows as '-'
