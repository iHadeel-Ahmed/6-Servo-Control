# Walking Motion Algorithm for Humanoid Robot

This algorithm describes how walking can be implemented in a humanoid robot using servo motors.

1. Start with the robot in a balanced standing position. All servos are at 90 degrees.
2. Shift the center of gravity to the left leg by slightly tilting the body using hip servos.
3. Lift the right leg by moving the servo connected to the hip and knee joints.
4. Swing the right leg forward.
5. Lower the right leg to the ground.
6. Return the body to the center, distributing the weight on both legs.
7. Repeat the same process for the left leg.
8. Alternate the above steps in a loop to simulate continuous walking.
9. Optional: Synchronize the arm movements in opposite direction to the legs to enhance balance.
