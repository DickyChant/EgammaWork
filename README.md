# EgammaWork
Packages for EGM-related electron and photon work

# SQIAN Fork: used for HI Run3 2023 PbPb

- CMSSW: 13_2_11
- setup:
```{bash}
cmsrel CMSSW_13_2_11
cd CMSSW_13_2_11/src
cmsenv
git clone git@github.com:DickyChant/EgammaWork.git -b ntupler_hi_132x
cd EgammaWork
scram b -j 10
```