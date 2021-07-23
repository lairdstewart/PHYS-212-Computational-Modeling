# Computational Modeling (PHYS 212 @Emory)

This is a collection of the 4 major projects in Physics 212 (Computational Modeling) at Emory. Syllabus: https://nemenmanlab.org/~ilya/index.php/Physics_212,_2020:_Computational_Modeling_For_Scientists_And_Engineers

Project 1: In this project I solve the problem of finding the resting position of a moving cart on the cable of a bridge. The bridge has a catenary shape and the cart has a built in motor. The cart will start at some point along the cable of the bridge and its built in motor will carry it untill it stops or reaches the top of one side or the other. This model is deterministic, static and continuous in space.

Project 2: In this problem I solve the problem of a pendulum with resistance and an applied force. The pendulum will be released from a ceartain angle and then swing back and forth depending on the air (or possibly water) resistance, and the applied force's magnitude and period.

Project 3: In this project I first model a falling object in a fluid with resistance. I then use the general model I created to try and find the fluid density and resistance constants of a real world problem being given the position vs. time data of the falling object. After finding these constants, I can use my model to fit the data with my own differential equation. I also fit the given data with four different polynomials.The model of this falling object that I create will be deterministic, dynamic (the data we are fitting involves time and trajectories), well-mixed (assuming uniform densities), and continuous in time and space. Although the data we are given has descrete (time, position) pairings, the model I will be fitting to it will be continuous

Project 4: Diffusion-limited aggregation is a natural process where particles or molecules undergoing brownian motion stick together to form a cluster. Diffusion-limited aggregation or DLA occurs in many different cases including the creation of snowflakes, or zinc ions aggregating onto electrodes. This project will use python to model this phenomenon.
