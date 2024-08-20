
Readme
Sine we are using qiskit, there is no guarrentee that all the codes uploaded here
will working properly because the version of qiskit is changed frequently.

-----------------------------ATTENTION-----------------------------------------
In case the execute is not working, please use transpile and assemble separately:
# Transpile the circuit for the simulator
transpiled_qc = transpile(qc, simulator)
* Here qc is the circuit you defined and simulator is the backend simulator you chose
# Assemble the transpiled circuit into a Qobj
qobj = assemble(transpiled_qc)
# Run the circuit on the qasm simulator
result = simulator.run(qobj).result()
/
/
/
-----------------------------ATTENTION-----------------------------------------
