# AIM:
To simulate and synthesis encoder using vivado.

# APPARATUS REQUIRED:
vivado 2023.2 software.

# PROCEDURE:
```
STEP:1 Start the vivado software, Select and Name the New project.
STEP:2 Select the device family, device, package and speed.
STEP:3 Select new source in the New Project and select Verilog Module as the Source type.
STEP:4 Type the File Name and module name and Click Next and then finish button. Type the code and save it.
STEP:5 Select the run simulation and then run Behavioral Simulation in the Source Window and click the check syntax.
STEP:6 Click the simulation to simulate the program and give the inputs and verify the outputs as per the truth table.
STEP:7 compare the output with truth table.
```
# ENCODER8TO3
![image](https://github.com/RESMIRNAIR/ENCODER3TO8/assets/154305926/824226c8-c767-44b5-ab35-26fed65b195e)
# Truth Table
![image](https://github.com/RESMIRNAIR/ENCODER3TO8/assets/154305926/e228c14b-b814-40c8-92eb-748d48570c04)
# Circuit Diagram
![image](https://github.com/RESMIRNAIR/ENCODER3TO8/assets/154305926/6fa5fe84-fe6f-472d-b9c0-e6dfa17413d3)
![image](https://github.com/RESMIRNAIR/ENCODER3TO8/assets/154305926/7d147e2a-ba03-4714-baee-17615c9c50c1)
# VERILOG CODE:
# ENCODER2TO4:
```
module encoder(d,a,b,c);
input [7:0]d;
output a,b,c;
or (a.d[4],[5],[6]d[7]);
or (b.d[2],[3]d[6],d[7]);
or (c.d[1],[3],[5].d[7]);
endrodule
```
# Output
![encoder](https://github.com/THARUN729/ENCODER8TO3/assets/161407766/2a15c82a-5977-4016-8a8f-8a309e9b4482)

# RESULT:
Thus the verilog program for encoder has been simulated and verified successfully.

