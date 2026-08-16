Hello! I am Sam Neblett and this is the ePortfolio I developed for CS-499 at SNHU as part of my Capstone project.

# Professional Self-Assessment
This ePortfolio, and the code artifacts described within it, were created as part of my Capstone project at the end of the Computer Science program at SNHU. The code artifacts, code review, and narratives presented in this ePortfolio are intended to demonstrate my capabilities as a full-stack developer by highlighting my technical abilities and thought processes when improving upon previous projects of mine from earlier in the Computer Science program.

While I am already employed as a software developer at the time of this writing, completing my coursework throughout the Computer Science program has allowed me to become a more well-rounded developer as it has pushed me to work outside of my comfort zone and typical scope of work. My past experience in software development has mostly centered around mobile and Unity-based projects written in C#, but the Computer Science program has pushed me to expand how I look at software requirements and technical approaches. An example of this is the CS-330 course, Computer Graphics and Visualization, which pushed me to explore new (to me) methods of rendering and controlling 3D content with OpenGL and C++. My past experience with Unity and 3D modeling helped me understand some of the earlier, high-level concepts presented in that course, but exploring concepts I was already familiar with through a new lens, OpenGL and C++, helped provide new perspectives and avenues I can explore in the future when deciding on approaches to developing software. One of the assignments from CS-330, an OpenGL Breakout-like game written in C++, serves as the basis for several significant enhancements I made for my Capstone project, available here as a Python project, and described in detail throughout this ePortfolio.

Throughout the Computer Science program, I have also refined my ability to collaborate in a team environment and communicate with stakeholders. Examples of this can be seen in my code review of the CS-330 OpenGL Breakout project, viewable here, as well as my thorough code documentation and adherence to coding standards like PEP 8. These demonstrate my ability to communicate effectively both with team members I collaborate with by adhering to industry standards and coding styles, and with technical and non-technical stakeholders by translating complex technical concepts into graspable ideas.

The Computer Science program also helped me refine my technical abilities in the areas of data structures and algorithms, software engineering and databases, and security. Learning how to evaluate technical approaches, manage trade-offs in architecture choices, optimize for time and complexity in algorithms, choose appropriate data structures for data in object-oriented programming, and define database schemas for CRUD operations are all examples of the industry-focused skills I have refined during the program that I can demonstrate in my career. These are all also backed up by a security mindset that I have developed to anticipate and prevent exploits in my software, which I demonstrate in the enhanced Python project through input sanitization and parameterized queries to prevent SQL injection attacks.

The technical artifacts presented in this ePortfolio represent my growth throughout my time in the Computer Science program and are split into three sections, each focusing on different enhancements of my work earlier in the program. Enhancement One focuses on Software Design and Engineering, and details how I ported the codebase of an OpenGL and C++ Breakout-like game I made for CS-330 to Python and achieved full parity between the original project and the Python port. Enhancement Two focuses on Algorithms and Data Structures, where I implemented complex collision detection and dynamic trajectory algorithms that the original project did not have. Finally, Enhancement Three focuses on Databases, where I created and integrated an SQLite database into the project to track and manage high scores. These enhancements build upon each other to create a fully playable full-stack application.


# Project Artifacts
## Full code artifact repository:
- [https://github.com/SamuelNeblett/CS-499-Breakout-Game](https://github.com/SamuelNeblett/CS-499-Breakout-Game)

## C++ project from CS-330 that I later enhanced for CS-499:
- [Full C++ project](https://github.com/SamuelNeblett/CS-499-Breakout-Game/tree/main/OriginalArtifact_CppCode/CS-330_Artifact/8-2_Assignment)
- [Primary C++ code of focus](https://github.com/SamuelNeblett/CS-499-Breakout-Game/blob/main/OriginalArtifact_CppCode/CS-330_Artifact/8-2_Assignment/Source/MainCode.cpp)

## Enhancement of my CS-330 C++ project for CS-499:
- [Completed, enhanced project ported to Python](https://github.com/SamuelNeblett/CS-499-Breakout-Game/tree/main/Enhanced_PythonPort)
- [Primary Python code of focus](https://github.com/SamuelNeblett/CS-499-Breakout-Game/blob/main/Enhanced_PythonPort/Neblett_BreakoutGame.py)

# Artifact Code Review
- [Video code review of the original C++ project, pre-enhancements](https://youtu.be/jWI7UXA1J_U)

# Project Enhancement Narratives
The enhanced project described above was created for my Capstone project for CS-499 at SNHU. The Capstone project in this ePortfolio demonstrates the mastery of the following CS-499 course outcomes:
1. Employ strategies for building collaborative environments that enable diverse audiences to support organizational decision making in the field of computer science
2. Design, develop, and deliver professional-quality oral, written, and visual communications that are coherent, technically sound, and appropriately adapted to specific audiences and contexts
3. Design and evaluate computing solutions that solve a given problem using algorithmic principles and computer science practices and standards appropriate to its solution, while managing the trade-offs involved in design choices
4. Demonstrate an ability to use well-founded and innovative techniques, skills, and tools in computing practices for the purpose of implementing computer solutions that deliver value and accomplish industry-specific goals
5. Develop a security mindset that anticipates adversarial exploits in software architecture and designs to expose potential vulnerabilities, mitigate design flaws, and ensure privacy and enhanced security of data and resources

Each of the three project enhancement categories demonstrate the following course outcomes:
- Software Engineering and Design
  - Course Outcome 2: Design, develop, and deliver professional-quality oral, written, and visual communications that are coherent, technically sound, and appropriately adapted to specific audiences and contexts
  - Course Outcome 4: Demonstrate an ability to use well-founded and innovative techniques, skills, and tools in computing practices for the purpose of implementing computer solutions that deliver value and accomplish industry-specific goals
- Algorithms and Data Structures
  - Course Outcome 3: Design and evaluate computing solutions that solve a given problem using algorithmic principles and computer science practices and standards appropriate to its solution, while managing the trade-offs involved in design choices
- Databases
  - Course Outcome 1: Employ strategies for building collaborative environments that enable diverse audiences to support organizational decision making in the field of computer science
  - Course Outcome 5: Develop a security mindset that anticipates adversarial exploits in software architecture and designs to expose potential vulnerabilities, mitigate design flaws, and ensure privacy and enhanced security of data and resources

My full enhancement plan for this project can be found here:
- [Enhancement Plan](https://github.com/SamuelNeblett/CS-499-Breakout-Game/blob/main/EnhancementPlan.docx)

# Enhancement One: Software Design and Engineering - Narrative
1.	Briefly describe the artifact. What is it? When was it created?

The artifact selected for the Software Design and Engineering enhancement is a Breakout-like game where the player moves a paddle at the bottom of the screen and launches balls towards bricks to break them with the goal of clearing the screen. The original artifact, before my enhancements, was a C++ project created for the 8-2 Assignment: Coding Collisions assignment in CS-330 Computational Graphics and Visualization. This project was originally created on May 26th, 2026.

2.	Justify the inclusion of the artifact in your ePortfolio. Why did you select this item? What specific components of the artifact showcase your skills and abilities in software development? How was the artifact improved?

This artifact was chosen for my ePortfolio because it demonstrates my knowledge of both C++ and Python, as well as my ability to port a project from one language to another. I selected this item because I currently work in real-time app and game development, but I primarily build applications within the Unity and Unreal engines, so the inclusion of this application demonstrates my ability to work outside of the constraints of game engines for developing real-time applications. Specifically, I want to showcase my ability to create game loops outside of game engines, which this project allows me to do. I also want to showcase my knowledge of Python, which is a language that I have not had much experience using in the professional space. This artifact was improved from its original state by porting it to Python, a more user-friendly and readable language compared to C++. Multiple new features were added during this enhancement including the inclusion of GUI elements for a Main Menu, score tracking, life tracking, level progression across 3 levels, and new brick properties that allow for multiple hits before being destroyed.

***Enhanced Python Artifact: New ImGUI Main Menu***
```python
  # Start a new ImGui frame
  # This allows us to draw OpenGL GUI elements
  impl.process_inputs()
  imgui.new_frame()

  # Menu loop
  if current_state == "MENU":
      imgui.begin("Main Menu")
      if imgui.button("Start Game"):
          score = 0
          lives = 5
          current_level = 1
          load_level(current_level)
          current_state = "PLAYING"
      
      if imgui.button("High Scores"):
          print("High Scores to be implemented later...")

      if imgui.button("Wipe High Scores"):
          print("High Scores to be implemented later...")

      if imgui.button("Quit"):
          glfw.set_window_should_close(window, True)
      
      imgui.end()
```

***Enhanced Python Artifact: New ImGUI In-Game HUD for scores, lives, and level***
```python
  # Menu loop
  if current_state == "PLAYING":
      # Render the GUI for the score and lives
      # Used ImGui reference for flags and positioning here:
      # https://github.com/pthom/imgui_bundle/blob/main/bindings/imgui_bundle/demos_python/demo_imgui_bundle_intro.py
      imgui.set_next_window_pos(imgui.ImVec2(10, 10))
      imgui.set_next_window_bg_alpha(0.0) 
      imgui_flags = (imgui.WindowFlags_.no_title_bar |
                     imgui.WindowFlags_.no_resize |
                     imgui.WindowFlags_.no_move |
                     imgui.WindowFlags_.always_auto_resize)

      imgui.begin("GUI", flags = imgui_flags)
      imgui.text(f"Score: {score} | Lives: {lives} | Level: {current_level}")
      imgui.end()
```

***Enhanced Python Artifact: Level Progression Logic***
```python
  # Check progress for level completion
  bricks_remaining = 0
  for brick in active_bricks:
      # Only count bricks that are still "on" (not destroyed)
      # and bricks that are destructible
      if brick.onoff == OnOff.ON and brick.brick_type == BrickType.DESTRUCTABLE:
          bricks_remaining += 1

  # If all destructible bricks are destroyed, advance to the next level
  if bricks_remaining == 0:
      current_level += 1
      load_level(current_level)
```

***Original C++ Artifact from CS-330: Original Brick Class***
```cpp
  class Brick
  {
  public:
  	float red, green, blue;
  	float x, y, width;
  	BRICKTYPE brick_type;
  	ONOFF onoff;
  
  	Brick(BRICKTYPE bt, float xx, float yy, float ww, float rr, float gg, float bb)
  	{
  		brick_type = bt; x = xx; y = yy, width = ww; red = rr, green = gg, blue = bb;
  		onoff = ON;
  	};
```

***Enhanced Python Artifact: New Brick Class***
```python
  # Define the Brick class to represent each brick in the game
  class Brick:
      def __init__(self, brick_type, xx, yy, ww, red, green, blue, hits_remaining):
          self.red = red
          self.green = green
          self.blue = blue
          self.x = xx
          self.y = yy
          self.width = ww
          self.brick_type = brick_type
          # If hits_remaining > 1, the brick requires multiple hits to clear
          self.hits_remaining = hits_remaining
          self.onoff = OnOff.ON
```

3.	Did you meet the course outcomes you planned to meet with this enhancement in Module One? Do you have any updates to your outcome-coverage plans?

I met the two outcomes I had planned to meet for the Software Design and Engineering category that I outlined in my enhancement plan in Module One. The first course outcome that I had planned to meet for this category was “Design, develop, and deliver professional-quality oral, written, and visual communications that are coherent, technically sound, and appropriately adapted to specific audiences and contexts.” I have met this outcome because my application now visually communicates game progression through GUI elements, like the GUI showing the current score, level, and lives, and organizes options for the user on a central Main Menu. The source code also includes significant documentation via in-line comments and abides by PEP 8 standards to facilitate developer familiarization. The second outcome I had planned to meet for this category was “Demonstrate an ability to use well-founded and innovative techniques, skills, and tools in computing practices for the purpose of implementing computer solutions that deliver value and accomplish industry-specific goals.” I met this outcome because I employed innovative thinking to not only port a C++ project to Python, but to find direct equivalents to OpenGL frameworks like PyOpenGL, utilized popular libraries like ImGui for GUI elements, and utilized industry-standard conventions like PEP 8. I do not have any updates to my outcome-coverage plan, as I believe my enhancement plan from Module One should cover every outcome appropriately when I am finished with each category.

4.	Reflect on the process of enhancing and modifying the artifact. What did you learn as you were creating it and improving it? What challenges did you face?

The process of enhancing and modifying my chosen artifact went very well. I had a lot of fun converting the C++ code to Python, and I was surprised by how straightforward much of it was due to the GLFW bindings available in Python. For further enhancements, adding the new additional features was much more time-consuming than expected, mostly due to challenges with the GUI system, but I was able to get everything working well in the end. The biggest challenge I faced was creating the GUI. I initially tried using PyQt, as I had some experience with it in the past, but I could not get it to render correctly over the OpenGL content. This led me to research other GUI libraries that were compatible with OpenGL and Python, and I eventually landed on ImGui. After a few hours of debugging and trying to get PyImGui to install via pip, I discovered that it had last been updated in 2023 and did not appear to be compatible with anything newer than Python 3.11 (Jaworski). This led me to another ImGui library, “Dear ImGui Bundle”, which I was then able to utilize for GUI elements in my application (Thomet).

# Enhancement Two: Algorithms and Data Structures - Narrative
1.	Briefly describe the artifact. What is it? When was it created?

The artifact selected for the second enhancement, Algorithms and Data Structure, is the same artifact that I selected for the first enhancement, Software Design and Engineering, a Breakout-like game originally created as a C++ project for CS-330 Computational Graphics and Visualization as the 8-2 assignment Coding Collisions. This artifact was originally created on May 26th, 2026.

2.	Justify the inclusion of the artifact in your ePortfolio. Why did you select this item? What specific components of the artifact showcase your skills and abilities in algorithms and data structure? How was the artifact improved?

This artifact should be included in my ePortfolio because it demonstrates my ability to develop a gameplay loop that implements complex trajectory calculations, collision detection algorithms like axis-aligned bounding box (AABB) checking, and data structure creation. I selected this item because the original artifact from CS-330 handled several algorithms poorly and lumped data structures together illogically. Specifically, trajectory was very poorly calculated, only allowing the ball to go randomly in one of eight directions. The artifact also did not handle collision well, and data structures for the brick class and paddle were needlessly combined. Additionally, I was able to add a new data structure to the project to handle score tracking.
Original C++ artifact for CS-330 – ball (originally named “Circle”) trajectory limited to 8 directions, picked randomly:


***Original C++ Artifact from CS-330: Ball (originally named “Circle” here) trajectory limited to 8 directions, picked randomly***
```cpp
  class Circle
  {
  public:
  	float red, green, blue;
  	float radius;
  	float x;
  	float y;
  	float speed = 0.03;
  	int direction; // 1=up 2=right 3=down 4=left 5 = up right   6 = up left  7 = down right  8= down left
  	ONOFF onoff;
  
  	Circle(double xx, double yy, double rr, int dir, float rad, float r, float g, float b)
  	{
  		x = xx;
  		y = yy;
  		radius = rr;
  		red = r;
  		green = g;
  		blue = b;
  		radius = rad;
  		direction = dir;
  		onoff = ON;
  	}
```
```cpp
	int GetRandomDirection()
	{
		return (rand() % 8) + 1;
	}

	void MoveOneStep()
	{
		// If the circle is off, don't move the circle
		if (onoff == OFF)
		{
			return;
		}

		// Friction modifier to slow down as it hits things
		float frictionMod = 0.7f;

		if (direction == 1 || direction == 5 || direction == 6)  // up
		{
			// Flipped this to check top bounds
			if (y < 1 - radius)
			{
				// Flipped to go up instead
				y += speed;
			}
			else
			{
				direction = GetRandomDirection();
				
				// Ensure the speed never goes below 0, so it always moves
				if (speed < 0.001f)
				{
					speed = 0.001f;
				}
				else
				{
					// Apply friction to slow down the ball
					speed *= frictionMod;
				}
			}
		}

		if (direction == 2 || direction == 5 || direction == 7)  // right
		{
			if (x < 1 - radius)
			{
				x += speed;
			}
			else
			{
				direction = GetRandomDirection();

				// Ensure the speed never goes below 0, so it always moves
				if (speed < 0.001f)
				{
					speed = 0.001f;
				}
				else
				{
					// Apply friction to slow down the ball
					speed *= frictionMod;
				}
			}
		}

		if (direction == 3 || direction == 7 || direction == 8)  // down
		{
			if (y > -1 + radius)
			{
				y -= speed;
			}
			else
			{
				direction = GetRandomDirection();

				// Ensure the speed never goes below 0, so it always moves
				if (speed < 0.001f)
				{
					speed = 0.001f;
				}
				else
				{
					// Apply friction to slow down the ball
					speed *= frictionMod;
				}
			}
		}

		if (direction == 4 || direction == 6 || direction == 8)  // left
		{
			if (x > -1 + radius) {
				x -= speed;
			}
			else
			{
				direction = GetRandomDirection();

				// Ensure the speed never goes below 0, so it always moves
				if (speed < 0.001f)
				{
					speed = 0.001f;
				}
				else
				{
					// Apply friction to slow down the ball
					speed *= frictionMod;
				}
			}
		}
	}
```

***Enhanced Python Artifact: Ball (originally named “Circle” in the C++ project) now uses velocity and calculates reflection trajectory***
```python
  class Ball:
      def __init__(self, pos_x, pos_y, radius, velocity_x, velocity_y, red, green, blue):
          self.x = pos_x
          self.y = pos_y
          self.radius = radius
          self.red = red
          self.green = green
          self.blue = blue
          # Replace old direction logic with velocity
          self.velocity_x = velocity_x
          self.velocity_y = velocity_y
  
          self.onoff = OnOff.ON
```
```python
  # Called once per frame to handle movement
  def move_one_step(self):
      global lives, can_launch, current_state

      # If the ball is off, don't move the ball
      if self.onoff == OnOff.OFF:
          return

      # Add the new velocity to the X and Y coordinates to move the ball
      self.x += self.velocity_x
      self.y += self.velocity_y

      # Minimum velocity so we don't divide by zero
      # and so the ball never moves too slowly
      min_velocity = 0.005

      # Friction modifier to slow down as it hits things
      friction_mod = 0.3

      # Left bounds collisions
      if (self.x < -1 + self.radius):
          self.x = -1 + self.radius

          # Bounce off of the wall and slow down the ball
          self.velocity_x = (self.velocity_x * -1) * friction_mod
          
          # Ensure the velocity never goes below 0, so it always moves
          if abs(self.velocity_x) < min_velocity:
              self.velocity_x = min_velocity

      # Right bounds collisions
      if (self.x > 1 - self.radius):
          self.x = 1 - self.radius

          # Bounce off of the wall and slow down the ball
          self.velocity_x = (self.velocity_x * -1) * friction_mod
          
          # Ensure the velocity never goes below 0, so it always moves
          if abs(self.velocity_x) < min_velocity:
              self.velocity_x = -min_velocity

       # Top bounds collisions
      if (self.y > 1 - self.radius):
          self.y = 1 - self.radius

          # Bounce off of the wall and slow down the ball
          self.velocity_y = (self.velocity_y * -1) * friction_mod
          
          # Ensure the velocity never goes below 0, so it always moves
          if abs(self.velocity_y) < min_velocity:
              self.velocity_y = -min_velocity

      # Floor bounds collisions
      if (self.y < -1 + self.radius):
          # When the ball touches the bottom of the screen
          # A life is lost and the ball is disabled
          self.onoff = OnOff.OFF
          lives -= 1

          # If the player has no lives left, return to the main menu
          if lives <= 0:
              # Save the current score and push to the high score database
              score_db = PlayerScore("Player", score, current_level)
              score_db.save_to_database()

              current_state = "MENU"
          # Else, allow the player to launch a new ball
          else:
              can_launch = True
```
```python
  def draw_ball(self):
      # Only render the ball if it is "on" (not destroyed)
      if (self.onoff == OnOff.ON):
          glColor3f(self.red, self.green, self.blue)
          glBegin(GL_POLYGON)
          for i in range(360):
              deg_in_rad = i * DEG2RAD
              glVertex2f((math.cos(deg_in_rad) * self.radius) + self.x,
                         (math.sin(deg_in_rad) * self.radius) + self.y)

          glEnd()
```

***Original C++ Artifact from CS-330: collision checking for reflective bricks***
```cpp
	// Check collision for bricks
	void CheckCollision(Brick* brk)
	{
		// If the circle is off, don't check for collision between circle and brick
		if (onoff == OFF)
		{
			return;
		}

		if (brk->brick_type == REFLECTIVE)
		{
			if ((x > brk->x - brk->width && x <= brk->x + brk->width) && (y > brk->y - brk->width && y <= brk->y + brk->width))
			{
				direction = GetRandomDirection();

				// Adding direction-based offsets to move the ball slightly above the paddle so it does not get stuck
				// "Sticky paddle" issue referenced here https://learnopengl.com/In-Practice/2D-Game/Collisions/Collision-resolution
				if (x < brk->x)
				{
					x -= 0.02;
				}
				else
				{
					x += 0.02;
				}

				if (y < brk->y)
				{
					y -= 0.02;
				}
				else
				{
					y += 0.02;
				}

				// For the "Alter the state of the bricks upon collision" requirement
				// Increment the color of the brick by 0.1 for each color channel
				brk->red += 0.1f;
				brk->green += 0.1f;
				brk->blue += 0.1f;

				// Wrap each color channel around to 0 once it reaches > 1.0
				if (brk->red > 1.0f)
				{
					brk->red = 0.0f;
				}
				if (brk->green > 1.0f)
				{
					brk->green = 0.0f;
				}
				if (brk->blue > 1.0f)
				{
					brk->blue = 0.0f;
				}
			}
		}
```

***Enhanced Python Artifact: AABB collision checking, logic split to handle brick and paddle differently***
```python
  # Check collision with bricks and paddles using AABB
  def check_collision(self, obj):

      # Check if the passed obj is a brick or a paddle
      # The ball can collide with both, both use AABB collision detection
      isbrick = isinstance(obj, Brick)
      ispaddle = isinstance(obj, Paddle)

      # If the ball or brick is off, don't check for collision
      if (self.onoff == OnOff.OFF or obj.onoff == OnOff.OFF):
          return

      # Define a bounding box for the ball for AABB collision detection
      half_width = obj.width / 2
      if isbrick:
          # Bricks are square and have no height component
          half_height = half_width
      elif ispaddle:
          half_height = obj.height / 2

      min_x = obj.x - half_width
      max_x = obj.x + half_width
      min_y = obj.y - half_height
      max_y = obj.y + half_height

      # Find the closest points on X and Y
      # AABB closest point reference adapted from:
      # https://learnopengl.com/In-Practice/2D-Game/Collisions/Collision-detection
      closest_x = max(min_x, min(self.x, max_x))
      closest_y = max(min_y, min(self.y, max_y))

      # Find the distance between the ball's center and this closest point
      distance_x = self.x - closest_x
      distance_y = self.y - closest_y

      # Calculate the distance length using the Pythagorean theorem
      # Translated from C++ OpenGL glm::length() from:
      # https://learnopengl.com/In-Practice/2D-Game/Collisions/Collision-detection
      distance_length = math.sqrt((distance_x ** 2) + (distance_y ** 2))
      
      # Check if the distance is less than the ball's radius
      # to determine collision events
      if (distance_length < self.radius):
          # Safety check so we don't divide by zero
          if distance_length == 0:
              distance_length = 0.001

          # If the collision is with a brick
          if isbrick:
              self.brick_collision(obj,
                                   distance_length,
                                   distance_x,
                                   distance_y)
          # If the collision is with a paddle
          elif ispaddle:
               self.paddle_collision(obj,
                                     half_width,
                                     half_height)
```
```python
  # Collision event with a brick
  def brick_collision(self, obj, distance_length, distance_x, distance_y):
      global score

      # Normalize the distance vector to get the collision normal
      # Collision resolution concepts adapted from:
      # https://learnopengl.com/In-Practice/2D-Game/Collisions/Collision-resolution
      normal_x = distance_x / distance_length
      normal_y = distance_y / distance_length

      # Reflect the ball's direction based on the collision normal
      # Reflection vector math adapted from:
      # https://math.stackexchange.com/questions/13261/how-to-get-a-reflection-vector
      dot_product = (self.velocity_x * normal_x) + (self.velocity_y * normal_y)

      # Update the ball's velocity based on the reflection formula
      self.velocity_x = self.velocity_x - (2 * dot_product * normal_x)
      self.velocity_y = self.velocity_y - (2 * dot_product * normal_y)

      # Adding direction-based offsets to move the ball slightly
      # above the paddle so it does not get stuck
      # "Sticky paddle" issue referenced here:
      # https://learnopengl.com/In-Practice/2D-Game/Collisions/Collision-resolution
      self.x += normal_x * (self.radius - distance_length)
      self.y += normal_y * (self.radius - distance_length)

      # Check the brick type
      # Reflective bricks should change color on collision,
      # but not be destroyed
      if obj.brick_type == BrickType.REFLECTIVE:
          # Increment the color of the brick by 0.1 for each color channel
          obj.red += 0.1
          obj.green += 0.1
          obj.blue += 0.1

          # Wrap each color channel around to 0 once it reaches > 1.0
          if (obj.red > 1.0):
              obj.red = 0.0
          if (obj.green > 1.0):
              obj.green = 0.0
          if (obj.blue > 1.0):
              obj.blue = 0.0
          
      # Destructable bricks should decrement their hit count
      # and be destroyed if hits_remaining <= 0
      elif (obj.brick_type == BrickType.DESTRUCTABLE):
          # Decrement the hits remaining for the destructible brick
          obj.hits_remaining -= 1

          if obj.hits_remaining <= 0:
              obj.onoff = OnOff.OFF
              # Increment score when a destructible brick is destroyed
              score += 100
          else:
              # Decrement the color of the brick by 0.1
              # for each color channel
              obj.red -= 0.1
              obj.green -= 0.1
              obj.blue -= 0.1

              # Wrap each color channel around to 0 once it reaches > 1.0
              if (obj.red < 0.0):
                  obj.red = 1.0
              if (obj.green < 0.0):
                  obj.green = 1.0
              if (obj.blue < 0.0):
                  obj.blue = 1.0
                  
              # Increment score when a destructible brick is hit
              # but not destroyed
              score += 20
```
```python
  # Collision event with a paddle
  def paddle_collision(self, obj, half_width, half_height):
      # Calculate where the ball hit the paddle on the X axis
      # Used the following as reference for velocity calculation:
      # https://learnopengl.com/In-Practice/2D-Game/Collisions/Collision-resolution
      hit_pos_x = (self.x - obj.x) / half_width

      # Additional strength/speed to add to the ball after a hit
      velocity_mod = 0.01
      self.velocity_x = hit_pos_x * velocity_mod

      # Move the ball slightly above the paddle
      # so it does not get stuck
      # "Sticky paddle" issue referenced here:
      # https://learnopengl.com/In-Practice/2D-Game/Collisions/Collision-resolution
      self.velocity_y = abs(self.velocity_y)
      self.y = obj.y + half_height + self.radius
```

***Original C++ Artifact from CS-330: paddle defined as a brick type data structure, with a paddle being three different bricks***
```cpp
  // Define brick types
  // Added direction-specific reflection bricks for the paddle
  enum BRICKTYPE { REFLECTIVE, DESTRUCTABLE, REFLECT_UP, REFLECT_UP_LEFT, REFLECT_UP_RIGHT};
  enum ONOFF { ON, OFF };
  
  class Brick
  {
  public:
  	float red, green, blue;
  	float x, y, width;
  	BRICKTYPE brick_type;
  	ONOFF onoff;
  
  	Brick(BRICKTYPE bt, float xx, float yy, float ww, float rr, float gg, float bb)
  	{
  		brick_type = bt; x = xx; y = yy, width = ww; red = rr, green = gg, blue = bb;
  		onoff = ON;
  	};
  
  	void drawBrick()
  	{
  		if (onoff == ON)
  		{
  			double halfside = width / 2;
  
  			glColor3d(red, green, blue);
  			glBegin(GL_POLYGON);
  
  			glVertex2d(x + halfside, y + halfside);
  			glVertex2d(x + halfside, y - halfside);
  			glVertex2d(x - halfside, y - halfside);
  			glVertex2d(x - halfside, y + halfside);
  
  			glEnd();
  		}
  	}
  };
```
```cpp
  // Define a paddle using the brick as the base
  // Defining it in parts so we can affect collision direction based on where the ball hits the paddle
  Brick paddleCenter(REFLECT_UP, 0, -0.9, 0.1, 1, 0, 0);
  Brick paddleLeft(REFLECT_UP_LEFT, -0.1, -0.9, 0.1, 1, 0, 0);
  Brick paddleRight(REFLECT_UP_RIGHT, 0.1, -0.9, 0.1, 1, 0, 0);
```

***Enhanced Python Artifact: paddle data structure created (distinct from brick types), player score data structure created to hold scores***
```python
  # Define the Paddle class
  class Paddle:
      def __init__(self, pos_x, pos_y):
          self.x = pos_x
          self.y = pos_y
          # The paddle size and color will not change, so define those here
          self.width = 0.4
          self.height = 0.1
          self.onoff = OnOff.ON
  
      def draw_paddle(self):
          glColor3d(1, 0, 0)
          glBegin(GL_POLYGON)
  
          glVertex2d(self.x + self.width / 2, self.y + self.height / 2)
          glVertex2d(self.x + self.width / 2, self.y - self.height / 2)
          glVertex2d(self.x - self.width / 2, self.y - self.height / 2)
          glVertex2d(self.x - self.width / 2, self.y + self.height / 2)
  
          glEnd()
```
```python
  # Define a paddle for the player to use to launch and reflect balls at position
  paddle = Paddle(0, -0.9)
```
```python
  # Define the data structure for the player score
  # This will be pushed to a MySQL database that holds high scores
  # This will be expanded upon for the Databases enhancement
  class PlayerScore:
      def __init__(self, player_name, player_score, highest_level):
          self.id = None
          self.player_name = player_name
          self.player_score = player_score
          self.highest_level = highest_level
          self.timestamp = None
  
      def save_to_database(self):
          # Get the timestamp via datetime
          self.timestamp = datetime.datetime.now()
  
          # TODO: push to MySQL database
          # TODO: sanitize input for security
  
          print(f"FINAL SCORE | Player Name: {self.player_name}, Score: {self.player_score}, Level: {self.highest_level}, Timestamp: {self.timestamp}")
```

3.	Did you meet the course outcomes you planned to meet with this enhancement in Module One? Do you have any updates to your outcome-coverage plans?

I have met the third course outcome, “design and evaluate computing solutions that solve a given problem using algorithmic principles and computer science practices and standards appropriate to its solution while managing the trade-offs involved in design choices”, by completing the trajectory, collision, and data structure enhancements outlined above (SNHU). By utilizing the AABB algorithm for collision detection, calculating velocity and trajectory reflection, and creating distinct data structures, I balanced the trade-offs of the original simplistic approach in the C++ artifact with improved functionality that enhances gameplay as a design choice, allowing the game to feel more like the traditional Breakout game, rather than hitting a ball that goes in a random direction. Last week, in the Software Design and Engineering enhancement, I completed the second and fourth course outcomes, leaving the first and fifth course outcomes to be completed in the Databases enhancement. I do not have any updates on my outcome-coverage plan, as everything is progressing well.

4.	Reflect on the process of enhancing and modifying the artifact. What did you learn as you were creating it and improving it? What challenges did you face?

The trajectory calculations were the most difficult part of this enhancement. AABB itself ended up being relatively easy to calculate and was somewhat covered in some of the reading materials for CS-330, but calculating the trajectory, which is triggered after collision detection, took much longer than expected. The reading for CS-330 that covered AABB utilized glm::length(difference) to find the distance, but there does not appear to be an equivalent in Python, so I had to calculate it manually with the Pythagorean theorem (de Vries, n.d.). I am rusty on my linear algebra, but I later found a math reference mentioning that I need to normalize the vector before finding the dot product to get the reflection vector (Phrogz). This was a challenging experience, but fun. I have past experience with calculating inverse vectors for some work applications (e.g., billboarding planes towards a camera), but never anything exactly like this, so it was a fun exercise.



# Enhancement Three: Databases - Narrative
1.	Briefly describe the artifact. What is it? When was it created?

The original artifact selected for the Databases enhancement is the 8-2 Coding Collisions assignment, originally created for CS-330 Computational Graphics and Visualization as a C++ project that functions as a simplified Breakout-like game. This artifact was also used for the first enhancement, Software Design and Engineering, and the second enhancement, Algorithms and Data Structures. This artifact was originally created on May 26th, 2026.

2.	Justify the inclusion of the artifact in your ePortfolio. Why did you select this item? What specific components of the artifact showcase your skills and abilities in software development? How was the artifact improved?

I chose this artifact because it represents a full-stack application, with the inclusion of a database backend to handle persistent high scores with CRUD functionality, that is fully playable end-to-end. This showcases my skills in software development by demonstrating that I have an understanding of frontend and backend development and how to integrate both inside one package. This artifact was improved from its original state of not having any score saving capability or database to now including a fully working SQL database to store player scores, which demonstrates my ability to take an existing application and make functional improvements using databases. Specifically, I added the breakout_db SQL database with sqlite3, a player_scores table to store all player scores, a PlayerScore data structure to store player data, a function to save player data to the database, a function to show the top 10 high scores in a new High Scores screen, a function to wipe all high scores, and a feature for players to input their name before beginning a playthrough.
Enhanced Python artifact: breakout_db SQL database and player_scores table creation with sqlite3:
<img width="332" height="54" alt="image" src="https://github.com/user-attachments/assets/b1e1126f-8205-4f18-9f10-b2f6ae838b45" />
<img width="975" height="368" alt="image" src="https://github.com/user-attachments/assets/af4af10c-a898-4fdf-8ceb-52dcd987cd25" />

Enhanced Python artifact: PlayerScore data structure to store player data:
<img width="895" height="316" alt="image" src="https://github.com/user-attachments/assets/312b1a28-d347-4c51-903e-62864a254181" />

Enhanced Python artifact: function to save player data to the SQL database (breakout_db):
<img width="975" height="1278" alt="image" src="https://github.com/user-attachments/assets/4ebd865b-a5bb-466a-b44a-b9ccecef98c4" />

Enhanced Python artifact: function to show the top 10 high scores in a new High Scores screen:
<img width="975" height="608" alt="image" src="https://github.com/user-attachments/assets/4797c622-2016-45b2-b249-94905c23c976" />
<img width="900" height="813" alt="image" src="https://github.com/user-attachments/assets/21bb6cd0-e6be-4515-9fd7-20075c985f22" />

Enhanced Python artifact: function to wipe all high scores:
<img width="938" height="432" alt="image" src="https://github.com/user-attachments/assets/9b70f03e-7c81-453d-a1bf-18ad019dfb4a" />
<img width="757" height="170" alt="image" src="https://github.com/user-attachments/assets/9071b512-95a9-4dc0-844b-240effe54a20" />

Enhanced Python artifact: feature added for players to input their names for high scores
<img width="701" height="103" alt="image" src="https://github.com/user-attachments/assets/d1ff0e88-f5ca-4157-8bb8-383f270d4857" />
<img width="975" height="678" alt="image" src="https://github.com/user-attachments/assets/61821f34-515b-4bac-b7b3-42668728f8c4" />

3.	Did you meet the course outcomes you planned to meet with this enhancement in Module One? Do you have any updates to your outcome-coverage plans?

I have met the planned course outcomes for this enhancement, course outcome 1 “employ strategies for building collaborative environments that enable diverse audiences to support organizational decision making in the field of computer science” and course outcome 5 “develop a security mindset that anticipates adversarial exploits in software architecture and designs to expose potential vulnerabilities, mitigate design flaws, and ensure privacy and enhanced security of data and resources” (SNHU).
For course outcome 1, I employed strategies for building collaborative environments by creating and implementing a relational database for my application that stores player data that can both be contributed to and consumed by a diverse audience across organizations to aid in decision making. This means that groups outside of engineering can read from the database to inform decisions on direction of the application and the impact on the organization or the broader field of computer science. For example, the development team can view player metrics to inform refinements to game difficulty, a marketing team can use the database to determine how well marketing campaigns are working for player engagement and growth, a finance group can see how many users are repeat customers compared to new users, and an IT group can see how many total users the application has to inform decisions affecting deployment or migrations.
For course outcome 5, I developed a security mindset that anticipates adversarial exploits in the application by paying close attention to sanitizing user input to prevent exploits like SQL injection attacks. I mitigate the design flaws of SQL, with it being vulnerable to injection attacks, by ensuring all user input is sanitized and by binding all data read by SQL queries to the ‘?’ placeholder (Python). To safeguard user privacy, enhance security, and ensure the integrity of resources like the database, I utilize parameterized queries when connecting to the database (W3 Schools).
I do not have any updates to my outcome-coverage plans. I ended up changing my implementation of databases from MySQL to SQLite to simplify the project, which was a slight deviation from my original enhancement plan, but this did not affect my course outcome-coverage plan. By completing this enhancement, I will have completed all five course outcomes for this capstone.

4.	Reflect on the process of enhancing and modifying the artifact. What did you learn as you were creating it and improving it? What challenges did you face?

Developing the enhancements made for this milestone was rather straightforward, but I did struggle quite a bit near the beginning when implementing the SQL database. Originally, in my enhancement plan from module one, I wrote that I was going to use MySQL, so I went forward this week trying to build that out. This was challenging, but I ended up getting it working locally. This process made me realize that it would be difficult (and likely annoying) for other users to get my application running since they would need to set up a MySQL server for my application to communicate with, and this could be avoided if I went with a serverless SQL database. I chose to deviate from my original plan of MySQL and use Python’s SQLite library for my database, which provides the same functionality as the goals I stated in my enhancement plan, but was much easier to set up and will make it much easier for other users to use my application. I feel SQLite is a much better choice for my application due to the portability of SQLite, with it being integrated directly into Python, and the limited need my application has for a database, as it is only tracking local scores. This move to SQLite was a definite improvement over my original plan.
