# Syllabus

- [Schedule a time to visit with me](https://byuidatascience.github.io/visit/hathaway/), if needed.
- You might enjoy reading my [course and teaching paradigm](course_paradigm.md)


## Overview

__By the end of the semester, each student will be able to:__

> 1. __Explore and interpret distributed data at scale in business contexts, building upon previously learned data science methodologies (E.g. Databricks and Pyspark).__
> 2. __Implement the data engineering pipeline from API ingestion through feature engineering to containerized applications.__
> 3. __Present data-informed arguments for technical team decision-making.__
> 4. __Identify the differences and benefits of current industry technologies for big data storage and analysis.__

_The course follows [these principles](https://arxiv.org/ftp/arxiv/papers/1612/1612.07140.pdf) of teaching Data Science;_

> 1. Organize the course around a set of diverse case studies
> 2. Integrate computing into every aspect of the course
> 3. Teach abstraction, but minimize reliance on mathematical notation
> 4. Structure course activities to realistically mimic a data scientist’s experience
> 5. Demonstrate the importance of critical thinking/skepticism through examples

### Nice general outcomes. What tools are we using?

We use [Polars](https://docs.pola.rs/), [Pyspark](https://databricks.com/glossary/pyspark) and [SparkSQL](https://databricks.com/glossary/what-is-spark-sql#:~:text=Spark%20SQL%20is%20a%20Spark,on%20existing%20deployments%20and%20data.) within [Docker](https://hub.docker.com/r/jupyter/all-spark-notebook), the [Google Cloud Platform (GCP)](https://cloud.google.com) and with [Databricks](https://databricks.com/).  We will also leverage [git](https://git-scm.com/) and [Github](https://github.com/) heavily in our class and team collaborations.

### What are the assignments?

The semester is relatively open-ended regarding the work you submit for evaluation. We will generally work in groups, with each class participant submitting individual work at various times throughout the semester.

Review the current projects [here](https://github.com/byuibigdata#challenge-dates-and-links).

Often, the following challenges occur.

1. Your tools coding challenge (data munging and visualization)
2. Spark Team Feature Build Challenge (with team)
3. Spark Coding Challenges (data munging and feature creation)
4. In class, written code challenges (yes, a paper and pencil)
5. Analytics Deployment App (Streamlit or Marimo, Docker, and GCP)
6. Team 30-120 minute tools and code training

### Is this course a data engineering course?

It is a 'big data programming and analytics' course for data scientists.  We use the same tools as data engineers; however, we focus on how data scientists apply these big data tools for management and business decision-making.  

Data engineering is a ‘big client’ (building pipelines and tools that touch 1000's) with small daily changes (refining systems and delivering quicker results). In contrast, data science is a 'small client' (addressing the needs of 10s in management) with ‘big change’ in modeling and data sources (proposing the latest methods and demoing the data munging and value).

A data engineer would spend more time talking with IT and CS partners.  Also, they would interact heavily with the data scientists.  The data engineer would translate for the data scientist into the IT and CS domain, and the data scientist would translate for the data engineer into the business and business needs domain. A data scientist would spend less time talking with IT and CS than a data engineer.

With that said, the course is sufficiently open-ended to propose additional data engineering applications if they meet the needs of the larger project we are tackling.  

## Competency Assumptions

We assume that you have experience using data science programming in Python as practiced in [DS 250](https://www.byui.edu/catalog#/courses/HyZkmWq3Q).  You will also need a background in data science programming in R as practiced in [DS 350](https://www.byui.edu/catalog#/courses/r1lPvsfTe) or experience with Machine Learning as practiced in [CSE 450](https://www.byui.edu/catalog/#/courses/N1l4e2e2iW?q=450&itemTypes=courses&limit=20&skip=0&bc=true&bcCurrent=&bcCurrent=Machine%20Learning&bcItemType=courses). You can see all the [prerequisites at the BYU-I Catalog](https://www.byui.edu/catalog#/courses/rJnglmegB?bc=true&bcCurrent=Big%20Data%20Programming%20%26%20Analytics&bcItemType=Courses)

## Course Format

_This course assumes that you are capable of guided learning and working in teams._

### What does guided learning and working in teams mean?

The class runs like a start-up. We will work together to solve big-data problems as a ‘company.’ We are mandated to learn ‘big data programming’ and tackle complex data science problems. At the end of the semester, we should all feel more comfortable with Polars, Visualization, PySpark, Spark SQL, Docker, GCP, and Databricks.  Our team will choose how we get from week 1 to week 13. __You should not expect anything about this class to be ‘traditional’ in the context of academia.__ For example,

- We will all take turns providing guides on how to use the tools
- We will work in smaller teams, but as a class, to make decisions about our projects and work
- The class will be treated as working group meetings to mimic my industry experience as much as possible
- __If you need someone to give you due dates and precisely what you should read or do each night, this class will push you into a new paradigm for education.__ You can read [student feedback](course_reviews.md) to see how some have responded to the process of this course.

Hopefully, you will see how your previous data science and design thinking courses provide a foundation for building, learning, and developing with big data tools, gaining empathy for our data and clients, ideating proposed solutions, and prototyping our end products.

You can read more about the [design thinking process](design_thinking_agile.md) to better understand what will occur this semester.

### Preparation

You are not assigned weekly readings. However, you are expected to spend 6 hours outside class improving your Spark skills.  You are more than welcome to find your own resources if you don't want to leverage our [curated list of resources](resources.md). You can also work in your teams to create a study timeline to manage your resources.  You are expected to pace yourself and set a [learning timeline](learning_plan.md).

### Class Time

The goal is to avoid traditional in-class lectures. We will use class time for the following team activities.

- **Presentation development:** Almost all work will be done with a partner or in teams. Each project done during the class will require a presentation.
- **Decision point presentations:** Generally, these presentations will focus on class decision points where all groups will agree on a joint approach moving forward.
- **Individual development projects:**
- **Programming training:** As we decide on the learning proposals, the smaller student teams will take responsibility for developing a short activity for the class.

#### Presentations

These presentations are not expected to be high-impact proposals with highly polished slides. However, they should be organized and clear as your slides will persuade the class to move with your group's decision.

You can read more about [small group presentations](presentations.md) to ensure your team is prepared.

#### Learning and Training

Each partner/group will provide one 15-120 minute training on the class-selected learning topics.  These presentations should include a hands-on coding activity and be self-contained within our devotional GitHub repository within our [DS 460 GitHub organization](https://github.com/byuibigdata).

## Grading

The grading system's influence on our thinking is a side effect of mass learning and academia. We are in a class at an accredited university and will have to manage this side effect. __However, we don’t have to let it control our learning, thinking, or work. Discovering and practicing pertinent industry skills should motivate each activity.__

Class performance is tracked in four areas: impact, involvement, hours, and understanding. These areas generally map to how your future employer will value you.  Each area is essential to maximizing perceived performance, but not all areas need to be exceptional to earn the highest marks in this course or to succeed in the industry.

### Impact

> If your team doesn't understand why they need your services, they will eventually not need you.

- __Concept:__ Your team will make decisions and assignments. Ensure your team feels that you are an equal contributor.  Contributors are measured by the extent to which they assume responsibilities and deliver on them. It is ok to contribute more to some projects and less to others, but your team should feel like you typically make significant contributions. 

- __Class:__ _A primary contributor is defined by providing at least as much material and results for the project as 50% of the group members. An active contributor is a team member who makes some impact and is involved in the project life cycle._

### Involvement

> If your team and manager don't see and hear your ideas and work, they will question your leadership and interest.

- __Concept:__ Do your work before the class meetings and come prepared to listen and direct the planning. Class meetings are not a time to remain silent out of politeness or to avoid appearing foolish.  Get involved, ask questions, and provide answers.

- __Class:__ _This element is harder to explain the specifics on what should be done. I will contact you directly if you are not meeting expectations in your group involvement._

### Hours

> Putting in the time is the best predictor of success

- __Concept:__ Most employers expect you to work many hours each week.  If they only wanted specified products, they would hire consultants to deliver the product.  As a full-time employee, you will be given the space to explore new domains and then guide the group in their implementation.  However, you must guide your work. As a data scientist, each day will have new and unique challenges.

- __Class:__ _Full-time employment for a 3-credit class at BYU-I is 9 hours a week (6 outside & 3 inside class). Putting in full hours all semester will be a crucial element in defining your final grade. Excellent performance in the other three areas could help you achieve the highest marks without meeting the total hours (Generally, you will need to put in hours to do well on the other three)._

### Understanding

> You should know how to do things. But not everything.

- __Concept:__ When you are on a team, you should earn a reputation for knowledge in a few specific areas.  You want to be the person that everyone knows they can ask to get the correct answer.  You can find your niche and hone your skills. You should find moments to offer your help in these areas.

- __Class:__ _We will have coding challenges during the semester.  Some will take multiple days, the entire class period, or a few minutes before we start class.  All challenges will be announced at least 24 hours before the class period they occur, along with a programming topic._

- __Class:__ _We will choose assignments from DS 350 and CSE 450 to replicate using medium and big data APIs we are learning in this class. You will need to complete all assigned replication projects._

- __Class:__ _Training devotionals must be provided by each student._ 

### Competency Scale

The tables below summarize the specifications-based grading for the course.  You should read the details below for further understanding.

|  Grade  | Hours |  Challenges           |Oral/Written Challenge |   Replication |   Involvement                              | Impact                       |
| ------- | ----- | --------------------- |---------------------- | ------------- | ---------------------------------------- | ---------------------------- |
|  A      | 110   | 4 key* & 3 or higher  | pass 3                | All complete  | < 3 warnings & < 3.1 hours class missing |   Active all & primary > 2   |
|  B      | 90    | 3 key* &  3's on most | pass 2                | < 2 missing   | < 9.1 hours class missing or write-up    |   Active most & primary > 1  |
|  C      | 70    |   3 anytime           | pass 1                | < 3 missing   | < 4 warnings                             |   Active often & primary > 0 |
|  D      | 50    |   --                  | --                    | --            |  --                                      |      --                      |

*Key challenges are any Pyspark challenges and the app challenge at the end of the semester.
*Replication projects may or may not happen during the semester. If none happen, then you have completed them all.

__A Details:__

- Hours: 110
- Challenges: A satisfactory score (3) on all the challenges and at least a near perfect score (3.7 or higher) on the key challenges. All challenges must be completed.
- Replication: All replication assignments completed with full credit.
- Involvement: Two or fewer conversations from me or the TA about your lack of participation or preparedness. Missing class less than three times.
- Impact: Multiple projects where you were recognized as a primary contributor (making more impact than half of your team). All projects include your fingerprints.

__B Details:__

- Hours: 90
- Challenges: A satisfactory score on more than half of the challenges and all key challenges.
- Replication: All but one replication assignments completed with full credit.
- Involvement: Missing more than 9 hours of class or getting a write-up for low engagement.
- Impact: At least one project where you were recognized as a primary contributor (making more impact than half of your team), and most projects include your fingerprints. 


__C Details:__

- Hours: 70
- Challenges: A satisfactory score on at least one coding challenge.
- Replication: All but two replication assignments completed with full credit.
- Involvement: Three or fewer conversations from me or the TA about your lack of participation or preparedness.
- Impact: At least one project where you were recognized as a primary contributor (making more impact than half of your team). Significant participation in at least half of the projects.

__D Details:__

- Hours: 50

#### Coding Challenges & Replication Projects

The coding challenges and replication projects will be graded on a four-point scale:

1. Submitted work.
2. Some code aligns with the challenge.
3. Strong performance with satisfactory code.
4. Near flawless performance with clean and concise code.

#### Grade Request Letter

At the end of the semester, you will need to submit a completed grade request letter. This may be a new concept to some of you. Please review the [example of a poorly worded letter with a discussion](grade_request_letter.md).

#### Negotiating Competency Grade

If you feel you have greatly exceeded one of the competency areas, you can use that excess to negotiate a shortcoming in a different competency.  Here are a few examples you could argue (_These are example arguments and are not intended to signify a path to the grade requested_).

I achieved only a satisfactory score on my final coding challenge, but I completed 119 hours and was a key contributor to 5 projects. As such, I request an A.

> I was only recognized as a key contributor on one project.  However, I worked 107 hours and stayed involved in all work during class. As such, I request a B.

I worked only 50 hours in this class.  However, I got all 3s on my coding challenges and a 4 on the final coding challenge. Also, I was a key contributor on 5 projects and never missed class. I request an A-.

## Links

- [Design Thinking overview](design_thinking_agile.md)
- [Spark resources](resources.md)
- [On small group presentations](presentations.md)
- [Course Learning/Teaching Paradigm](course_paradigm.md)

