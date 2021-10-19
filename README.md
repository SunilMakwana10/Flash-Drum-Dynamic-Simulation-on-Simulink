# Flash-Drum-Dynamic-Simulation-on-Simulink
Developed a dynamic simulation model for a flash drum system with PID controller using model equations on Simulink

Model equations for the system:

Equation 1: 
![image](https://user-images.githubusercontent.com/87444991/137980327-978511c2-c40c-496c-ac2f-f2090177f74d.png)


Equation 2:
![image](https://user-images.githubusercontent.com/87444991/137980407-32845082-3371-4fad-af86-a657689126ee.png)


The transfer function for first equation will be:
![image](https://user-images.githubusercontent.com/87444991/137980464-8355d737-75b9-496c-8055-9e1e902db1fc.png)


Where τ = A * R, Let τ = 10
For F(s) = 20


Following are the results on Simulink:

![image](https://user-images.githubusercontent.com/87444991/137980491-f1b8a4c7-9f98-47ee-aa20-42313ce6071b.png)



PID Block:

![image](https://user-images.githubusercontent.com/87444991/137980572-69482c21-234a-4669-b60c-92ace5ffa801.png)


Scope:

![image](https://user-images.githubusercontent.com/87444991/137980602-c694d4d3-648a-467a-b31f-0c8cd0454286.png)

For Second equation:

The transfer function is:

![image](https://user-images.githubusercontent.com/87444991/137980651-2aae48a2-761c-43b8-b1bb-311bd30f2115.png)


Here, K = 1/(Cp*F) and τ= (Height*Density*Area)/F

Simulation is as follows:

![image](https://user-images.githubusercontent.com/87444991/137980720-7407f149-67cc-4535-8ff5-59e781514c8e.png)

Step Input (10) before PID

![image](https://user-images.githubusercontent.com/87444991/137980759-1e36fdbd-fd0f-4d7f-81d1-1cccc93f9ef0.png)

Response after PID

![image](https://user-images.githubusercontent.com/87444991/137980807-067c0cbf-02e6-49bf-baab-2cf731b128ed.png)

Scope:

![image](https://user-images.githubusercontent.com/87444991/137980858-cb6ee9c6-ba22-4b53-acdd-91bc5020dfac.png)

