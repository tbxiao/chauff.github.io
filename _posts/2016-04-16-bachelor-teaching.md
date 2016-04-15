---
layout: post
title: Reflections on teaching a large Bachelor course
---

Together with one of my colleagues (Alessandro Bozzon), I teach a Bachelor course 
called *Web and Database Technology* within the Technical Computer Science degree program at TU Delft.
The course is not only compulsory for our first year Computer Science students, but also for all those
students choosing Software Design & Application as their minor. 

This means that we usually have to deal with more than 300 students (the most recent edition had 320)
in the classroom - some of whom had never written a line of HTML before, others had 2-3 years of 
JavaScript programming experience already.

The course has a standard structure: two lectures (90 minutes each) and one 4-hour lab session per week for 
eight weeks. The midterm and final exam each account for 40% of the grade (~35 multiple-choice questions per 
exam), the lab project is worth the remaining 20%. I teach the *Web technology* part (8 of the 15 lectures).

## The problem
One aspect of large classes I continously battle with is how exactly to *engage* such a large number
of students. Nothing is worse than 300 students looking down at you (or more
likely at their laptops and smartphones) bored or completely lost 20 minutes into a 90 minute lectures. 
In the last two years I mostly relied on [FeedbackFruits](https://secure.feedbackfruits.com/) 
(a Web platform that turns any browser-enabled device into a clicker) to test the students' level 
of understanding through **multiple-choice questions**. My questions tend to look like this:

<img src="../img/mc-question-ti1506.png" width="600px">

or this:

<img src="../img/mc-question-ti1506-2.png" width="600px">

Unfortunately, I don't learn very much from the students' answers:

<img src="../img/mc-question-answers-ti1506.png" width="600px">

All I know is that 9% of the students got it right - I have no idea  **why** the rest of the class failed to answer
the question correctly. I either have the choice to take a stab in the dark and explain some of the material one 
more time or I move on to the next topic. Both options are unsatisfactory for the students and myself.

In this year's edition of the course we<sup>1</sup> addressed this issue in two ways:
+ We provided screencasts of almost all lectures: instead of simply recording ourselves during the lectures, we
created between 3 and 6 video segments per lecture. Students that were not able to follow the course should be 
able to catch up by watching the screencasts.
+ In some of the lectures we replaced FeedbackFruits with [ASQ](http://asq.inf.usi.ch/), which provides a much richer set of question types and a much richer set of realtime feedback, enabling *data analytics in the classroom* - who wouldn't want that!

So, how did we fare?

## Screencasts

Did any of the students actually watch the screencasts? I hoped so, considering the fact that attendance declined considerably over time (from >300 students at the beginning to ~180 students in the last lecture). Since we uploaded
all screencasts to YouTube, analytics are available with the click of a button. To make sense of the graph, I also
added the four (for the student) important milestones of the course: the midterm and final as well as their resits.

<img src="../img/watchtime-ti1506.png" width="900px">

The trend is not what I had hoped to see: at the beginning (when almost all students attended the lectures) the students watched more screencasts without a direct incentive (a midter/exam the next day) than in the later weeks
of the course. A month into the course, the students have settled on a strategy: to watch the screencasts 1 or at most 2
days before the test.

How many students did watch the individual screencasts? Again, YouTube Analytics has a straight answer:

<img src="../img/videos-ti1506.png" width="900px">

None of the screencasts hits 300 views, so not all students feel the need to rely on them to prepare for their tests.
Although I cut down the lectures into digestable pieces (of 10-15 minutes), none of them reached an average of 50% view
time (final column). As a side note, I have no idea why the cookies screencast is the most watched one, compared to some
of the other screencasts (node.js and JavaScript design patterns for instance) this is a rather easy topic.

The screencasts received high scores in the student satisfaction ratings, though based on the usage statistics I have doubts that the students actually benefitted from them in their learning.

## ASQ







<sub>
<sup>1</sup> Whenever I use '*we*' in this post I mean the entire course, not just *my* Web technology part.
</sub>

