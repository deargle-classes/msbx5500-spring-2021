---
title: Class Log
---

# Class Log

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

  Update 1-20-2020: Here are two figures that illustrate what I was getting at with how models make predictions. Right-click > "Open image in new tab" to make it bigger.

  ![how-models-make-predictions-continuous-threat-score]({{ '/assets/images/how-models-make-predictions-continuous-threat-score.png' | relative_url }})


# 1-26-2020

During last week, I wrote some more verbose guides about how to build your GitHub Pages sites locally,
and on how to get started with blogging on your GitHub Pages sites. Both added as supplements [to the bottom of the
relevant lab doc](https://classes.daveeargle.com/security-analytics-assignments/labs/lab-github-and-github-pages.html#supplemental).
I also spent an inordinate amount of time getting the table of contents on the left to work. _Remember, web dev is addicting!_

[Whiteboard link to class session](https://wbd.ms/share/v2/aHR0cHM6Ly93aGl0ZWJvYXJkLm1pY3Jvc29mdC5jb20vYXBpL3YxLjAvd2hpdGVib2FyZHMvcmVkZWVtLzg2ZDg2YzE5ZWIyZTQ4NDhiNTRiNTU3OGZhZDg5MzM5X0JCQTcxNzYyLTEyRTAtNDJFMS1CMzI0LTVCMTMxRjQyNEUzRA==)

Today in class, we discussed the following:

## Why Docker for scipy, pyspark, in your Unstructured Data Analysis class?

Because pyspark is nigh impossible to compile on Windows, and precompiled binaries that match
your specific operating system are a horrible pain to integrate into Anaconda.

## Why you're taking the cyber security networking class

[For your health](https://www.youtube.com/watch?v=wIaPvWWQli0). I know the topic is generally overwhelming, but if you had a chance to take a class
from Aristotle, would you take it, in hopes of gleaning _some_ knowledge? Of course!

## HinDom and Unit of analysis

We reviewed the [HinDom](https://scholar.google.com/scholar?hl=en&as_sdt=0%2C6&q=HinDom%3A+A+Robust+Malicious+Domain+Detection+System+based+on+Heterogeneous+Information+Network+with+Transductive+Classification&btnG=) paper that was assigned reading for your network security analytics class.

Discussed the concept of _unit of analysis_ -- how the "business question" drives this. We feed _1_ unit into our predictive models,
and _1_ prediction comes out. So if our raw data has more than 1 row per thing that we want a prediction for, we have to
_reshape the data_. Techniques for this include _grouping_ the data.

Or if the data is horribly violative of normalcy, it is often
far better to split the dataframe out into several smaller dataframes, and then to re-join those dataframes. This procedure, in effect,
_gathers_ the data, making multiple columns where there used to be multiple rows.

We used the example of moving from pcaps (one row per connection-packet) to netflows (one row per connection-timewindow)
to making predictions about whether an IP is a member of a botnet (one row per IP address).

In HinDom, by contrast, the unit of analysis is a _domain name_. Recall that a domain name can only be associated with
one IP address (ignoring load balancing systems), but that multiple IP addresses can be associated with a single domain
name.

HimDom is throws shade for days at domain-name-detection approaches that use static feature selection.
It uses some cool networking-based approaches to use _unlabeled_ data in combination with _labeled_
malicious-benign domains in order to better make domain predictions.

## Finding academic papers

One of the easiest ways is to paste the paper title into <https://scholar.google.com>.

## Getting help on your own

A student asked a question about usage of a `RandomForestRegressor` which had been used in one of the kaggle-learn lessons.
We collectively explored how to get help:

* we begun by google-searching the `from ... import` line found at the top of the snippet. First hit was to the docs
* We looked at the docs for a bit, and noticed the `source` link towards the top. We observed that the docs were dynamically
  built from comment blocks within the source code.
* we discussed how documentation can _lie_, that is, can be _wrong_. But how the source code itself _cannot lie_. I made passing
  reference to attaching debuggers to the source code, and said that following through functions that I am confused about
  is one of the primary ways that I learn new programming languages.
* we looked at how documentation lists datatypes, return values, etc.

## Random Seeds in data analytics

We linked the use of the `random_state` argument to sklearn functions back to learning about PNRG in the info security class.
We demonstrated that the most appropriate random_state value is always `42`. That the predominant use of random states is to meet
the _replicable_ goal of open data science.

## Structuring reports

I showed you my draft [CRISP-DM report structure](https://classes.daveeargle.com/security-analytics-assignments/crisp-dm-report-format), which can be used for analyses of all lengths.

## Python ML practice

I showed you my draft collection of [security-related datasets](https://classes.daveeargle.com/security-analytics-assignments/datasets).
In class, I tasked you with starting a simple CRISP-DM-structured analysis using what you'd seen in the [kaggle-learn](https://www.kaggle.com/learn/overview) courses.

I had you try to figure out how to use the `fetch_openml` function in sklearn to load the [Credit Card Fraud dataset](https://classes.daveeargle.com/security-analytics-assignments/datasets#credit-card-fraud).
We had fun.

## Coming up next

I have assigned you a few more kaggle-learn python lessons to complete, and also a few more textbook chapter exams to complete.
I will also have you convert one of your assignments from last semester into a portfolio piece.

See you soon!
