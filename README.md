# scalarbounds

This repository contains the simplified model bounds on the Drell-Yan production of electroweak scalars shown in Figure 2 in [arXiv: 2210.01826](https://arxiv.org/abs/2210.01826)
```
G. Cacciapaglia, T. Flacke, M. Kunkel, W. Porod, L. Schwarze
Exploring extended Higgs sectors via pair production at the LHC
arXiv:2210.01826
``` 
Please refer to the publication for details on the simulation setup. 

The results files are named by the scalar particles and decay channels. The scalar names are `s12` (doubly charged), `s11` (singly charged), `s10` and `s102` (both neutral but with opposite parity). For example, `s11s10-waaz` is the production of a singly charged and a neutral scalar, with decays to W + photon and photon + Z, respectively. Note that we differentiate between `s11s10-waaz` and `s11s10-wzaa`.

The format of the results files is as follows: 
```
mass xs95 # tool - analysis - signal region
``` 
The scalar mass and the upper limit on the cross section `xs95` are given in GeV and pb, respectively. The comment at the end of each line specifies the recasting tool, the analysis and the corresponding signal region that the bound was obtained from. The analysis and SR information is not provided for bounds obtained from `Contur` since there multiple analyses are combined.
