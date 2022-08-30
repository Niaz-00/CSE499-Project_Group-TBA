**NORTH SOUTH UNIVERSITY**

![](media/image1.gif)

**Shikhon  
An Interactive Learning Platform for Bangladeshi Children**

A DISSERTATION  
SUBMITTED TO THE DEPARTMENT OF  
ELECTRICAL AND COMPUTER ENGINEERING  
OF NORTH SOUTH UNIVERSITY  
IN THE PARTIAL FULFILMENT OT THE REQUIREMENTS  
FOR THE DEGREE OF  
BACHELOR OF SCIENCE IN  
COMPUTER SCIENCE AND ENGINEERING

**CSE 499B, Fall 2021  
SENIOR DESIGN PROJECT**

# Declaration

It is hereby acknowledged that:

  - No illegitimate procedure has been practiced during the preparation
    of this document.

  - This document does not contain any previously published material
    without proper citation.

  - This document represents our own accomplishment while being
    Undergraduate Students in the North South University.

Sincerely,

<table>
<thead>
<tr class="header">
<th><p><img src="media/image2.jpeg" style="width:0.95219in;height:0.672in" /></p>
<p><strong>Jarif Al Nayem</strong><br />
1721487042</p></th>
<th><p><img src="media/image3.jpg" style="width:1in;height:0.26667in" /></p>
<p><strong>Md. Niaz Mahmud Shihab</strong><br />
1721274042</p></th>
</tr>
</thead>
<tbody>
<tr class="odd">
<td><p><img src="media/image4.jpeg" style="width:1.75652in;height:0.736in" /></p>
<p><strong>Md. Maruf Saklain Lingkon</strong><br />
1721081642</p></td>
<td><p><img src="media/image5.jpeg" style="width:0.96in;height:0.90182in" /></p>
<p><strong>Tasmiah Morol Nilima</strong><br />
1620148042</p></td>
</tr>
</tbody>
</table>

# Approval

I certify that I have read this dissertation and that, in my opinion, it
is fully adequate  
in scope and quality as a dissertation.

I certify that I have read this dissertation and that, in my opinion, it
is fully adequate  
in scope and quality as a dissertation.

# Abstract

We have reached a point of technological advancement where computers are
integrated in almost every corner of our lives. With that, the demand of
talented individuals who are adept in the world of computer programming
is also increasing. That is why, most countries in the world are
creating an education system in such way that kids will get interested
in programming at an early age. But explaining the concept of
programming to the young minds is a bit tricky. We can’t teach them the
concept the way it is done to the adults. That is where the visual block
programming comes into picture. Most kids are naturally drawn to
pictures and animations. That is why we are seeing the integration of
these things even in our traditional teaching methods.  Block based
programming languages are created in such a way that the user won’t have
to learn the complex code behind the blocks and will be able to play
with the blocks and create different animations and moving objects. This
became the perfect tool to introduce programming to kids.  With this
foundation, various online platforms were created with where block-based
programming was implemented to attract the children. Scratch is the most
prominent of them all as it is very popular among many English-speaking
countries. But there is no such platform available in Bangla language. A
platform like this could attract many Bangladeshi kids into the
wonderful world of computer programming. With that goal in mind, we are
creating a platform where kids could play with blocks that have Bangla
titles and get interested in programming.

# Acknowledgements

At first, we’d like to remember the Almighty Allah for allowing us to
complete this report in time and successfully.

We would like to express our debt of gratitude to our honorable
supervisor **Dr. Md Shahriar Karim**, Assistant Professor, North South
University, for his constant inspiration, constructive criticism,
generous guidance, and deep interest in this study. Without his proper
guide line, the study might not be possible properly to complete in due
time.

We’d like to express our sincere thanks to the chair of Department of
Electrical and Computer Engineering.

We’d also like to thank so many amazing researchers all over the world
who are currently working on this very issue. For this research we were
not able to do any in person surveys or analysis because of COVID 19
situation. So, a good portion of our work depended on these amazing
researches, journals, periodicals and research papers that were
published by so many amazing researchers. Mentioning all of them here is
almost impossible. We’ve acknowledged them through countless citations
in all over our main body of report.

At last, we would like to thank our dear sir **Dr. Md Shahriar Karim**
once again for giving us the opportunity to do this research which
enriched all of us with our new found knowledge.

# Contents

[Declaration ii](#_Toc98005771)

[Approval iii](#approval)

[Abstract iv](#abstract)

[Acknowledgements v](#acknowledgements)

[Contents vi](#contents)

[Table of Illustrations viii](#table-of-illustrations)

[1 Introduction and Motivation 9](#introduction-and-motivation)

[1.1 Introduction 9](#introduction)

[1.2 Motivation 11](#motivation)

[1.3 Overall System Architecture 12](#overall-system-architecture)

[2 Literature Review 13](#literature-review)

[2.1 Interactive Learning Platforms and Bangladesh
13](#interactive-learning-platforms-and-bangladesh)

[2.2 Programming Platform for Children
14](#programming-platform-for-children)

[3 Method and Methodology 15](#method-and-methodology)

[3.1 Materials and Personnel 15](#materials-and-personnel)

[3.2 Design Approach and Content Planning
17](#design-approach-and-content-planning)

[3.2.1 Elementary Contents 17](#elementary-contents)

[3.2.2 Pre-SSC Contents 18](#pre-ssc-contents)

[3.2.3 Games and Animations 19](#games-and-animations)

[4 Result and Analysis 20](#result-and-analysis)

[4.1 Initial Contents 20](#initial-contents)

[4.2 Focused Survey Design 21](#focused-survey-design)

[4.2.1 Generalized Questions 21](#generalized-questions)

[4.2.2 Concentrated Questions 23](#concentrated-questions)

[4.2.3 Survey on Block-Based Programming
25](#survey-on-block-based-programming)

[4.3 Focused Survey Result 27](#focused-survey-result)

[4.3.1 Generalized Question Result 27](#generalized-question-result)

[4.3.2 Class 5 27](#class-5)

[4.3.3 Class 8 28](#class-8)

[4.3.4 Programming Portion Result 29](#programming-portion-result)

[4.4 Result 30](#result)

[4.4.1 Elementary Contents 30](#elementary-contents-1)

[4.4.2 Pre-SSC Contents 33](#pre-ssc-contents-1)

[4.5 Android Application 36](#android-application)

[5 Conclusion and Future Work 40](#conclusion-and-future-work)

[5.1 Future Works 40](#future-works)

[5.2 Conclusion 41](#conclusion)

[6 References 42](#_Toc98005808)

# Table of Illustrations

[Figure 1: System architecture design that provides the basic structure
of the platform 12](#_Toc98005916)

[Figure 2: Blockly and Scratch Block Configuration 16](#_Toc98005917)

[Figure 3: Class 5’s consensus on usability of the platform
27](#_Toc98005918)

[Figure 4: Class 5’s consensus on content satisfaction
28](#_Toc98005919)

[Figure 5: Class 8’s consensus on usability of the platform
28](#_Toc98005920)

[Figure 6: All Students’ consensus on Programming Section
29](#_Toc98005921)

[Figure 7: Addition-Subtraction simulation to teach fundamental
Mathematical theories 30](#_Toc98005922)

[Figure 8: Multiplication-Division simulation to teach fundamental
Mathematical theories 30](#_Toc98005923)

[Figure 9: Interactive “Map” describer 31](#_Toc98005924)

[Figure 10: Interactive “Basic Human Anatomy” describer
32](#_Toc98005925)

[Figure 11: Equivalent Fractions simulator to teach about fractions
32](#_Toc98005926)

[Figure 12: Interactive “Cell” describer 33](#_Toc98005927)

[Figure 13: Interactive “White Blood Cell” describer 33](#_Toc98005928)

[Figure 14: Acid-Base Game to teach fundamental Acid-Base
characteristics 34](#_Toc98005929)

[Figure 15: Interactive Electrical Circuits to show the electron and
current flow in a simple circuit 35](#_Toc98005930)

[Figure 16: Android App to offer multi-platform experience and increase
the usability of our system 36](#_Toc98005931)

[Figure 17: Contact Page of the android app 37](#_Toc98005932)

[Figure 18: Direct e-mail Contact 38](#_Toc98005933)

[Figure 19: Direct Phone Contact 38](#_Toc98005934)

[Figure 20: Comment to share user opinions and problems about any
specific project 39](#_Toc98005935)

**  
**

# Introduction and Motivation

## Introduction

There have been numerous studies conducted before on how developing
countries are lacking behind on implementing effective education system.
Bangladesh as a nation is not far from that assumption. It is not so
much that what we are learning in our schools are bad or out of place,
we are just falling behind on implementing environments that are
innovative and new. This is especially the case when it comes to kids.

While kids in other countries are familiarizing themselves with
technology at an early stage and learning from it, we are still on our
way to find suitable options to integrate technology in our learning
process. There is also a debate on how to handle this situation also.
Integrating technology on our current system is not the answer to all of
this. The focus of our system should be making it easier for children to
acquire knowledge. This is where technology and programming can be of
big help.

We are not just lacking behind in terms of traditional teaching methods.
Our children are also late most of the time in many other educational
technological activities. Internationally, kids are learning to use
computer and even computer programming at an early age. There are
countries where kids are learning programming at as early as 7 years
old. Our modern world is heavily revolved around computers and computer
programming. While the children in other countries are learning
difficult programming methods at an early age, kids in Bangladesh aren’t
even learning the basic concepts. Some may say that teaching complex
methods like programming to children may be difficult but there are
certainly methods that can ease that concern.

Children at an early age are really interested in visual learning. That
is why it is thought that construction-based coding activities will be
able to grab their attention. Various studies have already been
conducted on this topic and it is understood that most children managed
to adopt deliberative thinking and was able to understand and imitate
mechanical thinking while coding in a block-based environment like
scratch \[1\]. Block based programming platforms like scratch can easily
grab the attention of the children with their visually appealing block
systems and animations. Kids can master the foundational coding concepts
while playing with these blocks \[2\]. 

Platforms like Scratch are surely popular but they are limited to
English-speaking countries. Even though Scratch has recently added the
Bangla language as their automated Unicode translation, the native
environment still is a very foreign concept to our children from
Bangladesh. It is full of generalized references which could confuse
many children instead of attracting them. That is why an interactive
platform for kids in Bangladesh is badly needed.

Apart from computer programming, visual cues can also help children’s
learning in other areas too. Scientific Experiments are a big example of
that. Experiments and practical handling of scientific instruments are a
must have for all children in order for them to grasp the meaning behind
the theory that they are being taught. That is why, at the end of each
chapter of our science books, we see many different experiments that
ties the chapter’s teaching together. Teachers are supposed to show the
students how exactly these experiments work.

But most of the schools and colleges of Bangladesh do not have the
necessary facilities or the experienced teachers to do these experiments
live. Most of the time, the students just look over the written notes of
the experiments on their book and tries to visualize it without any
hands-on experimentation. This ultimately does not contribute to
anything in their learning process. Even though, the schools are getting
funding slowly, the necessary facilities are still just a dream for
them. That is why an interactive platform for science experiment
simulation could be a huge opportunity for these kids.

## Motivation

Digitalization in our education sector has started almost like 10 to 12
years ago. But have our teaching methods changed that much in that time?
Sure, the kids are not learning from the old and worn-out syllabus but
the learning process that we had are still in place to this date. The
goal of integrating technology was to bring ease to the learning process
but our children are still on that text-based learning path while the
rest of the world are experimenting with different innovative ideas.
Even our neighboring country India has platforms like Byju’s where
children are learning different topics in ways different than the text
books and other traditional oral format \[3\].

Creating an interactive platform where children can interact with
different programs while learning from it is our primary goal. We don’t
want to teach them anything new. We want to present the things that they
are already learning in a different manner to see if they are interested
in visual learning systems. Along with that, we also want to introduce
our children to the amazing world of programming with the help of
block-based programming languages. Platforms like Scratch have already
proved that teaching children programming concept at an early age gives
them slight edge over those who picks up later \[2\].

As things stands right now, most kids in our country are unaware of
basic programming concepts. Without a proper and easy to use platform,
we cannot reach them. As a result, most programmers in our country
starts their programming experience later than those from other
countries. We have already seen the usefulness of block-based
programming and how they can affect children from the success of Scratch
and Scratch Jr. The goal of our project is to use the same concept but
instead of the default blocks, we are going to use blocks that can be
easy to understand for the Bangladeshi children. We are hoping to create
an environment such that kids from our country can relate to them and
learn the basic concepts of programming by playing with them.

## Overall System Architecture

![](media/image6.png)

<span id="_Toc98005916" class="anchor"></span>Figure : System
architecture design that provides the basic structure of the platform

The basic architecture of our platform revolves around two distinct
wings of operations.

  - User Actions

  - System Actions

The user actions revolve around the interaction with the system and its’
components. Specifically, user actions have two directories. User can
interact with the system to edit user information and user can interact
with the system in order to access the blocks for compilation. The
system actions take commands from the users and perform background
operations in order to deliver the desired results.

It is important to mention that the components of the system are
accessible by both types of actions. The system has generalized
components mostly other than the compiler portion which has many
individual private components like ‘Block Translator’, ‘Block Processor’
etc. Most basic component structure looks like this,

  - User Interface

  - Database

  - Block Compiler

  - Communication and Interaction

# Literature Review

## Interactive Learning Platforms and Bangladesh

E-learning platforms has many different features. While there is
abundance of learning platforms on the internet, most of them are not
interactive. Her by interactive we mean to say where students can
interact and change the variables presented on the site. This can be
animations, moving blocks, eye tracking etc. Platforms like these are
can be very effective learning tools as they are very compelling to the
children. Ani Matei and Catalin Vrabie of Romania’s National School of
Political Science and Public Administration think that distant learning
platforms are slowly overtaking the traditional administrative learning
system \[4\].

Some researchers believe that design of the product on the learning
platform may have significant influence on its effectiveness. Meng-Dar
Shieh and His-Yin Hsieh briefly discussed about the motivation and
effectiveness of proper product design on their studies \[5\]. Their
argument was that children’s motivation to go through the desired
platform is heavily dependent on the content and their interactive
aspect \[5\]. In most of the cases, kids did not like contents that are
too tight knitted and are similar to traditional text-based form \[5\].

A group of 7 Indian researchers found that dual mode online platforms
have some amazing results in e-learning \[6\]. Dual mode online
platforms are the type of platforms where along with the provided
content, there are continuous exchange of content between educators and
students. This type of platform is more suitable for older group of
students. But, in a situation like the covid 19 pandemic, this kind of
platforms have also showed their effectiveness for children and their
academic learning process \[6\].

Unfortunately, most of the learning platform in Bangladesh do not have
that smartness factor to them. They are mostly video-based platforms
that creates content in video format \[7\]. Some prime examples could be
’10-Minute School’, ‘Shikkhok Batayon’, ‘Amar Pathshala’ etc. Honestly,
they are pioneering e-learning in Bangladesh specially ’10-Minute
School’ is really popular among young students \[8\]. But these are
not the kind of platform that we are looking to build. We mean to build
a platform where content can come from both sides in an interactive
manner. That is why block-based programming is also a part of our
platform.

## Programming Platform for Children

When we look at other works that are done in this field, we will see
that most of them are done for a generalized term of kids. So, we are
going to work with these generalized studies which are applicable for
all rather than the Bangladesh aspect.

A study by Amanda Strawhacker and Marina Umaschi suggests that
block-based programming can certainly make the kids understand the
concept of programming but their level of understanding and the level of
problem-solving skills are varied in different age groups \[2\]. They
argued that different teaching methods for different age groups like
kids, pre-teen, and teenagers could improve the learning capabilities of
children \[2\]. This concept was also used by Scratch as they launched
‘ScratchEd’ and ‘ScratchJr’ focusing on two different age groups among
kids. Our platform could also use a little diversification but we don’t
see that happening right away. This could be something that can be
implemented in future but right now we are focusing on just one
platform.

Another study by Sofia Papavlasopoulou, Michail Giannakos and Letzia
Jaccheri suggests that children learn the concept of programming very
easily with block-based programming but keeping them interested is a bit
tricky \[1\]. Their study suggested that if the platform can offer
things like new games and changing animations then kids are more likely
to stick to programming without losing their interest \[1\]. Platforms
like Scratch and ScratchJr already has features like these where you can
create small games and share among friends. This is something that can
be easily integrated in our project too.

Thamizh Selvan on the other hand went on a different route with his
study. He looked at different instances of kids learning programming and
tried to understand what format of teaching can guarantee a more complex
understanding of programming while also making it fun \[9\]. His study
found that the usability of the platform greatly influences the
attention of the kids. He suggested that animations and sound are a
great way to keep them interested \[9\]. He also found that kids find
joy by sharing their work and watching other children’s work. Community
sharing is certainly something that we are hoping to achieve.

All these studies focus on the kids and many technical aspects which
makes them interested in programming. We are certainly hoping to
integrate some of these technical aspects which would improve our
platform’s usability. We were hoping to find studies focused on how
breaking language barrier can help with programming study but we could
not find such studies.

# Method and Methodology

Previously we have built the core of the project using all kinds of
visual programming language with Scratch 3.0 and Blockly at the center
of it. In this run of our project work, we have decided to implement
those tools to demonstrate the usefulness of visual programming
languages in first hand. Our goal was to reach the children of all
social classes and make a platform that can attract them naturally. The
platform has to be inclusive to all children of the same age. At first,
we were starting to target children at general. But later we understood
that a more concentrated attention on a select few age group would give
us better result in the long run. That is why we chose two age groups
specifically. We started with Elementary classes and ended with classes
lower than JSC. We have felt that this could be the correct mixture of
target samples.

## Materials and Personnel

As this is an educational development project made by students, we are
not looking to use any large capital expenditure. Our goal is to use
whatever free and open-source developmental tools we can gather and use
them. That is why we looked for materials that has less licensing hassle
and can be used on the go without any legal trouble. Our project is a
software platform based on entirely cloud-hosting. So, we did not need
any kind of hardware materials for this project.

First and foremost, for the kid’s programming part of our platform, we
needed to select a bloc-based programming language. At first, we looked
at Google’s ‘Blockly’. Blockly is a block-based visual programming
language which is used mostly by entry level programmers and it provides
a mostly error-free coding environment with its natural language
integration \[4\]. But it lacked some sophistication and, in the end, we
went with something similar and a language that was actually made in
collaboration with Google’s Blockly.

So, for the compiler of the programming platform, we went with Scratch
3.0 language. We already know the vast popularity of Scratch’s platform
in the realm of kid’s programming. Unlike Blockly, this is already
catered towards and created thinking of children and their growth. Like
Blockly, Scratch 3.0 is also open source and various components of its’s
compiler’s code base is readily available on GitHub.

From the numerous source codes that were available on GitHub for
Scratch, we had to pick one that would be easily developable. At first,
we went with Scratch Blocks. But soon realized that it is only going to
give us the block component but not the full compiler. After some
rigorous searching and researching, we decided to go with Scratch GUI,
as it has a stable code base where all the other components of the
scratch development kit could be inserted into.

![](media/image7.png)

<span id="_Toc98005917" class="anchor"></span>Figure 2: Blockly and
Scratch Block Configuration

Apart from the components of the compiler, for now we built a web-based
platform. This platform was created around the compiler of Scratch. For
this we used some basic web designing languages like HTML, CSS, PHP etc.

Now that we have the materials or building blocks of our project sorted
out, we focused on the personnel who are going to use our platform. Like
we have said before, this is an interactive learning platform for kids
in Bangladesh. So, our primary focus is kids. But so far on our
development, we have only touched the technical aspect of our project
and built the foundation upon which we are going to decorate our
platform. So, we have not yet done a survey or any data collection from
our potential users. We are leaving that for future development.

## Design Approach and Content Planning

For the design of the ‘Explore’ portion of our project, we have first
chosen to follow some of the topics that are taught at school. For this
we decided to go over the contents of text books provided by the NCTB
and use them for the necessary visual programs that we are going to
create in this portion.

As we have said before, the two concentrated age groups include
elementary or primary education class and pre-SSC education class. With
these two groups in our mind, we have selected the following topics from
the text books of NCTB.

### Elementary Contents

All of these contents were selected from NCTB provided curriculum. But
we have taken inspiration in only the topic part. In the actual
execution of these programs, we have stayed with our original plan and
designed the programs in a way that is interactive and holds its
educational integrity at the same time.

  - **Addition-Subtraction:** This program simply interacts with the
    user and performs various addition and subtraction problems along
    with solves it and shows the answer. At the start of the program, we
    offer the option to select between addition and subtraction. Upon
    selecting any of the option, it provides various addition or
    subtraction problems to the user and asks for solution. If the user
    is able to answer the questions correctly then the program adds a
    number to the total score. This continues until the user gets one
    wrong and then it stops calculating the total number of correct
    runs.

  - **Multiplication-Division:** This works in the same way the
    ‘Addition-Subtraction’ program. The UI and user interaction is
    exactly the same. But this time the program offers only
    multiplication and division problems to the user.

  - **Bangladesh:** This is an interactive program which has a goal of
    teaching the history of Bangladesh to the users. This not only
    teaches some historically significant aspects of our country but
    also some geographical aspects.

  - **Basic Anatomy:** This program teaches the basic anatomy to the
    users. As it is under elementary portion of our project, it does not
    include and internal organs or anything. This is basically one for
    one anatomy that are taught in primary schools all over the world.

  - **Equivalent Fractions:** For the final program of this section, we
    have chosen equivalent fraction as the topic. This is a fairly easy
    concept that many children struggle with. We created a simple UI for
    this where users are given bunch of random number and are asked to
    create bunch of fractions that are equivalent to each other. For
    every group of equivalent fractions, the program resets itself and
    provides new options and adds 100 score to the user’s inventory. The
    program ends when the user can no longer make out any more
    equivalent fractions.

### Pre-SSC Contents

This part includes just some of the content provided in pre-SSC text
books in our country. So, this is mostly for class six, seven and
eight’s children. We have focused only on contents from science books
for this portion. Two of these programs are biological, one is chemistry
related and the other can be found in physics section.

  - **Cell:** This is an infographic that shows and tells the different
    parts of an eucaryotic cell’s organelles. The UI is interactive, so
    user can choose whichever part of the cell they want to know about.
    The program will zoom in on that section and offer some detailed
    information and also provide an option to announce the dubbed
    version of the written part.

  - **White Blood Cell:** The inner workings of this program are the
    same as cell. This just focuses more on white blood cells.

  - **Acid-Base Game:** This program offers a bunch of acids and bases
    at the initial period. The users can mix them up together and the
    program will offer a result of the chemical reaction and what salt
    was crated because of their mixing of the two compounds.

  - **Simple Electrical Circuit:** This program shows the inner working
    of a simple electrical circuit. The user can interact with the UI
    and learn how a simple circuit works and how it can be used.

### Games and Animations

This part of the project shows some simple games and animations that can
be made using the provided scratch compiler. This can offer some
refreshments along with some needed educational content for the user.

  - **Nouka-Baich:** A racing game inspired by a popular local boat
    racing competition. It has an option for multiplayer feature where
    two users can interact with each other.

  - **Science Game:** This program provides yet another educational
    program but with its focus on interactive UI, its actually less
    educational and more on the evaluation spectrum.

  - **Car Racing:** A traditional computer car racing game. This is a
    throwback to the early mobile games that are very popular. Like them
    it works in a additive manner and offer rewards for overtaking
    vehicles along the way.

  - **Joy-Bangla Game:** This was initially a passion program for one of
    our group members. Later we decided to add it to the project as it
    has a patriotic aspect to it. It is a traditional click and shoot
    game as you shoot at the target of some war criminals.

  - **Corona Awareness Animation:** Features the popular characters from
    Meena cartoon where Meena and Meethu goes over the various to dos
    during the pandemic to control the spread of corona virus.

# Result and Analysis

## Initial Contents

As per the described design on methodology we conducted our initial
implementation of contents. The contents were created on Scratch 3.0
compiler as it is integrated on our platform. All of the content were
created with visual and auditory features as we have heavily emphasized
how visual and auditory learning can help children in their learning
process \[2\].

The contents do not deviate that much from the information provided in
the NCTB text books but the information presentation helps kids to grasp
the content much faster. Because of the interactive aspect of the
programs, they also do not get bored too early so it delivers on the
promise of engagement.

Initial contents were created as an experimentation as we planned on
changing some specification of the content after getting direct feedback
from both our instructor and the kids. Getting first hand feedback from
children is the best possible way for us to improve on our content. So,
the initial contents had options of changing features. Still, all of
them were complete programs with the necessary features.

On the concept of these programs, we have to admit that we cut some
corners. We made some assumptions on what could be appealing to the
children and what could not. We decided to make the contents of primary
students heavily focused on graphic and animation. This is important for
grabbing their attention and keeping them active on the content. But we
did not do the same for the Pre-SSC contents. This is the early teenage
and teenage groups. We felt like some of them are mature enough to
dislike overuse of animations. So, in their contents we cut down on
moving objects and focused more on simulations and experiments.

We also did the same in terms of auditory aspect. For kids’ contents we
decided to replay the instructions both in text and audio format. As
there are animations involved, audio queues were prominent in this
sector. But for the teenage group, we cut down the audio to the bare
necessity and decided to give them more freedom on their information
intake.

## Focused Survey Design

Previously in the design section, we arranged our content in such a way
so that we can conduct a survey later on to get direct feedback from
children of any primary or high school. We selected class 5 and class 8
for our survey group as they can be a good representation of both
primary and high school level. Most of our content was also focused on
math and science as we felt like getting feedback on these subjects
would be easier as the result from these subjects can be quantified very
easily.

To go to the next phase of our survey, we decided to do two different
surveys on these two focus groups. But that doesn’t mean there wouldn’t
be any generalized questions as both of these groups are going to use
our UI and other functions. We planned to conduct the survey on two
parts. One for the contents provided on the platform and other for the
programming learning feature.

### Generalized Questions

First of all, there will be some general-purpose questions for students
of both of these classes. These questions are crafted in a way that it
will give us an idea about their current learning process and the level
of satisfaction that they have with their current process. The general
part of the questionnaire is mainly to get acquainted with the students
so there is not much to quantify here.

1.  How do you feel at school? (Evaluative)
    
    1.  Happy
    
    2.  Neutral
    
    3.  Sad
    
    4.  Don’t want to come

2.  What is your favorite subject?
    
    1.  Math
    
    2.  English
    
    3.  Sociology
    
    4.  Science
    
    5.  Other \_\_\_\_\_\_\_\_\_

3.  What is the most memorable topic you have learnt recently? (Mention
    one or two) (Evaluative)

\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_.

4.  What made the topic easier to understand?

\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_.

5.  How long did it take to understand that topic?

\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_.

6.  Do the pictures on your text book help you learn faster?
    (Evaluative)
    
    1.  Yes
    
    2.  No
    
    3.  Neutral

7.  Do you have a smartphone or computer at home?
    
    1.  Yes
    
    2.  No

8.  Do you know how to use the internet?
    
    1.  Yes
    
    2.  No

9.  If yes, what do you generally do on smartphone or computer?
    
    1.  Play Games
    
    2.  Watch Videos
    
    3.  Use social media (Facebook and others)
    
    4.  Communicate with friends.
    
    5.  Other \_\_\_\_\_\_\_\_\_\_\_\_\_.

10. Have you ever taken help from the internet to understand any topics?
    
    1.  Yes
    
    2.  No

### Concentrated Questions

After the general-purpose questionnaire, we are going to show some
programs to both of these groups from our platform.

  - For class five, for now we have chosen ‘Small or Big’ program which
    teaches students which number is smaller and which number is greater
    and also help them understand how to make largest and smallest
    possible numbers from some pre given digits. This is a topic from
    the first chapter in the math book given out by NCTB.

  - For class eight, we have chosen ‘White Blood Cell’ program. This
    will help them understand basic structures of a white blood cell.
    This is from chapter two of science book developed by NCTB.

We will also let them interact with other programs and infographics
available on our platform. But the next set of questionnaires will be on
the above two topics.

**Class Five**

1.  Was the program fun to interact with? (Evaluative)
    
    1.  Strongly Disagree
    
    2.  Disagree
    
    3.  Neutral
    
    4.  Agree
    
    5.  Strongly Agree

2.  Do you now have a clear understanding of the problem?
    
    1.  Strongly Disagree
    
    2.  Disagree
    
    3.  Neutral
    
    4.  Agree
    
    5.  Strongly Agree

3.  Which part of the program intrigued you the most?
    
    1.  Animation
    
    2.  How it reacts to your command.
    
    3.  Voice lines.
    
    4.  Other \_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_.

**5, 3,2,4,8 are some digits. Now answer question 4 and 5.**

4.  What is the greatest odd number possible from these digits?

\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_.

5.  What is the smallest even number possible from these digits?

\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_.

6.  Are the animations better than still pictures from your book?
    
    1.  Strongly Disagree
    
    2.  Disagree
    
    3.  Neutral
    
    4.  Agree
    
    5.  Strongly Agree

7.  Does the audio description of the instruction help you understand
    better than reading?
    
    1.  Strongly Disagree
    
    2.  Disagree
    
    3.  Neutral
    
    4.  Agree
    
    5.  Strongly Agree

8.  In the evaluation part, how do you want to interact with the digits?
    
    1.  Dragging them
    
    2.  Clicking them.
    
    3.  Re-arranging them.

9.  Do you feel comfortable using programs like these along with your
    text book?
    
    1.  Strongly Disagree
    
    2.  Disagree
    
    3.  Neutral
    
    4.  Agree
    
    5.  Strongly Agree

10. Would you be interested to make such a program yourself?
    
    1.  Yes
    
    2.  No
    
    3.  I don’t know how to.

This last question will be a segue way to introduce the kids programming
section of the platform. We will then show the Scratch compiler to them
and how it’s used. Similar question was also created on the contents
provided on students from class eight.

### Survey on Block-Based Programming

We designed this part of the survey to gain feedback on the kids’
programming section and what could be improved upon further on.

1.  Making animations seems very hard-
    
    1.  Strongly Disagree
    
    2.  Disagree
    
    3.  Neutral
    
    4.  Agree
    
    5.  Strongly Agree

2.  Instruction for the process was adequate enough-
    
    1.  Strongly Disagree
    
    2.  Disagree
    
    3.  Neutral
    
    4.  Agree
    
    5.  Strongly Agree

3.  Dragging is better than clicking-
    
    1.  Strongly Disagree
    
    2.  Disagree
    
    3.  Neutral
    
    4.  Agree
    
    5.  Strongly Agree

4.  More audio description would be helpful-
    
    1.  Strongly Disagree
    
    2.  Disagree
    
    3.  Neutral
    
    4.  Agree
    
    5.  Strongly Agree

5.  Default language change should be easier-
    
    1.  Strongly Disagree
    
    2.  Disagree
    
    3.  Neutral
    
    4.  Agree
    
    5.  Strongly Agree

6.  Platform should be on mobile devices-
    
    1.  Strongly Disagree
    
    2.  Disagree
    
    3.  Neutral
    
    4.  Agree
    
    5.  Strongly Agree

## Focused Survey Result

### Generalized Question Result

The feedback on the generalized questions is mostly positive towards
trying to find a new form of learning. The children replied positively
on the UI situation as they thought it was very easy to use. For the
primary age group, there was some students who opted for a more colorful
UI.

100% of all students replied that they have smartphones or computer at
home. 70% of them said that they know how to use internet. 40% have said
that they have taken help from internet before on their study. 90% of
the students thought the animations provided on the platform was better
than still pictures on their text books. The rest 10% remained neutral.
There were no negative feedbacks on animation and visual elements of the
platform.

### Class 5

<span class="chart">\[CHART\]</span>

<span id="_Toc98005918" class="anchor"></span>Figure 3: Class 5’s
consensus on usability of the platform

The survey was conducted on 10 class 5 students. The above chart shows
the usability matrix of the evaluative questions. The chart below shows
the content satisfaction from the evaluative questions.

<span class="chart">\[CHART\]</span>

<span id="_Toc98005919" class="anchor"></span>Figure 4: Class 5’s
consensus on content satisfaction

### Class 8

The survey was conducted on 10 students from Betagi Model High School’s
class 8 students. They were provided with the platform technicalities
beforehand. After evaluating all the questions, we are presenting here
the two areas of feedback. One is on the usability of the platform. The
other is the content satisfaction.

<span class="chart">\[CHART\]</span>

<span id="_Toc98005920" class="anchor"></span>Figure 5: Class 8’s
consensus on usability of the platform

<span class="chart">\[CHART\]</span>

Fig 4.4: Class 8’s consensus on content satisfaction

### Programming Portion Result

For this portion, we evaluated the result and compiled it into only
concerns. Rather than focusing on every question’s individual answer, we
focused on what each students felt strongly about on the survey on each
question.

<span class="chart">\[CHART\]</span>

<span id="_Toc98005921" class="anchor"></span>Figure 6: All Students’
consensus on Programming Section

## Result

### Elementary Contents

  - Addition-Subtraction
    
      - An addition subtraction simulation software that teaches the
        fundamental theories of addition and subtraction. The program
        also offers quizzes and interactive puzzles that can be solved
        using fundamental knowledge of addition and subtraction.

![](media/image8.PNG)

<span id="_Toc98005922" class="anchor"></span>Figure 7:
Addition-Subtraction simulation to teach fundamental Mathematical
theories

  - Multiplication-Division
    
      - A multiplication- division simulation software that teaches the
        fundamental theories of multiplication and division. The program
        also offers quizzes and interactive puzzles that can be solved
        using fundamental knowledge of multiplication and division.

![](media/image9.PNG)

<span id="_Toc98005923" class="anchor"></span>Figure 8:
Multiplication-Division simulation to teach fundamental Mathematical
theories

  - Bangladesh
    
      - Offers many geographical facts about Bangladesh in a graphical
        manner instead of words. Clicking on any area of the map will
        trigger a voice command that describes the fundamental
        geographic facts about that area. Children can take part in
        interactive quizzes based on geographical knowledge of
        Bangladesh. To reduce stress of text-based quizzes, all
        implementation done here are done from a graphical standpoint.

![](media/image10.PNG)

<span id="_Toc98005924" class="anchor"></span>Figure 9: Interactive
“Map” describer

  - Basic Anatomy
    
      - Offers basic information about anatomy of a human body. It is
        designed in a way to accustom children of different ages to
        different body parts and their general works. Like the previous
        programs, this is also focused heavily on graphics and voice
        commands as we thought that would attract the attention of kids
        more. Clicking on any specific anatomy on the body would show a
        close-up image and its information. There is also a further
        information tab that links to a Wikipedia page of human anatomy.

![](media/image11.PNG)

<span id="_Toc98005925" class="anchor"></span>Figure 10: Interactive
“Basic Human Anatomy” describer

  - Equivalent Fractions
    
      - This is from class 5’s math book. This program teaches children
        about the basics of equivalent fractions and its usages. The
        content taught in this program is taken from the NCTB text book
        but the information is presented in a new manner that is
        appealing to the children. There is also an interactive puzzle
        game involving equivalent fractions.

![](media/image12.PNG)

<span id="_Toc98005926" class="anchor"></span>Figure 11: Equivalent
Fractions simulator to teach about fractions

### Pre-SSC Contents

  - Cell
    
      - Gives the students the basic idea of what a cell is and provides
        graphical information about a eukaryotic cell. Information is
        presented in both text and voice form as the older kids might
        prefer either of them. Clicking on any part of the cell will
        prompt a new window which will show or say information about
        that specific part.

![](media/image13.PNG)

<span id="_Toc98005927" class="anchor"></span>Figure 12: Interactive
“Cell” describer

  - White Blood Cell
    
      - This content is taken from class 8’s science textbook. This
        program describes what a white blood cell is and its inner
        workings. Similar to the previous program, it provides graphical
        interpretation of white blood cell rather than focusing on the
        text-based information that is provided in our children’s text
        books. Both text and voice-based presentation is applied here
        also.

![](media/image14.PNG)

<span id="_Toc98005928" class="anchor"></span>Figure 13: Interactive
“White Blood Cell” describer

  - Acid-Base Game
    
      - Provides information on acid and base’s nature in a puzzle form
        and students learn different aspects of these chemicals through
        interactions rather than information memorizing. Each level of
        the game opens with some basic information on the nature of acid
        and base and their relation. Based on that information, the
        students are then asked to complete different tasks. As the
        level of the game progresses, the difficulty and depth of
        information presented also increases.

![](media/image15.PNG)

<span id="_Toc98005929" class="anchor"></span>Figure 14: Acid-Base Game
to teach fundamental Acid-Base characteristics

  - Simple Electrical Circuit
    
      - This gives a demonstration of a simple electrical circuit that
        is provided in our high school text books. Rather than a still
        picture, this demonstration happens live and students are able
        to see how electrons travel from negative to positive end. The
        interactive nature of the program dictates the circuit such a
        way that students are able to remove and add more components and
        are able to see what changes happens in real time. This program
        is useful for students who don’t have practical knowledge of
        electrical circuits.

![](media/image16.PNG)

<span id="_Toc98005930" class="anchor"></span>Figure 15: Interactive
Electrical Circuits to show the electron and current flow in a simple
circuit

## Android Application

![](media/image17.png)

<span id="_Toc98005931" class="anchor"></span>Figure 16: Android App to
offer multi-platform experience and increase the usability of our system

The homepage contains,

1.  Directing button (Top left) which leads to explore our website.

2.  Drawing button (Top right), to create drawings  

3.  Download e-books button (Bottom left), to download pdf version of
    text books from class 5 to class 10

4.  Ask for assistance button (Bottom right), to ask for help or any
    other assistance

The navigation buttons below,

1.  Home button (Bottom left), to return to home page

2.  News button (Bottom middle), to get updated about the latest
    educational news.

3.  Contact button (Bottom right), to contact us for any queries

Basically, this app is to help the kids in their education by providing
them news and updates. So, the “news button” is mostly the helpful one.
After that the “Ask for assistance” option will help them clear their
confusions about anything. That will work like a feed so that everyone
can share their problems and see the other’s. We will be updating this
app according to user needs. This is going to be the basic launch.

![](media/image18.png)

<span id="_Toc98005932" class="anchor"></span>Figure 17: Contact Page of
the android app

This is the contact page. Clicking on email will directly generate the
user to send mail page. The default receiver is one of our group
members. Also, the call button will directly call our hotline. No need
to insert the email address and phone number manually.

![](media/image19.png)

<span id="_Toc98005933" class="anchor"></span>Figure 18: Direct e-mail
Contact

![](media/image20.png)

<span id="_Toc98005934" class="anchor"></span>Figure 19: Direct Phone
Contact

This is the comments page. We added our project to firebase which will
save all the comments added in this section.

![](media/image21.png)

<span id="_Toc98005935" class="anchor"></span>Figure 20: Comment to
share user opinions and problems about any specific project

# Conclusion and Future Work

## Future Works

We wanted to add a lot of features into our project. But due to time and
significant skill limitation, we had to fall short. But still we are
hopeful that we have brought our project to a level where it can be
further improved upon very easily. Some of these improvements need just
library addition and integration work. Most of the heavy lifting code is
already present. So, let’s look at areas that could be improved upon in
future:

  - A working offline version of our project was our goal from the very
    beginning. We have already built the offline version of our website.
    But the Scratch atmosphere has some node js issues that we could not
    figure out so far.

  - Seamless mobile and web integration is also in our vicinity. For
    now, we have both of the platform ready but apart from key features
    like database, most options don’t work in unison with the others.

  - We can be further trim down rendering time for the integrated
    programs with the help of AI integration. We have already trimmed
    down significant portion of waiting time. But AI integration on the
    platform can be more advantageous in this section in the future.

  - More robust scientific simulator is our goal for future. We have
    already built some of the simulation programs like circuits and
    cells. But with the help of Scratch, we can also make a fully
    automated rendering program that can work as a scientific simulator.
    This is a big task that we are hoping to implement down the road.

## Conclusion

Modern world is developing at an alarming rate. The children from other
developed countries are getting necessary attention and the support
necessary to develop their cognitive and problem-solving skill. They are
picking up various technological knowledge at an early stage. But
children from our country are lagging behind in these early
developments. It is not at all their fault because we as a society are
failing to provide neither the guidance nor the necessary resources that
they need. So, a platform like ours could help to open up these kids to
some new possibilities and help them get those early developments so
that they don’t lag behind the rest of the world. We have worked and
will continue to work towards that goal and further improve our
platform.

# References

|  |  |
|  |  |
|  |  |
|  |  |
|  |  |
|  |  |
|  |  |
|  |  |
|  |  |
|  |  |
|  |  |
|  |  |
|  |  |

\[1\] S. Papavlasopoulou, M. N. Giannakos and L. Jaccheri, "Exploring
children's learning experience in constructionism-based coding
activities through design-based research," *Computers in Human
Behavior,* vol. 99, pp. 415-427, 2019. \[2\] A. Strawhacker and M. U.
Bers, "What they learn when they learn coding: investigating cognitive
domains and computer programming knowledge in young children,"
*Educational Technology Research and Development,* vol. 67, p. 541–575,
2019. \[3\] India CSR, "BYJU’S to Empower Children with Free Learning
Program," CSR India, December 2021. \[Online\]. Available:
https://indiacsr.in/byjus-to-empower-children-with-free-learning-program/.\[4\]
A. Matei and C. Vrabie, "E-Learning Platforms Supporting the Educational
Effectiveness of Distance Learning Programme: A Comparative Study on
Administrative Sciences," *Procedia: Social and Behavioral Sciences,*
vol. 93, pp. 526-530, 2013. \[5\] M.-D. Shieh and H.-Y. Hsieh, "Study of
Influence of Different Models of E-Learning Content Product Design on
Students' Learning Motivation and Effectiveness," *Frontiers in
Psychology,* 2021. \[6\] R. Mahaja, K. Gupta, S. Kaur, K. T. Sidhu, U.
Kaur, P. K. Goyal and S. Bedi. \[7\] Sahrifuzzaman, "E-learning: 5
Bangladeshi platforms to look out for," TBS, 21 January 2021.
\[Online\]. Available:
https://www.tbsnews.net/feature/pursuit/e-learning-5-bangladeshi-platforms-look-out-189121.\[8\]
Prothom Alo, "Celebrate September through learning with Likee and ‘10
Minute School’," Prothom Alo, 19 September 2021. \[Online\]. Available:
https://en.prothomalo.com/corporate/local/celebrate-september-through-learning-with-likee-and-10-minute-school.\[9\]
T. Selvan, "Case study: Making programming fun to learn for kids," 25
December 2020. \[Online\]. Available:
https://bootcamp.uxdesign.cc/making-programming-fun-to-learn-for-kids-9-15-2a6bf22209ef.
\[Accessed August 2021\].\[10\] "Wikipedia," \[Online\]. Available:
https://en.wikipedia.org/wiki/Solar\_System.\[11\] "Stardome Observatory
Planetarium," \[Online\]. Available:
https://www.stardome.org.nz/wp-content/uploads/2016/10/WEB-PDFs\_solar-system-chart\_2016.pdf.\[12\]
"Wikipedia," \[Online\]. Available: https://en.wikipedia.org/wiki/Earth.
