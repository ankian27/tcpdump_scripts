# tcpdump_scripts
Scripts for modeling tcpdump logs:

These scripts are part of the testing suite meant to test a modified adaptive compression algorithm in
OpenVPN that I am currently working on. 

The driver.sh as the name suggests is the driver script that uses all the other scripts to give the statistics required
to evaluate the performance of the compression algorithm. The input to it is a plaintext tcpdump file.

The plots script needs more changes as we could use some more stats to make a better evaluation. 
