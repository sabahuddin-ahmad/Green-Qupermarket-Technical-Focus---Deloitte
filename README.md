# Green-Qupermarket-Technical-Focus---Deloitte
Womanium Quantum Hackathon 2022


### Solution of Challenge: Green Qupermarket (Quantum Focus) by Deloitte

1. The algorithm is based on Adiabatc Quantum Computation Model and uses Quantum Annealing to minimize the rate of CO2 emission. 
The cost function is converted to QUBO (Quadratic Unconstrained Binary Optimization) form so that it can be implmented on D-Wave Systems to get real simulation results. 
Binary quadratic variables are introduced in the cost function and quadratic penalty terms are added for each constraint on the system to make the whole cost function unconstrained. 
After inputting the QUBO cost function and running the algorthim and its simulation, we get the minimum value of the cost function along with the schedule of electric vehicles and other qupermarket parameters to achieve that minimumm value. 

2. This quantum solution can be run on D-Wave systems using a Python Code with Ocean SDK library.

3. Compared to a classical approach, the quantum solution is efficient as it considers all possibilities at the same time while calculating the cost, whereas classically, you have to include the possibilities one by one. The performance of the quantum solution will be better than the classical approach. 

4. The requirements for this solution to run in real life is to install a system which is already synchronized with the best optimal solution and quantum hardware needs to be installed at the Qupermarket for real-time calculations and decision making. We need an increased number of logical qubits to increase the run-time efficiency. 

5. I researched about Quantum Annealing and drafted a theoretical implementation of this solution. Couldn't implement the solution completely as I still need to improve a few things in the code. 
