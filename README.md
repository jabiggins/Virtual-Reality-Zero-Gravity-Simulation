# Virtual-Reality-Zero-Gravity-Simulation
The code behind my group's 2018 submission to Maryland's "Bitcamp" hackathon


This repository serves as a record for the C# code that was required in order to complete the "GG0G" or "Good Game Zero Gravity" hackathon submission
to the Bitcamp hackathon at the University of Maryland. There are two important things to note:

1) All of the VR integration was done using imported prefabs that I claim NO ownership of; my job was making those componenets work
    for our specific project. As such, there is very limited C# code that I can show.
2) The script that instantiates and manages the forces that are needed to move the user in the 3D 0-gravity environment is provided
    for context, but since I was not directly responsible for its creation(two other teammates worked on it), I claim only organizational 
    and debugging credit.

So what did I do? As stated above, there are many parts of this project that are done in the Unity Editor, from positioning 3D assets that
I found on the store and positioned, to setting up the Unity environment for the Oculus Rift, to many other tasks. I did around 80-90%
of the editor work.  The code that I did write is found in the other two scripts provided. These scripts handled keyboard input to reset the user if 
they got stranded in the middle of space(yes the simulation was that realistic) and also creating a GUI that displayed the necessary 
information for the other group members to properly debug the physics forces script.

For those curious about how we simultaneously worked on the same Unity project, I organized Unity's "team collaboration" serice to store
the current version of the simulation on the cloud and push changes to other members. GitHub was not used in this projects creation.

--James Biggins
