# Week 3 Entry

This week we have had our initial meeting with our Supervisors. LJ and I have clearly outlined exactly what our project will entail.
Essentially, we will be using these tables (plinths) with microcomputers inside of them to control LED strips built into the surface. Each plinth has a set of LEDs and a microcomputer that hosts it's own Site. Given that there are 9 plinths, there are also 9 sites to visit in order to change the colour of each individual one.

Also, these plinths have a few bugs... the major one is that once they drop connection to the WiFi, they cannot reconnect unless they're switched off and back on again. We're currently unsure how to fix this issue, an early idea is to just constantly ping the plinth in order to maintain that connection. 

Another unideal aspect of the plinths is that the basic site that each microcomputer hosts takes up 30% of the memory... memory that could be otherwise spent with more important tasks. 

Our plan is to create a web application that doesn't just connect to one plinth individually, but all of them at once. Anyone in Sensilab would have the ability to go to the site and change the colour of any plinth they chose. We have done some research into good UI primarily looking at applications developed by LifX and other Smart Home tech companies.
We have decided to use React.js for the front end and Php in the back. We've decided on a division of labour that i believe we're both happy with. 

# Goals
We aim to create mockups and have a skeleton site ready for use by thursday of next week. This does seem like quite challenge given the research specification is also due at the end of next week but thankfully the skeleton site doesn't have a super strict deadline.