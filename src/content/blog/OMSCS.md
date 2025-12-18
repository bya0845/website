---
title: "OMSCS Roundup"
date: 2025-12-18
description: "This is a general survey of my experience in Georgia Tech's Online Master of Science in Computer Science Program"
---

# **Overview**<br><br>

I started the [OMSCS](https://omscs.gatech.edu/about-omscs) program in Fall of 2023 with the intention of switching careers from civil engineering. I wanted to work in a field with new technologies and more opportunities. The rise of LLMs also persuaded me to learn more about artificial intelligence to brace for what seemed like a profound change in work and society. I didn't want to get left behind, and I didn't want to be forced to use a tool I didn't understand.<br><br>

Last weekend I attended commencement in Atlanta and officially got out after two hectic but fruitful years of learning. Below is a summary of the courses I took and my thoughts on them.

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

I had little CS knowledge heading into the program. This course was recommended as a gentle introduction to the pace and format of OMSCS and also to machine learning. The lectures were prerecorded by [Dr. Tucker Balch](https://www.cc.gatech.edu/people/tucker-balch) who was no longer at the school. They were somewhat dated, but concise and easy to digest. The content was directly relevant to our homework projects (this is not always the case with other classes). Topics covered included decision trees/forests, reinforcement learning (Q-learning), ensemble learners, and using pandas and NumPy to extract, process, and train on stock data. All coding was done in Python. The course also taught basic finance knowledge ranging from technical vs. fundamental analysis to the risk in naked options. Instructors communicated via a forum (Ed Discussion) and office hours.<br><br>

I appreciated the organized structure of the course and the availability of the TAs who held office hours daily. The material was interesting. The finance knowledge was both educational and instructive for what individual investors should and shouldn't do. The machine learning techniques taught were outdated but still served as a useful introduction to the field (we were assigned Tom Mitchell - Machine Learning). As it was my first course and I didn't know what to expect, I attended most of the optional office hours and spent time before the semester catching up on background knowledge.<br><br>

Most projects had written deliverables that asked to document our training process. For both the coding and writing portions of the assignments I wished the graders gave more feedback than an occasional one-liner comment. The lack of feedback was partially due to how big the class was. This experience, luckily, was not common to the rest of the program. Grade: A<br><br>

### Graduate Introduction to Operating Systems - Spring 24<br><br>

GIOS was well-reviewed and one of the most popular classes in the program. From talking with other students I realized the importance of obtaining a solid systems background. The class also has the most active Slack in the program where TAs actively participate.<br><br>

The assignments taught network programming, IPC (inter-process communication), and RPC (remote procedure call). We used POSIX and C API to create multi-threaded client/server frameworks for file sharing. The last assignment used C++, gRPC, and protobuf. My experience was in line with the reviews. The lectures were clear, organized, and taught many fundamental concepts of computing systems that came up in every subsequent class. I found the experience of working in C and figuring out POSIX APIs invaluable for absorbing lecture concepts and learning to think like a software engineer. The Slack facilitated fruitful discussions over high level concepts among students that participated (there's a private GIOS alumni channel for the most active students) (yes I'm it).<br><br>

I spent the entire winter break reading Beej and taking a C/Linux MOOC to prepare. During the semester I estimate having spent roughly 100 hours on P1, 50 hours on P2, then considerably less on P4. Most of the time was dedicated to debugging concurrency and distributed systems code, a theme that would come up again and again for the rest of the program. I look back on the class fondly as a more innocent time when I had not considered using LLMs for anything other than generating entertaining text and parsing the occasional Gradescope error output. I tried to refrain from delegating my learning to it for most of the program, as developing an adequate level of code-reading comprehension, writing ability, and thought process was essential to someone with a non-CS background. Grade: A<br><br>>

### Computer Networks - Spring 24<br><br>

I paired this class with GIOS as they overlapped on networked concepts and the reviews sold it as a light class. There was a lot of rote memorization as the quiz and test content barely deviated from the lectures, which were very dry. Network knowledge is always useful but the presentation of this class left much to be desired. The professor was absent except for when reading off an answer sheet in post-exam office hours. The assignments were easy to medium Leetcode graph problems wrapped in a network path finding context. The workload was very light, true to the reviews. Grade: A<br><br>

### Graduate Algorithms - Fall 25<br><br>

Possibly the most notorious class in the program, GA spawns the highest number of complaint threads on the OMSCS subreddit and have made countless students switch program tracks. I managed to get into the class by clicking very fast after my time ticket opened. I spent the summer practicing Leetcode and prepping via doing practice problems from the book (DPV - Algorithms). I only had time to go through Dynamic Programming but it was enough for me to not get overwhelmed for the first section. The three sections of the class were DP, graphs, and NP Complete proofs.<br><br>

After two out of three exams I needed only 2/60 points on Exam 3 to pass. An A was in reach but I second guessed myself on a Rudrata Path/Hamiltonian Cycle proof and fell short by 1.4 pts, which still haunts me. The class's main challenge wasn't the material but the harsh exam question weights. Getting one detail wrong could lead to surrendering most of the points on the question. Each exam had only two long answers that made up half of the exam grade. A lot of students struggled from the stress of the exams as much as not knowing the material. I'm glad to have taken the course early in the program as the knowledge helped tremendously for future classes where any sort of algorithmic efficiency needed to be considered. I did not have the same experience as most of the reviews as the exam questions came straight from the practice material, which I went through diligently, and thus encountered no surprises. Grade: B<br><br>

### Introduction to Information Security - Fall 25<br><br>

This was a very forgettable class. The programming assignments were capture the flag style puzzles that involved exploiting security flaws in code. Those included SQL injections, buffer overflows, etc. I would do the assignments in one or two sitting over the weekend in between studying for GA. I appreciated having to use different languages and tools for each assignment. Some of the puzzles also required out-of-the-box thinking to solve. But I retained very little, not because of the time dedicated but because the class was entirely assignment based, the lectures were optional, and thus there was nothing to make the material stick and nothing was talked about in depth. Grade: A<br><br>

### Artificial Intelligence - Spring 25<br><br>

After making it through the previous semester, I knew I could handle higher difficulty courses and took this class to prepare for Deep Learning. Artificial Intelligence/CS-6601 is a general survey of AI theory from Turing machines to Transformers. There were six assignments with two week-long take-home exams. The assignments were mostly straightforward except for the first one, which consisted of implementing search algorithms from scratch starting from priority queue to dijkstra's to tri-directional search. I found the textbook (Artificial Intelligence: A Modern Approach) a great read. It was well-written and comprehensive and covered the entirety of modern AI history. This was the first time I encountered the term "agent" in an AI context; used to refer to a model akin to self-driving cars that could perceive and process data from the environment and output an action. This was not quite the way it was touted in news cycles at the time about agentic AI.<br><br>

It was not only fascinating to learn about the foundational algorithms of AI and the different approaches before deep learning, but also to read about the history of AI research and hyper cycles before LLMs. The class was great prep for Deep Learning and provided an excellent theoretical foundation. The take-home exams were not time-consuming but not overly difficult. The assignment medians were in the high 90's after the first one. I appreciated that the professor, [Thad Starner](https://www.cc.gatech.edu/people/thad-starner) showed up for every office hour, including one with no students present, to answer each question. I regret not having picked his brain more about what the industry was experiencing. I enjoyed the class but though the assignments could have been larger in scope and more difficult. Grade: A<br><br>

### Advanced Operating Systems - Spring 25<br><br>

AOS was a combined on-campus/online class with a low headcount and a very involved professor in [Kishore](https://omscs.gatech.edu/people/umakishore-ramachandran). It's focused on modern system design, with programming assignments on concurrency mechanisms (barrier implementation), host/VM cpu/memory management, and big data processing (Map Reduce). Since CS as a field of study moves quickly, some of the class material was outdated, but still somewhat beneficial to learn as a reference for modern implementations. The exams were based on lectures and a large portfolio of research papers going back several decades. The assignments were a step up from GIOS. The exams were around the same difficulty as most of the questions were released two days before and we were allowed to discuss solutions. This format lead to several weekends of cramming, which I was used to by this time in the program. I found it beneficial to work in C and C++ again after the previous semester. By this time I was much more capable than even a year ago. The class covered so many topics that I wish I had not doubled it with another class. Grade: A<br><br>

### Deep Learning - Summer 25<br><br>

I debated between taking DL versus a lighter course, NLP, that covered some of the same topics. I wanted to learn the material to understand what was going on in tech and the wider world that was becoming more and more reliant on LLMs. The class had some hard prerequisites