# Avalanche
Autonomous 6WD off-road survillance vehicle

(https://github.com/guadabernal/Avalanche/blob/master/rendering/robot%20render1.JPG)

https://www.thingiverse.com/thing:219...
https://github.com/guadabernal/Avalanche
https://hackaday.io/project/20636-ava...

The robot is using an 8 year-old laptop bought on ebay for $64.99. 

(human-i-t Dell Latitude E5410 14" Core i5-520M 2.40GHz 4GB DDR3 250GB HDD WIN7COA No OS ... US $64.99)

No GPU acceleration, just an old but nice CPU.
The warning message you can see on the screen is the battery which was out of charge, and it died miserably a few minutes later. You get for what you paid for.

No LIDAR, no radar, no range finders, no depth camera, no sonar; just a standard webcam and in a pretty harsh environment. 
Illumination changes due to the sun, clouds, trees, time of the day makes this problem incredibly difficult for computer vision. But it is flawlessly solved in here. Yet the big auto corporations can't get lane departure warning working.

I only use less than 400 frames for training. What if I had used more? I would have had a lot more precision for sure.

I already added a GPS and a compass but haven't had time to change the algorithm to use the heading info to guide the robot. I spent too much time trying to calibrate the stupid compass which still isn't working. That's why I had to change its direction a few times so it could follow the path I wanted it to go and not the other paths.

I didn't write the info on the screen but it's running at an astonishing 20fps.
