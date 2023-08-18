

# Course Overview 2023 / 2024 {#Course_overview}

## Intended Learning Outcomes

By the end of the course you will be able to:

- Understand and apply the principles of open and reproducible science

- Generate and explore hypotheses and research questions for experimental and observational research

- Select appropriate research designs and methodologies for different research questions
Demonstrate critical awareness of the assumptions of these methods and analyses and the limitations associated with experimental and observational research designs

- Identify the ethical issues involved in experimental and observational research

- Work as a group to plan and execute a small-scale research project using quantitative research methods
- Demonstrate critical analysis, evaluation and synthesis of ideas

- Use the programming language R to conduct a range of descriptive and inferential statistics.

## Assessments

- **MCQs (5%)**

    - Answer Multiple Choice Questions (MCQs) related to content from Research Methods 1 including lectures, data skills sessions and labs

- **Data skills portfolio (15%)**

    - Two data skills worksheets using R and R Studio, each worth 7.5%

- **Stage one report (30%)**

    - Group submission of a planned introduction and method. 

 - **stage two report (50%)** 
 
    - Individual submission of a full lab report.

Please check the [Assessment Information Sheets](#AIS) chapter for detailed information and deadlines.

## Course overview

Below is a provisional order of content in this semester. We will notify you of any changes in advance but feel free to read ahead if you would like:


```r
time_table <- read_xlsx("Supporting/Timetable.xlsx")

kable(time_table)
```

<table>
 <thead>
  <tr>
   <th style="text-align:right;"> Week </th>
   <th style="text-align:left;"> Week Commencing </th>
   <th style="text-align:left;"> Lecture </th>
   <th style="text-align:left;"> Lab </th>
   <th style="text-align:left;"> Data skills </th>
   <th style="text-align:left;"> Research Skills </th>
   <th style="text-align:left;"> Assessment </th>
  </tr>
 </thead>
<tbody>
  <tr>
   <td style="text-align:right;"> 0 </td>
   <td style="text-align:left;"> 2023-09-18 </td>
   <td style="text-align:left;"> Inductions </td>
   <td style="text-align:left;"> NA </td>
   <td style="text-align:left;"> NA </td>
   <td style="text-align:left;"> NA </td>
   <td style="text-align:left;"> NA </td>
  </tr>
  <tr>
   <td style="text-align:right;"> 1 </td>
   <td style="text-align:left;"> 2023-09-25 </td>
   <td style="text-align:left;"> Introduction to Quantitative Research Methods </td>
   <td style="text-align:left;"> Introduction to the course and assignments </td>
   <td style="text-align:left;"> Chapter 1 - Programming Basics </td>
   <td style="text-align:left;"> Quantitative Project / MSLQ Overview </td>
   <td style="text-align:left;"> NA </td>
  </tr>
  <tr>
   <td style="text-align:right;"> 2 </td>
   <td style="text-align:left;"> 2023-10-02 </td>
   <td style="text-align:left;"> NA </td>
   <td style="text-align:left;"> NA </td>
   <td style="text-align:left;"> NA </td>
   <td style="text-align:left;"> NA </td>
   <td style="text-align:left;"> NA </td>
  </tr>
  <tr>
   <td style="text-align:right;"> 3 </td>
   <td style="text-align:left;"> 2023-10-09 </td>
   <td style="text-align:left;"> NA </td>
   <td style="text-align:left;"> NA </td>
   <td style="text-align:left;"> NA </td>
   <td style="text-align:left;"> NA </td>
   <td style="text-align:left;"> NA </td>
  </tr>
  <tr>
   <td style="text-align:right;"> 4 </td>
   <td style="text-align:left;"> 2023-10-16 </td>
   <td style="text-align:left;"> NA </td>
   <td style="text-align:left;"> NA </td>
   <td style="text-align:left;"> NA </td>
   <td style="text-align:left;"> NA </td>
   <td style="text-align:left;"> NA </td>
  </tr>
  <tr>
   <td style="text-align:right;"> 5 </td>
   <td style="text-align:left;"> 2023-10-23 </td>
   <td style="text-align:left;"> NA </td>
   <td style="text-align:left;"> NA </td>
   <td style="text-align:left;"> NA </td>
   <td style="text-align:left;"> NA </td>
   <td style="text-align:left;"> NA </td>
  </tr>
  <tr>
   <td style="text-align:right;"> 6 </td>
   <td style="text-align:left;"> 2023-10-30 </td>
   <td style="text-align:left;"> NA </td>
   <td style="text-align:left;"> NA </td>
   <td style="text-align:left;"> NA </td>
   <td style="text-align:left;"> NA </td>
   <td style="text-align:left;"> NA </td>
  </tr>
  <tr>
   <td style="text-align:right;"> 7 </td>
   <td style="text-align:left;"> 2023-11-06 </td>
   <td style="text-align:left;"> NA </td>
   <td style="text-align:left;"> NA </td>
   <td style="text-align:left;"> NA </td>
   <td style="text-align:left;"> NA </td>
   <td style="text-align:left;"> NA </td>
  </tr>
  <tr>
   <td style="text-align:right;"> 8 </td>
   <td style="text-align:left;"> 2023-11-13 </td>
   <td style="text-align:left;"> NA </td>
   <td style="text-align:left;"> NA </td>
   <td style="text-align:left;"> NA </td>
   <td style="text-align:left;"> NA </td>
   <td style="text-align:left;"> NA </td>
  </tr>
  <tr>
   <td style="text-align:right;"> 9 </td>
   <td style="text-align:left;"> 2023-11-20 </td>
   <td style="text-align:left;"> NA </td>
   <td style="text-align:left;"> NA </td>
   <td style="text-align:left;"> NA </td>
   <td style="text-align:left;"> NA </td>
   <td style="text-align:left;"> NA </td>
  </tr>
  <tr>
   <td style="text-align:right;"> 10 </td>
   <td style="text-align:left;"> 2023-11-27 </td>
   <td style="text-align:left;"> NA </td>
   <td style="text-align:left;"> NA </td>
   <td style="text-align:left;"> NA </td>
   <td style="text-align:left;"> NA </td>
   <td style="text-align:left;"> NA </td>
  </tr>
</tbody>
</table>

Week 1

Lecture: Intro to Quantitative Research Methods
Data skills: Programming basics
Research skills: Academic Writing; Types of evidence and finding sources
Lab week 1

Week 2

Lecture: Summarising data - measurement and descriptive statistics
Data skills: Intro to R & Starting with Data
Research skills: How to formulate research questions and hypotheses
Lab week 2

Week 3:

Lecture: Statistics and probability
Data skills: Data wrangling 1
Research skills: Academic writing and APA referencing
Lab week 3

Week 4:

Lecture: Hypothesis testing
Research skills: Where does data come from? 
Data skills:  Data wrangling 2
Lab week 4

Week 5:

Lecture: Correlation
Pre-registration overview and guidance
Data skills: Data wrangling 3
Lab week 5
Assessment: MCQs (5%)

Week 6: 

Reading week

Week 7:

Lecture: t-tests
Research skills: How to write a methods section
Data skills: Intro to Data Visualisation and Correlation
Lab week 7
Assessment: Data skills worksheet 1 (7.5%)

Week 8:

Lecture: Power & one-sample t-test
Research skills: How to write a results section
Data skills: t-tests and Power and Effect Sizes
Lab week 8

Week 9 

Lecture: Independent samples and paired samples t-test
Research skills: Discussions and abstracts
Data skills: Probability
Assessment: Pre-registration group submission (30%)

Week 10

Lecture: Bringing it all together
Research skills: Report writing
Data skills: Screening data
Assessment: Data skills portfolio 2 (7.5%)

Week 11

Revision week

Week 12

Assessment: Quant report individual submission (50%)

## Available Support

There is a lot of support on this module to help you build your knowledge and understanding of research methods and analysis. You do not have to use all the different support, and some will work better for you than others will. Part of learning is about finding what helps you best. Below are a few of the main approaches we have on this module to help you and if in doubt, please just ask:

- Weekly lab sessions with your tutor and time for questions in each lab

- GTA support sessions in person and online

- Teams channel for discussion, questions and support

- Student Office Hours (sometimes called Student Drop-in Hours)  - just turn up and ask anything

- Assessment information sheets and common questions and answer documents to support assignments

The best approach is to write down your questions when they come up, check the available material for answers, and if you are still unsure after that, use one of the approaches above.

Please note, however, we would ask that you do not send questions, either about a topic or an assignment, as a direct message (CHAT) on Teams to an individual staff member. Whilst we always want to help, this approach is not sustainable and there is a highly likely chance your question will get missed and go unanswered. We would strongly encourage you to post the question on TEAMS channel as that way everyone can try to answer. Alternatively, use the Student Office Hours or your Lab sessions to ask questions more privately.

## Individual work and groupwork

In this course, we will encourage you to make use of groupwork from time to time, and even put you into groups for the stage one report Assignment. Working as a group is essential in science and collective knowledge is also incredibly beneficial for learning. That said, we will also remind you at times when an assignment or activity should be done by yourself to avoid contravening University plagiarism rules. Beyond that, individual assignments help you see what you have learned. The first rule of science is that we must not fool ourselves. If in doubt though as to what should be done together and alone, please just ask.

In brief:

- You will work on the pre-registration as a group. We will let you know when allocations are ready to view. All other assignments are individual assignments.

- Use each other’s strengths and knowledge throughout the semester to help you learn about the topics we discuss and introduce.

- Support each other through discussion and interaction on the Teams channel.

## Trust Yourself and Work With Us!

This course, and the knowledge and skills we will help you learn, is new to everybody. It will take time and it will take trial and error. Academic writing, especially for reports, and learning data skills are both challenging. That said, there is nothing to say that you can't do this and that you can't achieve extremely highly in the skills you will learn here. You may not love this module but you can do it. Take your time. Trust yourself. Work with us and ask us questions to help clarify anything you are unsure of!
