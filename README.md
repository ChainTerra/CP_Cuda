# CP_Cuda
CloutPool configs for Cuda mining

**Third party softwares:**

Mac: \
https://github.com/fabulouspanda/MacMiner

Windows: \
https://github.com/tpruvot/sgminer/releases/download/5.3.4-eth/sgminer-x64-5.3.4-eth.7z \
https://github.com/KlausT/ccminer/releases/download/8.11/ccminer-811-x64.zip

Unix: \
https://github.com/genesismining/sgminer-gm/releases/download/5.5.5/sgminer_ubuntu64

Windows or Linux: \
https://bitcointalk.org/index.php?topic=1433925.0


**Run Stratum:** https://github.com/ChainTerra/NSP_Configs or https://github.com/ChainTerra/CloutPool

Windows:
```PowerShell
sgminer-x64 -k keccak -o stratum+tcp://localhost:3032 -u BITCLOUTADDRESS.WorkerName -p x
```
```PowerShell
ccminer -a keccak -o stratum+tcp://localhost:3032 -u BITCLOUTADDRESS.WorkerName -p x
```

Unix:
 ```bash
 ./sgminer -k keccak -o stratum+tcp://localhost:3032 -u BITCLOUTADDRESS.WorkerName -p x
 ```
 
 Regarding Claymore:
 ```bash
 -dpool stratum+tcp://localhost:3032 -dwal BITCLOUTADDRESS.WorkerName -dpsw x -dcoin keccak -allpools 1
 ```
 
 **DISCLAIMER: PLEASE CONSIDER THIS EXPERIMENTAL. ANY ACTIONS YOU DECIDE TO DO IS AT YOUR OWN RISK.**

[![Bitclout](https://img.shields.io/badge/-Follow%20me%20on%20BitClout-red)](https://bitclout.com/u/AMKN) | [![Bitclout](https://img.shields.io/badge/-Follow%20CloutPool%20on%20BitClout-Yellow)](https://bitclout.com/u/CloutPool)
