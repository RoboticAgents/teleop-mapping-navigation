# Report by Katie, Gary, zackery, peter

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
2. Going throught the tutorials to get a better understanding on how we will be starting the mapping of our turtle bot.
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

## Challenges and Learning Experiences

While completing the work on this assignment some challenges that we ran into were getting the network to work with our laptops and the turtle bot to get it to move. Another issue we ran into was saving our image of the map our turtle bot created. One more of the challenges that we ran into was getting our robot to move from the start point to the end point. We solved these issues as a group and ultimately got to our goal of having our turtle bot complete the task of moving from a start point to an end point. The biggest learning take away was seeing a real-world applciation of AI in combination with a camera. Seeing it be able to make its own route and execute a path it came up with opened our eyes to some new possibilities in the field of robotics.

## Team Work

For our group our strategy is to work evenly and failry with thoughts of action leading toward our each individual strong suits. For the ultimate goal of getting our turlebot to create a map and complete a course with a start point and an end point.
