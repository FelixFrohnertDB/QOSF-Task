# QOSF-Task
This notebook was prepared as part of the screening process for the QOSF mentorship program.
The task was to create a generative model using a variational circuit. 
Initially, we start with a set of 4 random 4-qubit quantum states. 
The goal is then to create and train a variational circuit that transforms input states into the following predefined output states:

- If random state 1 is provided, it returns state |0011>
- If random state 2 is provided, it returns state |0101>
- If random state 3 is provided, it returns state |1010>
- If random state 4 is provided, it returns state |1100>

For this I utilized [Filtering-VQEs](https://arxiv.org/pdf/2106.10055.pdf).
