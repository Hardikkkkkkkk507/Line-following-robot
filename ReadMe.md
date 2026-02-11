**Project demonstrates a line following bot, with 2 stages of development:**

**1:** Basic Tire rotation and line following logic:



   \* Simple direction correction based on sensor readings.

   \* Less stable on curves, oscillates at high speeds.



**2:** Using PID logic to improve stability and reduce oscillations by appropriate tuning.

 

   \* Much more stable at higher speeds as oscillations are near invisible.

   \* Smoother motion.





**Technology used and skills developed:**



**\*Arduino**



**\*Embedded C**



**\*IR sensors**



**\*PID control algo -** Understanding the error calculation and appropriate correction per         		iteration of the loop to move from discrete-step corrections to continuous-		valued 	control signals.





**Note:** Integral accumulation introduced overshoot due to rapid error changes in a moving system. Since steady-state offset was negligible, PD control was sufficient, hence Ki is set as 0.

