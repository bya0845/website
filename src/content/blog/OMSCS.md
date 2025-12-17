---
title: "OMSCS Roundup"
date: 2025-12-18
description: "This is a general survey of my experience in Georgia Tech's Online Master of Science in Computer Science Program"
---

# **Overview**<br><br>

I started the [OMSCS](https://omscs.gatech.edu/about-omscs) program in Fall of 2023 with the intention of switching careers from civil engineering. I wanted to work in a field with new technologies and more opportunities. The rise of LLMs also persuaded me to learn more about artificial intelligence to brace for what seemed like a profound change in work and society. I didn't want to get left behind, and I didn't want to be forced to use a tool I didn't understand.<br><br>

Last weekend I attended commencement in Atlanta and officialy got out after two hectic but fruitful years of learning. Below is a summary of the courses I took and my thoughts on them.

<!-- prettier-ignore -->
<div class="course-table">

| Course                                     | Semester    | My Rating (out of 5) |
| :----------------------------------------- | :---------- | :------------------: |
| Machine Learning for Trading               | Fall 2023   |         3.5          |
| Graduate Introduction to Operating Systems | Spring 2024 |          5           |
| Computer Networks                          | Spring 2024 |          2           |
| Graduate Algorithms                        | Fall 2024   |          4           |
| Introduction to Information Security       | Fall 2024   |         3.5          |
| Artificial Intelligence                    | Spring 2025 |          4           |
| Advanced Operating Systems                 | Spring 2025 |          4           |
| Deep Learning                              | Summer 2025 |          5           |
| System Design in Cloud Computing           | Fall 2025   |          4           |
| Database System Implementation             | Fall 2025   |          4           |

</div>

### Machine Learning for Trading - Fall 23<br><br>

I knew little about CS heading into the program. This course was recommended as a gentle introduction to the pace and format of OMSCS and also to machine learning. The lectures were prerecorded by [Dr. Tucker Balch](https://www.cc.gatech.edu/people/tucker-balch) who was no longer at the school. They were somewhat dated, but concise and easy to digest. The content was directly relevant to our homework projects (this is not always the case with other classes). Topics covered included decision trees/forests, reinforcement learning (Q-learning), ensemble learners, and using pandas and NumPy to extract, process, and train on stock data. All coding was done in Python. The course also taught basic finance knowledge ranging from technical vs. fundamental analysis to the risk in naked options. Instructors communicated via a forum (Ed Discussion) and office hours.<br><br>

I appreciated the organized structure of the course and the availability of the TAs who held office hours daily. The material was interesting. The finance knowledge was both educational and instructive for what individual investors should and shouldn't do. The machine learning techniques taught were outdated but still served as a useful introduction to the field (we were assigned Tom Mitchell - Machine Learning). As it was my first course and I didn't know what to expect, I attended most of the optional office hours and spent time before the semester catching up on background knowledge.<br><br>

Most projects had written deliverables that asked to document our training process. For both the coding and writing portions of the assignments I wished the graders gave more feedback than an occasional one-liner comment. The lack of feedback was partially due to how big the class was. This experience, luckily, was not common to the rest of the program. Grade: A<br><br>

### Graduate Introduction to Operating Systems - Spring 24<br><br>

GIOS was well-reviewed and one of the most popular classes in the program. From talking with other students I realized the importance of obtaining a solid systems background. The class also has the most active Slack in the program where TAs actively participate.<br><br>

The assignments taught network programming, IPC (interprocess communication), and RPC (remote procedure call). We used POSIX and C API to create multi-threaded client/server frameworks for file sharing. The last assignment used C++ with gRPC and protobuf. My experience was in line with the reviews. The lectures were clear, organized, and taught many fundamental concepts of computing systems that came up in every subsequent class. I found the experience of working in C and figuring out POSIX APIs invaluable for absorbing lecture concepts and learning to think like a software engineer. The Slack faciliated fruitful discussions over high level concepts among students that participated (there's a private GIOS alumni channel for the most active students) (yes I'm it).<br><br>

I spent the entire winter break reading Beej and taking a C/Linux MOOC to prepare. During the semester I estimate having spent roughly 100 hours on P1, 5o hours on P2, then considerably less on P4. Most of the time was dedicated to debugging concurrency and distributed systems code, a theme that would come up again and again for the rest of the program. I look back on the class fondly as a more innocent time when I had never considered to use LLMs for anything other than generating entertaining text. Other than the fact they are forbidden by class policy, learning should be delegated as sparingly as possible, especially when the learner has a non-CS background. Grade: A<br><br>>

### Compputer Networks - Spring 24<br><br>

I paired this class with GIOS as they overlapped on networked concepts and the reviews sold it as a light class. There was a lot of rote memorization involved as the quiz and test content barely deviated from the lectures, which were very dry. Network knowledge is always useful but the presentation of this class left much to be desired. The professor was absent except for reading off an answer sheet in post-exam office hours. The assignments were easy to medium Leetcode graph problems assigned in a network path finding context. The workload was very light, true to the reviews. Grade: A<br><br>

### Graduate Algorithms - Fall 25<br><br>

Possibly the most notorious class in the program, this class spawns highest number of complaint threads on the OMSCS subreddit and have made countless students switch tracks. I managed to get into the class by clicking very fast after my time ticket openeed. I spent the summer  practicing Leetcode and prepping for the class via doing practice problems from the book. I could only get through Dynamic Programming but it was enough for me to not get overwhelmed. After two exams I needed only 2/60 points on Exam 3 to pass. An A was in reach but I second guessed myself on a Rudrata Path/Hamiltonian Cycle proof which will haunt me forever. The class's main obstacle is harshly weighted exam questions. Getting one detail wrong can cost an exam letter grade. Students struggle from both the stress and not having done enough practice problems. Algorithm knowledge is essential and I'm happy to have taken the course early in the program as everything taught in the class is highly relevant to designing software. Grade: B<br><br>
