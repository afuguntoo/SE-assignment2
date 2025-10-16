# SE-assignment2: Version Control Using GitHub

## 1. Overview
This repository demonstrates a practical implementation of Git and GitHub for collaborative software development. It shows the use of branches, pull requests, and conflict resolution to manage multiple features while collaborating with others. 

The project simulates a simple console-based interaction where users can introduce themselves and state their goals. 


## 2. Branches and Features
- **Feature-1:** Basic “Hello, World!” program with an additional greeting.
- **Feature-2:** Updated greeting message to simulate a merge conflict.
- **Feature-Introduction:** Allows users to input their personal introduction.
- **Feature-Goals:** Allows users to input and display their goals.
- **INDIGZZZ-patch-1:** Used to whish a user a nice day (added by a classmate: EmmanuelAli)


## 3. Issues and Resolutions
During development, the project addressed two main features:

- **Introduction Section:** Implemented a user input feature that allows users to enter and then display their personal introduction.
- **Goal Section:** Added functionality for users to input both short-term and long-term goals, which are then printed later.
- **RESOLUTION:** Both sections were successfully integrated into the program, ensuring full interactivity and functionality. 


## 4. Workflow Summary
This project follows a structured Git workflow:
1. Created separate branches for new features.
2. Committed incremental changes to each branch.
3. Opened pull requests for code review and merging them to the main branch.
4. Resolved merge conflicts manually when branches modified the same code lines.
5. Added a teammate as a collaborator to contribute their section of the code.

After merging all features, the final version of the program successfully integrates all functionalities without conflict.


## 5. Final program (Python)

print("Hello, World!") <br>
print("Hi!, Conflict solved") <br>

#EmmanuelAli<br>
print("Have a nice day")<br>

print("Hi! Joaquin Owono")<br>
print("Hi! Feature-2 Version")<br>

intro = input("Please, introduce yourself: ")<br>
print(f"Introduction: {intro}")<br>

goals = input("Enter your goals: ")<br>
print(f"Goals: {goals}")<br>

