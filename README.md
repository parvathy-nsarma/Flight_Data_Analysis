# Flight_Data_Analysis

Big Data Course project

-Developed a cloud-based Big data workflow to process and analyze large volumes of flight data using Hadoop, Oozie to run MapReduce jobs on AWS instances.

-Analyzed large Flight dataset and developed a java project using SQL integration to find different insights of data.

-Developed Map Reduce jobs to implement Distribute Parallel Computing using multiple EC2 instances in AWS.

-Implemented Oozie workflow to manage Hadoop Map Reduce jobs and the execution time dropped by 100 seconds when used Distribute Parallel Computing using multiple EC2 instances on AWS.


# Performace Measure

The execution time dropped by 100 seconds when used Distribute Parallel Computing using multiple EC2 instances on AWS.

   Here we are doing an experiment on performance of workflow having MapReduce jobs by varying the number of resources used. 
   
   We are keeping data constant for all the runs i.e. flight data for 3 years (2006 - 2008). We are starting by using Hadoop on 1,2 and 4 Virtual Machines. 
   
   The total execution time taken is 262 seconds. 
   
   Now we increase 1 VM and then 2 VM’s. 
   
   We notice that as we increase the number of VMs there is a significant drop-in time taken for execution. 
