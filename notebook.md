## Table of Contents

- [Blocks](#blocks)
- [Concepts](#concepts)
- [Vocabulary](#vocabulary)
- ## Blocks
 Hat Block
Name: Hat Block

Shape/Type: Rectangular b lock with a rounded top

What It Does: Starts a VEX VR program. It is usually the first block in a project and tells the VR Robot when to begin running the code.

Example: When started begins the program when you run the project.

 Stack / Command Block
Name: Stack / Command Block

Shape/Type: Rectangular block that connects to other blocks above and below it

What It Does: Gives the Robot an instruction. Multiple command blocks can be connected to create a sequence of actions.

Example: Drive forward for 500 mm tells the Robot to drive forward 500 millimeters.

 C-Block
Name: C-Block

Shape/Type: C-shaped block

What It Does: Holds other blocks inside it. C-blocks are used when you want a group of commands to run as part of a loop or decision.

Example: Commands placed inside a repeat block will run repeatedly.

Reporter / Oval Block
Name: Reporter / Oval Block

Shape/Type: Oval-shaped block

What It Does: Gives information or a value that another block can use. Reporter blocks can provide things such as the VR Robot's position, distance, or sensor information.

Example: A block that reports the distance from an object can be used to determine how far the VR Robot is from something.

 Boolean / Hexagonal Block
Name: Boolean / Hexagonal Block

Shape/Type: Hexagonal-shaped block

What It Does: Gives a TRUE or FALSE answer. Boolean blocks are commonly used as conditions in decision-making blocks.

Example: A condition such as is the distance sensor less than 100 mm? can report TRUE or FALSE.

 Repeat Block
Name: Repeat Block

Shape/Type: C-shaped loop block

What It Does: Runs the commands inside it a specific number of times.

Example: A repeat 4 block containing turn right 90 degrees can make the VR Robot turn in a square pattern.

 Wait Until Block
Name: Wait Until Block

Shape/Type: Stack block with a hexagonal condition space

What It Does: Makes the VR Robot pause until a specified condition becomes TRUE. It needs a condition that can be checked as TRUE or FALSE.

Example: wait until distance sensor is less than 100 mm makes the VR Robot wait until it gets close enough to an object.

 If Then Block
Name: If Then Block

Shape/Type: C-shaped decision block with a hexagonal condition space

What It Does: Checks a condition. If the condition is TRUE, the VR Robot performs the commands inside the block. If the condition is FALSE, the commands are skipped.

Example: if distance sensor < 100 mm then → stop driving.

 Forever Block
Name: Forever Block

Shape/Type: C-shaped loop block with a rounded bottom

What It Does: Repeats the commands inside continuously while the program is running. It is useful when the VR Robot needs to constantly check sensors or perform an action.
## Concepts
Sequence
What It Means: The order in which commands are run in a program.

In My Own Words: The VR Robot follows commands in the order they are placed, so changing the order can change what the robot does.

Example: If the robot is told to drive forward and then turn right, it will drive first and turn second. If the commands are switched, the robot will turn first.

 Parameters
What It Means: Inputs that change how a command works.

In My Own Words: Parameters let you choose things like how far, how fast, or how long the VR Robot should perform an action.

Example: Changing drive forward 200 mm to drive forward 500 mm makes the VR Robot travel farther.

 Loops / Iteration
What It Means: Repeating a set of instructions multiple times.

In My Own Words: Loops save time because I can tell the VR Robot to repeat commands instead of writing the same commands over and over.

Example: A repeat 4 loop containing drive forward and turn right 90 degrees can make the VR Robot drive around a square.

 Sensors
What It Means: Devices or tools that allow the VR Robot to collect information about its environment.

In My Own Words: Sensors help the VR Robot "see" or detect what is around it so the program can respond.

Example: The Distance Sensor can detect how far an object or wall is from the VR Robot.

 Booleans & Conditions
What It Means: A Boolean is information that can only be TRUE or FALSE. Conditions are questions that produce one of these answers.

In My Own Words: The VR Robot can use TRUE or FALSE information to decide what to do next.

Example: Is the distance less than 100 mm? can be TRUE or FALSE.

Sense → Think → Act
What It Means: A robot gets information, makes a decision based on that information, and then performs an action.

In My Own Words: The VR Robot senses something, decides what it means, and responds.

Example: The Distance Sensor detects a wall (Sense) → the program determines the robot is too close (Think) → the robot stops (Act).

 Comparisons
What It Means: Comparing two values using symbols such as <, >, or =.

In My Own Words: Comparisons help the program determine whether one value is smaller, larger, or equal to another value.

Example: distance < 100 asks whether the distance is less than 100 mm. The answer is TRUE or FALSE.

 Coordinates
What It Means: X and Y values that describe a location on the VEX VR Playground.

In My Own Words: Coordinates tell the program where the VR Robot is located on the grid.

Example: If the robot's position is X = 3, Y = 2, those two values identify its location on the Playground.

 Conditionals
What It Means: Programming structures that allow a program to make decisions based on conditions.

In My Own Words: Conditionals let the VR Robot choose what to do depending on whether something is TRUE or FALSE.

Example: if <distance < 100> then → stop driving. The robot only stops if the condition is TRUE.

 Patterns
What It Means: Repeated actions or behaviors that can be recognized and used to create an algorithm.

In My Own Words: If I notice that the VR Robot keeps doing the same group of actions, I can use a loop or a simpler algorithm instead of repeating every command.

Example: If the robot needs to drive forward, turn right, drive forward, turn right several times, I can recognize the pattern and use a repeat loop to make the code shorter.
## Vocabulary
VR Robot + Playground
Terms: Robot, Playground

What It Means: The Robot is the virtual robot that you program in VEXcode VR. The Playground is the virtual environment where the Robot moves and completes challenges.

In My Own Words: The Robot is what I control with code, and the Playground is the virtual world where it operates.

Example: I can program the Robot to drive through a maze on the Playground.

Programming Language + Project
Terms: Programming Language, Project

What It Means: A Programming Language is a system used to write instructions for a computer or robot. A Project is the collection of code created to make the Robot perform a task.

In My Own Words: The programming language is how I communicate instructions to the Robot, and the project is the code I create.

Example: I can create a VEXcode VR project using blocks to solve a maze.

Behavior + Command
Terms: Behavior, Command

What It Means: A Behavior is an action or response performed by the Robot. A Command is an instruction that tells the Robot what to do.

In My Own Words: Commands tell the Robot what to do, and the behavior is what the Robot does because of those commands.

Example: The command drive forward causes the Robot to move forward.

Drivetrain
Terms: Drivetrain

What It Means: The Drivetrain is the part of the Robot that controls its movement, including driving and turning.

In My Own Words: The drivetrain is what allows the Robot to move around the Playground.

Example: I can use drivetrain commands to make the Robot drive forward 500 mm and then turn right.

Loop + Iteration
Terms: Loop, Iteration

What It Means: A Loop repeats a group of commands. Iteration means one cycle or repetition of those commands.

In My Own Words: A loop makes the Robot repeat instructions, and each time the instructions repeat is an iteration.

Example: A repeat 4 loop has four iterations of the commands inside it.

Sensor + Bumper Sensor
Terms: Sensor, Bumper Sensor

What It Means: A Sensor allows the Robot to collect information about its environment. A Bumper Sensor detects when the Robot's bumper is pressed or comes into contact with something.

In My Own Words: Sensors help the Robot gather information, and the Bumper Sensor can tell the program when the Robot has bumped into something.

Example: The Robot can use the Bumper Sensor to detect when it reaches a wall.

Boolean + Condition + TRUE/FALSE
Terms: Boolean, Condition, TRUE, FALSE

What It Means: A Boolean is a value that can only be TRUE or FALSE. A Condition is a question or test that produces a Boolean answer.

In My Own Words: A condition asks the Robot a question, and the answer is either TRUE or FALSE.

Example: Is the Bumper Sensor pressed? can return TRUE if it is pressed or FALSE if it is not.

Distance Sensor + Threshold
Terms: Distance Sensor, Threshold

What It Means: The Distance Sensor measures how far the Robot is from an object. A Threshold is a value used as a limit for making a decision.

In My Own Words: The Distance Sensor tells the Robot how far away something is, and the threshold gives the Robot a number to compare that distance to.

Example: If the threshold is 100 mm, the program can check whether the Distance Sensor detects an object closer than 100 mm.

Coordinate Plane + X/Y Coordinates
Terms: Coordinate Plane, X-axis, Y-axis, X-coordinate, Y-coordinate

What It Means: A Coordinate Plane is a grid used to describe locations. The X-axis shows horizontal position, and the Y-axis shows vertical position. The X-coordinate tells the position along the X-axis, while the Y-coordinate tells the position along the Y-axis.

In My Own Words: Coordinates give the Robot a way to describe exactly where it is on the Playground.

Example: A location such as (3, 2) means the X-coordinate is 3 and the Y-coordinate is 2.

Location Sensor
Terms: Location Sensor

What It Means: The Location Sensor provides information about the Robot's position and orientation on the Playground.

In My Own Words: The Location Sensor helps the program know where the Robot is and which direction it is facing.

Example: A program can use the Robot's X and Y location to determine when it has reached a certain area of the Playground.

Comment
Terms: Comment

What It Means: A Comment is a note added to code to explain what part of the program does. Comments do not control the Robot.

In My Own Words: Comments help me and other programmers understand what my code is supposed to do.

Example: I can add a comment saying "Drive to the blue wall" above the commands that move the Robot there.

Eye Sensor
Terms: Eye Sensor

What It Means: The Eye Sensor detects colors and objects in the Robot's environment.

In My Own Words: The Eye Sensor helps the Robot identify what it sees so the program can make decisions.

Example: The Robot can use the Eye Sensor to detect a red object and then stop.

Conditional Statement
Terms: Conditional Statement

What It Means: A Conditional Statement allows a program to make a decision based on whether a condition is TRUE or FALSE.

In My Own Words: A conditional statement lets the Robot decide what to do depending on what its sensors or program detect.

Example: If the Bumper Sensor is pressed, then stop driving.



- [Notebook Style Guide](#markdown-style-guide-for-coding-notebooks)

  - [Headings](#headings)

  - [Text Formatting](#text-formatting)
 



## Markdown Style Guide for Coding Notebooks

Follow this guide to keep your coding notebook **clear, consistent, and professional**.  

This ensures your notes are easy for you (and others) to read later.

---

## Headings

**When to use:** Organize your notebook into sections (like days, topics, or projects).  

- `#` for the notebook title (use once at the top).  

- `##` for each day or major topic.  

- `###` for subsections (like "Notes", "Practice", "Reflections").  

# Example:

# My Coding Notebook

## Day 1

### Notes

### Practice

# Text Formatting

When to use: Highlight important ideas or add emphasis.

Use bold for key terms or definitions.

Use italic for emphasis or side comments.

Use inline code for keywords, functions, or commands.

 

# Example:

**Class** = a blueprint for objects  

*Remember:* always test your code  

Use `System.out.println()` to print

 

# Code Blocks

When to use: Anytime you write multiple lines of code.

Inline code for short snippets.

Fenced code blocks with language for full examples.

# Example:

```java

public class Hello {

    public static void main(String[] args) {

        System.out.println("Hello World!");

    }

}

```

# Lists

When to use: Organize steps, notes, or key points.

Numbered lists for sequences or steps.

Bulleted lists for unordered ideas.

# Example:

Define the class
Write the main method
Test your program
Variables

- Loops

- Conditionals

 

# Checklists

When to use: Track progress on assignments or tasks.

# Example:

[x] Complete coding warm-up

- [ ] Finish project draft

- [ ] Reflect on learning

 

# Blockquotes

When to use: Call out notes, reminders, or teacher comments.

# Example:

> 💡 Remember: Loops repeat code until a condition is false.

 

# Tables

When to use: Compare values, track progress, or organize data neatly.

# Example:

| Task        | Status   | Notes          |

|--------------|------------|-----------------| 

| Homework 1  | Done #  | Submitted      |

| Homework 2  | Pending  | Needs review   |

 

# Links & Images

When to use: Add references, resources, or visuals.

# Example:

[Java Docs](https://docs.oracle.com/javase/8/docs/api/)  

![Markdown Logo](https://upload.wikimedia.org/wikipedia/commons/4/48/Markdown-mark.svg)

To make an image that is a link, paste the image, then add the following before it, replacing website address with the link:

<a href="website address">

And after the image info, add: </a>

# Collapsible Sections

When to use: Hide solutions, extended notes, or extra details.

# Example:

<details>

  <summary>Click to reveal solution</summary>

  

System.out.println("Answer: 42");

</details>

 

# Footnotes

When to use: Add references or side notes without cluttering the page.

# Example:

This concept is related to object-oriented programming.[^1]

[^1]: See "Objects and Classes" in your textbook.

 

# Style Rules

Consistency matters more than creativity

Always use headings to structure your notes.

Always use code blocks for multi-line code.

Clarity first

Bold key terms.

Use lists instead of long sentences when outlining steps.

Professional tone

Don’t mix casual notes with formal work in the same section.

Use blockquotes for reflections or teacher feedback.

Track your learning

Use checklists to mark what’s done.

Use collapsible sections if you want to hide answers until review time.

 

# Bottom Line:

Headings = Structure

Bold/Italic = Emphasis

Code blocks = Code

Lists = Steps/Ideas

Tables = Organization

Checklists = Progress

Blockquotes = Notes/Tips

Collapsible = Hide/Show detail

Keep it simple, consistent, and clear.
