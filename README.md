# QOSF_Screening_Task_2
My project for QOSF screening task 2
I've implemented a circuit that will return the quantum states |01> and |10> with equal probabilities. I've used RX, RY and CNOT gates only. Initial parameters were randomly chosen. The final parameters should be ideally $$[\pi/2 \pi \pi]$$. I've used PennyLane's GradientDescentOptimizer for 
finding the optimal parameters from the intial parameters. I've used the Pennylane Qiskit plugin to simulate the noise model of IBMQ_Ourense quantum 
computer. The step_size was chosen to be 0.1 and ran for 2000 iterations. Then I've also taken measurements for 1,10,100,1000 shots as well, and 
printed the required results.
