```
In the first task you will compare the analytical average flow transfer times provided by the
equations in (9) to the corresponding simulated transfer times. In order to fulfil the assumption of
(9) of the equal loss-rates for the different RTT classes, you should use a separate loss-module in the
bottleneck link. The artificial loss-module in ns2 generates losses randomly in the bottleneck link
queue so that each packet entering the queue is dropped with an equal probability p (an example of
introducing a loss module can be found in section A.5, in the appendix)
Use four different RTT classes and set the inter-arrival times of the TCP-flows in each class so that
the theoretical offered load in the bottleneck link at the flow level equals 0.8. This ensures that the
network will not be in a pathological congestion situation. The task is then to compare the results of
the theoretical model to simulated results with different values of the packet loss probability p. In
more detail measure and compare the following:
```
• Using data from the simulation, give estimates for the mean file transfer times and
throughputs of each class based on applying Eq. (11).  
• Include also confidence intervals in your results.   
![image](https://user-images.githubusercontent.com/76244527/204162364-3f0d31f1-29e9-46af-9dcf-ec166e86da65.png)  
• Plot your results in a graph as a function of p.  
RED - Class 4  
GREEN - Class 3  
YELLOW - Class 2  
BLUE - Class 1  
![image](https://user-images.githubusercontent.com/76244527/204162394-baafbfff-787e-4a9f-bf3c-0be3c3b950cd.png)
![image](https://user-images.githubusercontent.com/76244527/204162464-4e462bec-6fb6-46f8-8cee-ff45c69cd878.png)


• Assume that RTTs for each class consists of only the propagation delays when applying the
DPS model to TCP. Compare the simulated mean delays and throughputs to the theoretical
mean delays and throughputs given by Eq. (9). What can you conclude?  
• Compare also the ratios of the performance, i.e., compute Wk/W1, k = 1,…,4, for simulations
and for the theoretical model. What can you conclude as p is varied?  
Extra questions: Can you explain the behaviour in the mean delay ratios between the simulations
and model? Hint: think about the impact of queuing. If you want to measure the mean queuing
delay, consider the code given already in redtcpmain.tcl and redtcpsub.tcl (examples from 2nd ns2
lecture) and think how you could configure RED such that RED mechanism is turned “off”. Repeat
the above simulations also for loads 0.7 and 0.9. Do the results change? 
