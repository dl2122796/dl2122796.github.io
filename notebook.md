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

6. Sense → Think → Act
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
