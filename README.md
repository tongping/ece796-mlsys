# ECE597/697TL: ML and Systems

 Machine learning is widely employed in a range of applications. This course has two parts. The first part is about ML systems, which will talk about the most recent research in machine learning, such as efficient model training, inference, and serving, distributed and parallel learning algorithms and systems, ML programming models and abstractions. The second part is about ML for systems, where ML is deployed to solve system problems, such as identifying performance, reliability, and scalability issues in both static and dynamic scenarios. This course will review cutting-edge research on these topics and allow students to work on a hands-on project. The course will primarily involve reading, presenting, and discussing papers, and a final project to build an end-to-end machine learning pipeline.

This seminar **will primarily involve reading, presenting, and discussing recent research papers in ML and systems, and a final project focusing on the combination of ML and system topic, either using ML to improve the system or improving a ML system (e.g., inference or training)**.

## Course Prerequisites

This course is not an introductory course for machine learning. Here, I assume that you have the basic background of machine learning as shown in http://cs231n.stanford.edu/ or ECE597/697ML as described in http://ece.umass.edu/ai-data-engineering/courses. Also, I assume that you have some prior knowledge in Python programming, ECE322 (https://people.umass.edu/tongping/teaching/ece322/index.html), and ECE570/670 (https://people.umass.edu/tongping/teaching/ece570/index.html). 


## Course Information

**Class Meetings:** 09/01/2021 - 12/8/2021, TuTh. 8:30AM - 9:45AM, Marston Hall room 211

**Piazza Link:** http://piazza.com/umass/fall2021/ece697tl

**Review System:** https://umass-ece697tl-2021fall.hotcrp.com/

**Participation Record:** 
https://docs.google.com/spreadsheets/d/1179vSCO3NU0f0wyO-xtnQDYUtDKvURLPOiJbc7T79ws/edit?usp=sharing

**Schedule:**
http://github.com/tongping/ece697-mlsys/blob/main/Schedule.md

## Grading
- 20% presentation 
- 10% participation: attendance, discussion
- 20% reviews
- 50% course project: presentation (10%), bi-weekly discussion (10%), code and report (30%)

**Note:** 
Presentation: Each student will be required to present at least once or twice, depending on the number of students and the papers. In order to ensure the quality and also reduce the anxiety of presentation and preparation, each presentation should be prepared by two students together, one focus on **Motivation** and **Body of Work**, while the other one will be responsible for **Discussion** section, which are detailed in the following.
 
Paricipation: you should update the participation record by youself at the same day of each class. For each class, you will need to record 3 points if you have attended, and record 3 additional points if you have participated the discussion (such as asking and helping answer the question). 100 points are required to get full credits for this part. 

Reviews: each will be required to write mandatory reviews for all papers and one or two summary for the presenting papers. We will introduce the peer review for  the comments, where all reviews will be anonymous initially and every one could comment others with **Good Work** or **other negative comments**. The one with the most negative comments will be not counted as a qualified review, which could be compensated by writing a new review for a new paper or fix the review for the current paper by writing a new review. **Note that the review should be submitted before the end of the day before each class** (e.g., 11:59pm of Mondays and Wednesdays), which will allow the presentor to write the summary. All reviews should be submitted before 12/08 to be counted. The instrutor may occasionally grade the reviews as well. If a student have 4 times of bad reviews will be deducted 50% of scores for the review section, and will not get any credit if getting more than 8 bad reviews.

The **final grade distribution** will be like the following: 

| Percentage | Letter Grade |
| ----------- | ----------- |
| 93 ~ 100  | A  |
| 90 ~ 92.9 | A- |
| 87 ~ 89.9 | B+ |
| 83 ~ 86.9 | B  |
| 80 ~ 82.9 | B- |
| 70 ~ 79.9 | C  |
| 60 ~ 69.9 | D  |
| <= 60     | F  |

## Bi-weekly Meetings
Project meetings: you should plan to have a bi-weekly meeting at the determined slot (30 minutes) to discuss with the instructor about the progress and any issues. 


## Writing Review

Each review should include more than 200 words, which includes the following content, borrowed from [Emery Berger's blog](https://emeryblogger.com/). Each review should contain the following components:

- Summary: what is the overview of this paper?

- Strength: what are good of this paper? 

- Weakness: what shortcomings this paper may have? 

- Possible extension: what you learned from the paper? What can you think of to improve this paper? 

Reviews will take the following questions into account:

- Is the paper well-motivated? What problem does it address, and is it an important problem?

- Does the paper significantly advance the state of the art or break new ground?

- What are the paper’s key insights?

- What are the paper’s key scientific and technical contributions?

- Does the paper credibly support its claimed contributions?

- What did you learn from the paper?

- Is the paper sufficiently clear that readers will be able to read and understand it?

- Does the paper clearly establish its context with respect to prior work? Does it discuss prior work accurately and completely? Are comparisons with previous work clear and explicit?

- Does the paper describe something that has actually been implemented? If so, has it been evaluated properly? Is it publicly available so that these results can be verified?

- What impact is this paper likely to have (on theory & practice)?

- Is the work of broad appeal and interest to the community?

## Presentation Guideline

Each class a student will present a paper, where questions could be asked in the middle of the presentation. The presentor is also the one who will summarize the paper before each class. Thus, the typical structure of a presentation would be like this, where the remaining time will be questions time:

 **Motivation:** What is the problem being addressed? Give the context of the work by assuming that audiences know nothing about this work. Why is this problem important? (Approx. 5 - 10 minutes)
 
 **Body of Work:** Focus on the big idea of the work, rather than the details. However, the enough details should be present to make the presentation informative. In the end, the evaluation results of the work should be presented. (Approx. 30 minutes)
 
 **Discussion:** The presentor should write the summary of the review, and then present the strengths and weaknesses of each paper based on the review comments of other students and yours. It will be better if such comments are included in the slides. (Approx. 15 minutes)


## Project Report
Each student should work for a project, which could be a group project (with at most 3 students). Each project should pick:

- either a system problem that can benefit from the use of ML algorithms, or
- or a use case ML application that requires systems support for data collection, machine learning training, inference, or a pipeline composing these steps. 


Note that each project should be agreed upon with the instructor. Initially, each group need to prepare a “problem statement” report that describes the application and challenges in terms of scalability, reducing running time, and/or usability. Then students should propose a solution, implement the solution, and then validate the claims experimentally. In the end, a technical report should be included that validates the system design through performance measurements and/or user studies. We may provide some topics in the classes. 

**Tentative project timeline:**

- Identify a Sys4ML or ML4sys problem and prepare 1-page problem statement (09/14)

- Midterm Review: each group prepares a talk around 15 minutes to talk about their progress. (10/14)

- Final presentation: each group prepares a talk around 25 minutes (including Q&A), which is similar to a paper presentation. (11/30, 12/02, 12/07)

- Project Deadline: you could write the report with [MLSys format](https://mlsys.org/Conferences/2021/CallForPapers). Please ensure the results reported are reproducable by preparing your code following [this guideline](https://ctuning.org/ae/submission.html). The final report will be submitted on the moodle.   (12/08)
        
