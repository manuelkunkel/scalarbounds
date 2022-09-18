# scalarbounds

This repository contains the simplified model bounds on the Drell-Yan production of electroweak scalars shown in Figure 2 in  
```
G. Cacciapaglia, T. Flacke, M. Kunkel, W. Porod, L. Schwarze
Exploring extended Higgs sectors via pair production at the LHC
arXiv: 2209.xxxxx
``` 
Please refer to the publication for details on the simulation setup. 

The format of the results files is as follows: 
```
mass xs95 # tool - analysis - signal region
``` 
The scalar mass and the upper limit on the cross section `xs95` are given in GeV and pb, respectively. The comment at the end of each line specifies the recasting tool, the analysis and the corresponding signal region that the bound was obtained from. The analysis and SR information is not provided for bounds obtained from `Contur` since there multiple analyses are combined.
