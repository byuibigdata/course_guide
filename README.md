# Syllabus

[Schedule a time to visit with me](https://byuidatascience.github.io/visit/hathaway/), if needed.

## Overview

__By the end of the semester, each student will be able to:__

> 1. __Integrate and extend previously learned data science tools to analyze remote and distributed data in business contexts.__   
> 2. __Explore, interpret, conceptualize, and validate assumptions of data at scale.__   
> 3. __Understand the differences and benefits of current industry technologies for big data storage and analysis.__   
> 4. __Leverage distributed computing for analysis.__   

_The course follows [these principles](https://arxiv.org/ftp/arxiv/papers/1612/1612.07140.pdf) of teaching Data Science;_

> 1. Organize the course around a set of diverse case studies
> 2. Integrate computing into every aspect of the course
> 3. Teach abstraction, but minimize reliance on mathematical notation
> 4. Structure course activities to realistically mimic a data scientist’s experience
> 5. Demonstrate the importance of critical thinking/skepticism through examples

You will find value in reading my [learning manifesto](https://datathink.io/my-learning-manifesto-aka-teaching-philosophy/).

### Nice general outcomes. What tools are we using?

We use [Pyspark](https://databricks.com/glossary/pyspark) and [SparkSQL](https://databricks.com/glossary/what-is-spark-sql#:~:text=Spark%20SQL%20is%20a%20Spark,on%20existing%20deployments%20and%20data.) within [Docker](https://hub.docker.com/r/jupyter/all-spark-notebook) and with [Databricks](https://databricks.com/).  We will also leverage Git and Github heavily in our class and team collaborations.

### What are the assignments?

The semester is relatively open-ended as to the work you submit for evaluation.  Each class will pick their path for a business venture with the supplied 'big data' provided in week 1.  In general, we will work in groups, with each class participant submitting individual work various times throughout the semester.

#### Semester Project

[SafeGraph](https://www.safegraph.com/) has graciously provided us free access to a few of their data sources.  We can use their [shop](https://shop.safegraph.com/?tab=datasets) or their [API](https://shop.safegraph.com/api/).

The [project_safegraph repo](https://github.com/byuibigdata/project_safegraph) contains most of the details for our semester long SafeGraph project.

#### Coding challenges

Often, the following challenges occur.

1. Your tools coding challenge (data munging and visualization)
2. Spark Team Feature Build Challenge (with team)
3. Spark Coding Challenge (data munging and feature creation in class)
4. Analytics Deployment App (Streamlit and Docker)
5. Team 30-120 minute tools and code training

### Is this course a data engineering course?

It is a 'big data programming and analytics' course focused on the data scientist's needs.  We touch all the same tools that a data engineer would use; however, we focus on how data scientists use those big data tools for management and business decisions.  

Data engineering is ‘big client’ (building pipelines and tools that touch 1000's) with small daily changes (refine systems and deliver quicker results). In contrast, data science is 'small client' (addressing the needs of 10's in management) with ‘big change’ in modeling and data sources (propose the latest methods and demo the data munging and value).

A data engineer would spend more of their time talking with IT and CS partners.  Also, they would interact heavily with the data scientists.  The data engineer would translate for the data scientist into the IT and CS space, and the data scientist would translate for the data engineer into the business and business need space. A data scientist would spend less of their time talking with IT and CS than a data engineer.

With all of that said, the course is open-ended enough to propose more data engineering applications if it meets the larger project's needs we are tackling.  

## Competency Assumptions

We assume that you have experience using data science programming in Python as practiced in [DS 250](https://www.byui.edu/catalog#/courses/HyZkmWq3Q).  You will also need a background in data science programming in R as practiced in [DS 350](https://www.byui.edu/catalog#/courses/r1lPvsfTe) or experience with Machine Learning as practiced in [CSE 450](https://www.byui.edu/catalog#/courses/view/5d026037f45fa12400239500). You can see all the [prerequisites at the BYU-I Catalog](https://www.byui.edu/catalog#/courses/rJnglmegB?bc=true&bcCurrent=Big%20Data%20Programming%20%26%20Analytics&bcItemType=Courses)

## Course Format

_This course assumes that you are capable of guided learning and working in teams._

### What does guided learning and working in teams mean?

The class runs like a start-up. We will work together to solve big-data problems as a ‘company.’ We have the mandate to learn ‘big data programming’ and tackle complex data science problems. At the end of the semester, we should all feel more comfortable with Docker, Pyspark, SparkSQL, and Databricks.  How we get from week 1 to week 13 will be our team’s choice. You should not expect anything about this class to be ‘traditional’ in the context of academia. For example,

- We will all take turns providing guides on how to use the tools.
- We will work in smaller teams but as a class team to make decisions about our projects and work.
- The class will be treated as working group meetings to mimic my industry experience as much as possible.
- __If you need someone to give you due dates and precisely what you should read or do each night, this class will push you into a new paradigm for education.__ You can read [student feedback](course_reviews.md) to see how some have responded to the process of this course.

Hopefully, you will see how your previous data science and design thinking courses give you a foundation to build, learn, and develop using big data tools to gain empathy for our data and clients, ideate on proposed solutions, and prototype our end products.

You can read more about the [design thinking process](design_thinking_agile.md) to gain a fuller understanding of what will occur this semester.

### Preparation

You are not assigned weekly readings. However, you are expected to spend 6 hours outside of class improving your Spark skills.  You are more than welcome to find your own resources if you don't want to leverage our [curated list of resources](resources.md). You can even work in your teams to create a study timeline to get through some of the resources.  You are expected to pace yourself and set a reading timeline.

### Class Time

The goal is to avoid traditional lectures in class. We will use class time for the following team activities.

- **Presentation development:** Almost all work will be done with a partner or in teams. Each project done during the class will require a presentation.
- **Decision point presentations:** Generally, these presentations will focus on class decision points where all groups will agree on a joint approach moving forward.
- **Learning path proposals:** We will have a few moments in the semester where your team will propose the 2-3 week learning goals and present them to the class.
- **Programming training:** As we decide on the learning proposals, the smaller student teams will take responsibility for developing a short activity for the class.

#### Presentations

These presentations are not expected to be high-impact proposals with highly polished slides. However, they should be organized and clear as your slides will persuade the class to move with your group's decision.

You can read more about [small group presentations](presentations.md) to make sure your team is prepared.

#### Learning and Training

Each partner group will provide one 30-120 minute training on the class selected learning topics.  These presentations should have a hands-on coding activity and be self-contained in a GitHub repo within our [DS 460 GitHub organization](https://github.com/byuibigdata).

## Grading

The grading system's influence on our thinking is a side effect of mass learning and academia. We are in a class at an accredited university and will have to manage this side effect. __However, we don’t have to let it control our learning, thinking, or work. Discovering and practicing pertinent industry skills should motivate each activity.__

The class performance is tracked in four areas - __impact, involvement, hours, and understanding__. These areas generally map to how you will be valued by your future employer.  Each area is essential to maximize your perceived performance, but all areas do not need to be exceptional to earn the highest marks in this course or to survive in the industry.

### Impact

> If your team doesn't understand why they need your services, they will eventually not need you.

- __Concept:__ Your team will make decisions and assignments. Make sure your team feels like you are an equal contributor.  Contributors are measured by taking responsibilities and delivering on those responsibilities. It is ok to contribute more on some projects and less on others, but your team should feel like you typically make significant contributions. 

- __Class:__ _A primary contributor is defined by providing at least as much material and results for the project as 50% of the group members. An active contributor is a team member who makes some impact and is involved in the project life cycle._

### Involvement

> If your team and manager don't see and hear your ideas and work, they will question your leadership and interest.

- __Concept:__ Do your work before the class meetings and come prepared to listen and direct the planning. Class meetings are not a time to stay quiet to be polite or avoid looking dumb.  Get involved, ask questions, and provide answers.

- __Class:__ _This element is harder to explain specifics on what should be done. I will reach out to you directly if you are not meeting expectations in your group involvement._

### Hours

> Putting in the time is the best predictor of success

- __Concept:__ Most employers expect you to work many hours each week.  If they only wanted specified products, they would hire consultants to deliver the product.  As a full-time employee, you will be given the space to figure out new domains and then guide the group on their implementation.  But you have to guide your work. As a data scientist, each day will have new unique challenges.

- __Class:__ _Full-time employment for a 3-credit class at BYU-I is 9 hours a week (6 outside & 3 class). Putting in full hours all semester will be a crucial element in defining your final grade. Excellent performance in the other three areas could help you achieve the highest marks without meeting the total hours (But, generally you will need to put in hours to do well on the other three)._

### Understanding

> You should know how to do things. But not everything.

- __Concept:__ When you are on a team, you should earn a reputation for knowledge in a few specific areas.  You want to be the person that everyone knows they can ask to get the correct answer.  Find your niche and hone your skills. You should find moments to offer your help in these areas.

- __Class:__ _We will have coding challenges during class.  Some will take multiple days, the entire period, or a few minutes before we start class.  All challenges will be announced at least 24 hours before the class period they occur, along with a programming topic. Also, you may be responsible for helping your team members debug their code during the projects._

### Competency Scale

The below tables summarizes the specifications-based grading for the course.  You should read the details below for further understanding.

|  Grade  | Hours |  Understanding    | Involvement                            | Impact                    |
| ------- | ----- | ----------------- | -------------------------------------- | ------------------------- |
|  A      | 107   |   3 & 4           | < 3 warnings & < 3.1 hours class missing |   Active all & primary > 2   |
|  B      | 98    |   3 & 3           | < 9.1 hours class missing or write-up  |   Active most & primary > 1   |
|  C      | 75    |   3 anytime       | < 4 warnings                           |   Active often & primary > 0 |
|  D      | 50    |   --              |   --                                   |      --                   |

__A Details:__

- Hours: 107
- Understanding: A satisfactory score on more than half of the challenges or a near-perfect score on one of the Spark focused challenges. All challenges must be completed.
- Involvement: Two or fewer conversations from me or the TA about your lack of participation or preparedness. Missing class less than three times.
- Impact: Multiple projects where you were recognized as a primary contributor (making more impact than half of your team). All projects include your fingerprints.

__B Details:__

- Hours: 98
- Understanding: A satisfactory score on more than half of the challenges.
- Involvement: Missing more than 9 hours of class or getting a write-up for low engagement.
- Impact: At least two projects where you were recognized as a primary contributor (making more impact than half of your team), and most projects include your fingerprints. 


__C Details:__

- Hours: 75
- Understanding: A satisfactory score on at least one coding challenge.
- Involvement: Three or fewer conversations from me or the TA about your lack of participation or preparedness.
- Impact: At least one project where you were recognized as a primary contributor (making more impact than half of your team). Significant participation in at least half of the projects.

__D Details:__

- Hours: 50

#### Coding Challenges

The coding challenges will be graded on a four-point scale:

1. Submitted work.
2. Some code aligns with the challenge.
3. Strong performance with satisfactory code.
4. Near flawless performance with clean and concise code.

#### Negotiating Competency Grade

If you feel you have greatly exceeded one of the competency areas, you can use that excess to negotiate a shortcoming in a different competency.  Here are a few examples you could argue (_These are example arguments and are not intended to signify a path to the grade requested_).

> I only got a satisfactory score on my final coding challenge, but I completed 119 hours and was a key contributor on 5 projects. As such, I request an A.

> I was only recognized as a key contributor on one project.  However, I worked 107 hours and stayed involved in all work during class. As such, I request a B.

> I only worked 50 hours in this class.  However, I got all 3s on my coding challenges and a 4 on the final coding challenge. Also, I was a key contributor on 5 projects and never missed class. I request an A-.

## Links

- [Design Thinking overview](design_thinking_agile.md)
- [Spark resources](resources.md)
- [On small group presentations](presentations.md)
- [Big project general outline](big_project.md)
- [Little project suggestions](little_projects.md)
