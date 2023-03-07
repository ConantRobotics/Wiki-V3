# Drive System 

A robot combat drive system is the mechanism that allows a robot to move and control its position and orientation during a combat. There are various types of drive systems that can be used for robot combat, each with its own advantages and disadvantages. Here are some of the most common types of drive systems used in robot combat and how they work:

- Differential Drive: Differential drive is the most common type of drive system used in robot combat. It uses two independently controlled wheels or tracks on each side of the robot, with each wheel or track powered by a separate motor. By varying the speed and direction of each motor, the robot can turn, move forward or backward, and spin in place. Differential drive provides good maneuverability and control, but can be vulnerable to tipping over if the weight distribution is not well-balanced.

Insert image of Janktality internals here

Janktality used a differential drive system due to its simplicity and manueverability, enabling it to run circles around its opponents in the final competition.

- Differential Drive with Casters: This is the same basic concept as a differential drive, but it utilizes two additional wheels in the front of the robot to reduce scraping on the arena floor. By using these additional wheels, the robot is able to better traverse uneven terrain (such as a torn-up arena floor) and often has improved control. However, it's extremely difficult to create a wedge using this drive system, as a wedge needs to scrape the floor in order to be effective. As such, this method is often used on very long or wide robots that "sag" in the center, using the two caster wheels to lift the center back up.

![spatula being flipped by janktality, exposing its underside](../img/mechanics/diffdrivecasters.png) 

Spatula, a hydraulic flipper, used two ball casters under its wedge to prevent the wedge from scraping the ground and reducing manueverability. There's only one in the picture as we knocked off the other one.

- Tank Treads: Tank treads are a type of drive system that use continuous tracks on each side of the robot, similar to those used on tanks. They provide good traction and stability, making them ideal for robots that need to traverse rough terrain or obstacles. However, they are typically slower and less maneuverable than other types of drive systems, resulting in them being rarely used in the Robot Rumble.

Insert image of some tracked robot here

- Omni-Directional Drive: Omni-directional drive systems use three or more wheels or rollers arranged in a specific pattern to provide the robot with the ability to move in any direction, rotate around its own axis, and move sideways. These systems provide excellent maneuverability and speed, but can be more complex and expensive to build. They are rarely used in the Robot Rumble due to their high weight and lack of power delivery when ramming other robots.

Insert image of some full-body spinner here (NOT A MELTY BRAIN)

- Four-Wheel Drive: Four-wheel drive systems use four independently controlled wheels to provide the robot with greater stability and traction than a two-wheel drive system. By controlling the speed and direction of each wheel, the robot can turn, move forward or backward, and spin in place. Four-wheel drive systems are typically more stable and maneuverable than two-wheel drive systems, but due to their weight are not used within the Robot Rumble.

Insert image of some four-wheeled robot here 

- Hybrid Drive: Hybrid drive systems combine two or more types of drive systems, such as differential drive and tank treads or omni-directional drive and four-wheel drive. These systems offer the benefits of each type of drive system, but can be more complex and difficult to control. The most common usage of these drives is in the creation of custom geartrains, as some robots will use tracks as a method of gear reduction.

Insert image of a wide polycarbonate robot from Hersey in RR2023 as they were using a system similar to this

In addition to the type of drive system used, the motors and controllers used to power and control the robot's movement are also important. High-quality, durable motors and controllers are essential for providing the robot with the power and precision it needs to navigate the battlefield and outmaneuver its opponents. The drive system and motors should be designed to work in harmony with the robot's other systems, such as its weapon and control systems, to provide an effective and efficient combat robot.

# Differential Drive Limitations

Due to it's frequent usage within battlebot competitions, it's important to address the limitations and the functionality of a differential drive in greater detail.

A differential drive is a type of drive system commonly used in robots for its simplicity and maneuverability. This system consists of two independently controlled wheels or tracks, one on each side of the robot. Each wheel is powered by its own motor, which allows the robot to move forward and backward and turn in place by varying the speed and direction of each motor.

The differential drive system works by using the difference in speed between the two wheels to turn the robot. For example, if the robot wants to turn to the left, the motor on the right side of the robot will slow down while the motor on the left side will speed up. This causes the robot to turn to the left as the wheels on the left side move faster than the wheels on the right side.

The differential drive system is easy to implement and provides good control and maneuverability in a variety of environments. It is also relatively efficient and has a low power consumption compared to other drive systems.

However, the differential drive system has some limitations. One major issue is that it can be prone to tipping over if the weight distribution of the robot is not well-balanced. This is because the robot relies on its wheels for stability, and if the weight is not distributed evenly, the robot may tip over when turning or accelerating.

Additionally, a robot with too much weight on one side will have greater traction on that side. This results in the heavy side speeding up much faster than the other side, making the robot much harder to manuever as the robot will overshoot or undershoot turns unpredictably.

Insert image of Janktality with batteries located on both sides of the weapon.

This 

Insert image of Janktality with batteries located on one side of the weapon.

Another limitation of differential drive systems is that they can struggle on uneven or rough terrain. This is because the wheels may lose traction or become stuck on obstacles, making it difficult for the robot to move or turn. This is often resolved by placing casters on the bottom of the robot that can roll over any terrain differences, but it can be compensated for with a skilled driver.

Overall, the differential drive system is a versatile and efficient drive system that is well-suited for many types of robot combat. However, designers must be aware of its limitations and work to ensure the robot's weight distribution and wheel design are optimized for maximum stability and control.

---
This article authored by Anmay Gupta and ChatGPT in March 2023.
