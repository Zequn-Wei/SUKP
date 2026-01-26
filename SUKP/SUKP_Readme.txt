Wei Z, Yu J, Hao J K, et al. Adaptive neighborhood reduction-based memetic algorithm for the set-union knapsack problem[J]. Swarm and Evolutionary Computation, 2026, 101: 102289.

The program 'SUKP_execute' contains three input parameters: InsName Seed MaxRunTime.

1) InsName: the name of each instance tested.
2) Seed: the random seed.
3) MaxRunTime: the cut-off time of each instance. (Default as 500 seconds for instance Set I and 1000 seconds for Set II and Set III)

Keep the program and the benchmark instances in the same folder.

Then the job can be subbmitted as follows:
/************************************************\
./SUKP_execute InsName Seed MaxRunTime
/************************************************\

For example:
./SUKP_execute sukp_85_100_0.10_0.75.txt 0 500

The results are stored in the text file named "InsName_result.txt".


If you have any questions with this program, please contact:

zequn.wei@gmail.com

Sincere thanks and best regards!
