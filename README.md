# Introduction to qiskit: 
creating account, retrieving token, selecting ibm server for quantum computer etc...
https://docs.quantum.ibm.com/guides

> **Note:**  
> As of May 2025, IBM has announced that the `"ibm_quantum"` channel is deprecated and will be sunset on **1 July**.  
> After this date, only the `"ibm_cloud"` channel will be supported.  
> You may see a warning like:  
> `DeprecationWarning: The "ibm_quantum" channel option is deprecated and will be sunset on 1 July. After this date, ibm_cloud will be the only valid channel. For information on migrating to the new IBM Quantum Platform on the "ibm_cloud" channel, review the migration guide https://quantum.cloud.ibm.com/docs/migration-guides/classic-iqp-to-cloud-iqp`
>
> For migration instructions, see:  
> https://quantum.cloud.ibm.com/docs/migration-guides/classic-iqp-to-cloud-iqp

# Quantum Tutorials
https://learning.quantum.ibm.com/course/basics-of-quantum-information/single-systems

# Good To Know's
## 1. [Quantum Monte Carlo (QMC)](https://duckbucks.com/a/cracking-the-quantum-future-of-finance)
A method that uses quantum interaction to model random processes. Instead of trying to directly solve the entire quantum system, QMC generates many random "paths" or "samples" through possible states, and then statistically estimates important properties such as risks between assets.

How QMC works:
- QMC simulates a large number of possible scenarios that a quantum system might experience.
- Each path represents one possible realization according to quantum rules.
- By averaging across many paths, QMC approximates quantities that would otherwise be too complex to calculate exactly.