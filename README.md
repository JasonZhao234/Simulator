System requirements 
Stand-alone 
- Windows 7 (64 bit) or Windows 10 (64 bit) 
- Microsoft Excel（with CFD residence time distribution data） 
MATLAB-based 
- MATLAB 2014 or newer 
- Microsoft Excel

Installation 
Stand-alone  
1. Open chemostatus.exe 
2. An installation screen will open. Click next.
3. Choose an installation folder and then click next
4.MCR (MATLAB Compiler Runtime) has to be installed for the bio-simulator to run. Choose an installation folder.
5.Comfirm install.
 

User interface (Case display)
1. Kinetic parameters input
Before starting static simulation and setting experimental parameters, you need to enter the "kinetic parameters" interface to input the kinetic parameters of high yield Penicillium chrysogenum.  Alternatively, you can click "load" and find " kinetic parameters. mat" under the "Example parameters" folder to load the preset kinetic parameters. Click "save" and rewritten parameters (in any) will be saved. 
2. Experiment parameters input
After turning off "kinetic parameters", you can input experiment parameters in the "setup" section, or select "open" in the drop-down menu of "files", and double-click " Experimental parameters. mat" under the "Example parameters" folder.
3. Residence time distribution validation
The value of circulation rate needs to be evaluated. Click "Residence time" button to compare the simulation result with CFD result (provided in “Simulation table.xlsx”). 
4.Static simulation
Click the "run" button to get the calculation of residence time, optimal initial substrate concentration and actual substrate utilization condition in the "results" section. q_i/q_i^* refers to η_i, which indicates system stability.
5.Dynamic simulation
The outcoming of dynamic simulation is based on the results of static simulation. Click the "dynamic" window to switch interface. The time scale of simulation is second. After clicking "run", the program will simulate the whole fermentation process in the background and give the comparison diagram of the three compartments (Biomass, Substrate, Product, Productivity, Regime, Growth rate).
 

# Simulator
