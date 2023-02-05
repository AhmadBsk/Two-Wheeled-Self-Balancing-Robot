*author: AhmadReza Boskabadi* *date: 8 Feb 2015* *Email: [ahmadreza.boskabadi\@gmail.com](mailto:ahmadreza.boskabadi@gmail.com)*

# Controller for Two-Wheeled-Self-Balancing-Robot

Made a ......(LQR-PID-Fuzzy) Controller For Two-Wheeled Self-Balancing Robot

## - Different types of two-wheeled arrangement together

![image](https://user-images.githubusercontent.com/123794462/216826918-5d643155-89e8-4ad2-b239-bae303164e88.png)

### - The difference in movement on different surfaces with two wheels and four wheels

![image](https://user-images.githubusercontent.com/123794462/216826978-dacccbb3-76dd-4391-8b9f-159bd264e746.png)

### -The first successful example of an inverted pendulum [*Kazuo yamafuji*]{.ul}

![image](https://user-images.githubusercontent.com/123794462/216826952-3b9fda6f-896f-408d-bd69-b6a3fa022542.png)

## - The structure of the components of all the circuits used in the robot

![image](https://user-images.githubusercontent.com/123794462/216827006-0650cc33-8689-49d8-80b5-c981f2becfd2.png)

## - Physical equations governing the robot

![image](https://user-images.githubusercontent.com/123794462/216827021-84d61a8c-bd8a-441b-a805-1b51116f8345.png)

## - Estimation of inclination angle with accelerator

![image](https://user-images.githubusercontent.com/123794462/216827033-266583df-f861-4cfd-8a50-9588032c74ae.png)

![image](https://user-images.githubusercontent.com/123794462/216827050-72735895-b7a7-4f69-96d3-77367feabc6f.png)

![image](https://user-images.githubusercontent.com/123794462/216827057-0997b1af-8986-425d-a41a-7c8b6398fc05.png)

## -   Motor speed control using PWM *pulse amplitude control

![image](https://user-images.githubusercontent.com/123794462/216827113-57f14171-0289-4e29-9eea-7ca952039769.png)

## - Accelerometers are very sensitive and this makes every small vibration cause a value in its output, so you cannot know the angle of the robot just by relying on the read values. One of the ways to remove this noise and reach the correct values is to use the Kalman filter.

![image](https://user-images.githubusercontent.com/123794462/216827124-0b4ec9f5-1dd2-4089-9824-fa35bb3accc8.png)

## - Comparison of accelerometer output and Kalman output

![image](https://user-images.githubusercontent.com/123794462/216827136-889f3a89-12ec-468f-a8fe-f11acb0304ff.png)

## - Modeling and extraction of mathematical relationships governing robots

![image](https://user-images.githubusercontent.com/123794462/216827155-067093a0-a09c-429f-9d63-6c746d557c63.png)

![image](https://user-images.githubusercontent.com/123794462/216827176-171928cf-3cb9-49dc-82e4-2103bcbb1bf6.png)
![image](https://user-images.githubusercontent.com/123794462/216827194-536d9a8d-512c-47ce-9377-3529e165d1c1.png)

## - Non-linear robot model

![image](https://user-images.githubusercontent.com/123794462/216827201-15048d34-3b9c-4d28-b61a-3b30cdc1612b.png)

## - Calculation of system state equations

![image](https://user-images.githubusercontent.com/123794462/216827223-d298e85e-d53a-420e-b1fb-5a74f48c17ee.png)

## - Open loop step response

![image](https://user-images.githubusercontent.com/123794462/216827236-42e5d0e9-b64b-481b-b708-b679fb929fcd.png)

![image](https://user-images.githubusercontent.com/123794462/216827252-176af700-8451-4261-a41a-8fcd469c630a.png)

![image](https://user-images.githubusercontent.com/123794462/216827266-88763cd4-a2f7-48c3-9821-43f53ab03ac6.png)

![image](https://user-images.githubusercontent.com/123794462/216827272-c792af4d-35d4-44f9-9226-930a6165c157.png)


## - Linear Quadratic Regulator (LQR) feedback control

![image](https://user-images.githubusercontent.com/123794462/216827291-2c7b73d9-63e2-4b05-a671-1b774eb6bf5c.png)

![image](https://user-images.githubusercontent.com/123794462/216827300-46502402-d4f8-4046-add2-e2836eb5270f.png)

## - PID controller (proportional integral derivative controller)

![image](https://user-images.githubusercontent.com/123794462/216827313-627ba293-061c-492b-9eb4-91f1cc98e89f.png)

![image](https://user-images.githubusercontent.com/123794462/216827320-82e5b690-a7e3-46a1-bd23-c8d165cbfd71.png)

![image](https://user-images.githubusercontent.com/123794462/216827334-34421134-e778-4bab-9605-bfc14d2894f8.png)

## - Fuzzy Controler

![image](https://user-images.githubusercontent.com/123794462/216827343-c021130d-0a8a-47e4-85f5-ab461c12e548.png)

![image](https://user-images.githubusercontent.com/123794462/216827348-f2b787c2-1972-4f0a-a156-69613c19d48d.png)

![image](https://user-images.githubusercontent.com/123794462/216827365-b1598534-7fa9-4f7a-bdd2-c642bc130565.png
 
![image](https://user-images.githubusercontent.com/123794462/216827380-dbffbb66-f7f7-4e63-86e2-c7adfd984ed3.png)

![image](https://user-images.githubusercontent.com/123794462/216827386-4c4daf36-6347-406e-9766-2877ef93dc87.png)

![image](https://user-images.githubusercontent.com/123794462/216827392-5818f37a-23a0-4d02-9259-dc02d138993f.png)

![image](https://user-images.githubusercontent.com/123794462/216827411-4de58d89-916a-4867-a426-43eaae4dbe53.png)

![image](https://user-images.githubusercontent.com/123794462/216827423-a2e804f4-ea51-46b9-a50b-8f9ab3f7cd17.png)

## - Comparison of control output results by all methods

![image](https://user-images.githubusercontent.com/123794462/216827428-a027d5e8-d005-4350-8e70-53c5a5d513bf.png)

## - Changes in the distance between the center of gravity of the robot and the axis of the wheels (L)

![image](https://user-images.githubusercontent.com/123794462/216827440-53f2da14-8d2f-47dd-8740-4da71eab2251.png)

## - Wheel radius changes (R)

![image](https://user-images.githubusercontent.com/123794462/216827505-1c5c9221-b8be-4ba6-8aaf-cfe9539c45ac.png)

## - Conclusion

By comparing the results of the simulated model we can find, two PID and fuzzy controllers have the best functions in the field of controlling this robot. During the preparation of the practical model made of this robot, in addition to the above, we found that by observing the following two points, the level of stability can be increased:

\- The sensors are placed in a place parallel to the surface of the wheels and on its axis. This makes the sensor more sensitive to angle changes.

\- High torque motors make the robot more stable.

*author: AhmadReza Boskabadi* *date: 8 Feb 2015* *Email: [ahmadreza.boskabadi\@gmail.com](mailto:ahmadreza.boskabadi@gmail.com)*
