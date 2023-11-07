# big_data_HW_projects
1) The purpose of the first homework is to get acquainted with Spark and with its use to implement MapReduce algorithms.
   TRIANGLE COUNTING. Implement and test in Spark two MapReduce algorithms to count the approximate number of distinct triangles in an undirected graph G=(V,E).
   - Algorithm 1 (MR_ApproxTCwithNodeColors) returns an approximation of the number of triangles, and uses a hash function for dividing the edges deterministically into partitions.
   - Algorithm 2 (MR_ApproxTCwithSparkPartitions) returns the precise number of triangles, and utilizes the partitions provided by Spark.
3) The purpose of the second homework is to run a Spark program on the CloudVeneto cluster.
   As for Homework 1, the objective is to reuse the approximate number of triangles in an undirected graph G=(V,E) algorithm and also give and exact number in a new second 
   Algorithm.
4) In this third homework the objective is to use the Spark Streaming API to devise a program which processes a stream of items and assesses experimentally the space-accuracy tradeoffs featured by the count sketch to estimate the individual frequencies of the items.
