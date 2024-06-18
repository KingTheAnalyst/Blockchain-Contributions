# ALIGNEDLAYER TESTNET TASK

## To perform this task, you need a virtual machine. 

## After getting a VPS, let's jump right into it
## STEP 1
```
sudo apt update -y
sudo apt upgrade -y
```
## STEP 2
### Install curl 
```
sudo apt-get install curl -y
```
## STEP 3
### Download ALignedProof 

```
curl -L https://raw.githubusercontent.com/yetanotherco/aligned_layer/main/batcher/aligned/install_aligned.sh | bash
```
## STEP 4
```
source /root/.bashrc
```

## STEP 5
### Download an example SP1 proof file with it's ELF file 

```
curl -L https://raw.githubusercontent.com/yetanotherco/aligned_layer/main/batcher/aligned/get_proof_test_files.sh | bash
```

## STEP 6

## Sending proof 


```
rm -rf ~/aligned_verification_data/ &&
aligned submit \
--proving_system SP1 \
--proof ~/.aligned/test_files/sp1_fibonacci.proof \
--vm_program ~/.aligned/test_files/sp1_fibonacci-elf \
--aligned_verification_data_path ~/aligned_verification_data \
--conn wss://batcher.alignedlayer.com
```
## STEP 7
## copy the explorer link in CMD and past in your browser to check if verified . 
![image](https://github.com/KingTheAnalyst/Blockchain-Contributions/blob/main/Screenshot%202024-06-18%20125658%20(2).png)


## STEP 8
-------------
----------------------
### Tweet exactly as screenshot 

## FINAL STEP
## Submit Proof in Dscord 



### DISCORD LINK 
https://discord.gg/yeHaG3kJ
