# SE-Midterm-Exam  
*You are going to do so good on this midterm!!*  

## Version Control  
*Version control is a tool (usually a piece of software) that will keep track of changes to your files and help you coordinate different developers working on different parts of your system at the same time.

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