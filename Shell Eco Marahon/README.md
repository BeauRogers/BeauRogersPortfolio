# Shell Eco Marathon


The Shell Eco Marithon is an annual international competition
for Univeristy Teams to compete to build the most fuel efficient
vehicle. In the year 2017-2018, I was tasked with being the
team leader to switch our vehicle to an electric motor system.

With 3-5 people working on this, we created simulations for the 
size of motor that would be needed, the gear ratios as well as the
predicted time to reach cruising speed. The motor was selected based
off these simulations.

The motor controller was largely based off a Vedder open source motor controller
that we stripped down to meet our needs. The Vedder micro controller was substituted
with an Arduino Mega for ease of programming across the whole team. 

Stripping down the system involved understanding the Vedder motor controller system, 
remvoing features that were irrelavent,
performing power calculations for our expected currents and creating plans to 
safely and incrementally test each system. 

Arduino code was written to interpret motor position based on digital kanaught maps, 
fault states of the motor, temperature input and speed control via user input through a potentiometer.

At the end of the year, I created a hand-over document outlining all
the knowledge that would be needed to carry the project on further as
that was my last year of university. 