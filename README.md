# 4-bit-Unsigned-Array-Multipiler
Array multiplication process for two 4-bit unsigned numbers a and b is shown below.

![image](https://user-images.githubusercontent.com/97019009/148881908-c5b6bdef-8d44-47a5-87e2-78384f5e6854.png)

On the contrary to the sequential multiplier, array multiplier is parallel. A array of full adders are used for the multiplication process. For n-bit data width, total n(n-1) full adders are used in this multiplier. Carry outputs of a stage is added in the next stage to form a systolic architecture. But in the last stage carry is used in the same stage to reduce hardware. The architecture of the array multiplier is shown below.

![image](https://user-images.githubusercontent.com/97019009/148881957-13d4ff91-70f8-43e9-bec5-ab8b0f130f98.png)

Based on these fundamental Knowledge, I create that multiplier in Quartus II and there is its RTL Viewer:

![image](https://user-images.githubusercontent.com/97019009/148882129-c82e8f92-69d7-4b3c-868f-e72916f1fe1c.png)

Then i try simulate this file on ModelSim with 2 input 5 and 7 and there is the result:

![image](https://user-images.githubusercontent.com/97019009/148882592-6a037d3a-45f9-480f-8acc-d71058ad0d87.png)
