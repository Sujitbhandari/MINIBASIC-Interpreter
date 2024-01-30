# MINIBASIC-Interpreter

Objective:
Create a Java program to serve as a MINIBASIC interpreter, capable of reading, simulating, and executing programs written in a simplified MINIBASIC programming language. The MINIBASIC language comprises simple statements, conditional statements, and an end-of-program marker.

Key Features:

File Selection and Execution:

Users are prompted with a file dialog to select an input file containing MINIBASIC code.
The program reads and executes the MINIBASIC program, displaying the output in a scrollable console text area.
GUI Controls:

The graphical user interface (GUI) includes control buttons such as Read, Run, Save, and Reset.
"Read" allows users to choose another file containing a MINIBASIC program for execution.
"Run" initiates the execution of the loaded MINIBASIC program.
"Save" enables users to save edits made to the program.
"Reset" clears the displayed program and console for subsequent operations.
Independent Code Display Frame:

The GUI features a separate frame that displays the MINIBASIC program code, resembling a console.
The code display frame enhances user interaction by providing a clear view of the loaded program.
Editing and Re-execution (Extra Work):

Optionally, users may edit the MINIBASIC code directly in the displayed frame.
A "Save" button saves edited code, and a "Reset" button clears the console for subsequent runs.
Implementation Notes:

Utilize Hashtables or Vectors for both the code and symbol table.
Ensure thorough documentation, appropriate variable naming, and the use of classes, extensions, and constructors.
Handle spaces in if, goto, and print statements during program execution.
Include exception handlers and proper javadoc documentation for classes.
Testing Notes:

Test the program with various MINIBASIC programs, including loops, conditional statements, and complex expressions.
Execute specific test cases, such as a loop adding 5 in each iteration and an endless loop, to validate program functionality.
Assess the interpreter's ability to handle complex expressions, like the provided example (c = 5; a = 56 * (78/c) / (56+6)).
