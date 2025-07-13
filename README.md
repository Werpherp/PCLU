# PCLU
Hey, if you're reading this, then you're interested in our robot, enjoy reading and hope you like our work 

Team name: Siribtech

Robot name: Ginadman

Teammates: John Viray, John Kenneth Orellano. Naithan Velasco

Match name: Self Driving car

1.0 Introduction 
-----------------------

1.1 About us!

John Viray

16

Programmer/ Technical analysis

I enjoy driving, surfing, and boxing. A lot of my inspiration comes from those cool machines like F1 cars and fighter jets. Single.

--------------------------------------------------------------------------------------------------------------------------------------------------------------------
John Kenneth Orellano

16

Robot engineer / Research developer

I like gaming, playing chess, and watching movies/anime until morning and sketching if I'm bored but most of the time, I'm watching movies and anime

---------------------------------------------------------------------------------------------------------------------------------------------------------------------
Naithan Velasco

16

Programming / Engineer

I like playing, playing mobile games and watching anime.

----------------------------------------------------------------------------------------------------------------------------------------------------------------------

1.2 Team Management

This project is the result of the hardwork of our team and a showcase of our spirit and drive to succeed in the competition and create a feat of robotics that we can be proud of that is worthy of a showcase at the largest robotics event in the phillipines. Each of our members worked hand in hand to be able to represent La union and we have learned more than we could've imagined by working on this project.


Team Supervisor: John Viray

Coaches: Bong John Abraham Agno/James


1.3 Reason to participate

We participate in this competition in order to showcase our skills and talents in order to succeed and cooperate as a great team. We must utilize our skills and cooperation in order to represent our province of La Union and be able to make our people proud and give them something to be proud about. We enjoy the challenge of being able to go against the biggest schools in the phillipines and creating robots that could one day make a difference.Most of all, we aim to win, but we also aim to have fun while doing so and enjoy what we do despite the hardcomning and all the negativities that come along our way on our path to victory

2.0 About the car
-----------------------

2.1 Our autonomous cars logic

1. The robot begins its by engaging its driving motors, allowing it to move forward

2. It then turns after a bit of time decided by a wait function

3. As a person would, it adjusts when it feels it's about to hit something, made possible by the multiple ultrasound sensors.

4. After 3 laps, it dies

5. it can differentiate colors through a mix of color sensors and a camera

6. The camera works as eyes and allows it to see better colors

7. if theres too much of a certain color and the distance is too close, it'll read the color and turn accordingly



2.2 Flow diagram

2.3 Why Ev3?

Ev3 ultimately proved to be a much more reliable and faster option for us as its motor were much less jittery and much more durable. Additionally, the parts for Ev3 were much more accessible and allowed us to utilize it to a much higher potential than we ever could have with Aisteam, we work with what we have and we believe that we have enough to win the competition.

3.0 Mobility Management
------------------------------------


3.1 Bill of Materials
__________________________________________________________

![image can't be loaded so either click the link or get wifi](Rorke.pdf)

3.2 wiring diagram

3.3 why we used the motors we did

We used a combination of large motors and medium motors as it allowed us to utilize the best of both worlds. We can utilize the torque and stability of the large motor to push the robot through thick and thin. The medium motor allows the front wheel drive to snap left and right allowing the robot to quickly respond to obstacles or anything in its path


3.4 motors axle system

3.5 Rack and pinion system 

Our self driving car uses an Rack and pinion steering system which provides precise and stable controls for moving and turning. 


3.5.1 how does the system wprks?

The rack and pinion steering system converts the rotational motion of your steering wheel into the linear motion needed to turn the car's wheel. this system is used to reduce the tires in slipping and prevents oversteer and understeer. pressure must be constantly applied for the steering gear to be in contact with pinion bar 

4.0 Power management

4.1 Power distribution diagram


4.2 power source
The battery powering the self driving car is a Rechargeable DC (Li-ion) type with a capacity of 2050 mAH and a nominal voltage of 7.4v.
This battery primarily use to power the Ev3 brick which is the brain of our robot and it provides a reliable and rechargeable power source, allowing our robot to run for an extended period of time without needing of constantly replacing batteries 


4.3 why we used out sensors and camera

The camera can differentiate colors by utilizing the color detection built in. the color differentiation allows us to avoid the green and red accordingly to the regulations. Our infrared avoidance sensors are utilized in order to detect near by obstacles and walls in order to avoid or adjust accordingly depending on the object, it's distance, and it's direction

5.0 Building the robot

5.1 The base

The base was created to be compact enough to fit regulations but light enough to be quick enough to run laps in a quick and efficient manner, through revisions and the such we ultimately found our base to be effective at the job at hand, modifications were made so it could hold all our components.

5.2 Adding the components

The components are all connected by pegs, no adhesives were used when connecting the components to the robot. While most components simply click into place and just sit there, a few components require to be locked in such as the pinion in the steering system.

5.3 Wiring

The wiring is organized in order to not inhibit the robot or it's movements, most of the wires simply slip under the robot into its respective port and once connected is left there. Markings indicate where the wires go but we still get confused so we guess sometimes

6.0 strategy


6.1 Walls

Just like in real life, it is preferred not to crash into a wall while driving at high speeds. Our robot uses the same logic by turning to the right when it detects a wall or the corner line, additionally we would prefer not to scrape the paint off of the walls so a sensor will detect walls to the sides of the robot, once a limitation is reached and the gap between the robot and a wall becomes too close, it will simply adjust and straighten.

6.2 Lines

How do you know when to turn when you're driving? Probably before you hit someone. Thankfully we have lines, these lines dictate when our robot turns, if a line is detected, we turn to the right, if not, then we don't turn, simple as.

6.3 Obstacles

Red and green are colors, our camera can tell colors apart, if its red then the robot turns left, if green, it turns right and slows down so we don't hit the inner wall.

6.4 Open challenge 

7.0 Parking strategy 

After completing the Three laps. Our robot begins the detection of the parking boundaries, the vehicle assess the available space and align it self with the detected area. If the robot commited the exact angle prior on the given parking space, the vehicle executes a parallel parking maneuver. The vehicle adjust its orientation to locate the exact parking area. Repeating this process until successful parking Achieved

