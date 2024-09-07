# CSC413/2516: Neural Networks and Deep Learning

Instructor: Colin Raffel

TAs: Aida Ramezani (lead), Zongliang Ji, Umangi Jain, Andreas Burger, Yuchi Zhao, Ruofan Liang, and Gül Sena Altintas	

Quercus: https://q.utoronto.ca/courses/352639

Piazza (for all course communications): Available on Quercus

Term: Fall 2024

Sections: 0101, 0201, 2001, and 2101

Lectures: Wednesdays, 9-11am and 11am-1pm in MP134 (McLennan Physical Laboratories)

Tutorials: Mondays 9-10am in BA1190 (Bahen) and 11am-12pm in GB244 (Galbraith)

Deep learning is the branch of machine learning focused on training neural networks.
Neural networks have proven to be powerful across a wide range of domains and tasks, including computer vision, natural language processing, speech recognition, and beyond.
The success of these models is partially thanks to the fact that their performance tends to improve as more and more data is used to train them.
Further, there have been many advances over the past few decades that have made it easier to attain good performance when using neural networks.
In this course, we will provide a thorough introduction to the field of deep learning.
We will cover the basics of building and optimizing neural networks in addition to specifics of different model architectures and training schemes.
The course will cover portions of the "[Dive into Deep Learning](https://d2l.ai/)" textbook and will have a standard lecture/homework/exam format.

## Prerequisites

Students should have taken courses on machine learning, linear algebra, and multivariate calculus.
Further, it is recommended that students have some basic familiarity with statistical concepts.
Finally, students must be proficient in reading and writing Python code.
For a list of courses that serve as prerequisites for the undergraduate version of this course, see [here](https://artsci.calendar.utoronto.ca/course/csc413h1).

## Lecture and tutorial schedule

The following schedule is tentative; the content of each lecture may change depending on pacing.
All readings refer to corresponding sections in [Dive into Deep Learning](http://d2l.ai).
Because the book is occasionally updated, the sections listed may become out-of-date.
If a reading seems incongruous with the topic of the lecture, please let me know and I will check if the sections changed.
Tutorials will more directly cover the background and tools needed for each homework assignment or, when preceding an exam, will consist of an exam review.
Homeworks are due on **Thursdays** at 11:59pm -- for example, Homework 1 is due on 9/26 at 11:59pm.

| Date  | Subject                                                                        | Reading                              | Homework            |
| ----- | ------------------------------------------------------------------------------ | ------------------------------------ | ------------------- |
| 9/4   | Class introduction, linear & logistic regression                               | 2.1-2.7 (optional), 3.1-3.5, 4.1-4.5 | H1 assigned         |
| 9/11  | Under/overfitting, regularization, multilayer perceptrons                      | 3.6-3.7, 5.1-5.2, 5.6                |                     |
| 9/18  | Backpropagation, numerical stability, automatic differentiation                | 5.3-5.4                              |                     |
| 9/25  | Gradient descent, adaptive gradient methods                                    | 12.1-12.6, 12.10                     | H1 due, H2 assigned |
| 10/2  | Convolutional neural networks, batch/layer normalization, residual connections | 7.1-7.5, 8.5-8.6                     |                     |
| 10/9  | Sequences, recurrent neural networks, and sequence-to-sequence learning        | 9.1-9.7, 10.1-10.8                   |                     |
| 10/16 | Midterm                                                                        |                                      | H2 due, H3 assigned |
| 10/23 | Attention                                                                      | 11.1-11.6                            |                     |
| 10/30 | No class - fall reading week                                                   | —                                    |                     |
| 11/6  | Transformers part 1                                                            | 11.7, 15.8-15.10                     | H3 due, H4 assigned |
| 11/13 | Transformers part 2, large language models                                     | 11.8-11.9                            |                     |
| 11/20 | Additional architecture grab bag: GNNs, autoencoders, UNet, MoE                | —                                    |                     |
| 11/27 | Deep learning engineering; fairness, accountability, and transparency          | 13.5-13.6, 4.7                       | H4 due              |

## Grading

  1. **Homework**, 50 points: There will be 4 homework assignments. Homework will consist of some combination of math and coding. Each homework is worth 12.5 points.
  1. **Midterm**, 20 points: The midterm will take place on 10/16 and will cover all topics discussed before the midterm.
  1. **Final Exam**, 30 points: The final exam will take place during our scheduled final exam slot and will cover all topics discussed in the class.

## Late work, collaboration rules, and the honor code

Every student has a total of 7 grace days to extend the coursework deadlines through the semester.
Each grace day allows for a 24 hours deadline extension without late penalty.
That is, you may apply the grace days on a late submission to remove its late penalty.
The maximum extension you may request is up to the remaining grace days you have banked up.
We will keep track of the grace days on MarkUs.
After the grace period, assignments will be accepted up to 3 days late, but 10% will be deducted for each day late, rounded up to the nearest day.
After that, submissions will not be accepted and will receive a score of 0.

You are welcome to work together with other students on the homework.
You are also welcome to use any resources you find (online tutorials, textbooks, papers, chatbots, etc.) to help you complete the homework.
However, **you must list any collaboration or resources you used to complete each homework on each assignment**.
If you hand in homework that involved collaboration and/or makes use of content that you did not create and you do not disclose this, you will get a 0 for that homework.
In addition, it is likely that you will be able to use some resource (be it another student, ChatGPT, or whatever) that can help you solve many of the homework problems.
However, note that if you rely too much on such resources you will likely not learn the material and will do poorly on the exams, during which such resources will not be available.


## Conduct

I ask that we all follow the [NeurIPS Code of Conduct](https://nips.cc/public/CodeOfConduct) and the [Recurse Center Social Rules](https://www.recurse.com/social-rules).
I value the perspectives of individuals from all backgrounds reflecting the diversity of our students.
I broadly define diversity to include race, gender identity, national origin, ethnicity, religion, social class, age, sexual orientation, political background, and physical and learning ability.
I will strive to make this classroom an inclusive space for all students.
Please let me know if there is anything I can do to improve.

## Resources

Please be aware of the following resources at U of T which can help ensure your academic success and personal well-being:

- [Writing at U of T](http://www.writing.utoronto.ca/)
- [University of Toronto Academic Integrity](http://academicintegrity.utoronto.ca/)
- [U of T Student Life](http://www.studentlife.utoronto.ca/)
- [Accessibility Services](http://www.accessibility.utoronto.ca/)
- [Health Services](https://studentlife.utoronto.ca/department/health-wellness/)
    
## Changes

I reserve the right to make changes to the syllabus, including project due dates and test dates.
These changes will be announced as early as possible.
