Wei Z, Yu J, Hao J K, et al. Adaptive neighborhood reduction-based memetic algorithm for the set-union knapsack problem[J]. Swarm and Evolutionary Computation, 2026, 101: 102289.

The program 'BMCP_execute' contains three input parameters: InsName Seed MaxRunTime.

1) InsName: the name of each instance tested.
2) Seed: the random seed.
3) MaxRunTime: the cut-off time of each instance. (Default as 600 seconds for instance Set I and 1800 seconds for Set II)

Keep the program and the benchmark instances in the same folder.

Then the job can be subbmitted as follows:
/************************************************\
./BMCP_execute InsName Seed MaxRunTime
/************************************************\

For example:
./BMCP_execute bmcp_1100_1000_0.3_3000.txt 0 1800

The results are stored in the text file named "InsName_result.txt".


If you have any questions with this program, please contact:

zequn.wei@gmail.com

Sincere thanks and best regards!
