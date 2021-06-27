# CS230_James_Porter
This repository is used for the CS 230 GitHub requirement created in week 7 and filled in week 8.

**Briefly summarize The Gaming Room client and their software requirements. Who was the client? What type of software did they want you to design?**
The Gaming Room has developed a game called Draw It or Lose It which is currently only offered as an Android application. The Game Draw It or Lose It is like the game show Win, Lose or Draw where teams alternate taking turns guessing the picture that is being drawn. If the team doesn't guess the picture in time (30 seconds) the opposing team gets a short amount of time (15 seconds) to guess right and steal the point. The Gaming Room has asked for help in streamlining the development to make the game Draw It or Lose it available as a web-based application.
They also have some requirements for the game that we have needed to implement in out planning document. First and foremost, there must only be one instance of the game service available at a time. To complete this requirement, we used the singleton pattern to ensure that only one instance of the game is ever created. As for the number of games, teams, and players, there could be as few as 0 (none) to as many instances of each as desired. This relation where there can be any number of instances is often referred to as zero to many. These three classes are also related to each other such that each game service can have zero to many instances of games, each game can have zero to many instances of teams, and each team can have zero to many instances of players. Additionally, each team, game and player are required to have a unique identifier. Lastly, the web-based application was required to be available across multiple platforms for multiple users. 

**What did you do particularly well in developing this documentation?**
I feel like I did a very good job with my recommendations and my domain model for this project. I struggled with a lot of it, but these were the sections that I both scored well in (when accounting for instructor feedback) and the sections that I understood the most. The other sections I struggled with a little more and as such, I don't think that they reflect the areas of this assignment that I did well on.

**What about the process of working through a design document did you find helpful when developing the code?**
The process of working through a design document allowed me to take a step back and work through how the code should work before writing any code. This greatly reduces the amount of time required to write the code and reduces the number of times you must rewrite and fix mistakes. If you were starting to work on this code before writing this document, you could end up having to rewrite the code multiple times and waste a lot of time on these rewrites.

**If you could choose one part of your work on these documents to revise, what would you pick? How would you improve it?**


**How did you interpret the user’s needs and implement them into your software design? Why is it so important to consider the user’s needs when designing?**


**How did you approach designing software? What techniques or strategies would you use in the future to analyze and design a similar software application?**
