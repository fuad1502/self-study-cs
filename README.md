# Self Study CS

 * [What's this repository for?](#whats-this-repository-for)
 * [Background](#background)
 * [Specialization Plan](#specialization-plan)
 * [Self Study Curriculum Overview and My Progress](#self-study-curriculum-overview-and-my-progress)
 * [Projects & Exercises](#projects-exercises)
    + [Projects](#projects)
    + [Exercises](#exercises)
 * [Topics Breakdown](#topics-breakdown)
 * [Reference](#reference)

## What's this repository for?
Originally, I created this repository to show potential recruiters what I've
been doing in my ~7 months career gap. However, I quickly realized that this
would also be useful to anyone out there who also found themselves wanting to
study everything there is in the computer science field of study by themselves.

## Background
I am an Electrical Engineering graduate and have been working in the hardware
(*RF / electronics / embedded*) industry for over 4 years. However, after
finally getting my dream job abroad at *Keysight Technologies* Malaysia, I
resigned after only working for a shy of 2 years due to some personal reasons.
At that point, I also realized that I am more suited to pursue a career that
allows me to work remotely. Along with [other reasons]() that I wont be
discussing here, **I realized that I want to be in the computing industry.**

However, scrapping away (almost) all of my previous knowledge and 4 years of
experience to start from basically "zero" is not easy. Moreover, I don't want
to only have practical skills that would get me an interview quickly without
having a solid understanding of the fundamentals. From my experience, having a
holistic view of your field of study is the upmost important thing in mastering
your field of study. That's why I searched for a "self study CS curriculum".
And if you're like me, you'll stumble upon [**Teach Yourself Computer
Science**](https://teachyourselfcs.com/). **That is the main source for my self
study journey.**

[**Teach Yourself Computer Science**](https://teachyourselfcs.com/) seems
perfect for me at first. However, I quickly realized that I lack some knowledge
that are not listed there. Moreover, I also still need some practical knowledge
on current technologies to understand how the industry is running today. **With
that additions, I came up with this self study checklist.**

## Specialization Plan
Since the beginning of my journey, I have determined to at least scratch the
surface of every sub domain there is in Computer Science. And I encourage you
to do so to. The reasons are:
- To remove bias when you have to make a decision on which specialization path to
  choose. 
- You might found yourself needing to draw knowledge from multiple domains to
  craft a solution / product.
- It simply is intelectually interesting to see how each of the specialization
  are related and interacts with one another from a holistic view.

However, of course once you feel *confident* that you know the *crux* of each
subdomain, you have to make a decision on what to focus on if you want to be
technically successful. ***For me, I would like to focus on Systems***.

The reason why I love *Systems* the most throughout my study, is because of my
deep curiosity on seeing what's behind the abstraction, to see the complex
machinery that make the systems that we all have taken for granted *just work*.
That's actually the reason why 10 years ago I chose EE, but let's not [get into
that]() here. There are of course further specialization down this road, but
for now, one level of specialization below *Computer Science* is good enough
for me.

## Self Study Curriculum Overview and My Progress
Here is an overview of what I have and will learn throughout my self study
jouney up till now (March 2024). Started studies with progress above 75% are
marked with 🟢, started studies with progress above 25% and below 75% are
marked with 🟡, while studies not yet started are marked with ⚫.

**Note that some topics might get more sub topics with more knowledge acquired.**

| ID    | Topic                             | [Reference](#reference)\*                    | Dependencies | Progress   |
|-------|-----------------------------------|----------------------------------------------|--------------|------------|
| 0     | **Computer Science Fundamentals** |                                              |              |            |
| 0.0   | Algorithms*                       | Algorithm Design Manual                      |              | 🟡         |
| 0.1   | Computer Systems                  | Computer Systems: A Programmer's Perspective |              | 🟢         |
| 0.2   | Computer Networks                 | Computer Networks: A Top Down Approach       |              | 🟡         |
| 0.3   | Computer Architecture             | Computer Architecture                        |              | ⚫         |
| 0.4   | Discrete Mathematics              | Mathematics for Computer Science             |              | 🟡         |
| 0.5   | Programming                       | SICP                                         |              | ⚫         |
| 0.6   | Automata Theory                   | Introduction to Automata Theory              |              | ⚫         |
| 1     | **Software Engineering**          |                                              |              |            |
| 1.0   | Object Oriented Programming       | Head First Java                              |              | 🟢         |
| 1.1   | Design Patterns                   | Head First Design Patterns                   | 1.0          | 🟢         |
| 1.2   | Database Application              | Database Management Systems                  | 0.2          | 🟢         |
| 1.3   | Software Craftmanship             | Clean Code                                   |              | 🟡         |
| 3     | **Advanced Computer Systems**     |                                              |              |            |
| 3.0   | Operating Systems                 | Operating Systems: Three Easy Pieces         | 0.1          | 🟡         |
| 3.1   | Linux                             | The Linux Programming Interface              | 3.0          | ⚫         |
| 3.2   | Database Implementation           | Database Management Systems                  | 1.2          | ⚫         |
| 3.3   | Distributed Systems               | Designing Data Intensive Applications        | 1.2          | ⚫         |
| 4     | **Computer Hardware**             |                                              |              |            |
| 4.0   | RTL Design                        | SystemVerilog for Simulation & Syntehsis     |              | 🟢         |
| 4.1   | RTL Verification                  | SystemVerilog for Verification               | 4.0          | ⚫         |
| 4.2   | Modern Processor Design           | Modern Processor Design                      | 0.1, 0.3     | ⚫         |
| 5     | **Computer Languages**            |                                              |              |            |
| 5.0   | Introduction to Interpreters      | Crafting Interpreters                        |              | 🟡         |
| 5.1   | Compiler Theory                   | Compilers: Principles, Techniques, and Tools | 0.6, 5.0     | ⚫         |
| 6     | **Computer Security**             |                                              |              |            |
| 6.0   | Computer Security                 | Computer Security: Principles & Practice     | 0.1, 0.2     | ⚫         |
| 7     | **Computer Graphics**             |                                              |              |            |
| 7.0   | Computer Graphics                 | 3D Computer Graphics: A Mathematical Intro   |              | ⚫         |
| 8     | **Technologies**                  |                                              |              |            |
| 8.0   | *Programming Languages*           |                                              |              |            |
| 8.0.0 | HTML / CSS / JS                   | MDN Learning Area                            |              | 🟢         |
| 8.0.1 | Rust                              | The Rust Programming Language                |              | 🟢         |
| 8.0.2 | C++                               | A Tour of C++                                |              | 🟡         |
| 8.0.2 | C                                 | The ANSI C Programming Language              |              | 🟢         |
| 8.0.3 | Go                                | A Tour of Go                                 |              | 🟢         |
| 8.0.4 | Java                              | Effective Java                               |              | 🟡         |
| 8.0.6 | Any FP Language                   |                                              |              | ⚫         |
| 8.1   | *Library / Framework*             |                                              |              |            |
| 8.1.0 | React                             | Learn React                                  | 8.0.0        | 🟢         |
| 8.2   | *DevOps Tools*                    |                                              |              |            |
| 8.2.0 | Docker / Podman                   | Docker Guides                                |              | 🟢         |
| 8.2.1 | Make                              | Makefile Tutorial By Example                 |              | 🟢         |
| 8.2.2 | CMake                             | CMake Tutorial                               |              | 🟢         |

\* Notice that most of my references are books. If you like online courses
better, unfortunately you'll need to look it up yourself.

\* *Algorithms is not listed in any of the dependency lists, altough it is
assumed that the Algorithms reference is already read with at least 50%
progress before moving on to other topics.*

## Projects & Exercises
**To really solidify the knowledge of what you've learned**, you'll have to use
that knowledge to solve problems by writing some code. I categorize two ways
that you can do this, by doing projects and exercises. 

**Projects** are usually larger, strikes close to what you might actually do in a
specific target industry, and requires knowledge on various technologies.

**Exercises** on the other hand are small close ended problems that are
specifically designed to test and solidify your knowledge on a very specific
topic, sometimes in a *prepared* learning environment. In contrast to projects,
the resulting code itself *usually* don't have much practical use outside of
the learning environment.

**Both are essential for learning**. Most of the time, you need to do some
exercises before diving into a project. Just doing exercises will deprive you
of a holistic view and practical skills, but just doing projects will deprive
you of really understanding specific things that might otherwise be lost in
abstractions, and therefore hinder your ability to tackle the project.

### Projects
Started and finished (is it ever finished?) projects have an entry in the
repository column.

| Project Problem Statement                              | Repository                            | Related Topics                           | Target Industry           |
|------------------------------------------------------- | ------------------------------------- | ---------------------------------------- | ------------------------- |
| Develop a typing test Web Application                  | <https://github.com/fuad1502/kibi>    | 8.0.0, 8.1.0\*                           | Frontend Web Development  |
| Develop & deploy your own Social Media Web Application | <https://github.com/fuad1502/bilbob>  | 0.2, 1.2, 8.0.0, 8.0.3\*, 8.1.0\*, 8.2.0 | Backend Web Development   |
| Implement a pipelined RISC-V CPU                       | <https://github.com/fuad1502/rvsv>    | 0.1, 4.0                                 | Hardware                  |
| Implement an out of order RISC-V CPU                   |                                       | 0.3, 4.2                                 | Hardware                  |
| Implement a RISC-V Assembler                           | <https://github.com/fuad1502/rubbler> | 0.1, 5.0, 8.0.1\*                        | Systems, Languages        |
| Implement your own RISC-V Kernel                       |                                       | 3.0                                      | Systems                   |
| Implement your own Relational Database                 |                                       | 3.2                                      | Systems                   |
| Implement Lox in a language other than Java\*          | <https://github.com/fuad1502/ceplox>  | 5.0, 8.0.2\*                             | Languages                 |

\* You can use any programming language of your choosing.

### Exercises

| Exercise                                                      | Repository                                             | Related Topics    |
| ------------------------------------------------------------- | ------------------------------------------------------ | ----------------- |
| Wrote Design Pattern examples in a language other than Java\* | <https://github.com/fuad1502/head_first_rust_patterns> | 1.0, 1.1, 8.0.1\* |
| Solve LeetCode problems using multiple languages              | <https://leetcode.com>                                 | 0.0, 8.0.\*       |
| Participate in *Advent of Code* using multiple languages      | <https://github.com/fuad1502/advent_of_code_2023>      | 8.0.\*            |
| Do the lab assignments from the Computer Systems reference    | <https://github.com/fuad1502/csapp>                    | 0.1               |
| Do the *projects* from the Operating Systems reference        | <https://github.com/fuad1502/ostep>                    | 3.0               |
| Do the *exercises* from each book references                  | \*                                                     | \*                |

\* A repository containing my solutions to selected exercises from several book references is given here:

| Book Reference                               | Repository                           |
|--------------------------------------------- | ------------------------------------ |
| Algorithm Design Manual                      | <https://github.com/fuad1502/skiena> |
| Computer Systems: A Programmer's Perspective | <https://github.com/fuad1502/csapp>  |
| Operating Systems: Three Easy Pieces         | <https://github.com/fuad1502/ostep>  |

## Topics Breakdown

## Reference
