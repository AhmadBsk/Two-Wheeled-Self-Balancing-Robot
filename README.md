*author: AhmadReza Boskabadi*
*date: 8 Feb 2015*
*Email: [ahmadreza.boskabadi\@gmail.com](mailto:ahmadreza.boskabadi@gmail.com)*

# Controller for Two-Wheeled-Self-Balancing-Robot

Made a ......(LQR-PID-Fuzzy) Controller For Two-Wheeled Self-Balancing Robot

## - Different types of two-wheeled arrangement together

![](C:/Users/ACER/AppData/Local/RStudio/tmp/paste-0932A1AB.png)

### - The difference in movement on different surfaces with two wheels and four wheels

![](C:/Users/ACER/AppData/Local/RStudio/tmp/paste-7795C14B.png)

### -The first successful example of an inverted pendulum [*Kazuo yamafuji*]{.ul}

![](C:/Users/ACER/AppData/Local/RStudio/tmp/paste-B8D22AB4.png)

## - The structure of the components of all the circuits used in the robot

![](C:/Users/ACER/AppData/Local/RStudio/tmp/paste-7013D59A.png)

## - Physical equations governing the robot

![](C:/Users/ACER/AppData/Local/RStudio/tmp/paste-DF1E05F5.png)

## - Estimation of inclination angle with accelerator

![](C:/Users/ACER/AppData/Local/RStudio/tmp/paste-D092C13D.png)

![](C:/Users/ACER/AppData/Local/RStudio/tmp/paste-87B73E9F.png)

### ![](C:/Users/ACER/AppData/Local/RStudio/tmp/paste-B4BDF90A.png)
- Motor speed control using PWM *pulse amplitude control*
![](C:/Users/ACER/AppData/Local/RStudio/tmp/paste-00F82556.png)

## - Accelerometers are very sensitive and this makes every small vibration cause a value in its output, so you cannot know the angle of the robot just by relying on the read values. One of the ways to remove this noise and reach the correct values is to use the Kalman filter.

![](C:/Users/ACER/AppData/Local/RStudio/tmp/paste-5849331E.png)

## - Comparison of accelerometer output and Kalman output

![](C:/Users/ACER/AppData/Local/RStudio/tmp/paste-1630E2FF.png)

## - Modeling and extraction of mathematical relationships governing robots

![](C:/Users/ACER/AppData/Local/RStudio/tmp/paste-0DAD015B.png)

![![](C:/Users/ACER/AppData/Local/RStudio/tmp/paste-580E2172.png)](C:/Users/ACER/AppData/Local/RStudio/tmp/paste-12A72C7F.png)

## - Non-linear robot model

![](C:/Users/ACER/AppData/Local/RStudio/tmp/paste-9C115EFA.png)

## - Calculation of system state equations

![](C:/Users/ACER/AppData/Local/RStudio/tmp/paste-05F56281.png)

## - Open loop step response

![](C:/Users/ACER/AppData/Local/RStudio/tmp/paste-66AFF48F.png)

![![](C:/Users/ACER/AppData/Local/RStudio/tmp/paste-61528912.png)](C:/Users/ACER/AppData/Local/RStudio/tmp/paste-003BDD79.png)

![](C:/Users/ACER/AppData/Local/RStudio/tmp/paste-6617F0C1.png)

## - Linear Quadratic Regulator (LQR) feedback control

![](C:/Users/ACER/AppData/Local/RStudio/tmp/paste-491D9307.png)

![](C:/Users/ACER/AppData/Local/RStudio/tmp/paste-19CE8843.png)

## - PID controller (proportional integral derivative controller)

![](C:/Users/ACER/AppData/Local/RStudio/tmp/paste-C8F69E7E.png)

![](C:/Users/ACER/AppData/Local/RStudio/tmp/paste-5001A786.png)

![](C:/Users/ACER/AppData/Local/RStudio/tmp/paste-7DBF7B0D.png)

## - Fuzzy Controler

## ![](C:/Users/ACER/AppData/Local/RStudio/tmp/paste-3EAEE4D5.png)

## ![](C:/Users/ACER/AppData/Local/RStudio/tmp/paste-7884C35C.png)

## ![](C:/Users/ACER/AppData/Local/RStudio/tmp/paste-A13D30F6.png)

## ![](C:/Users/ACER/AppData/Local/RStudio/tmp/paste-05EE3370.png)

## ![](C:/Users/ACER/AppData/Local/RStudio/tmp/paste-7BB27F9F.png)

## ![](C:/Users/ACER/AppData/Local/RStudio/tmp/paste-FC128DAC.png)

## ![](C:/Users/ACER/AppData/Local/RStudio/tmp/paste-000526BC.png)
![](C:/Users/ACER/AppData/Local/RStudio/tmp/paste-EFDB8619.png)

## - Comparison of control output results by all methods

## ![](C:/Users/ACER/AppData/Local/RStudio/tmp/paste-2EB54FD1.png)

## - Changes in the distance between the center of gravity of the robot and the axis of the wheels (L)

## ![](C:/Users/ACER/AppData/Local/RStudio/tmp/paste-14B7FDFC.png)

## - Wheel radius changes (R)

## ![](C:/Users/ACER/AppData/Local/RStudio/tmp/paste-BAD89128.png)

## - Conclusion

By comparing the results of the simulated model we can find, two PID and fuzzy controllers have the best functions in the field of controlling this robot. During the preparation of the practical model made of this robot, in addition to the above, we found that by observing the following two points, the level of stability can be increased:

\- The sensors are placed in a place parallel to the surface of the wheels and on its axis. This makes the sensor more sensitive to angle changes.

\- High torque motors make the robot more stable.

*author: AhmadReza Boskabadi*
*date: 8 Feb 2015*
*Email: [ahmadreza.boskabadi\@gmail.com](mailto:ahmadreza.boskabadi@gmail.com)*
