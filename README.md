
# AIM: 
To simulate and synthesis  DFF  using vivado. 
# APPARATUS REQUIRED: 
vivado 2023.2 software. 
# PROCEDURE: 
STEP:1 Start the vivado software, Select and Name the New project. 
STEP:2 Select the device family, device, package and speed. 
STEP:3 Select new source in the New Project and select Verilog Module as the 
Source type. 
STEP:4 Type the File Name and module name and Click Next and then finish 
button. Type the code and save it. 
STEP:5 Select the run simulation and then run Behavioral Simulation in the 
Source Window and click the check syntax. 
STEP:6 Click the simulation to simulate the program and give the inputs and 
verify the outputs as per the truth table. 
STEP:7 compare the output with truth table. 
# D_FLIPFLOP
![image](https://github.com/RESMIRNAIR/D_FLIPFLOP/assets/154305926/4f3e1d9d-e0c3-464e-b0e4-e47946c813bd)
# Truth Table
![image](https://github.com/RESMIRNAIR/D_FLIPFLOP/assets/154305926/42d38f79-9cc3-4b09-a46f-e0c1241dee57)
# verilog code:
module dff(d,clk,rst,Q); 
input d,clk,rst; 
output reg Q; 
always @(posedge clk) 
begin 
if(rst==1) 
Q=1'b0; 
else 
Q=d; 
end 
endmodule 
# output
![Screenshot (57)](https://github.com/lathika024/D_FLIPFLOP/assets/165888553/bce44a58-b228-4bbe-9ded-0f011cec7d9e)
# result
Thus the DD flipflop is verified successfuly

