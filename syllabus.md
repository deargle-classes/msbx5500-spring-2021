---
title: Syllabus for MSBX 5500 -- Security Analytics with Python
course: MSBX 5500
school: CU
year: "2021"
semester: spring
---

# Syllabus

_{{ page.course }} \| {{ page.semester | capitalize }} {{ page.year }}_



Instructor: Dave Eargle ([contact](<mailto:David.Eargle@colorado.edu>))

See [my.cu.edu](https://my.cu.edu) for class meeting day and time.

See [Canvas](https://canvas.colorado.edu) for office hours and slack workspace information


# Course Description

This class is a capstone class for the security analytics track of the business analytics masters at CU Boulder. This is the second time ever that this class has been taught.

This class explores the application of data analytics to the domain of information security. It uses python machine learning libraries to both build and deploy models for both supervised and unsupervised modeling algorithms. Business problem contexts include classifying the likelihood that a file or website is malicious based on either extracted static indicators or dynamic behavioral analysis (predictive analytics), as well as network anomaly detection on organizational network traffic data or on user account usage (unsupervised machine learning).

Consider this sage prediction:

<blockquote class='blockquote' markdown='1'>
"The year 2020 expects to see an increase in the preventative approach of deep learning environments, which will become outdated and dangerous. TTPs will continue to evolve cyber threats; we’ll fight AI with AI. Drones hovering outside office windows will discuss ML and AI to combat the threat landscape. These AI will announce a strike over Twitter, the first monumental disruption in 2020.

"Real-time data and analytics and machine learning and AI creates unpreparedness by corporations and Big Tech companies. Managed detection engines are built on human made logic, but keeping this up-to-date against the latest studies costs almost three million cyber security. Perhaps the most attention raised by increasingly employed AI-based solutions is our need to reconsider our notions of what makes a mistake."

_-- Kelly Shortridge, VP of product strategy at Capsule8's, [bot](https://www.cyberscoop.com/2020-cyber-predictions-kelly-shortridge/)._
</blockquote>


# Prereqs

This class has the following prerequisites:
- Mastery of computer networking and infosec, as some examples and labs throughout go into depth for both.
- Mastery of basics of statistics and machine learning. Goes deeper into certain areas of CRISP-DM, assuming foundational knowledge

Students in the security analytics track of the MSBA pass both prerequistes. MBAs _may_ take the class, but only if they demonstrate competency to me in the two above prereqs. _This is not a "learn python ML from scratch" class._

# Learning Outcomes

Since this is a capstone course for y'all Security Analytics track MSBA students, I have both class-specific and track-specific learning outcomes. I will try to map assignments to these learning outcomes.

## Class-specific

[//]: # I need to convert these to use [learning outcomes verbs](http://ccc.clinton.edu/CurriculumCommittee/ListofMeasurableVerbs.cxml)

Basics on collaborative and open-source coding
: Includes:
  * Git and github
  * sharing read-only Jekyll notebooks on github
  * Markdown language

Example with malware analysis kaggle winner of multinomial prediction of malware
: Includes:
* Multinomial classification
* example of winners getting domain knowledge by reading academic papers and extracting methods

Deep learning exposure
: Neural nets, Dan Becker

Continuous self-education
: Includes:
  * Learn to read python documentation and source code using sklearn
  * Learn about cutting-edge ML technologies using wikipedia rabbit hole

CRISP-DM Predictive machine learning -- fill gaps in whatever they don't already understand from other classes
: Includes:
  * model induction
    * with a focus on "how do the models make predictions"
  * model evaluation
    * using python sklearn and also datarobot
    * cross-nested validation
    * confusion matrices, ROC curves, precision-recall curves, lift curves
  * feature importances
    * using python sklearn and also datarobot

Unsupervised learning with example of network traffic and user anomaly behavior
: example datasets:

  * MTU-13 labeled botnet traffic
  * sherlock mobile malware analysis project
  * kaggle malware competition

Deployment of models with python
: Includes:
  * choosing a cutoff threshold -- automating using optimization of F1 (and why)
  * python-"Pickling" a model
    * sklearn pipelines for easy replicability
  * aws api ml endpoint
  * Docker, heroku, binder

Communicating results
: Writing a full crisp-dm report and publishing it, recommend a model based on evaluation scores, report feature importances, written for a managerial audience. Github deliverable, team-based.


## Track-specific

* Have a web portfolio of projects from the program
* Have a resume and apply to jobs



## Communication

Canvas announcements, Slack for async watercooler type banter and help, and a class Github repo for assignments.

You aren't _required_ to read and be aware of _everything_ that happens on slack to complete assignments. If it comes up
in slack that something in the assignments is wrong, or broken, I'll make an effort to update the assignment document webpage. Therefore,
don't rely on offline, potentially out-of-date assignment documents.

You _are_ required to be aware of all announcements I make via Canvas.


## Technology Requirements

I'll try to make it so that you don't need a fancy-pants laptop for any of our class content. We'll do cloud computing etc.


## Text Materials

You _must_ grok this book:

* Provost, Foster and Tom Fawcett (2013), _Data Science for Business: What You Need to Know About Data Mining and Data-Analytic Thinking_. O’Reilly Media. [Available on Amazon](https://www.amazon.com/Data-Science-Business-Data-Analytic-Thinking/dp/1449361323)



# Assignments

This is a labs-based class. I will typically give you at least a week to complete each assignment.
Assignments may include programming and report writing, reading and exams, and deliverables on projects.
As one of my key goals for you is for you to have portfolio-ready work and job market-ready domain mastery,

I may give you the ability to redo certain assignments after I have given you feedback.

Assignments will be _hosted_ on GitHub but _formally assigned_ on Canvas. Deliverables may often be for you
to give me a link pointing to your completed work.


## Rubric

Assignments will be weighted when assigned. Sorry that I can't tell you all of the assignments and weights ahead
of time -- this is only the second time this class have ever been taught, so I want to maintain some flexibility.
But I won't change the weighting after I have given the assignment. I'll use Canvas to post all assignments with their
weights, so that you have an overview idea at any given time. That is to say, if I assign you something, it won't not
be on Canvas. So you can use Canvas for tracking.


## Participation

Besides assignments, your grade will be determined by your "participation." Examples of participation may include, but are not limited
to, the following:

* attending class sessions (attendance is required!)
  * having your camera on during class
  * "engaging" during class
    * _not_ doing other things during class
    * eye contact?
    * using the zoom "chat" feature during class
    * verbally asking questions or making comments (not a hard requirement)
* participating on the class Slack workspace. This is more about being a community member.
  * asking good questions
  * answering questions
  * leaving slack reactions
  * not changing your display name to be "Llama Face"
    * actually this arguably counts as positive slack participation

Like last semester, I'll give you an opportunity to suggest and justify a participation score for yourself.






# Relevant University Offices, Policies, and Procedures


## Classroom Behavior

Both students and faculty are responsible for maintaining an appropriate learning environment in all instructional settings, whether in person, remote or online. Those who fail to adhere to such behavioral standards may be subject to discipline. Professional courtesy and sensitivity are especially important with respect to individuals and topics dealing with race, color, national origin, sex, pregnancy, age, disability, creed, religion, sexual orientation, gender identity, gender expression, veteran status, political affiliation or political philosophy. For more information, see the policies on [classroom behavior](http://www.colorado.edu/policies/student-classroom-and-course-related-behavior) and the [Student Code of Conduct](https://www.colorado.edu/sccr/sites/default/files/attached-files/2020-2021_student_code_of_conduct_0.pdf).


## Requirements for Covid-19

As a matter of public health and safety due to the pandemic, all members of the CU Boulder community and all visitors to campus must follow university, department and building requirements, and public health orders in place to reduce the risk of spreading infectious disease. Required safety measures at CU Boulder relevant to the classroom setting include:

* maintain 6-foot distancing when possible,
* wear a face covering in public indoor spaces and outdoors while on campus consistent with state and county health orders,
* clean local work area,
* practice hand hygiene,
* follow public health orders, and
* if sick and you live off campus, do not come onto campus (unless instructed by a CU Healthcare professional), or if you live on-campus, please alert [CU Boulder Medical Services](https://www.colorado.edu/healthcenter/coronavirus-updates/symptoms-and-what-do-if-you-feel-sick).

Students who fail to adhere to these requirements will be asked to leave class, and students who do not leave class when asked or who refuse to comply with these requirements will be referred to [Student Conduct and Conflict Resolution](https://www.colorado.edu/sccr/). For more information, see the policies on [COVID-19 Health and Safety](https://www.colorado.edu/policies/covid-19-health-and-safety-policy) and [classroom behavior](http://www.colorado.edu/policies/student-classroom-and-course-related-behavior) and the [Student Code of Conduct](http://www.colorado.edu/osccr/). If you require accommodation because a disability prevents you from fulfilling these safety measures, please see the “Accommodation for Disabilities” statement on this syllabus.

All students who are new to campus must complete the [COVID-19 Student Health and Expectations Course](https://www.colorado.edu/protect-our-herd/how#anchor1). Before coming to campus each day, all students are required to complete the [Buff Pass](https://pass.colorado.edu/login). In this class, you may be reminded of the responsibility to complete the Buff Pass and given time during class to complete it.

Students who have tested positive for COVID-19, have symptoms of COVID-19, or have had close contact with someone who has tested positive for or had symptoms of COVID-19 must stay home. In this class, if you are sick or quarantined, please contact me via email or slack.


## Accommodation for Disabilities

If you qualify for accommodations because of a disability, please submit your accommodation letter from Disability Services to your faculty member in a timely manner so that your needs can be addressed. Disability Services determines accommodations based on documented disabilities in the academic environment.  Information on requesting accommodations is located on the [Disability Services website](https://www.colorado.edu/disabilityservices/). Contact Disability Services at 303-492-8671 or dsinfo@colorado.edu for further assistance. If you have a temporary medical condition, see [Temporary Medical Conditions](http://www.colorado.edu/disabilityservices/students/temporary-medical-conditions) on the Disability Services website.



## Preferred Student Names and Pronouns

CU Boulder recognizes that students' legal information doesn't always align with how they identify. Students may update their preferred names and pronouns via the student portal; those preferred names and pronouns are listed on instructors' class rosters. In the absence of such updates, the name that appears on the class roster is the student's legal name.



## Honor Code


All students enrolled in a University of Colorado Boulder course are responsible for knowing and adhering to the Honor Code. Violations of the policy may include: plagiarism, cheating, fabrication, lying, bribery, threat, unauthorized access to academic materials, clicker fraud, submitting the same or similar work in more than one course without permission from all course instructors involved, and aiding academic dishonesty. All incidents of academic misconduct will be reported to the Honor Code (honor@colorado.edu); 303-492-5550). Students found responsible for violating the academic integrity policy will be subject to nonacademic sanctions from the Honor Code as well as academic sanctions from the faculty member. Additional information regarding the Honor Code academic integrity policy can be found at the [Honor Code Office website](https://www.colorado.edu/osccr/honor-code).



## Sexual Misconduct, Discrimination, Harassment and/or Related Retaliation

The University of Colorado Boulder (CU Boulder) is committed to fostering an inclusive and welcoming learning, working, and living environment. CU Boulder will not tolerate acts of sexual misconduct (harassment, exploitation, and assault), intimate partner violence (dating or domestic violence), stalking, or protected-class discrimination or harassment by members of our community. Individuals who believe they have been subject to misconduct or retaliatory actions for reporting a concern should contact the Office of Institutional Equity and Compliance (OIEC) at 303-492-2127 or cureport@colorado.edu. Information about the OIEC, university policies, [anonymous reporting](https://cuboulder.qualtrics.com/jfe/form/SV_0PnqVK4kkIJIZnf), and the campus resources can be found on the [OIEC website](http://www.colorado.edu/institutionalequity/).

Please know that faculty and graduate instructors have a responsibility to inform OIEC when made aware of incidents of sexual misconduct, dating and domestic violence, stalking, discrimination, harassment and/or related retaliation, to ensure that individuals impacted receive information about options for reporting and support resources.



## Religious Holidays

Campus policy regarding religious observances requires that faculty make every effort to deal reasonably and fairly with all students who, because of religious obligations, have conflicts with scheduled exams, assignments or required attendance.  In this class, please contact me far in advance about any such conflicts, so that we can work something out.

See the [campus policy regarding religious observances](http://www.colorado.edu/policies/observance-religious-holidays-and-absences-classes-andor-exams) for full details.
