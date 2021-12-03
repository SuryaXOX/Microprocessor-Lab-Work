# Microprocessor-Lab-Work
In this Lab, I completed the assembly of my custom printed circuit board. Here at Github, I've uploaded the software used to run a kitchen timer that will control the behavior of my embedded system. All coding was done in Embedded C and in Code Composer Studio.
These are the various segments used to buld the code.

->Hardware Timers
The project makes use of two (2) TIMER32 peripherals on the MSP432.  One timer will generate an interrupt every 1 second.  The second timer will generate an interrupt every 2mS.

->Magnetic Buzzer
The PWM peripheral connected to the buzzer shall be configured to run at 4Khz and a 50% duty cycle. 

->I2C Driver

![image](https://user-images.githubusercontent.com/71836374/144602667-9f49746e-75c4-467f-b3ca-3825f10dd7b5.png)

The seven segment displays on the custom board are controlled by 11 IO pins. The AT42QT2120 is used to detect when the user presses the capacitive touch buttons (electrodes) on the custom board.

This diagram below explains how the board works

![image](https://user-images.githubusercontent.com/71836374/144602920-044fcd74-4886-4af8-94bd-c0e884a4561d.png)
![image](https://user-images.githubusercontent.com/71836374/144602971-c733bdd8-2094-47b8-ab53-4dcd83032292.png)
