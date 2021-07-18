# Task-two

#  Controling Dc Motor
In this subtask our main goal is controling dc motor,using five components: Arduino uno, H-bridge(Motor driver), 2 Dc motor, 9V Battary.
Moreover, each components provide importent tool, starting with the new components the dc motor and the motor driver that control the dirction of the roution and the speed for dc motors. On the other hand, dc motor is one of the  most common components on the robotic field and in the industrial field in genrel because it's transfering the electrical energy to michenical energy. Furthermore, we use the arduino to program the dirction of the dc motors and provide 5V addtion to the battary.

# Build the Circuit
first we use the breadbord to conecting our coponents, the motor driver in the middle of the circuit and we have 16 pins each pin have their use we will conecting pin3,6(output1,2) to the number 1 dc motor, also pin11,13(output3,4) to the number 2 dc motor. Pins1,9 to the PWM pins in the arduino within the pins1,7,10,15(inputs pins) to control the dirction of the motors.Pin 8 (Vs) to the 5V pin on the arduino, pin 16(Vss) to postive side of the battary, the remain pins(gnd) goes to arduino and the battary gnd pin. Finally the remains is programing the arduino.     
the Comparison of the four types


# Choosing the suitable Bttary 

This task is about choosing the battary depending on cost, efficiency, and the forumla for calulating the total battary supply . we need to caluclate the consmption current for our components, Arduino:  uno: 50mA, H-bridge(Motor driver):600mA, 2 Dc motor:600mA, total current = 600+600+50=1250mA, assumeing the time is 4hours, the total supply battary= 4h * 1250mA = 5000mAh, and 12V due to the highest components(Dc motor). Second, the Comparison was between four types of battaries: lead acid, Ni-mh Li-ion, , buand Li-po depending on the resourses i read and watch the highst battery cost is the Li-po, but it's provide high efficiency within high voltage and light weight which make the robot don't need to carry heavy weight from the lead acid. moreover the problem of the Li-ion if we want to use it we will need more than three battary to operate the project that eventually make the cost higher, finally Ni-MH can't work for many ours and feed the circuit with the voltage we need.

# Resources
https://www.youtube.com/watch?v=OxrdpDPpD9Y
https://www.youtube.com/watch?v=9kfXC9i9pgA&t=226s
https://www.engineersgarage.com/choosing-battery-for-robots/
  
