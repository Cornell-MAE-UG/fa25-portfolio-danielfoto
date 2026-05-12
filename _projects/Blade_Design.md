---
layout: project
title: Mechatronics Robot 
description: Designing a robot that collects cubes and detects colors to maneuvur 
technologies: [Fusion 360, Engineering Design, Circuit]
image: /assets/images/image.png
---


# Project Overview
Our initial strategy for designing our robot was to not have many moving parts and keep the design simple to avoid technical problems. We knew that getting the robot to properly drive, turn, color sense, and collect cubes will be difficult to achieve on its own so we wanted to keep a decently simple design to focus greatly on the robot’s movements. We originally liked the idea of having two arms to collect cubes on each side of the robot while having a triangle piece on the front to funnel the cubes to the arms and avoid the cubes hitting the wheels. We also thought it would be advantageous to add positional servos to the arms and have them open to a specific angle to extend our funnel area and collect more cubes. 
We had difficulties with milestone 3 as we couldn't properly get both the QTI sensors to function and sense the black arena borders. We couldn’t figure it out as we were also having great trouble with our color sensor, however we switched out our 9V battery and we were able to get the color sensor to detect everything properly, but still couldn't get the QTI sensors to work. We ultimately decided to just use the color sensor because we wanted to focus more on getting the positional servos to work as that was a bigger design focus for us. 
Another issue we ran into was for milestone 4 as our initial design had the cotter ball in the back and the main motor wheels in the front to have stronger turning radius, however we ran into design constraint problems where the cubes would most likely not funnel properly because there was only a 1 inch gap between the front wheels and the arms for the cubes to funnel through, and we couldn't extend the arms any further because of the 8 inch by 8 inch starting size constraint. Therefore we redesigned the robot and inverted it so the cotter ball was now in the front and the arms were facing the opposite direction, therefore giving almost 2 inches of space between the chassis and the arms for the cubes to properly funnel through. This required some revision of the code to invert the drive forward and drive backward commands that we originally wrote but that wasn’t too difficult to fix. Once we knew our dimensions were within the 8 by 8 inch starting constraint and the 12 in diameter constraint, we moved forward with our 3D print as we knew we would only get one shot at it as the most expensive part of our budget. Once we assembled everything we completed milestone 4 very easily. After completing this milestone we figured out how to properly code the positional servos to open at the start of the competition and close during turns, and then we were ready for competition day. 


# Project Conclusion
If we were to revise our robot for improvement, the first change would be to use QTI sensors for detecting the black borders. Relying on the color sensor made black detection unpredictable because the lighting in Duffield varied significantly. Boards near the windows had very different frequency ranges, causing our robot to miss black borders entirely. 
Another improvement would be to use two separate color sensors (one tuned for yellow and one for blue). This would allow each sensor to be calibrated precisely for its target color. Our robot behaved reliably when starting on blue, but when placed on yellow, the sensor readings shifted enough to affect the servo arm behavior and turning distance. 
We also identified issues with the wheels and rubber bands given. This caused uneven traction and resulted in one wheel rotating faster than the other. Purchasing a higher‑quality wheel set would give us more uniform grip, better straight‑line motion, and potentially higher speed.



