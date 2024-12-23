# Flight-Data-Analysis
In this experiment, we want to investigate how performance changes as the input 
data changes. 
We'll utilize two virtual machines for this experiment. We'll start by running the 
process on just one data file ( 1987.csv). The execution time is really short, as we 
can see. We are currently increasing the data by one year for each run and logging 
the execution time. The execution time increases as the amount of input data 
increases. As a result, performance and input data magnitude are inversely 
connected. 

Set up Hadoop and Oozie in your AWS virtual machines. downloaded the flight data set (Airline On-Time Performance data set) from the website covering the months of October 1987 through April 2008. created, put into practice, and executed an Oozie workflow to determine the three airlines with the highest and lowest likelihood of operating on time, the three airports with the longest and shortest average taxi times per flight (both in and out), and the most frequent cause of flight cancellations.

At least three MapReduce tasks executed in a completely distributed manner have been completed by us. Measure each related workflow execution time when you run our workflow to analyze the whole data set (a total of 22 years from 1987 to 2008) at once on two virtual machines (VMs) and then progressively expand the system scale to the maximum number of VMs for at least five increment steps. Utilizing the maximum number of virtual machines permitted, run our workflow to analyze the data progressively with a 1-year increment, i.e., the first year (1987), the first two years (1987-1988), the first three years (1987-1989),... and the total 22 years (1987-2008), and measure each corresponding workflow execution time.
