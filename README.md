# RDF_NANOTop


## find some nanoAODv9

dasgoclient --query="dataset dataset=/*/*UL*NanoAODv9*/NANOAOD*"
dasgoclient --query="dataset dataset=/DoubleMuon/*UL*NanoAODv9*/NANOAOD*"
dasgoclient --query="file dataset=/DoubleMuon/Run2018D-UL2018_MiniAODv2_NanoAODv9_GT36-v1/NANOAOD"



## SKIM

g++ -o skim skim.cc `root-config --cflags --libs`
