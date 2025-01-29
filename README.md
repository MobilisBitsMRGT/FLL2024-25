My Blocks:

The program uses 2 main blocks: One for going straight and one for turning.

For going straight the program uses PID. It has 3 parameters. PID (Proportional-Integral-Derivative) is a control algorithm that adjusts an output based on the proportional, integral, and derivative terms of an error signal to achieve desired system performance. The first one is the angle that we want to go in, that is an absolute angle. The second one is the distance, which measure how far we want to travel. The third one is the speed, it sets how fast we want to go.

For turning the program uses a PID turn, in the program we call it Turn_v2. It only has 1 parameter which is the absolute angle. There is no speed parameter, since the My Block calculates it by itself.

Parts of the program:

There are 2 main parts of the program. The starter and the rounds. The starter can be found under the name "indito". In it the current operator can decide which program they would like to start from 1 to 7. The rounds determine which tasks the robot will do.
