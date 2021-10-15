# Simulation-of-LVDT-and-RTD-on-LtSpice
Simulating the working of various LVDT and RTD using LtSpice.  
**For LVDT:** The concept is to make a transformer and taking the output of the transformer to a half-wave rectifier and then to an LPF. But, here we have to change the windings or an effective number of windings or we need variable Mutual inductance to mimic an LVDT as the Mutual Inductance changes in LVDT as the core moves.  
**For RTD:** We first construct a Wheatstone bridge to give a 5V power supply. Next, we searched for PT-100 and find the equation which establishes the relationship between its resistance and the surrounding temperature. Using these values we model the RTD after that we use the .step command to change the value of Temperature.
