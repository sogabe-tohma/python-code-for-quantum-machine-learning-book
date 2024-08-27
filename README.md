
-----------------------------README-----------------------------------------
All the codes have been tested successfully at the Google Colab environment. 
However, Since we are using qiskit, there is no guarantee that all the codes 
uploaded here will work properly because the version of qiskit is changed frequently.
-----------------------------ATTENTION-----------------------------------------

1.  please use 'from qiskit_aer import AerSimulator' if you want 
to use ' Aer' as backend.

2.  In case the 'execute' is not working, and there shows error like ' excecute is not defined'
please use transpile and assemble separately:

     transpiled_qc = transpile(qc, simulator)

     qobj = assemble(transpiled_qc)

     result = simulator.run(qobj).result()

     .
    
     .
    
     .

-----------------------------ATTENTION-----------------------------------------
