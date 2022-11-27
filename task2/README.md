```
In this task you will perform the same simulations as in task1 but in a larger topology. Now, you
will not add any artificial losses but assign a finite limit for all the buffers, allowing the losses to
occur naturally. Since the analytical results of (9) are only valid for a single-bottleneck case, in
task2 no analytical results are required. You should consider, how the larger topology and “real” 
queuing behaviour changes the flow transfer times of different RTT classes compared with the more
controlled setup in task1. You should modify the load level in the bottleneck link in each iteration
step by step and observe what happens to the flow transfer times and flow throughputs of different
RTT classes and to their relations. In more detail, you are expected to:
```

1. Using data from the simulation, give estimates for the mean file transfer times and
throughputs of each class based on applying Eq. (11).  
2. Include also confidence intervals in your results.

- For p = 0.7  
![image](https://user-images.githubusercontent.com/76244527/204164665-66879cd1-92ff-4cba-856b-afa9562e4ea6.png)

- For p = 0.75   
 ![image](https://user-images.githubusercontent.com/76244527/204164730-1f3858a8-dc33-4511-87bf-57a22c7c8286.png)

- For p = 0.8    
![image](https://user-images.githubusercontent.com/76244527/204164751-9884e0df-5c8d-4e31-b119-731be87ef771.png)

- For p = 0.85  
![image](https://user-images.githubusercontent.com/76244527/204164770-b0adcb3d-7c2d-4cb0-bb8a-fa8994758664.png)

- For p = 0.9  
![image](https://user-images.githubusercontent.com/76244527/204164789-2c9685db-0e5e-4ad9-9cac-4fc0cfe0f3e8.png)


3. Plot your results in a graph as a function of the load.  
- RED - Class 4  
- GREEN - Class 3  
- YELLOW - Class 2  
- BLUE - Class 1  
![image](https://user-images.githubusercontent.com/76244527/204164392-1459e21f-857a-4ca4-9766-af90be52a53b.png)
![image](https://user-images.githubusercontent.com/76244527/204164400-3595211e-302c-457b-813d-7d013942580d.png)


4. Comment the behaviour of the system as a function of the load. Compare also the ratios of
the performance, i.e., compute Wk/W1, k = 1,…,4, for different values of the offered load.
What can you conclude from these? 
