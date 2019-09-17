# Assignment {#introduction-assignment status=ready}

This assignment gives an introduction to our course and reviews some basic material you will need. *Hand ins will be noted in italics. Create an answers.txt file in your Github repository (see handin instructions at the bottom of this page) in which to write your answers.*

## Course Form

Fill out the [form](https://docs.google.com/forms/d/1H9RmjkpoRjVK3JAbkEogyKDuwZQWIR6a7M4KQng4Tf0/viewform?edit_requested=true) in order to apply for admission to the course.

## Collaboration Policy

Please read and sign the [collaboration policy for CS1951R](https://cs.brown.edu/courses/cs1951r/assignments/introduction/collaboration_policy.pdf). *Submit the signed pdf with filename collaboration_policy.pdf.*

## Safety Policy

Please read and sign the [safety policy for CS1951R](https://cs.brown.edu/courses/cs1951r/assignments/introduction/safety_policy.pdf). *Submit the signed pdf with filename safety_policy.pdf*

## Motivations (20 points)

*Submit the answers to these questions in answers.txt*

Before you start putting a lot of time into this course, it is important to figure out what you will get out of the course. Think about what you expect to learn from this course and why it is worth investing a lot of time. 

1. What is a robot?
A robot is a computer that has been equipped with sensor and actuators

2. If I can fly a drone by remote, what can I get out of programming it?
By programming, I am able to instruct the drone to do more complex and faster moves and task than I would have been able to do with a remote. A remote require a human input while a program is an automated and precise order.


## Matrices and Transformations (20 points)

*Write the answers to these questions in the corresponding section of answers.txt.*

Transformation matrices are fundamental to reasoning about sensors and actuators. For example, the robot might detect a landmark with its camera, and we might want to know the location of the landmark relative to the robot's base. Or we might want to know where we can expect the landmark to be located after the robot has moved forward. We will cover this in detail but for know are asking you to do a warmup on these topics.

For this problem we strongly recommend you do these calculations by hand, because they are warmup questions designed to remind you of some of the prerequisite material for the class.

1. Multiply the matrix by the following vector: $$\begin{bmatrix}1 & 0 & 1\\ 0 & 1 & 2\\ 0 & 0 & 1\end{bmatrix} \times \begin{bmatrix}0\\ 0\\ 1\end{bmatrix}$$
[1 2 1]

2. Multiply the matrix by the following vector: $$\begin{bmatrix}0& 0& 1\end{bmatrix} \times \begin{bmatrix}1 & 0 & 4\\ 0 & 1 & 10\\ 0 & 0 & 1\end{bmatrix} $$
[4 10 1]

3. Imagine a robot is located in the $(x, y)$ coordinate plane at the origin $(0,0)$. It uses a sensor to detect an obstacle at a distance of $ 6\mbox{m} $ and a heading of $ 30^{\circ} $. The positive y-axis represents $ 0^{\circ} $, and the degrees increase when turning clockwise. What are the $(x, y)$ coordinates of the obstacle? Give the coordinates in *answers.txt*. Then draw your answer on a map and add it to your repo as *map.png*.



## Law of Leaky Abstractions (20 points)

*Write your answers in the corresponding section of answers.txt*

Read [The Law of Leaky Abstractions](https://www.joelonsoftware.com/2002/11/11/the-law-of-leaky-abstractions/). How might this be especially relevant to robotics? Make sure you address:

1. Give an example of a system that you have worked with that had an abstraction that "leaked."  Describe the abstraction, what it was hiding, and what went wrong so that the abstraction broke down. 
I once had a motobike, that require the use of a clutch to change gear. the abstraction that was hidden in my motobike is that the clutch is the mechanical divice that transfers the rotational power from the engine to the wheels. I accidentally under press the clutch to change gear and the wheels jammed.

2. How can we use abstractions in light of these challenges?
I think the use of an abstraction is a great thing as long as we keep his complexicity to a minimal level. for example i would have prefered that in the case of my motobike i only have to press the clutch once for the entire ride. Although abstraction are needed, we should limite it use.

## Handin

If you do not have a Github account, please create one at [this link](https://github.com/). We will be using git repos throughout the course for versioning, moving code around, and submitting assignments.

Once you have a github account, click on [this link](https://classroom.github.com/a/Kx6uuWcO) to join our Github classroom. This should ask you to select your name from the list and create a repository for you. Clone the directory to your computer

```
git clone https://github.com/h2r/assignment-introduction-yourGithubName.git
```

This will create a new folder. Before you submit your assignment, your folder should contain

- collaboration_policy.pdf
- safety_policy.pdf
- answers.txt
- map.png

Commit and push your changes before the assignment is due. This will allow us to access the files you pushed to Github and grade them accordingly. If you commit and push after the assignment deadline, we will use your latest commit as your final submission, and you will be marked late.

```
cd assignment-introduction-yourGitHubName
git add collaboration_policy.pdf safety_policy.pdf answers.txt map.png
git commit -a -m 'some commit message. maybe handin, maybe update'
git push
```

Note that assignments will be graded anonymously, so don't put your name or any other identifying information on the files you hand in.

If your name is not in the list of names, please email [cs1951rheadtas@lists.brown.edu](mailto:cs1951rheadtas@lists.brown.edu) and we will make sure your name is added to the list.
