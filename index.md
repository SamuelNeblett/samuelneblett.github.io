# Professional Self-Assessment
_In work..._

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

# Enhancement One: Software Design and Engineering - Narrative
1.	Briefly describe the artifact. What is it? When was it created?
The artifact selected for the Software Design and Engineering enhancement is a Breakout-like game where the player moves a paddle at the bottom of the screen and launches balls towards bricks to break them with the goal of clearing the screen. The original artifact, before my enhancements, was a C++ project created for the 8-2 Assignment: Coding Collisions assignment in CS-330 Computational Graphics and Visualization. This project was originally created on May 26th, 2026.
2.	Justify the inclusion of the artifact in your ePortfolio. Why did you select this item? What specific components of the artifact showcase your skills and abilities in software development? How was the artifact improved?
This artifact was chosen for my ePortfolio because it demonstrates my knowledge of both C++ and Python, as well as my ability to port a project from one language to another. I selected this item because I currently work in real-time app and game development, but I primarily build applications within the Unity and Unreal engines, so the inclusion of this application demonstrates my ability to work outside of the constraints of game engines for developing real-time applications. Specifically, I want to showcase my ability to create game loops outside of game engines, which this project allows me to do. I also want to showcase my knowledge of Python, which is a language that I have not had much experience using in the professional space. This artifact was improved from its original state by porting it to Python, a more user-friendly and readable language compared to C++. Multiple new features were added during this enhancement including the inclusion of GUI elements for a Main Menu, score tracking, life tracking, level progression across 3 levels, and new brick properties that allow for multiple hits before being destroyed. 
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
<img width="791" height="495" alt="image" src="https://github.com/user-attachments/assets/b6c8f42c-38f4-47e0-b3d6-1e2980557be5" />
<img width="922" height="1350" alt="image" src="https://github.com/user-attachments/assets/adc30a74-3854-4766-824c-670e6fd8496f" />
<img width="679" height="1350" alt="image" src="https://github.com/user-attachments/assets/4065d6f0-4287-4671-9e4a-a157da1f566b" />

Enhanced Python artifact – ball (originally named “Circle”) now uses velocity and calculates reflection trajectory:
<img width="934" height="432" alt="image" src="https://github.com/user-attachments/assets/d6dff3fb-37cf-4b8e-917b-3ce6aec8e133" />
<img width="635" height="1350" alt="image" src="https://github.com/user-attachments/assets/1069101c-df16-4cee-beb4-490a2501bb5f" />
<img width="781" height="917" alt="image" src="https://github.com/user-attachments/assets/9b385d24-0d98-4a87-bab7-e395473f549a" />

Original C++ artifact for CS-330 – collision checking for reflective bricks:
<img width="975" height="1266" alt="image" src="https://github.com/user-attachments/assets/2b1669d1-b5dd-4dae-a212-94d7ff9e0080" />

Enhanced Python artifact – AABB collision checking, logic split to handle brick and paddle differently:
<img width="653" height="1350" alt="image" src="https://github.com/user-attachments/assets/99048eac-1a43-4107-a654-dc75e2aa53c6" />
<img width="954" height="1323" alt="image" src="https://github.com/user-attachments/assets/75d5c130-cb4d-4445-9e80-05834c9533cf" />
<img width="823" height="906" alt="image" src="https://github.com/user-attachments/assets/0587a878-21dd-4df1-8d08-e44aed8328e3" />
<img width="885" height="545" alt="image" src="https://github.com/user-attachments/assets/7ad536ec-8d5f-40fe-9798-ea0d228259f8" />

Original C++ artifact for CS-330 – paddle defined as a brick type data structure, with a paddle being three different bricks:
<img width="945" height="1185" alt="image" src="https://github.com/user-attachments/assets/ce8b730c-172e-4b87-adf8-679c86edfea7" />
<img width="975" height="163" alt="image" src="https://github.com/user-attachments/assets/37a74c49-9eb4-42ff-accd-1d200532511c" />

Enhanced Python artifact – paddle data structure created (distinct from brick types), player score data structure created to hold scores:
<img width="797" height="635" alt="image" src="https://github.com/user-attachments/assets/d80597f1-f45d-40e7-98e5-4fdb9c07dcc2" />
<img width="873" height="78" alt="image" src="https://github.com/user-attachments/assets/2e2de752-5f04-44db-b5f8-a8cb8213da9d" />
<img width="975" height="383" alt="image" src="https://github.com/user-attachments/assets/cc42b8c6-01ee-4471-8d81-b4db32594120" />

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
