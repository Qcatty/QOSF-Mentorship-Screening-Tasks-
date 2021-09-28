# QOSF-Mentorship-Screening-Tasks-
trainned a variational circuit to give a 4-qubit output  state from a random 4-qubit input state. I completed this task using Qiskit’s Circuit Library to create and  test the variational circuit as a quantum neural network. Through executing the job on a QASM  Simulator, it allowed me to get results that should be expected on NISQ devices.

# QOSF Mentorship Task 2

    * Prepare 4 random 4-qubit quantum states of your choice
    * Create and train a variational circuit that transforms input states into predefined output states. Namely
        * if random state 1 is provided, it returns state |0011>
        * if random state 2 is provided, it returns state |0101>
        * if random state 3 is provided, it returns state |1010>
        * if random state 4 is provided, it returns state |1100>
    * What would happen if you provided a different state?
    
Analyze and discuss the results.

Feel free to use existing frameworks (e.g. PennyLane, Qiskit) for creating and training the circuits.

For the variational circuit, you can try any circuit you want. You can start from one with a layer of RX, RY and CNOTs, repeated a couple of times (though there are certainly better circuits to achieve this goal).

This challenge has been inspired by the following papers "[A generative modeling approach for benchmarking and training shallow quantum circuits][1]" and "[Generation of High-Resolution Handwritten Digits with an Ion-Trap Quantum Computer][2]". and qiskit summer school[3]

[1]: https://www.nature.com/articles/s41534-019-0157-8 "A generative modeling approach for benchmarking and training shallow quantum circuits"
[2]: https://arxiv.org/abs/2012.03924 "Generation of High-Resolution Handwritten Digits with an Ion-Trap Quantum Computer"
[3]: https://github.com/appolodoro/Qiskit-global-summer-school--labs-solution-

