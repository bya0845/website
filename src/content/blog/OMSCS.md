---
title: "OMSCS Roundup"
date: 2025-12-20
description: "This is a general survey of my experience in Georgia Tech's Online Master of Science in Computer Science Program"
---

# **Overview**<br><br>

I started the [OMSCS](https://omscs.gatech.edu/about-omscs) program in Fall of 2023 with the intention of switching careers from civil engineering. I wanted to work in a field with new technologies and more opportunities. The rise of LLMs also persuaded me to learn more about artificial intelligence to brace for what seemed like a profound change in work and society. I didn't want to get left behind, and I didn't want to be forced to use a tool I didn't understand.<br><br>

Last weekend I attended commencement in Atlanta and officially got out after two hectic but fruitful years of learning. Below is a summary of the courses I took and my thoughts on them.

<!-- prettier-ignore -->
<div class="course-table">

| Course                                              | Semester    | My Rating (out of 5) |
| :-------------------------------------------------- | :---------- | :------------------: |
| [Machine Learning for Trading](#ml4t)               | Fall 2023   |         3.5          |
| [Graduate Introduction to Operating Systems](#gios) | Spring 2024 |          5           |
| [Computer Networks](#cn)                            | Spring 2024 |          2           |
| [Graduate Algorithms](#ga)                          | Fall 2024   |          4           |
| [Introduction to Information Security](#iis)        | Fall 2024   |         3.5          |
| [Artificial Intelligence](#ai)                      | Spring 2025 |          4           |
| [Advanced Operating Systems](#aos)                  | Spring 2025 |          4           |
| [Deep Learning](#dl)                                | Summer 2025 |          5           |
| [System Design in Cloud Computing](#sdcc)           | Fall 2025   |          4           |
| [Database System Implementation](#dsi)              | Fall 2025   |          4           |

</div>

### <span id="ml4t">Machine Learning for Trading - Fall 23</span><br><br>

I had little CS knowledge heading into the program. This course was recommended as a gentle introduction to the pace and format of OMSCS and also to machine learning. The lectures were prerecorded by [Dr. Tucker Balch](https://www.cc.gatech.edu/people/tucker-balch) who was no longer at the school. They were somewhat dated, but concise and easy to digest. The content was directly relevant to our homework projects (this is not always the case with other classes). Topics covered included decision trees/forests, reinforcement learning (Q-learning), ensemble learners, and using pandas and NumPy to extract, process, and train on stock data. All coding was done in Python. The course also taught basic finance knowledge ranging from technical vs. fundamental analysis to the risk in naked options. Instructors communicated via a forum (Ed Discussion) and office hours.<br><br>

I appreciated the organized structure of the course and the availability of the TAs who held office hours daily. The material was interesting. The finance knowledge was both educational and instructive for what individual investors should and shouldn't do. The machine learning techniques taught were outdated but still served as a useful introduction to the field (we were assigned Tom Mitchell - Machine Learning). As it was my first course and I didn't know what to expect, I attended most of the optional office hours and spent time before the semester catching up on background knowledge.<br><br>

Most projects had written deliverables that asked to document our training process. For both the coding and writing portions of the assignments I wished the graders gave more feedback than an occasional one-liner comment. The lack of feedback was partially due to how big the class was. This experience, luckily, was not common to the rest of the program. Grade: A<br><br>

### <span id="gios">Graduate Introduction to Operating Systems - Spring 24</span><br><br>

GIOS was well-reviewed and one of the most popular classes in the program. From talking with other students I realized the importance of obtaining a solid systems background. The class also has the most active Slack in the program where TAs actively participate.<br><br>

The assignments taught network programming, IPC (inter-process communication), and RPC (remote procedure call). We used POSIX and C API to create multi-threaded client/server frameworks for file sharing. The last assignment used C++, gRPC, and protobuf. My experience was in line with the reviews. The lectures were clear, organized, and taught many fundamental concepts of computing systems that came up in every subsequent class. I found the experience of working in C and figuring out POSIX APIs invaluable for absorbing lecture concepts and learning to think like a software engineer. The Slack facilitated fruitful discussions over high level concepts among students that participated (there's a private GIOS alumni channel for the most active students) (yes I'm it).<br><br>

I spent the entire winter break reading Beej and taking a C/Linux MOOC to prepare. During the semester I estimate having spent roughly 100 hours on P1, 50 hours on P2, then considerably less on P4. Most of the time was dedicated to debugging concurrency and distributed systems code, a theme that would come up again and again for the rest of the program. I look back on the class fondly as a more innocent time when I had not considered using LLMs for anything other than generating entertaining text and parsing the occasional Gradescope error output. I tried to refrain from delegating my learning to it for most of the program, as developing an adequate level of code-reading comprehension, writing ability, and thought process was essential to someone with a non-CS background. Grade: A<br><br>

### <span id="cn">Computer Networks - Spring 24</span><br><br>

I paired this class with GIOS as they overlapped on networked concepts and the reviews sold it as a light class. There was a lot of rote memorization as the quiz and test content barely deviated from the lectures, which were very dry. Network knowledge is always useful but the presentation of this class left much to be desired. The professor was absent except for when reading off an answer sheet in post-exam office hours. The assignments were easy to medium Leetcode graph problems wrapped in a network path finding context. The workload was very light, true to the reviews. Grade: A<br><br>

### <span id="ga">Graduate Algorithms - Fall 25</span><br><br>

Possibly the most notorious class in the program, GA spawns the highest number of complaint threads on the OMSCS subreddit and have made countless students switch program tracks. I managed to get into the class by clicking very fast after my time ticket opened. I spent the summer practicing Leetcode and prepping via doing practice problems from the book (DPV - Algorithms). I only had time to go through Dynamic Programming but it was enough for me to not get overwhelmed for the first section. The three sections of the class were DP, graphs, and NP Complete proofs.<br><br>

After two out of three exams I needed only 2/60 points on Exam 3 to pass. An A was in reach but I second guessed myself on a Rudrata Path/Hamiltonian Cycle proof and fell short by 1.4 pts, which still haunts me. The class's main challenge wasn't the material but the harsh exam question weights. Getting one detail wrong could lead to surrendering most of the points on the question. Each exam had only two long answers that made up half of the exam grade. A lot of students struggled from the stress of the exams as much as not knowing the material. I'm glad to have taken the course early in the program as the knowledge helped tremendously for future classes where any sort of algorithmic efficiency needed to be considered. I did not have the same experience as most of the reviews as the exam questions came straight from the practice material, which I went through diligently, and thus encountered no surprises. Grade: B<br><br>

### <span id="iis">Introduction to Information Security - Fall 25</span><br><br>

This was a very forgettable class. The programming assignments were capture the flag style puzzles that involved exploiting security flaws in code. Those included SQL injections, buffer overflows, etc. I would do the assignments in one or two sitting over the weekend in between studying for GA. I appreciated having to use different languages and tools for each assignment. Some of the puzzles also required out-of-the-box thinking to solve. But I retained very little, not because of the time dedicated but because the class was entirely assignment based, the lectures were optional, and thus there was nothing to make the material stick and nothing was talked about in depth. Grade: A<br><br>

### <span id="ai">Artificial Intelligence - Spring 25</span><br><br>

After making it through the previous semester, I knew I could handle higher difficulty courses and took this class to prepare for Deep Learning. Artificial Intelligence/CS-6601 is a general survey of AI theory from Turing machines to Transformers. There were six assignments with two week-long take-home exams. The assignments were mostly straightforward except for the first one, which consisted of implementing search algorithms from scratch starting from priority queue to dijkstra's to tri-directional search. I found the textbook (Artificial Intelligence: A Modern Approach) a great read. It was well-written and comprehensive and covered the entirety of modern AI history. This was the first time I encountered the term "agent" in an AI context; used to refer to a model akin to self-driving cars that could perceive and process data from the environment and output an action. This was not quite the way it was touted in news cycles at the time about agentic AI.<br><br>

It was not only fascinating to learn about the foundational algorithms of AI and the different approaches before deep learning, but also to read about the history of AI research and hyper cycles before LLMs. The class was great prep for Deep Learning and provided an excellent theoretical foundation. The take-home exams were not time-consuming but not overly difficult. The assignment medians were in the high 90's after the first one. I appreciated that the professor, [Thad Starner](https://www.cc.gatech.edu/people/thad-starner) showed up for every office hour, including one with no students present, to answer each question. I regret not having picked his brain more about what the industry was experiencing. I enjoyed the class but though the assignments could have been larger in scope and more difficult. Grade: A<br><br>

### <span id="aos">Advanced Operating Systems - Spring 25</span><br><br>

AOS was a combined on-campus/online class with a low headcount and a very involved professor in [Kishore](https://omscs.gatech.edu/people/umakishore-ramachandran). It's focused on modern system design, with programming assignments on concurrency mechanisms (barrier implementation), host/VM cpu/memory management, and big data processing (Map Reduce). Since CS as a field of study moves quickly, some of the class material was outdated, but still somewhat beneficial to learn as a reference for modern implementations. The exams were based on lectures and a large portfolio of research papers going back several decades. The assignments were a step up from GIOS. The exams were around the same difficulty as most of the questions were released two days ahead and we were allowed to discuss them. The format lead to multiple weekends of cramming, which I was used to by this time in the program. The paper topics ranged from seminal to irrelevant. Most were interesting and covered a very wide range of systems design, which included OS structure, virtualization, distributed systems, security, concurrency, and more. The class is somewhat like AI in its breadth over depth approach. I tried my best to keep up and read as many papers as I could. The combination of the two classes made this by far my busiest semester yet.

Thep projects used C and C++, which was a welcoming change after the theory-heavy algorithm class of previous semester. By this time I was much more capable in both languages than even a year ago. The projects went more smoothly as a result. Grade: A<br><br>

### <span id="dl">Deep Learning - Summer 25</span><br><br>

I debated between taking DL versus a lighter course, NLP, that covered some of the same topics. I wanted to learn the material to understand what was going on in tech and in wider industry as it becomes more and more reliant on LLMs products. The class had some hard math prerequisites in linear algebra and matrix calculus. I reviewed as much as I could over the two or so weeks in between semesters. Previous classes compiled a great list of resources. Many alumni advised to watch Justin Johnson's University of Michigan Deep Learning for Computer Vision lectures in tandem with the class lectures, which were in many ways worse at explaining the basics but covered slighly more up-to-date topics. The UM lectures were some of the best STEM lectures I had seen. I would not have understood, or more impportantly, appreciated the topic, if it were not for Justin Johnson's illuminating and highly efficient explanations and slides. Our class was structured similarly to the UM class, starting from matrix multiplication and backpropagation and ending at generative models and deep reinforcement learning. Both classes provide an overview of the history of neural networks starting from the perceptron to AlexNet to multiheaded attention. The last third or so of the class lectures were recorded by Meta FAIR employees, some of whom held guest office hours throughout the semester where they answered (almost) any question, and as a result provided great entertaiment along with industry-relevant knowledge. I took the class before the shakeup at FAIR/Meta AI so my questions were tame compared to what could have been asked.

The topic of deep learning is fascinating both in theory and application. I enjoyed learning from the basics, which the class reinforced with hand-calc'd backpropgation and computation graph assignments. The programming homeworks ranged from building a two layer neural network with only NumPy, to building and training a transformer with PyTorch locally or over Google Colab. The last project was a group project. We chose to research pruning methods and examine lighweight CNNs and what made them unique. The resulting paper can be read [here] (https://github.com/bya0845/CS7643-DL-Project/blob/main/Paper.pdf). I enjoyed the class immensely. Learning what was behind modern "AI" made me a less anxious about the present. Learning about LLMs right after a system design class was also a unique experience. More on that in another post. Grade: A <br><br>

### <span id="sdcc">System Design for Cloud Computing - Fall 25</span><br><br>

SDCC is the only class in the program with a mandatory synchronous portion, which is a weekly meeting on Wednesdays at 8PM EST. Like AOS, the on-campus and online sections are combined. There are no exams or traditional homework assignments. The course is comprised of four modules, each with 3 workshops and a final project built on top of the workshops. Each workshop is evaluated via a demo session with TAs. Most of the class chose to partner up, which was highly encouraged due to the workload. The lectures cover everything cloud computing. The assignments are SDN (Software Defined Networking), NFV (Network Function Virtualization), Systems (building and deploying MR on Azure), and a self-designed Apps module.<br><br>

### <span id="dsi">Database System Implementation - Fall 25</span><br><br>
