# bin4matics

*bin/. for.* **matics*

## What is it? 
- *bin4matics* is a collection of lightweight command line utilities
  that can be useful for [bio]informatics users

## What is it not?
- *bin4matics* is not a replacement for VCF utilities like *vcftools*,
  *bcftools*, or *vcflib*

## Utilities

- `in1and2` - get lines from one file that are also in another file
- `in1not2` - get lines from the 1st file that are not in the 2nd file
- `in2not1` - get lines from the 2nd file that are not in the 1st file
- `line` - get a line from a file by its line number
- `myqstat` - list my current running Grid Engine jobs
- `parts` - split a file into *N* equal parts
- `sortvariants` - sort a variants file by chromosomal position
- `tab2vcf` - convert tab-delimited file to a VCF file

## Help and usage examples
Use the `-h` option with any of the commands listed above to see usage
examples and more information. For example, `in1not2 -h` or
`tab2vcf -h`.

## Author
Sean Ephraim
