# BOOLEAN_FUNCTION_MINIMIZATION

**AIM:**

To implement the given logic function verify its operation in Quartus using Verilog programming.

F1= A’B’C’D’+AC’D’+B’CD’+A’BCD+BC’D 

F2=xy’z+x’y’z+w’xy+wx’y+wxy

**Equipment Required:**

Hardware – PCs, Cyclone II , USB flasher

**Software – Quartus prime**

**Theory**

**Logic Diagram**   

**Procedure**

1.	Type the program in Quartus software.

2.	Compile and run the program.

3.	Generate the RTL schematic and save the logic diagram.

4.	Create nodes for inputs and outputs to generate the timing diagram.

5.	For different input combinations generate the timing diagram.


**Program:**
```
module experiment2(a,b,c,d,f1,w,x,y,z,f2);
input a,b,c,d,w,x,y,z;
output f1,f2;
assign f1=((~b&~c)|(~a&b&d)|(a&b&~c));
assign f2=((~y&z)|(x&y)|(w&y));
endmodule
```
/* Program to implement the given logic function and to verify its operations in quartus using Verilog programming. 

Developed by: KARTHIKEYAN C RegisterNumber:24900091*/
**TRUTH TABLE**
![392007889-b2e6f509-64de-444c-a5fa-e40898d2b160](https://github.com/user-attachments/assets/6247d250-dfe5-4617-87f6-6c3af00c8556)
![392007968-0ff0cc8d-a388-4297-ac03-7771303160b7](https://github.com/user-attachments/assets/25b969c5-272e-4adb-9366-6235a56d97f8)

**RTL realization** 
![Screenshot 2024-12-06 203438](https://github.com/user-attachments/assets/d719e96b-5c6c-4995-9efb-e5a6eb3523d7)

**OUTPUT**   
**RTL**   

![387574673-4bfc069b-5f93-4d1a-b89d-8529cbe889b7](https://github.com/user-attachments/assets/45ba91f7-21e9-4afb-9b1b-f36db4d88d72)

**Result:**  The Basic Logic gates are studied and truth table are verified.

Thus the given logic functions are implemented using and their operations are verified using Verilog programming.

