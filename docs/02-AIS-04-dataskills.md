

# Data skills

## General information 

- Data Skills Assignment 1 deadline: **December 1st 2023**. Feedback will be returned by December 19th.

- Data Skills Assignment 2 deadline: **December 1st 2023**. Feedback will be returned by December 19th.

- In total, this assessment is worth 15% of your final course grade. Each portfolio submission is worth 7.5% and you will be awarded a mark out of 22.

- There will be separate submission links for each Assignment where you will submit a single .Rmd file to each. You should only submit the .Rmd file.

- The assignment and submission link will be made available one week before the deadline.

## Type of assessment/structure

- Over two data skills assignments we will ask you to complete a series of tasks including general statistical knowledge questions, data wrangling and visualisation tasks, descriptive and inferential statistics tasks, and interpretation questions. Note that this list is indicative and non-exhaustive.

- We will not ask you anything that has not been covered yet in either the lectures or the data skills book.

- Normally there will be approximately 11 questions in each assignment with each question will being worth 1, 2 or 3 marks to sum to the UofG 22 point scale of Schedule A.

## Assessment support

- All the coding tasks you will be asked to do will have been covered in the data skills book, and the activities within the book. Theoretical tasks will have been covered in the lectures, labs, and data skills book. 

- For coding tasks it is important to try the code in the book as you go along and ask questions about what you are doing. This will really help you in the assignments.

- You are free to ask questions regarding the assignment on the available forums, in-class, or in student office hours. However, please do not post answers or code that would be close to giving the answer as this would contravene the University policy on plagiarism. Policies regarding how to use the forums can be found on the main forum pages. If a member of the team needs to see the code you are trying they will ask you for it.

- To avoid confusions: you are allowed to post code when asking questions about a task in the data skills book but you should not post code relating to a question about either of the data skills assignments unless asked to by a member of staff. Again, this is because posting code related to an answer in an assignment could count as plagiarism. 

- When submitting the file make sure that you submit the completed .Rmd file for that lab only. You must include your GUID in the filename, followed by ‘MSc_RM1’ and the Assignment Number. The file that you are given will have most of this information already but when submitted it should read, for example, ‘9804672_MSc_Rm1_Assignment1.Rmd’.

- Please note that these are individual assessments and not groupwork. Whilst we encourage students to work together and learn the skills together, copying and passing each other code and answers by any means will be considered plagiarism and can result in your being reported to Senate.

- Further information about feedback can be found in the [Feedback Information Sheet](#FIS) chapter.

## How to do well in these assignments

- Completing all formative and summative work on the practical data skills. All the assignments build on each other and information within the formative assignments are needed to complete the summative assignments.

- Use the data skills book activities to guide you – in almost all cases the answers to the assignments require using skills that you have already covered in these materials.

- Avoid making changes to the .Rmd file other than to provide answers and your GUID (e.g., avoid deleting backticks, changing code chunk names, not using the file provided).

- Try to use the code that we teach in the book.

- Read the question carefully and ensure that you provide exactly what is asked for (e.g., code or a single value). Do not deviate from what the question asks. You are more than encouraged to practice different approaches in your own time, but for the assignments you should only do what the questions ask.

- Follow the instructions for how to fill out the .Rmd file carefully making sure you do not change anything in the file you shouldn’t.

- Please pay special attention if the question asks for a specific output, e.g. *value* or a *tibble*/*data_frame*; when asked for a *value* as an output, make sure it is a single value and not a value stored in a tibble. Finally, when altering code inside the code blocks, *do not* re-order, rename, or remove the code blocks (e.g. T01, 0T2, ... etc.). If you do, this will impact your grade and may result in you receiving an H grade for this assignment! If you are unsure about any of these points, ask a member of staff.

- Test that the .Rmd file you are submitting is reproducible, after completing it, by "knitting" it as an html file. This also shows what you've accomplished and allows you to spot potential errors. If your code does not knit, this may result in you receiving an H grade for this assignment.

- A great test of your code is to close R Studio, restart it, open and knit your code, see that it runs, and go through it to make sure it is correct. This will test whether you have remembered to include essential elements, such as libraries, in your code. This does not mean that your code is correct, however, it simply means that your code runs. You need to check the output and compare to the question to see that it matches.

- When loading in data, you must use a relative path as opposed to an absolute path.  Relative would mean having the datafile in the same folder as the .Rmd file and just calling the datafile when reading it in, e.g. `read_csv("data.csv")`. Absolute would be using a path specific to the folder structure of your computer, e.g. `read_csv("C:/PhilsComputer/PhilsFolder/data.csv")`. Only use relative paths and under no circumstances should you rename the datafile from the one we tell you to use. Note that “data.csv” is a different name from “data (1).csv” and different from “data_1.csv”. Only use the name we give you.

- The following functions are considered forbidden and must not appear anywhere in your code at all.  Inclusion of them in your code may result in you receiving no marks for the assignment. The functions are: `install.packages()`, `help()`, `vignette()`, `setwd()`,`help.start()`, or `View()`.

- Read the feedback you are given!

- Collate your notes and learn from your mistakes. These assignments are weighted low in order to allow you the space to make mistakes and to not have a major impact on your overall course grade. It is imperative that you take this opportunity. 

- Refer back all the time to what you have done previously. The skills stay the same; only the data changes.

## Common Mistakes

- Changing the .Rmd file other than to provide answers and your GUID.

- Changing the name of the datafile to something other than the one we provide – e.g. “data.csv” and “data (1).csv” are two different files.

- Using code that is very different to that taught in the book. We will check any incorrect answers and if you have used different code that produces what is asked you will still get the mark, however, using different code from the book increases the risk that you will produce a different output to the one intended. 

- Failure to follow instructions (e.g., writing code when a single value was requested).

- Including any illegal code in your .Rmd file, e.g., install.packages (you should never write code that would change something on someone else’s machine, it causes issues and it’s impolite!). 
- We always ask students to use the function `read_csv()` to load in data yet students often use `read.csv()`. There is a difference between the output these create so always do what the questions ask.

- Be very careful with spelling. For example, UK is not the same as Uk. Do what the questions ask.

- Never do more than what the question asks. We check the output of a task to see that it matches what we expect. If it does not match what we expect then it is wrong. Remember the point is about being reproducible and replicable. Think of this in terms of you are sending your good to a colleague who expects a certain thing, and if your code works differently then that is not good practice.

- Try things out in the console and in your own scripts but only put your final answers in the .Rmd.

- Failing to read your feedback from previous assignments.

- Failing to check that your code knits before submitting it.

- Failing to check that you are submitting the right file. Only one submission is allowed per lab.

## How is the assessment related to the lectures for this course?

These practical data assignments assess your ability to wrangle and visualise data in an open and reproducible way, to interpret and work with data, to understand analysis and research methods, and to present studies in a professional manner, as discussed in the lecture series. Whilst these assignments are of course most closely related to the Research Methods and Statistics lectures, understanding data and analysis will help with your critical evaluation of research in all fields of Psychology. By understanding where the results come from will give you a much deeper approach to critically assessing the claims of the research.

## Why am I being assessed like this?

The practical skills taught through these assignments are very important for psychological researchers to develop in order to understand analysis, methods, and research. Your skills will progress throughout your degree, but the best approach to developing these skills is through regular continuous assessment. Much like learning a language, more practice over a longer period of time will give you better results than cramming at the last minute. Continual regular practice is better than one big chunk. As such, these assignments ensure that you are maintaining a steady and solid rate of progress. 

## How does this relate to previous work I have completed?

- The individual and generic feedback from previous assignments, and solutions for these assignments will help you complete these assignments. In addition, the data skills book activities will really help you in completing these assignments. You should not overlook the importance of these formative tasks.

- Don't forget that asking questions on the forums or speaking with GTAs and team members in labs is also giving you feedback and feedforward and will help you complete this assessment.

## Feedback information
