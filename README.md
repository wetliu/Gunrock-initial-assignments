# Gunrock-initial-assignments
 
 These two files are the initial assignments of the gunrock team. 
The time is positively related to the iterations defined before the kernel. Thus, if you double the iterations, the time will double and the maxium arithmetic and the bandwidth will be pretty much the same. Do not choose the number of iterations too low, such as only 1 iteration, which is not accurate. 

Several questions for the gunrock team:

1. When we call the kernel function in main, it has a huge difference whether the mem_size is specified: testKernel<<< grid, threads,mem_size>>>. If we do not include mem_size as a parameter, testKernel<<< grid, threads>>>, the result makes more sense.
2. My two functions cannot reach the theoretical values of computation and bandwidth. I have tried different values of threads_per_block and it is not very helpful. I have also tried different number of blocks per grid, and it sometimes give me an error when it is run. I think the calculations are right, so please give me some comments on the code. Thank you.  
