# Teleop, Mapping, and Navigation

## Step 1: Getting Started and `teleop`

1. Open the box for the robot and take out the dock. Place the dock on the floor in an open space and plug it into the nearest outlet.
2. Power on the robot and plug the router into the wall
3. Connect the computer's network to the router, ensuring that the robot connects to the router as well.
4. Make sure that the robot has the keyboard control ros commands installed. If not, make sure to install them.
5. Run the keyboard commands and watch the robot move when you type commands!

`source /opt/ros/galactic/setup.bash`
`ros2 run teleop_twist_keyboard teleop_twist_keyboard`

## Step 2: Implementation Details

1. Getting our turtle bot connected to our laptops.
2. Going throughout the tutorials to get a better understanding on how we will be starting the mapping of our turtle bot.
3. Getting the keyboard command up working to get the movement of our turtle bot functioning.
4. Run the commands to open the mapping software.
5. Start the creation of our map.
6. Save our map.
7. Get our turtle bot to complete the task of starting at one point and moving to the end point that we choose.

- <https://turtlebot.github.io/turtlebot4-user-manual/tutorials/driving.html>
- <https://www.youtube.com/watch?v=T3if0aPj0Eo>
- <https://turtlebot.github.io/turtlebot4-user-manual/tutorials/generate_map.html>
- <https://github.com/turtlebot>
- <https://www.youtube.com/watch?v=35U4JKThOFU>

Our task we decided to pursue was to get the robot to move around the table. We decided to do this because it was the largest natural boundary that we had to make it have a harder time coming up with its ideal path around. We used the above resources in order to come up with and accomplish this idea and plan.

## Outcomes

Located in the img_and_vid folder.

We thought it was interesting that it was able to automatically plan its route only given a start and end location. We didn't do this in the video, but when we stood in front of the robot it would attempt to go around us, even if this wasn't in the original map that it came up with.
