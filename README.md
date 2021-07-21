# Task-two

#  Controling Dc Motor
 In this task, we aim to build a circuit control for two dc motors. First, using five components: Arduino Uno, H-bridge(Motor driver), 2 Dc motor, 9V Battery.Moreover,  the circuit has differents components that provide essential ability. However,  we will give brief information for the dc motor and the motor driver that controls the direction of the rotation and the speed for dc motors. On the other hand, the dc motor is one of the most common components in the robotic and industrial field, because it's transferring electrical energy to mechanical energy. Furthermore, we use the Arduino to program the direction of the dc motors and provide 5V addition to the battery.

# Build the Circuit
First, we use the breadboard to connecting our components, the motor driver in the middle of the circuit, and we have 16 pins each pin have their use we will connecting pin3,6(output1,2) to the number 1 dc motor, also pin11,13(output3,4) to the number 2 dc motor. Pins1,9 to the PWM pins in the Arduino within the pins1,7,10,15(inputs pins) to control the direction of the dc motors. Pin 8 (Vs) to the 5V pin on the Arduino, pin 16(Vss) to the positive side of the battery, the remaining pins(gnd) goes to Arduino and the battery gnd pin. Finally, the remains are programming the Arduino.     
the Comparison of the four types


# Choosing the suitable Bttary 

This task is about choosing the battery depending on cost, efficiency, and the formula for calculating the total battery supply.  We need to calculate the consumption current for our components, Arduino:  uno: 50mA, H-bridge(Motor driver):600mA, 2 Dc motor:600mA, total current = 600+600+50=1250mA, assuming the time is 4hours, the total supply battary= 4h * 1250mA = 5000mAh, and 12V due to the highest components(Dc motor). Second, the Comparison was between four types of batteries: lead-acid, Ni-MH Li-ion, Li-po and depending on the resources we read and watch the highest battery cost is the Li-po, on the other hand, it provides high efficiency within high voltage and lightweight that makes the robot doesn't need to carry heavyweight like the lead-acid battery. Moreover, if we decide to use the Li-ion will need more than three batteries to operate the project that eventually makes the cost higher and the Ni-MH battery can't work for many of us and feed the circuit with the voltage we need.
Finally, due to our lack of knowledge in designing charge circuits, we copy the design from the website that will be missioned in the resources below.

# Resources
https://www.youtube.com/watch?v=OxrdpDPpD9Y
https://www.youtube.com/watch?v=9kfXC9i9pgA&t=226s
https://www.engineersgarage.com/choosing-battery-for-robots/
https://www.circuitstoday.com/lipo-battery-charger-circuit
https://www.circuitstoday.com/lipo-battery-charger-circuit


# The Robot Eyes
In this task, we need to design the eye circuit with three devices: Arduino uno, Transistor, two LEDs, three resistors. Furthermore, we have to determine connecting the led parallel or series with reason: the led consumed 20 mA we need to make each led to take the same amount of current than the best way to ensure that they will take the same current by connecting them in series. In addition,  we need a breadboard to contain the elements. Next, we'll set the transistor on the board and the Base we will connect a 220omh resistor connected to the digital pins, after that the LEDs will be connected to the Collector in series as we mentioned and with each led we will connect 220 resistors to minimize the risk of damaging the eyes (LEDs). Finally, the Emitter will connect to the ground and,  we will supply our circuit with 5V from the Arduino board.   
