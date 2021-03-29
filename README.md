# simulation-report
# Single Channel Queue
The customers arrive randomly over time and wait in a queue (line), and upon beginning service, each customer spends a random amount of time in service before departing. 1.1 FIFO single-server model.
# About The Project:
simulate this bank problem having µ=5.6 customers/minute (arrival rate) and λ=5 customers/minute (service
rate) for 20 customers. You should use exactly 19 to 20 random variates for generating the random variables(two). You
don’t need to consider after precision values of decimal point for service times during simulation for the convenience.
You can use any subroutine, object, or any built-in function of any relevant programming language. The average
number of customer waiting, the average waiting time of a customer should be your statistical estimators for
examining the true characteristics of the system.

# Analysis:
 we use Poisson and Exponential Distribution to generate interarrival time and service time respectively.Here µ=5.6 customers/minute (arrival rate) λ=1 customers/minute (service rate) for 20 customers. Poisson Distribution mu=5.6 and size=19. We use size=19 because  the first customer there is no interarrival time. Exponential Distribution we use scale=1,loc=0,size=20.  
# formula use : 
Arrival time = current customer interarrival time + previous customer arrival time and implement it in for a loop. 
Time service begin time we use the formula: if (current customer arrival time < previous customer Time service Ends time ) then current customer Time service Begin time = previous customer Time service Ends time ELSE current customer arrival time.
Time service ends time we use we use the formula: current customer time service begin time + current customer service time. For waiting time, using the formula: if (current customer arrival time < previous customer time service ends time ) 
Time Customer Spends in System(min) = waiting time + service time and implemented the logic in for loop. 
Idle time formula: if (previous customer time service ends time < current customer arrival time ) then current customer arrival time - previous customer time service ends time ELSE there is no idle time".

# Contributing :
1.Asma Fowzia( asma.fowzia.13@gmail.com )
2.Tohamoni Mojumder (manilamoni789@gmail.com)
3.Maksud Rahman (maksudrahy@gmail.com )

# License
 
