---
---

# 1-13-2020

Run, don't walk. We need to get you caught up with some fundamentals. I'm assigning
you some introductory python lessons, using Kaggle Learn's free courses.

Up front, we'll also review the final exam from infosec management from last semester.

Next in line, you need to crash-course learn the fundamentals of machine learning.
First priority is that you nail the _concepts_, and second is that you get hands-on
experience with those concepts using python libraries. We'll go over these repeatedly
this semester, and you'll also have overlap in your other classes. But first,
a firehose. Learning through repetition. Starting probably the second week, I'll have
reading assignments and mini-open-note-and-repeatable exams be due.

I'll also give you an assignment to help you start building an analytics portfolio.
Basic web presence kind of stuff. Probably also second week. Also a job market assignment to
make sure you're on track.

Over the semester, we'll do several mini projects with security-related datasets.
I'll give you some colab-hosted jupyter notebooks. They'll have named, emtpy (gutted)
functions, which below them will show output from when the functions were run before
they were gutted. You'll be tasked with filling in the functions to replicate the output.
Fun, eh? [Chris Vargo](https://www.colorado.edu/cmci/people/advertising-public-relations-and-media-design/chris-vargo),
teaching in the marketing track, gave me that idea, bless his heart.

In general, I'll give you a lot of work at a fast pace, at least in the beginning. You'll also have other
classes competing for your attention. As with last semester, if you need extra time
for mental health, lmk and we'll work something out. But naturally, I think my content
will be the most useful for your sakes. If you have to choose, I'd vote that you focus
on my stuff over the other stuff. But of course I would vote that! Consider me your personal
trainer. I'll push you, but if you're literally going to die, pls don't die. Recover, then
keep going! In a non-dying way! And did you know that ["literally" can mean "figuratively"?](https://www.merriam-webster.com/words-at-play/misuse-of-literally)

Woo! See you on slack. We'll all need its community-togetherness to survive this last semester.

# 1-19-2021

Okay, so you don't have to _run_ if you don't want to. You can just power-walk. I'll
try make content _available_ fast enough for those who want to go crazy, but I'll have
duedates be more reasonable.

### Last-semester infosec content
We didn't spend classtime going over the infosec exam today, because I decided that it would
be mind-numbing to do that. We may still do that later this semester, and I may still
require that you be able to pass that exam by the end of this semester, stay tuned.

Also, remind me that I still need to give you a shot at the malware lab.

### Content covered

[Link to debatably-unintelligible whiteboard that I used during class](https://wbd.ms/share/v2/aHR0cHM6Ly93aGl0ZWJvYXJkLm1pY3Jvc29mdC5jb20vYXBpL3YxLjAvd2hpdGVib2FyZHMvcmVkZWVtLzI4YWM0NTEzYjE5ZTQzNDJiYTVmZWYzODk3MDI5ZTA5X0JCQTcxNzYyLTEyRTAtNDJFMS1CMzI0LTVCMTMxRjQyNEUzRA==)

* Goal of this class is deep conceptual mastery, wide tech mastery. See [T-based Persons](https://en.wikipedia.org/wiki/T-shaped_skills)
* Job search starts now!
  - I have been collecting [job search tips from past students](https://classes.daveeargle.com/security-analytics-assignments/labs/lab-job-market.html).
  - If you don't already one, start the creation of an online portfolio. We looked at
    having each portfolio piece be a separate github repository. Then we looked at creating
    a central portfolio landing page using GitHub Pages. Formally assigned [a "GitHub Pages"
    lab](https://classes.daveeargle.com/security-analytics-assignments/labs/lab-github-and-github-pages.html).
  - I'll prepare some resume guidelines soon, too.
  - Portfolio pieces should be some magical combination of manager-interpretable descriptions of analytics, presentation of code, output from code, and discussion of code results. For exactly this purpose exists Jupyter Notebooks!
    - You should go through past semesters' projects, and jupyter-ify them.
      - Say what you're going to do
      - Do it (code, and meaningful code output)
      - Discus what you did.
* Discussed the difference between "statistics" and "machine learning." See [my blog post](https://daveeargle.com/2020/02/11/notes-on-ml-evaluation/) for a summary.
* Emphasized the two stages of life of a model -- training, and use.
  - Machine learning != aritficial intelligence (AI). AI does the two stages iteratively --
    observes whether predictions were correct, then re-trains its internal models. ML
    does no such thing on its own -- it's deploy-and-done, unless an analyst comes
    along later and refits a new model.
  - Emphasizing the two stages, in the Facebook - Cambridge Analytica (CA) scandall,
    CA pinky-promises that they deleted all of the personal information that they
    used to train their models. But that's no cost to them, because the models, once
    trained, don't need the data anymore! The models are statistical machines grown
    from the fodder of input data.
      - Remember my conversation with my seven-year-old son this morning. He thought
        he knew enough about math, and so didn't need to go to school anymore. Said
        I to him:

        > Son, I teach my students how to make _machines_ with math.

        Don't make me a liar. Fit some models, and then use those models for ML!

* I made a feeble attempt to lift the hood on how models make predictions. I tried to think
  of a security domain example with a continuous dependent variable as opposed to a categorical one, but I couldn't think of one. Next class, I'll try again with a categorical
  example, discussing probability predictions. I'll try to bring you through model evaluation
  (confusion matrices).
