# PCLU
Hey, if you're reading this, then you're interested in our robot, enjoy reading and hope you like our work.

Team name: Siribtech

Robot name: Ginadman

Teammates: John Viray, John Kenneth Orellano. Naithan Velasco

Match name: Self Driving car

- [1.0 Introduction](#10-introduction)
  - [1.1 About us!](#11-about-us)
  - [1.2 Team Management](#12-team-management)
  - [1.3 Reason to participate](#13-reason-to-participate)
- [2.0 About the car](#20-about-the-car)
  - [2.1 Our autonomous cars logic](#21-our-autonomous-cars-logic)
  - [2.2 Flow diagram](#22-flow-diagram)
  - [2.3 Why Ev3?](#23-why-ev3)
- [3.0 Mobility Management](#30-mobility-management)
  - [3.1 Bill or Materials](#31-bill-of-materials)
  - [3.2 Wiring diagram](#32-wiring-diagram)
  - [3.3 Why we use medium and large motor?](#33-why-we-use-medium-and-large-motor)
  - [3.4 Motors axle system](#34-motors-axle-system)
  - [3.5 Rack and pinion system](#35-rack-and-pinion-system)
       - [3.5.1 How does the system works?](#351-how-does-the-system-works)
- [4.0 Power management](#40-power-management)
  - [4.1 Power source](#41-power-source)
  - [4.2 Why we use sensors and camera?](#42-why-we-use-sensors-and-camera)
- [5.0 Building the robot](#50-building-the-robot)
  - [5.1 The base](#51-the-base)
  - [5.2 Adding the components](#52-adding-the-components)
  - [5.3 Wiring](#53-wiring)
- [6.0 Strategy](#60-strategy)
  - [6.1 Walls](#61-walls)
  - [6.2 Lines](#62-lines)
  - [6.3 Obstacles](#63-obstacles)
  - [6.4 Open challenge](#64-open-challenge)
- [7.0 Parking strategy](#70-parking-strategy)
  - [7.1 Video Open Challenge](#71-video-open-challenge)
# 1.0 Introduction 
-----------------------

## 1.1 About us!

| Name | Age | Role | Facts |
| :---: | :---: | :---: | :--- |
| John Viray | 16 | Programmer/Technical Analysis | I enjoy driving, surfing, and boxing. A lot of my inspiration comes from those cool machines like F1 cars and fighter jets. Single.|
| John Kenneth Orellano | 16 | Robot engineer/Research developer | I like gaming, playing chess, and watching movies/anime until morning and sketching when i'm bored but most of the time im just watching movies or anime |
| Naithan Velasco | 16 | Programmer/robot engineer | I like playing badminton, playing mobile games and watching anime |


## 1.2 Team Management

This project is the result of the hardwork of our team and a showcase of our spirit and drive to succeed in the competition and create a feat of robotics that we can be proud of that is worthy of a showcase at the largest robotics event in the Phillipines. Each of our members worked hand in hand to be able to represent La Union and we have learned more than we could've imagined by working on this project.


Team Supervisor: John Viray

Coaches: Bong John Abraham Agno/Michael James Estipular Ergino 


## 1.3 Reason to participate

We participate in this competition in order to showcase our skills and talents in order to succeed and cooperate as a great team. We must utilize our skills and cooperation in order to represent Region 1 and be able to make our people proud and give them something to be proud about. We enjoy the challenge of being able to go against the biggest schools in the Phillipines and creating robots that could one day make a difference. Most of all, we aim to win, but we also aim to have fun while doing so and enjoy what we do despite the hard comning and all the negativities that come along our way on our path to victory.

# 2.0 About the car
-----------------------

## 2.1 Our autonomous cars logic

1. The robot begins its by engaging its driving motors, allowing it to move forward.

2. It then turns after a bit of time decided by a wait function.

3. As a person would, it adjusts when it feels it's about to hit something, made possible by the multiple ultrasound sensors.

4. After 3 laps, it automatically stops. 

5. It can differentiate colors through a mix of color sensors and a camera.

6. The camera works as eyes and allows it to see better colors.

7. If theres too much of a certain color and the distance is too close, it'll read the color and turn accordingly.



## 2.2 Flow diagram
<div align="center"><img width=80% src="schemes/Flow Diagram.jpeg"></img></div>

## 2.3 Why Ev3?

Ev3 ultimately proved to be a much more reliable and faster option for us as its motor were much less jittery and much more durable. Additionally, the parts for Ev3 were much more accessible and allowed us to utilize it to a much higher potential than we ever could have with Aisteam, we work with what we have and we believe that we have enough to win the competition.

# 3.0 Mobility Management
------------------------------------


## 3.1 Bill of Materials
__________________________________________________________

| Component | Quantity | Function |
| :--- | :---: | :--- |
|Ev3 Large Motor |1 |Serves as the main driving motor for the robot, creates a lot of torque|
|Ev3 Medium Motor |1 |serves as our motor for turning and very fast|
|Ev3 Hub |1 |The brain of our robot the one that controls the motor and sensors |
|Ev3 Battery |1 |A rechargeable Battery with a capacity of 2050mAh lithium-ion battery |
|Ev3 Infrared Sensor |2 |This sensors dictate the robots main logic and allow it to avoid the walls and cetrain objects within its radius around it |
|Camera|1 | Camera is use to detect the obstacles and serves as the robots eyes |

## 3.2 Wiring diagram
<div align="center"><img width=80% src="schemes/wiring diagram.png"></img></div>

## 3.3 Why we use medium and large motor?

We used a combination of large motors and medium motors as it allowed us to utilize the best of both worlds. We can utilize the torque and stability of the large motor to push the robot through thick and thin. The large motor allows the vehicle to move faster and gives the speed needed for stability and for manuever. The medium motor allows the front wheel drive to snap left and right allowing the robot to quickly respond to obstacles or anything in its path. 


## 3.4 Motors axle system

The large motor are connected to an axle in the rear, which allow the car to run faster and the medium motor is connected to the steering system in front. This allows our wheels to support the weight of the robot. This axle is important for the car to move forward and backwards and ensuring a smooth turn in curves. It improves the stability of our vehicle, which is important for tight corners.

## 3.5 Rack and pinion system 

Our self driving car uses an Rack and pinion steering system which provides precise and stable controls for moving and turning. This system is use so our vehicle can turn on the corners smoothly with this kind of system its makes our work a lot easier when turning. 


### 3.5.1 How does the system works?

The rack and pinion steering system converts the rotational motion of your steering wheel into the linear motion needed to turn the car's wheel. This system is used to reduce the tires in slipping and prevents oversteer and understeer. Pressure must be constantly applied for the steering gear to be in contact with pinion bar. 

# 4.0 Power management

## 4.1 Power source
The battery powering the self driving car is a Rechargeable DC (Li-ion) type with a capacity of 2050 mAH and a nominal voltage of 7.4v.
This battery primarily use to power the Ev3 brick which is the brain of our robot and it provides a reliable and rechargeable power source, allowing our robot to run for an extended period of time without needing of constantly replacing batteries.


## 4.2 Why we use sensors and camera?

The camera can differentiate colors by utilizing the color detection built in. The color differentiation allows us to avoid the green and red accordingly to the regulations. Our ultrasonic sensors are utilized in order to detect near by obstacles and walls in order to avoid or adjust accordingly depending on the object, it's distance, and it's direction.

# 5.0 Building the robot

## 5.1 The base

The base was created to be compact enough to fit regulations but light enough to be quick enough to run laps in a quick and efficient manner, through revisions and the such we ultimately found our base to be effective at the job at hand, modifications were made so it could hold all our components. This base was made so it can support the weight of the hub, sensors and other needs for our vehicle but light enough so it can still move fast.

## 5.2 Adding the components

The components are all connected by pegs, no adhesives were used when connecting the components to the robot. While most components simply click into place and just sit there, a few components require to be locked in such as the pinion in the steering system. 

## 5.3 Wiring

The wiring is organized in order to not inhibit the robot or it's movements, most of the wires simply slip under the robot into its respective port and once connected is left there. Markings indicate where the wires are needed to plug.

# 6.0 Strategy


## 6.1 Walls

Just like in real life, it is preferred not to crash into a wall while driving at high speeds. Our robot uses the same logic by turning to the right when it detects a wall or the corner line, additionally we would prefer not to scrape the paint off of the walls so a sensor will detect walls to the sides of the robot, once a limitation is reached and the gap between the robot and a wall becomes too close, it will simply adjust and straighten.

## 6.2 Lines

How do you know when to turn when you're driving? Thankfully we have the lines, these lines dictate when our robot needs to turn. To detect the lines we use color sensor. This sensor detects the color blue and orange. Because of the color sensor we can detect the lines to indicate where to turn clockwise or counterclockwise, left or right. The blue color indicates counterclockwise and the orange indicates clockwise rotation. 

## 6.3 Obstacles

In the obstacle challenge we use camera, this camera detects the obstacles like green and red. Once the camera detects the color green it needs to turn left and right for the color red. This camera helps us to know the distance between our robot and the obstacle. So it can adjust itself for the remaining time before it hit the obstacles. 

## 6.4 Open challenge 

For the open challenge we use ultrasonic and color sensors, the ultrasonic sensors detects the inner and outer walls. Once the vehicle is near the walls the sensors detects it and adjust itself a bit further the walls. The ultrasonic sensors help the car not to bump on the inner and outer walls. The color sensor detects the color blue and orange once it detects a color it will turn clockwise or counterclockwise.

# 7.0 Parking strategy 

After completing the Three laps. Our robot begins the detection of the parking boundaries, the vehicle assess the available space and align it self with the detected area. If the robot commited the exact angle prior on the given parking space, the vehicle executes a parallel parking maneuver. The vehicle adjust its orientation to locate the exact parking area. Repeating this process until successful parking Achieved. 

# 7.1 Video Open Challenge
 
https://youtu.be/yuSwamgULuo?si=QfCYIgs6R4ly2_1n
