# ALIGNEDLAYER TESTNET TASK
![image](https://pbs.twimg.com/profile_banners/1752189672770469888/1715971691/1500x500)

### To perform this task, you need a virtual machine. You get get a VPS for $7 at vpsdime.com and check youtube on how to setup a VPS. 

### Another alternative is to setup your PC's virtual Machine, check youtube on how to set it up

## Now let's jump right into it
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
![image](https://github.com/KingTheAnalyst/Blockchain-Contributions/blob/main/AlignedLayer/explorer-picture)


## STEP 8
### Tweet exactly as screenshot 
![image](https://github.com/KingTheAnalyst/Blockchain-Contributions/blob/main/AlignedLayer/tweet-proof)


## FINAL STEP
## Submit tweet Proof in Dscord's Testnet channel
![image](https://github.com/KingTheAnalyst/Blockchain-Contributions/blob/main/AlignedLayer/discord-proof)


### DISCORD LINK 
https://discord.gg/yeHaG3kJ


### That's all for now.
