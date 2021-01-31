**This syllabus is effective as of Sunday, January 31, 2021 at 04:49
PM**

## Course Information

-   **Instructors:**
    -   Abhijit Dasgupta (abhijit.dasgupta at georgetown.edu)
    -   Marck Vaisman (marck.vaisman at georgetown.edu)
-   **TA’s:**
    -   Anderson Monken (aem303)
    -   Yunice Xiao (yx197)
    -   Nicole Yoder (ny130)
-   **Class Schedule:**
    -   Class meets Tuesdays 6:30-9:00pm
    -   Recurring Zoom Link (GU credentials required):
        <https://georgetown.zoom.us/j/xxxxxxxxxxx>
    -   Both sections meet together

### Course Description

Data is everywhere! Many times, it’s just too big to work with
traditional tools. This is a hands-on, practical workshop style course
about using cloud computing resources to do analysis and manipulation of
datasets that are too large to fit on a single machine and/or analyzed
with traditional tools. The course will focus on Spark, MapReduce, the
Hadoop Ecosystem and other tools.

You will understand how to acquire and/or ingest the data, and then
massage, clean, transform, analyze, and model it within the context of
big data analytics. You will be able to think more programmatically and
logically about your big data needs, tools and issues.

### Course Objectives

By the end of the term, you will to be able to:

-   Operate big data tools and cloud infrastructure, including Spark
    (with all of Spark’s APIs), MapReduce, Hadoop, and other tools in
    the big data ecosystem
-   Develop strategies to break down large problems and datasets into
    manageable pieces
-   Recognize and use ancillary tools that support big data processing,
    including git and the Linux command line
-   Setup and manage big data infrastructure and tools in the cloud on
    Microsoft Azure and Amazon Web Services
-   Identify broad spectrum resources and documentation to remain
    current with big data tools and developments
-   Execute a big data analytics exercise from start to finish: ingest,
    wrangle, clean, analyze, store and present

### Pre-requisites

-   Proficiency with Python, R, and and SQL. **Note:** We will use
    Python as the primary interface to Apache Spark, through
    [PySpark](https://spark.apache.org/docs/latest/api/python/index.html)
-   Familiarity with programming concepts such as flow control,
    input/output, variable assignment

## Mandatory Pre-Work

This is a technical course where you will use the [command
line](https://en.wikipedia.org/wiki/Command-line_interface),
[git](https://en.wikipedia.org/wiki/Git) and
[SQL](https://en.wikipedia.org/wiki/SQL), among other tools. You will
use [ssh](https://en.wikipedia.org/wiki/SSH_(Secure_Shell)) to connect
to remote machines.

You will use the command line and terminal heavily in this course.
Please take a look at the following depending on your laptop’s operating
system:

-   **Windows users:** Students with Windows machines will be using
    PowerShell as the terminal for command line operations. [Please read
    this
    article](https://www.howtogeek.com/336775/how-to-enable-and-use-windows-10s-built-in-ssh-commands/)
    to enable it on your machine. **You will need the latest version of
    Windows 10, make sure to update your machine!** Even if you have
    PuTTY or another ssh client installed, we will be using
    [PowerShell](https://docs.microsoft.com/en-us/powershell/scripting/getting-started/getting-started-with-windows-powershell?view=powershell-7)
    as the terminal in this course and will not support anything else.
-   **Mac users:** Macs have a built-in Terminal. I prefer using
    [iTerm](https://www.iterm2.com/) as an alternate Terminal
    application. I’ve been using it for years and I love it. This is not
    required, but highly recommended.
-   **Linux users:** Linux machines have a built-in terminal.

**You must complete the pre-work before the first class meeting on
Tuesday, January 26.** There will be a quiz to assess your knowledge of
the pre-work. Spend a few hours on the lessons listed below (which are
the key ones for this course), from [MIT’s Missing Semester of CS
Education](https://missing.csail.mit.edu/).

-   Lesson 1 - Course overview and the shell
    [content](https://missing.csail.mit.edu/2020/course-shell/)
    [video](https://youtu.be/Z56Jmr9Z34Q)
-   Lesson 2 - Shell Tools and Scripting
    [content](https://missing.csail.mit.edu/2020/shell-tools/)
    [video](https://youtu.be/kgII-YWo3Zw)
-   Lesson 3 - Editors (Vim)
    [content](https://missing.csail.mit.edu/2020/editors/)
    [video](https://youtu.be/a6Q8Na575qc)
-   Lesson 4 - Data Wrangling
    [content](https://missing.csail.mit.edu/2020/data-wrangling/)
    [video](https://youtu.be/sz_dsktIjt4)
-   Lesson 5 - Command line environment
    [content](https://missing.csail.mit.edu/2020/command-line/)
    [video](https://youtu.be/e8BO_dYxk5c)
-   Lesson 6 - Version Control (git)
    [content](https://missing.csail.mit.edu/2020/version-control/)
    [video](https://youtu.be/2sjqTHE0zok)

Some additional resources for you to complement the six lessons above.
These are not required, but highly encouraged:

-   [git - the simple guide](http://rogerdudler.github.io/git-guide/)
-   [Nico Riedmann’s Learn git concepts, not
    commands](https://dev.to/unseenwizzard/learn-git-concepts-not-commands-4gjc)
-   [SQLBolt - Learn SQL with simple, interactive
    exercises](https://sqlbolt.com/)

## Books, Software and Cloud Resources

### Readings (for assigned readings)

There is no required textbook for the course. We have selected specific
chapters from several sources as well as several fundamental papers in
the big data space, and these will be provided to you in PDF format. We
may also provide supplemental materials (articles, links, videos, etc.)
to complement the readings. **You must read assigned readings prior to
the lectures.**

### Cloud Resources

You will use cloud resources on [Microsoft
Azure](https://azure.microsoft.com/en-us/) and [Amazon Web
Services](http://aws.amazon.com). We will discuss how to setup your
accounts and environments in class and lab within the first couple of
weeks. You will get credits on both platforms that will be enough to
support your coursework throughout the semester.

**WARNING: IT IS YOUR RESPONSIBILITY TO MANAGE THE CREDITS AND RESOURCES
PROVIDED TO YOU. YOU MUST SHUT DOWN YOUR CLOUD RESOURCES WHEN NOT IN
USE. IF YOU RUN OUT OF CREDITS BECAUSE OF MIS-MANAGEMENT, WE CANNOT HELP
YOU.**

## Learning Activities

This is a hands-on, practical, workshop style course that provides
opportunities to use the tools and techniques discussed in class.
Although this is not a programming course per se, there is programming
involved.

### Lectures and In-Class Labs

The course is split into a lecture/lab format. During the lecture, we
will discuss the concepts and techniques. During the lab sessions, you
will be completing exercises and following examples which are designed
to show you how to implement the ideas and concepts with different
tools.

Some class meetings may be more lecture focused, some may be lab
focused. Lectures may not cover all the material.

### Quizzes

Quizzes are unannounced and will be given during lecture at random
intervals and times. Quizzes ensure you are keeping up with the material
presented in the class. Quizzes are meant to be brief with a time limit
of 10 minutes, and the material will be drawn from lectures, labs, and
readings.

### Problem Sets

You will be given problem sets as homework assignments. The goal of
these problem sets is to use the big data tools to answer some questions
about large datasets. The problem sets will build on the labs and will
be much more elaborate. Deliverables from the problem sets will usually
include code written for your programs and the output produced.

**Important Note:** We reuse problem set questions, we expect students
not to copy, refer to, or look at the solutions in preparing their
answers. Since this is a graduate-level class, we expect students to
want to learn and not search online for answers.

### Big Data Project

Project details will be posted mid-February.

## Grading and Evaluation

Some assignments are code based, some are qualitivate, and some are a
mix of both. Grading is generally holistic, meaning that there may be no
specific point value for individual elements of a deliverable. Each
deliverable submission is unique and will be compared to all other
submissions.

For code based assignments:

-   We will look at the results files and/or scripts. If the result
    files are exactly what is expected, in the proper format, etc., we
    may run your scripts to make sure they produce the output. If
    everything works, you will get full credit for the problem.
-   If the submitted results are not what is expected, we will look at
    and run your code and provide partial credit wherever possible and
    applicable.

For qualitative/open-ended assignments:

-   If a deliverable exceeds the requirements and expectations, that is
    considered **A** level work.
-   If a deliverable just meets the requirements and expectations, that
    is considered **A-/B+** level work.
-   If a deliverable does not meet the requirements, that is considered
    **B** or lower level work.

Points will be deducted for any of the following reasons:

-   The instructions are not followed
-   There are missing sections in the deliverables
-   The overall presentation and/or writing is sloppy
-   There are no comments in your code
-   There are files in the repository other than those requested
-   There are absolute filename links in your code
-   The repository structure is altered in any way
-   Files are named incorrectly (wrong extensions, wrong case, etc.)

### Late Deliverables

There are no extensions to due dates unless there are extraordinary
circumstances, and those will be determined on a case-by-case basis. If
you if you miss a quiz or and assignment, you will receive a grade of 0
(zero).

We realize life gets in the way sometimes and you may not be able to
come to class or complete an assignment on time. Therefore, in lieu of a
late policy, we will allow you to drop your two lowest quiz grades and
lowest assignment grades. This gives you flexibility if you have to miss
class (not take the quiz) or cannot do an assignment for some reason.

**This does not apply to the final project.**

### Grade Breakdown

-   Quizzes: 20%
-   Assignments: 50%
-   Project: 30%

Total is 100%. We have no plans to curve the final grade and the
following table shows the conversion from points to letter grade.

-   **A:** &gt;= 91.5
-   **A-:** &gt;= 89.5, &lt; 91.5
-   **B+:** &gt;= 87.99, &lt; 89.5
-   **B:** &gt;= 81.5, &lt; 87.99
-   **B-:** &gt;= 79.9, &lt; 81.5
-   **C:** &lt; 79.9

## Course Calendar

This calendar is subject to change. We will make make any changes known
in advance. Also check Canvas.

| Class | Date   | Topics                                                                      | What is Due                        |
|------:|:-------|:----------------------------------------------------------------------------|:-----------------------------------|
|     1 | Jan 26 | Course overview, big data concepts, tools overview (git, ssh, command line) | Complete Pre-Work                  |
|     2 | Feb 02 | Scaling up on a single machine, map, reduce, parallelization                | A1 (Python skills) due Thu 2/4     |
|     3 | Feb 09 | Cloud concepts: IAAS, PAAS, SAAS. Cloud Services.                           | A2 (Parallelization) due Thu 2/11  |
|     4 | Feb 16 | MapReduce, Hadoop, Distributed Filesystems, Hadoop Streaming                |                                    |
|     5 | Feb 23 | Intro to Spark, RDDs, Spark DataFrames, SparkSQL                            | A3 (Hadoop/MapReduce) due Thu 2/25 |
|     6 | Mar 02 | Spark 2                                                                     |                                    |
|     7 | Mar 09 | Spark 3                                                                     |                                    |
|     8 | Mar 16 | Spark 4                                                                     |                                    |

## General Policies & Expectations

-   **Online Zoom Rules**
    -   Please participate and speak while on Zoom. We know it’s harder
        to do classes over Zoom, but we love participation. Ask
        questions. Make comments. Challenge us. Acknowledge us. If we
        speak for the entire class to a silent classroom, it is a lot
        more boring and tiring for everyone.
    -   Focus your attention to the class. Online classes require higher
        level of engagement for everyone. Don’t multitask (you know what
        we mean…)
    -   Turn on your camera. If you have a bad hair day, that’s ok (we
        do too.) We want to see you. If you have bandwidth issues and
        can’t use your camera, we understand as well.
-   **Communication:**
    -   All announcements will be posted on Canvas
    -   We have setup a Slack channel for communication and
        collaboration. Please use this tool for any question you may
        have about the course, about assignments or any technical issue.
        This way everyone can learn from each other’s questions. The
        instructional team will be monitoring and providing answers on a
        regular basis. [See the collaboration rules](#rules) to know
        what is allowed in Slack
    -   Individual emails containing any question that is not personal
        will not be answered
-   **Class materials are for class use only:** Please refrain from
    making your private GitHub repositories or any other class materials
    public. A breach of this request is considered an Honor Code
    Violation.
-   **Open Door Policy:** Please approach or get in touch with us if
    something is not working for you regarding the class, methods, etc.
    Our pledge to you is to provide the best learning experience
    possible. If you have any issue please do not wait until the last
    minute to speak with us. You will find that we are fair, reasonable
    and flexible and we deeply care about your success.

## Academic Integrity and Collaboration - ZERO TOLERANCE POLICY

All students are expected to maintain the highest standards of academic
and personal integrity in pursuit of their education at Georgetown.
**Academic dishonesty in any form is a serious offense, and students
found in violation are subject to academic penalties that include, but
are not limited to, reduced grade, failure of the course, termination
from the program, and revocation of degrees already conferred.** All
students are held to the Georgetown University Honor Code. For more
information about the Honor Code see
[https://honorcouncil.georgetown.edu/]().

We have a ZERO TOLERANCE POLICY and if students are found to be in
violation there will be consequences and the students will be penalized
and reported.

### Rules

-   Any deliverable labeled as individual, is by definition, INDIVIDUAL.
-   All submitted code must be your own. This will be verified for every
    deliverable against every submission, and any similarity greater
    than 60% will be considered to be unauthorized collaboration.
-   All other deliverables must be your own as well.
-   All work must be done on your own cloud resources. This will be
    verified for every deliverable.
-   The following collaboration and communication is allowed in Slack
    -   The discussion of ideas and approaches to problems
    -   The discussion and resolution of any technical issue
    -   Sharing code snippets (a few lines) for a very specific things

## University Policies and Support Services

### Accommodations for students with disabilities

Students with documented disabilities have the right to specific
accommodations that do not fundamentally alter the nature of the course.
Please alert us should you require accommodations.

### Title IX Sexual Misconduct Statement

Please know that as faculty members we are committed to supporting
survivors of sexual misconduct, including relationship violence and
sexual assault. However, university policy also requires us to report
any disclosures about sexual misconduct to the Title IX Coordinator,
whose role is to coordinate the University’s response to sexual
misconduct.

Georgetown has a number of fully confidential professional resources who
can provide support and assistance to survivors of sexual assault and
other forms of sexual misconduct.

More information about campus resources and reporting sexual misconduct
can be found at [http://sexualassault.georgetown.edu]()
