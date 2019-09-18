YaGIP: Yet another Guide to Interview Preparation 
=================================================
> [nafSadh](http://sadh.me) //
[notes](https://notes.nafsadh.com) //
[`YaGIP`](http://yagip.sadh.me) / 
[Preface](http://yagip.sadh.me/preface) / 
[Reading Log](http://intvw-rl.sadh.me) /
[Resources](http://yalipr.sadh.me)

This article talks about what are the things to focus on and how to prepare for 
software engineering job interviews. 

## Table of Contents
- [Mindset and approach](#mindset-and-approach)
- [Role](#role)
- [Things to focus on](#things-to-focus-on)
- [Your Profile](#your-profile)
- [Your Story](#your-story)
- [Data Structures and Algorithms](#data-structures-and-algorithms)
  - [Topics](#dsa-topics)
  - [Reading Materials](#dsa-reading-materials)
- [The Coding Interview](#the-coding-interview)  
   - [Types](#types-of-coding-interview)
   - [Screening rounds](#screening-rounds)
   - [The PREP](#preparing-for-the-coding-interview)
        - [Practice](#practice)
        - [Study](#study-to-learn)
        - [Collaborate](#collaborate)
        - [Pair programming prep](#preparing-for-pair-programming-interviews)
        - [Screening round prep](#preparing-for-screening-rounds)

###### abbr.
I am using following abbreviations in this document:

- CSCQ -- [r/cscareerquestions](https://www.reddit.com/r/cscareerquestions/) subreddit 
- LC -- [LeetCode](http://leetcode.com) 

###### legends
- 🕶 - take a very brief look into the topic, you do not have to grok it
- 🔬 - deep dive into the topic, grok it
- ✨ - if you have time, please understand these topic well
- 🌪 - these topic needs very advanced understanding, if you can learn about those then awesome, 
but realistically I don't expect questions from these topics 
- 🔍 - search
<hr/>

## Mindset and approach
Having a right mindset is helpful. What is right for you may be different from 
someone else. But, invariably do these:

- Love your current job (or fake it)
- Practice effectively regularly (more on it later)
- Aim high
- Interview with more than a few companies at once
- Always thrive to better yourself


## Role
I am a software engineer, and this note is about interviewing for 
software engineering roles. Titles vary; but usually:
- Software Engineer
- Software Development Engineer

Often shortened as SE, SWE, SDE etc. For more info visit [level.fyi](http://level.fyi).
There would be a lot of qualifiers; e.g.: Senior SE/SDE/SWE, Staff ~.
Manager roles may be titled as: Software Engineering Manager, Engineering 
Manager, Director of Engineering etc. 

## Things to focus on
As a software engineer you need to focus on the following things:

- Your profile (LinkedIn and resume) 
- Your story (what story do you want to recruiters/mangers/peers)
- Understanding basic data structures and algorithms
- Problem solving and programming skill
- Understanding of software systems (system design, architecture, API design etc.)
- Understanding of software development process and lifecycle (SDLC, CD, CI etc)
- Interviewing (Applying/Getting interview requests and timing)
- Knowing your worth
- Making a decision


## Your Profile
Resume is important for job search. But, today, LinkedIn is the most important
form of profile. You have more room to list all of your achievements, voluntary 
works and what not. So, try to polish your LinkedIn profile. Do not exaggerate 
or lie. Remove stale info. Proudly showcase what you have done. For each role,
describe what you worked on, list your projects so on so forth. It is nice to 
have recommendations and endorsements, but these or of subjective value. 

Resumes should be strictly one page, should have your contact info and list your
relevant jobs and education. Read CSCQ FAQ on 
[resume](https://www.reddit.com/r/cscareerquestions/wiki/index#wiki_resumes) 
and utilize their threads on 
[resume review](https://www.reddit.com/r/cscareerquestions/search?q=Resume+Advice+Thread&restrict_sr=on&sort=new&t=all).



## Your Story
- What is your elevator pitch? 
- How can you introduce yourself in less than five minutes?
- Can you speak about yourself for 15-20 minutes?
- What did you do? What interests you? What are you working on?

[Notice how the storytelling changes with time length and format]

Be excited about what you are doing. Be excited about yourself. Exude confidence 
and passion. 
To prepare for this, take some time to reflect on your life and career. Go through 
your good old memories, and, if you can, through your past projects (their 
documentations, demos, videos, presentations, source code -- whatever you have).
If you are currently working, please, make sure you have an understanding of the 
bigger picture and architecture of your current project(s).

Also, reflect on any decisions (technical or otherwise) you have made at work or 
for yourself. Do some introspection. Was that a right decision? Why did you make 
those decisions etc. 

Know thyself. 


## Data Structures and Algorithms 
> DS&A

Understanding most used data structures and algorithms is a must. Depending on
how fresh is your knowledge, you may benefit from reading on them. Make sure that
you understand most of the following:

### DS&A Topics
**Data Structures**
- Arrays, Collections, Dynamic Arrays, Direct Access
- Linked Lists, Doubly LL, Circular LL 
- Stack, Queue, Heap/Priority Queue -- LL & array implementations
- Trees, BSTs, Binary, m-ary trees, Tries 
- Graphs
- Hashed map, hashed set etc. 📃 [hash-maps↗](http://shlegeris.com/2017/01/06/hash-maps)

**Algorithm concepts**

🔬 Basics: 
- Sorting, merge sort, quick sort, bubble sort, insertion sort, bucket sort etc. 
- Binary search
- Iteration, loop invariant

[Note that, you'd probably never be asked directly about these topics. However, a solid understanding of the
 aforementioned topics is the foundation on which you'll build your skills.]

🔬 Intermediate: 
- Recursion
- Back tracking
- Greedy 

✨ Somewhat Advanced: 
- Dynamic programming, memoization
- Graph traversal, BFS, DFS
- Common graph algorithms  
  e.g.:  Djisktra's, Krushkal's, Prim's, Floyd Wasrhall etc. 

🌪 Advanced (can skip):
- Maximum flow
- Number theory
- Randomized algorithms
- Cache oblivious algorithms
- Parallel algorithms


**Related concepts**
- Space and time complexity (Big O notations) 
    📃 [complexity](https://discrete.gr/complexity/), 
    [big-O c/s](http://bigocheatsheet.com/)
- NP hard, NP complete 🕶 

### DS&A Reading Materials
> Everyone has their own style of studying. So, adopt accordingly. 

These are some books that I have found to be useful in the past:
- [Sedgewick](http://a.co/d/9cUnqJI) -- it was my favorite book in undergrad
- [CLRS](http://a.co/d/aVnF8Eu) -- **_the_** algorithm text book
- [Skiena](http://www.algorist.com/) -- design manual, I keep it on my desk
- [DVP](http://cseweb.ucsd.edu/~dasgupta/book/index.html) -- Dasgupta _et al_; 
([↗pdf](http://algorithmics.lsi.upc.edu/docs/Dasgupta-Papadimitriou-Vazirani.pdf))

However, I used following resources to brush up my understanding of algorithms, 

- **💎 [Jeff Erickson](http://algorithms.wtf)** -- lecture notes by an UIUC
 professor, now converted into a book. Especially, chapters: 3 to 8
- Lecture on [Perfect Hashing](https://youtu.be/N0COwN14gt0) by Prof. 
[David Karger](https://w.wiki/8Rf) of MIT
- Lecture on [advanced string data structures](https://youtu.be/F3nbY3hIDLQ) - 
MIT Prof [Erik Demaine](https://w.wiki/8Re) talks about suffix tree and other 
advanced string topics
- [Max sum of non-adj nums](http://blog.gainlo.co/index.php/2016/12/02/uber-interview-question-maximum-sum-non-adjacent-elements/) · on Gainlo
- Dynamic Programming
  - [TopCoder Article](https://www.topcoder.com/community/competitive-programming/tutorials/dynamic-programming-from-novice-to-advanced/)
  - [Refdash](http://blog.refdash.com/dynamic-programming-tutorial-example/) 
  - [CodeChef](https://www.codechef.com/wiki/tutorial-dynamic-programming#Practice_Problems)
- Understanding sliding window on [Project Nayuki](https://www.nayuki.io/page/sliding-window-minimum-maximum-algorithm)
- [Arbitrage opportunity with Bellman-Ford](https://www.dailycodingproblem.com/blog/how-to-find-arbitrage-opportunities-in-python/)

Here is a [log of what I have read](https://intvw.nafsadh.com/reading_log) 
during my preparation. 


## The Coding Interview
> _**Hacking the Coding Interview**_  

Coding interview can feel like playing Russian roulette. You are expected to 
solve some problem, come up with an algorithm and code it within some time 
constraint. This can feel challenging. But, with practice, you  can get better 
at it. 

Preparing for coding interview is often colloquially known as *leetcoding*. This
is because [LeetCode](http://leetcode.com) is the ubiquitous resource that almost
everyone uses for preparations. 

### Types of coding interview
Let us talk about types of coding interviews. The goal of coding interview is to
test your ability to produce useful code. That is what you are primarily being 
hired for. So it makes total sense to test this skill. There some common formats
of coding interviews

- **Classic LC style** interviews: This is the most common format of coding 
interview. Your interviewer will ask you some LC style question and you are 
expected to solve it in 10-50 minutes based on the difficulty of the problem. 
These sessions are usually 45-60 minutes long. Of these, 10-15 are set aside for 
intro and wrap up. That means, you have 30-45 minutes to answer their questions.
<br/>
I have seen people asking questions straight from LeetCode; but I have also seen
questions that cannot be directly mapped to a LC question.
<br/>
Usually you are expected to solve one LC medium or LC hard question in 30-40 
minutes. Some time the interviewer might start with a warm up LC easy question
that you should be able to solve under 10 minutes and then there would be a 
following LC medium question. In a sixty minute interview, you are usually 
expected to solve two LC medium problems. Facebook expects you to solve two 
LC mediums during their 45 minute interview (so realistically one medium problem
under 19 minutes).
<br/>
For phone screening you'd usually do this exercise on a shared online coding 
environment like HackerRank, CoderPad etc. (in some odd case, you may have to 
write code on a Google doc or some other rich text format; may God help you in 
that scenario). On an on-site, generally, you'd write code on a whiteboard, but 
don't be surprised if you are actually coding on paper or on a computer. 

- **Pair Programming** interviews are becoming commonplace nowadays. Here you 
usually get paired with one interviewer and solve a problem incrementally. 
Instead of straight up LC style questions, you start by defining class or object
models or data models for some problem. Ideally, these problems reflect real life
scenario. You start with a simple scenario and gradually add more functionality 
to it. On a 45-60 minute coding session, expect to have 4 parts and 1 bonus part
of the problem.
<br/>
Think of this session as a rapid prototyping or proof of concept development. 
Or think about coding during a hackathon. But. remember that, code cleanliness 
and readability is crucial too.
<br/>
Don't be fooled by the term paired programming. You are supposed to come up with
the algorithm and logic and design.
<br/>
In my humble opinion, being very good at LC mediums and wonderfully fast at your
primary programming language helps you doing well in such interviews
<br/>
📃 Read more on: [Square blog](https://medium.com/square-corner-blog/ace-the-square-pairing-interview-1a886fec98be),
[Dev.to](https://dev.to/sophiedebenedetto/pair-programming-for-interviewees-1eem)
  
- **Online coding challenge**s are often given to you for initial screening. You 
would be given a link to some online IDE (HackerRank, AmCat etc.). When you start
a session you'd see some timed challenges. You'd have to solve those challenges.
Generally these problems are LC easy to medium. 

- ⚠(don't) **Take home Project**: some companies tend to give you a project that 
you can complete within some time. Generally these projects can take between 
6-20 hours of your valuable time. Most experienced dev do not like taking such 
tests. This a horrendous approach, since it takes a lot of your time but does 
not cost a penny to the company. So, they like giving out some projects. My 
personal take is, a interview process should cost proportional time on both end, 
otherwise such process is not a fair process. 


### Screening rounds

Most companies screen their candidates before inviting them to on-site. Screening
can be done using an online assessment (1-2hr) or a phone/video interview session 
(~1hr).   
*Some companies may want you to do longer online assessments or take home
tests. Anything that involves more than 90 minutes of your time and zero minutes
of your time is a big no.*

**Online assessments** then will have some LC style easy to medium problems to
solve. You are generally given a clear problem statement and an online coding 
editor where you can write, run and test codes. Often they will provide 2-3 
explained test cases and more than a few hidden test cases. Often you can run your
code and know if all hidden cases passed. These will be done using platforms like
HackerRank, AmCat etc. 

**Phone interview** is just a single session of on-site interview. Generally they'd
ask one-two LC style easy to medium questions, but some dark soul may also ask a
hard problem. _(It is not difficult to solve a hard problem, just that the remote
nature of the interview often cause technical issues and communication difficulties 
which may eat up time necessary for a hard problem.)_ Some companies may conduct
a remote pair programming session. Nothing to worry about either of these interviews.
One thing to note, even though this round in colloquially known as phone interview
(because originally it was conducted via telephone) it can utilize any remote 
communication tool, including but not limited to telephone calls, Hangout/Skype
etc. or other video conferencing (BlueJeans, Zoom) or online coding interview
platforms (e.g. HackerRank, CoderPad etc.). 


### Preparing for the coding interview
> a.k.a. grinding LeetCode

Preparing for a coding interview is like taking any standardized test; only that
such interviews are by no means standardized. Fear not, most large companies and
big names try to evaluate all of their candidates with one common yardstick. 
So, it is not very difficult to prepare. 

Most common approach is to solve problems on LeetCode.com. However, there are 
about a thousand problems on LC and there are problems outside of LeetCode.com. 
Moreover, if you try to cram solutions, that is not going to work. You are not 
going to see an exact LC problem but some refinement, variation or extension of
LC problems. It is also likely that you'd see a problem which cannot be related 
to some LC problem. Remember, there are engineers who device their won problems 
and there are engineers who just recycle from someone else's. Regardless, the 
goal of these kind of interview is to test your ability to use known algorithms
and data structures to solve some toy problems. They often mimic real life 
problems or are often simplified versions of them. 

#### How to "grind" LeetCode?

##### Prerequisite 
(if you can solve LC easy under ten, then you can skip this step)
First step is to build your base skills. Make sure you have basic understanding
of some of the most used data structures and algorithms:
- implement stacks and queues using both linked lists and arrays 
- implement heap operations (insert, delete and pop) on an array
- implement at least one sort algorithm
- implement binary search
- implement basic operations and traversals on binary trees and BSTs
- read about hashing, understand hash map, dictionaries, sets etc. in your programming language 

Once you are confident about these, try solving LC easy problems. Your goal is to
solve LC easy under ten minutes. 


##### Practice

I found following approaches to be useful:

- Subscribe to [**DailyCodingProblems.com**](http://dailycodingproblems.com). 
They'd email you one problem everyday.  If you upgrade (for ~$7/mo) then, they'd 
also send a detailed article with solutions the next day. What I liked about
them is that, they cover a lot of different types of algorithms, data structures 
and problem solving techniques. Moreover, getting a coding problem daily makes 
sure you approach at least one problem every day.

- LeetCode has few curated collections of problems under their explore tab.  
Solve curated top [medium](https://leetcode.com/explore/interview/card/top-interview-questions-medium/)
and some of curated top [hard](https://leetcode.com/explore/interview/card/top-interview-questions-hard/)
problems. This way, you'd solve wide variety of problem types. 

- When you are comfortable with problems of medium/intermediate difficulty, you 
can start solving hard problems. This is also the time, when you can start 
accepting job interviews and/or start applying. 


###### Most common interview problems 
There is a small collection of problems that covers a wider variety of common
challenges that you may face in an interview. It is a good idea to solve and 
understand all problems listed 
[here](https://jeremyaguilon.me/blog/ranking_interview_questions_by_cram_score).

##### Gauging your problem solving ability
Given enough time and tools, you can solve most medium problems. However, if you
need more than 60-70 minutes for a medium problem, that means you are struggling 
with the problem. So, try to solve a problem first. If you can do it within an 
hour or so, go to discussion, read the article (if there is one) about the 
problem. Look at different approaches to solve the problems and pros and cons of 
each solutions (runtime, space complexity etc.) If you encounter a new data 
structure or a new algorithm read up more about it. If you could not arrive to a
solution within an hour, mark the problem and revisit it after one or two weeks. 

###### Benchmark
Your goal is to be able to solve any LC medium problem under half an hour. 
Usually, a good benchmark would be, being able to solve average LC medium in 
fifteen to twenty minute. 

##### Other platforms for practice 
- Besides LeetCode, [HackerRank](https://www.hackerrank.com/) is also a great 
tool for interview preparation. 

- You can also solve problems in competitive programming platforms such as 
TopCoder, CodeForces, CodeChef etc and solve ACM ICPC problems. Specially, if you
find LeetCode and HackerRank boring then, TopCoder is your arena.

##### Study to learn

When athletes build their physique, they eat and practice. Same goes for building
problem solving skills. Just practicing is not enough, you need to nourish your
brain by providing proper reading materials. Seek to learn both actively and 
passively:

- When you find some new algorithm/ds/approach while solving a problem, you read
up about them. This is passive seeking.
- Besides, you should also actively look for new materials to learn from by 
looking at resources like those listed above


##### Collaborate

Engineers work through collaboration. So, naturally, preparing for interviews 
get better with collaboration. 

- If you have friends who are also preparing for interviews then, do mock 
interviews with each other. Take turns and solve problems. 

- Explain a newly learned concept to your peers.

Often doing these can be difficult for working engineers. To help with that, 
there are online platforms that can pair you up with random strangers.
[Pramp.com](http://pramp.com) is one such platform. Besides practicing with 
friends, it can be beneficial to conduct mock interviews on Pramp with strangers.
Besides, [interviewing.io](https://interviewing.io/) is good too.


#### Preparing for pair programming interviews

From my experience, being good at your work combined with being good at LC style
problem solving helps you do good at pair programming interviews. 

Even though this is called pair programming, it is still an interview where you 
are being judged. So, _you_ are expected to come up with solutions and _you_ are 
expected to do all of the coding. 

Problems in pair programming interviews are generally of medium difficulty. Your
pair may start with asking you to define a model or a class for some toy problem
(often representing a real scenario). They will gradually add more scenarios. 
For each part of this session, you may keep adding more function definitions and 
come up with algorithms for those sub-problems. There are generally 3-4 parts 
and often a fifth bonus question.

Since, these problems are not hard, you are expected to code fluently, come up
with solutions quickly and also be able to come up with test cases, edge cases 
and run tests.

Think of these 45-60 minute pair programming sessions as rapid prototyping 
sessions.

#### Preparing for screening rounds

Since these rounds are similar to on-site coding interviews, preparing for it is 
all the same. Just note that, if you found passing phone screening difficult, it 
is advisable to take way more preparation before going to on-sites. 


<br/>
<hr/>


> 2019 © nafSadh  
> Maintained on [GitHub](https://github.com/nafSadh/intvw-prep-res) by [nafSadh](http://nafSadh.com).   
> Please report issues and add suggestions [here](https://github.com/nafSadh/notes/projects/1).  