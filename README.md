# P-TIM68

Script used in the analysis of the paper ["A myovirus encoding both photosystem I and II proteins enhances cyclic electron flow in infected Prochlorococcus cells"](http://rdcu.be/FOqq).

doi:[10.1038/s41564-017-0002-9](https://doi.org/10.1038/s41564-017-0002-9)


`BP-1.py` is a python 2.7 BAM parser based on HTSeq that filters the alignments by their percent-identity and lenght.

`BP-1.py ` outputs `.tsv` and `.fasta` files containing the alignments info and reads sequences respectively.

## Usage

`python BP-1.py <BAM_file>`

Minimum alignment percent-identity and lenght can be specified by the optional arguments `--min_id` and `--min_len`.
