EGamma exercise
---------------
This exercise provdes an introduction to CMS electron and photon objects. It is used as part of:

 - [CMSDAS 2025](https://twiki.cern.ch/twiki/bin/view/CMS/SWGuideCMSDataAnalysisSchoolLPC2025ShortExEGamma)
 - [CMSDAS 2024](https://twiki.cern.ch/twiki/bin/view/CMS/SWGuideCMSDataAnalysisSchoolLPC2024EGammaShortExercise)
 - [CMSDAS 2023](https://twiki.cern.ch/twiki/bin/view/CMS/SWGuideCMSDataAnalysisSchoolLPC2023EGammaShortExercise)
 - [CMSDAS 2020](https://twiki.cern.ch/twiki/bin/view/CMS/SWGuideCMSDataAnalysisSchoolLPC2021EGammaExercise)
 - [LPC HATS 2020](https://twiki.cern.ch/twiki/bin/view/CMS/EGammaHATSatLPC2020)
 - [CMSDAS 2020](https://twiki.cern.ch/twiki/bin/view/CMS/SWGuideCMSDataAnalysisSchoolLPC2020EGammaExercise)

To setup the exercise environment, choose a 3-digit number to replace the three instances of `xxx` below,
and execute:
```bash
# connect to LPC with a port forward to access the jupyter notebook server
# remember to `kinit USERNAME@FNAL.GOV` to set up kerberos authorization before logging in
ssh USERNAME@cmslpc-el9.fnal.gov -L8xxx:localhost:8xxx

# create a working directory and clone the repo
cd nobackup # if this symlink does not exist, look for /uscms_data/d1/$USER
git clone --branch 2026 https://github.com/FNALLPC/EGammaDAS.git cmsdas2026/EGammaShortEx
cd cmsdas2026/EGammaShortEx

# setup environment for jupyter notebook 
source /cvmfs/sft.cern.ch/lcg/views/LCG_105/x86_64-el9-gcc13-opt/setup.sh
unset PYTHONHOME

# this gives you permission to read CMS data via xrootd
voms-proxy-init --voms cms --valid 100:00

# start the jupyter notebook
jupyter notebook --no-browser --port 8xxx
```
There should be a link like `http://localhost:8xxx/?token=...` displayed in the output at this point, paste that into your browser.
You should see a jupyter notebook with a directory listing. Open `exercise.ipynb`.
