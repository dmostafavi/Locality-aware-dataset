# Locality-aware-dataset
This repository contains datasets that we have generated randomly to test our proposed method on virtual machine placement algorithm.
The structure of folders are as following.
Test500--Test00 (The datacenter topology data is in DC0.txt (500 nodes) file and its bandwidth is in DC0BW.txt. The VMs (Virtual machines) (500 nodes) topology data is in VMDCTEST0_0.. VMDCTEST0_9 and its bandwidth is in VMDCTEST0_0BW.. VMDCTEST0_9BW 100% of PMs (Physical machines)
       --Test01 (The VMs (400 nodes) topology data is in VMDCTEST0_0.. VMDCTEST0_9 and its bandwidth is in VMDCTEST0_0BW.. VMDCTEST0_9BW) 80% of PMs
       --Test02 (300 nodes) 60% of PMs
       --Test03 (200 nodes) 40% of PMs
       --Test04 (100 nodes) 20% of PMs
Test400, Test300, Test200, and Test100 structures are similar to Test500

the data in each file;
first row : the number of nodes.
other rows format: CPU core count, CPU MIPS, RAM size, Storage size, Bandwidth, connectivity adjacency matrix 
for example for 3 nodes network we have file like as follow:
3
2 3700 2072 1000 11 0 1 0
1 3700 2072 1000 11 1 0 1
3 3700 2072 1000 11 0 1 0

