# FreeRTOS-on-STM32

Implemented this repository to improve practical skills related to CMSIS_OSv2-based application development using FreeRTOS in STM32. 

### Configuring FreeRTOS in Middlewares
![image](https://github.com/user-attachments/assets/61898673-982a-40f5-bda6-84e98c52671d)

### Here we have to place a timer instead of using the Systick timer because the FreeRTOS requires the Systick timer
![image](https://github.com/user-attachments/assets/8e337d2f-da14-4bf5-b5fd-687b0327b7b4)

### The two blink tasks were created with different priorities
![image](https://github.com/user-attachments/assets/766a690d-f742-4bbd-8099-b4bd8ebfbac7)
![image](https://github.com/user-attachments/assets/41cc1759-22cd-4115-8eba-2e0bc54cf8a7)

### The start functions were edited to toggle the same inbuilt LED but with different delays. I used osDelay() because it does not halt other operations while waiting.

![image](https://github.com/user-attachments/assets/bc130d45-bfae-4fdf-a48f-c609fcca40d3)

### In the below demo you can see that the 2 tasks overlap periodically. But as we know the higher priority task which is blink01 will be executed in that scenario.

https://github.com/user-attachments/assets/3349a8e7-16a1-4c91-bdca-e69e2d901073





