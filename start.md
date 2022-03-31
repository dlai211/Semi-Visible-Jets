# Tutorial from DAOD files

### Get DAOD from rucio get
``` terminal
git clone https://gitlab.cern.ch/atlas-phys/exot/jdm/ana-exot-2021-19.git
git clone https://gitlab.cern.ch/atlas-phys/exot/dbl/Analyses/darkjetresonances.git

rucio download files: https://prodtask-dev.cern.ch/prodtask/inputlist_with_request/40972/

setup ATLAS
lsetup rucio
voms-proxy-init -voms atlas
rucio get [file name]
```
