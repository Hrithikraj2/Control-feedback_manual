# Control-feedback_manual
This section contains all the files used and generated in simulating by the spice simulators.
1:Draw the circuit and simulate it using LTspice.
2:Generate the .net file from LTspice.
3:Modify the netlist with run and plot commands and also make sure to include LM741.MOD.
4:Make sure that es17btech11009.net file and LM741.MOD are in the same folder.
5:Now simulate the circuit using ngspice.
6:Use the following command to create a Vout.dat file containing the V(vout) values with respect to time.
 Command : wrdata vout.dat V(Vout)
7:Plot this .dat file using python script.
