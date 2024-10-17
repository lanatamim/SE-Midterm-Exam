# SE-Midterm-Exam  
*You are going to do so good on this midterm!!*  

## Version Control  
Version control is a tool (usually a piece of software) that will keep track of changes to your files and help you coordinate different developers working on different parts of your system at the same time.

**Job**  
- Coordinating source code for a particular release
- Collecting metrics on software productivity
- Studying the process of development
- Informing non-developers of the current state of the source code
- Bringing new and absent developers up to date  

**Commit Messages**  
The git commit messages must be in the proper form, such as:
- Use the imperative mood in the subject line, e.g., Fix, not Fixed, Fixing
- Capitalize the subject line, e.g., Fix, not fix
- Do not end the subject line with a period, e.g., Fix spelling of "calendar", not Fix spelling of "calendar".

**Branches**  
- Branches are copies of your code that you can make changes to without affecting code in the trunk. Won't affec the final version until implemented.
- Only use for radical changes to development, not code that can be implemented through file seperation.
- Copies of an object under version control that can be modified separately and in parallel.  

## Good-enough Design  
*"Perfect is great, but I deliver."*
*Good-enough design helps you deliver. It include refactoring the design to make the team more productive.*  

**SRP: Single Responsibility Principle**  
- Every object in your system should have a single responsibility, and all the object’s services should be focused on carrying out that single responsibility.
- A module should be responsible to one, and only one, actor.  
- Bigger classes, but less classes.
- I make sure that all the parts of your software have one well-defined job.

**DRY: Don't Repeat Yourself**  
- Have each pieve of information and behavior in the system in a single, sensible place.
- I help you make sure that everything has its place, and that place is only one place.  

**Compare and Contast SRP & DRY**  
- They are related and work in conjuction ensure functionality.  
- DRY is about putting a piece of functionality in a single place, such as a class; SRP is about making sure that a class does only one thing, and that it does that one thing well.  

## Big Board

- Dashboard on the wall that tracks what is in the pipeline, what is in progress, and what is done.
- Displays burn down and user stories.

## Velocity  

- Accounts for overhead; percentage of the day where you actually developing.  
- Higher velocity means there is more time of project work during the work day
- Lower velocity means there is less time of developing during the work day.  
- Best to be on the conservative side; how much your team works, for real.

## Utopian vs. Real-world Days  

**Utopian Days**  
- Programmers think in utopian days  
- Better-than-best case scenario  
- Underestimating  

**Real-World Days**  
- Developers think in real-world days  
- Accounting for velocity, overhead, deadlines when making estimates  

## Iteration and Deadline Planning  

## Estimation  
Estimates are supposed to realistically lay out a time frame of how long a user story should take. Keep under 15 days for accuracy.  

- Play Planning Poker:  
    - Start by displaying the user story  
    - Each take out a card and pick a number of days you think the user story will take without discussing it  
    - Turn over your cards simueltaneously  
    - Mark down a spread of all team members estimates
    - Discuss the reason for your estimate  
    - Try to eliminate as many assumptions as possible when agreeing on a final estimate  

## Use Case and Use Case Diagram  
Description of a system's behavior as it responds to a request that originates from outside of that system. 
Use cases represent the functional requirements of the system. 

- Previously stated as User Stories
- Describes what the system is supposed to do
- Often is given in English (i.e., not in a formal language)
- If a system does not meet the actual requirements, then it has failed  

![alt text](image.png)

