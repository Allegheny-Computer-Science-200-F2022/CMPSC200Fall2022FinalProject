## Requirements

## Honor Code Policy

It is required for all students to follow the honor code. Some important points from the class honor code are outlined below for your reference:

Students are not allowed to share code files and/or other implementation details outside their team. It is acceptable to have a healthy discussion with your peers. However, this discussion should be limited to sharing ideas only. 

Submitting a copy of the other team's program(s) is strictly not allowed. Please note that all work done during this project will be an opportunity for team members to learn, practice, and master the materials taught in this course. By doing the work individually, and within their team, students maximize the learning objectives.
\end{enumerate}

At any duration during and/or after the project, students are recommended to team up with the Professor and/or the Technical Leader(s) to clarify if there is any confusion related to the items in the project sheet and/or class materials. 

Include all your team member names in the Honorcode file. 

## Things to keep in mind
1) The course project must have a significant implementation and written part where you will develop and expand on the course topics covered this semester. The total points for this project is 100 and has a weight of 15% towards the final course grade. 

2) The course project must be extensive enough to qualify as a final project (think of work for at least 2 to 3 one-week lab assignments), but not too extensive so that you cannot finish it in the remainder of the semester.

3) The lab period after this initial project session meeting, is on December 1st and December 8th. It is highly recommended to attend these two sessions to catch up with your team, work on the project together, and make sure to plan and complete all the requirements and deliverables by the due date. 

## Project Options

There are three tracks for the final project, namely, Track 1, Track 2, and Track 3. Of course, if a student would want to pursue a completely different track, this option is also available. Consult with and get the Professor's approval, if you like to develop a new idea. 

Project Track 1 - Low-end Programming Computing Tool in C

The course project in this track must solve one or more low-end computing problems, programmatically using either C programming language or MIPS or both. This track is chosen by teams who want to do the project in pure programming front using C. 

A few examples, of what we did so far in this direction, are to implement the shift, binary addition, and subtraction operators, and converters such as binary to decimal and decimal to binary. In this track, it is important to focus on low-end computing tasks and simulate the execution of those tasks through one or more programs implemented in C and/or MIPS. 

A few examples of course projects that were done by the previous batch of students:

(a) Implement a basic version of a scientific calculator, from scratch, with the ability to compute addition, subtraction, multiplication, division, logarithms, exponents (power operator), etc. in C and/or MIPS programming language. In this project, these operators should be developed from scratch. For example, multiply and divide operators should be implemented using the multiply and divide algorithms discussed in class. Addition and Subtraction operators should be implemented using the techniques discussed in our lessons. It is worth noting that the power operator is repeated multiplication, and the logarithm operator is repeated division. In this project, users should be presented with a command-line interface to easily perform any scientific calculations using the operators outlined above. This project assumes the built-in mathematical and the operators in math.h library does not exist. This is a very good practice to master the low-end technical concepts and to further refine your C, MIPS programming skills learned in this course.  

(b) Implement an advanced data converter, from scratch, that performs a conversion using binary, decimal, and hexadecimal notations. That is, binary to decimal, decimal to binary, binary to hexadecimal, hexadecimal to binary, decimal to hexadecimal, and hexadecimal to decimal notation. The input and output data may be represented using an array for binary and hexadecimal notations. 

Project Track 2 - Computing Tool in C, Logism, and Mars

The course project in this track must solve one or more computing problems, both programmatically and logically using  C programming language, Assembly language using Mars, and Circuit Development using Logisim. This track is chosen by teams who want to have a diversified experience in their course project that includes both programming and logic circuit development.

A few examples, of what we did so far in this direction, are to implement use cases such as temperature classification, recommend actions during rainfall, compare the full match and partial match, etc. In this track, it is important to focus on small-scale computing tasks (real-world examples) and implement them in all three platforms. 

A few examples of course projects that were done by the previous batch of students:

(a) Implement the Rock Paper Scissors game using C, Mars, and Logisim. Here there are two persons providing their inputs for rock, paper, and scissors each. The inputs are 1/0 and each person's input could be using 3 bits (RPS) to show their Hand. 
For example a scheme of inputs could be 
100 -> Rock; 010 -> Paper; and 001 -> Scissors. 

The output of the circuit could be Win, Loss, and Tie. A circuit is developed by designing and formulating the logic based on the truth table used for the rules of the game. The general rules of an RPS game are as follows:

1) Rock wins against scissors
2) Paper wins against rock 
3) Scissors wins against paper 
4) If both players throw the same hand signal, it is considered a tie.

An advanced version of this circuit may use a counter to keep track of how many times the number of wins, losses, and ties by a player. There are controls such as counters that can be used to develop such a circuit. This is an advanced feature that may be explored by those who are willing to do some research on their own. A simple working implementation of an RPS game in all three platforms for the two user inputs should already satisfy the requirements to be a project in this track. 

(b) Implement the Tic Tac Toe game using C, Mars, and Logisim.
A simple google search will let you know the rules of the Game. This may be implemented using two person's input with 9 bits each for each of the elements in the grid. The grid used in this game is 3 rows by 3 columns grid. The two outputs should indicate who won. 

Implementing this game in all three platforms involves some thinking, planning, defining assumptions, and implementation. But the final reward is very satisfying to get the implementation done correctly. Again you get a very diversified experience by choosing to work on this track. 

Project Track 3 - Student-Designed Project
Students will develop an idea for their project that focuses on one or more real-world topics in the field of low-end computing. In this track, if you had chosen to implement in C, you are expected to use Dynamic and Heterogeneous Data Stores such as Pointers, and Structs in your implementation. After receiving the course instructor’s approval for your idea, you will complete the project and report on your results. For example, an extension of the songs and FBI program?
If you’re completely stumped in coming up with a project idea, you can certainly talk to me and we will set up a brainstorming session. Be creative and choose something interesting to you!

## Project Deliverables

(1) Proposal – Start developing an idea for your final project. Write a 1-page technical report (single or double spaced) of what you propose to do in your final project and submit a PDF copy of your proposal inside the writings folder through the GitHub link shared. I don’t expect the proposal to be very detailed at this point. But, it should summarize what project you are going to pursue, what you want to do (the real problem you will tackle, how you plan to solve this computing problem, and at least a couple of references to indicate that you have done some research about the problem. It is expected that you use the first project meeting session and the lab period to discuss this within your team and complete most of it within the lab period. Upload your PDF file to the writing directory in the repository.

Deadline: November 17th, 2022, 11:59 PM.
File Type: PDF
File Name: Proposal.pdf
Points: 10 points

(2) Progress Report – Start developing a 3-page technical report (single/double spaced) to document the progress done by the team. By this point, you should have made a good amount of progress towards implementing your project. Were there any unexpected challenges? Did you have to change your initial model/framework or the project skeleton code? Include everything you have done so far in your progress report, even if it is incomplete. No need to include the actual code (unless you want my help with it), just describe what progress you have made with it. Submit a PDF copy of your progress report using the GitHub link shared in the writing directory in the repository. 

Deadline: December 2nd, 2022, 11:59 PM.
File Type: PDF
File Name: Progress.pdf
Points: 20 points

(3) Presentation – Teams should present their course project by recording a 10 minutes video to virtually present their course project. It is expected that students use Slides during their presentation. The link below may be used to do the recordings. OBS is another option to record videos.
https://www.apowersoft.com/free-online-screen-recorder

By the presentation session, you should have finished implementation, run some basic testing, and done some code or circuit overview. In the presentation, you should describe the motivation, problem definition, challenges, approaches, and results and analysis. Use diagrams and a few bullet points rather than long sentences and equations. The goal of the presentation is to convey the important high-level ideas and give intuition rather than be a formal specification of everything you did. Design at least 6 to 10 slides, including a slide with the title of your project and your name. Also, it is required to show a short demo of your tool at the end of the presentation. Team members should contribute equally to the presentation. You may upload one video with an edited version of the different team members presentation or upload separate videos. The presentation slides and video should be uploaded to the following google driver folder using a folder named using your team's name:

https://drive.google.com/drive/folders/1PK62vibg24ZVA3XMdn_SY8W9TcDrzGPj?usp=sharing

Deadline: December 9th, 2022, 11:59 PM.
File Type: any type of your preference (make sure it is acceptable to be uploaded in google drive)
File Name: Slides, Presentation-video
Points: 35 points
 

(4) Final Report and Source code – Start developing a 5-page technical report (single/double spaced) to summarize the technical details of the tool developed by the team. The final report should be clear and well written, which includes no typos or grammatical errors. The report should be written professionally and technically. The report should include the following in the PDF format in the writing directory in the repository. 

(a) The motivation for your project. Why is the problem you decided to solve important or useful?
(b) Background of the proposed problem. What have others done for it already? Include references.
(c) Detailed project overview, a summary of the proposed implementation, and the methodology used. Include pseudocode, diagrams, and examples if appropriate. If you are extending existing work, briefly describe previous work and include references to it.
(d) Conclusion. Give a short overview of your project and its results. Describe what you learned, what were the biggest challenges, and the biggest rewards.

Make sure to upload all your source code files that is [C program (.c) files, Assembly language program (.asm) files, Circuit (.circ) files, and Jar files (logisim, mars)] to the tool directory in the repository. Edit the Readme file inside the tools directory to include detailed steps on how to execute your code, what are the expected input(s), what should be expect to get as output(s) from the program, how should we execute the different programs (commands) and in what order should the programs be executed? Basically, this read file should have all the details about executing your project source code correctly. 

Deadline: December 13th, 2022, 11:59 PM.
File Type: PDF
File Name: Report.pdf
Points: 35 points

## Lab Submission Checklist:
1) Honor code file
2) Source code files in the tools directory.
3) Proposal.pdf in the writings directory.
4) Progress.pdf in the writings directory.
5) Report.pdf in the writings directory.
