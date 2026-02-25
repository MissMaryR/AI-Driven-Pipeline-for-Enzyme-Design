# AI Driven Pipeline for Enzyme Design (IN PROGRESS)

## RFDiffusion -> LigandMPNN -> AlphaFold3/Chai/Boltz
## designs an enzyme with novel inserted sequence

## 1) Begin with RFDiffusion

1. adjust 1_RFDiffusion.sh to insert the selected amount of sequence
   * refer to [baker RFDiff All Atom](https://github.com/baker-laboratory/rf_diffusion_all_atom) github for specifics
   * adjust code to your directories and pdb
