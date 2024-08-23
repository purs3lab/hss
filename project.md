---
layout: page
title: Project
permalink: /project/
---

> Adopted from [Prof. William Enck's](https://enck.org/) course.

This course has a semester long project. The goal of the course project is to enable students to
experience various aspects of software security research. The result of the project will be a 
conference-style presentation. 

This is a semester-long project and is recommended to be done individually or in
groups of two students. Each project group is expected to decide milestones and will
receive grades based on the satisfactory completion of these milestones and the presentation.


Students can pick a project of their choice after discussing it with the professor.

## Overview

The research project requires that students execute research in {software or systems} {security or privacy}.  By completing the research project, students will
learn to think critically about security problems and solutions. All solutions
have limitations, and understanding the ramification of these limitations is
critical to understanding the security and privacy of an environment.

The research project track milestones mimic the steps required to create a
conference-quality paper submission. Be realistic about what can be
accomplished in a single semester. However, the work should reflect real
thought and effort - projects executed in the closing days of the semester are
unlikely to be well received.  The grade will be based on the following
factors: novelty, depth, correctness, clarity of presentation, and effort.
There is no specific rubric, because some factors (e.g., novetly) can out weigh
other factors (e.g., effort). The final written project will be assessed
similar to how papers are reviewed for conferences.

Project teams may include groups of up to two students; groups of
two will be expected to make greater progress. I will advise each
team/individual independently as needed. The project grade will be a
combination of grades received for a number of milestone artifacts, a
presentation, and a final written paper.

## Project Grading

The research project is out of 400 points distributed as follows:

* Milestone 1 (25 points): Project proposal - {{ site.data.project.research-project.ms1.date | date: site.dateformat }}
* Milestone 2 (50 points): Related work - {{ site.data.project.research-project.ms2.date | date: site.dateformat }}
* Milestone 3 (75 points): Research Plan - {{ site.data.project.research-project.ms3.date | date: site.dateformat }}
* Milestone 4 (25 points): Abstract/Intro - {{ site.data.project.research-project.ms4.date | date: site.dateformat }}
* Milestone 5 (25 points): Presentation - {{ site.data.project.research-project.ms5.date | date: site.dateformat }}
* Milestone 6 (200 points): Final written paper - {{ site.data.project.research-project.ms6.date | date: site.dateformat }}


## Milestone 1: Project proposal (25 points)

**Due:** {{ site.data.project.research-project.ms1.date | date: site.dateformat }}

Milestone 1 is possibly the hardest milestone of the research project, so do
not be discouraged. The purpose of this milestone is to settle on 1) a project
idea/area, and 2) a project team. While the specific project may change slightly
during the course of the semester in response to the related work survey and
implementation/experiment findings, it is important to have a strong direction.
Projects can be in any area of systems security, but must be approved by the
instructor. Example project areas include:

* cloud computing
* hardware improvements for security
* operating system security enhancements
* program security mechanisms
* web browser security
* smartphone security
* network security
* privacy

For ideas, students are encouraged to browse the last several years proceedings
of [USENIX Security](https://www.usenix.org/conference/usenixsecurity20), [ACM
CCS](http://www.sigsac.org/ccs/CCS2020/), [IEEE Security and Privacy
(Oakland)](http://www.ieee-security.org/TC/SP2020/), and
[NDSS](https://www.ndss-symposium.org/ndss2020/).

**Note:** You might also find this [blog post](https://zhiyunq.medium.com/how-to-look-for-ideas-in-computer-science-research-7a3fa6f4696f) by Zhiyun Qian very helpful.

The qualities of a good research project, at a minimum, include the following
(this is my own subjective view):

* It provides new insight
* It is important, or at least matters to someone, and there is practical significance
* The findings are non-obvious

There are many things *not* in this list. For example, nowhere does it say it
has to be difficult. I admire tenacity, and much excellent research requires
tremendous effort, but that is neither necessary nor sufficient.

In addition to the above qualities, you should consider the following questions
when choosing a research topic, at least for this course:

* What data will you need?
* If you plan to collect this data, what access will you need, and whose permission will be required?
* What resources (computers, storage, etc.) will you need?
* What skills / depth of knowledge will you need?
* Do you need to involve users in experiments / data collection?

**What to turn in:** Each student should turn in a PDF document that includes
**at least five** unique project ideas (not slight variations). If an idea is to
conduct an empirical study, the project idea should include: (a) title, (b)
research question, (c) proposed methodology, (d) expected findings. If the idea
is more along the lines of building a solution for a problem, the project idea
should include: (a) title, (b) problem, (c) solution idea, (d) solution
approach, (e) expected findings. After the project proposal is submitted, you
must meet with the instructor to determine the final project.

**Note:** You are encouraged to meet also with the instructor **before** turning
in the project proposal to discuss project ideas. Meet during office hours, or
email the instructor for an appointment.

**Examples:** I've provided several [example]({% link hss/static_files/project/rms1-examples.pdf %}) project proposals. 
You may download the `.tex` for this example [here]({% link hss/static_files/project/rms1-examples.tex %}).

## Milestone 2: Related Work (50 points)

**Due:** {{ site.data.project.research-project.ms2.date | date: site.dateformat }}

One of the most critical and often overlooked portions of a research project is
a sufficient investigation of related work. For this milestone, you will write
a related work section. A good related work section is not simply a laundry
list of papers and corresponding summaries. Rather, a good related work tells a
story of how technology and research has advanced to address problems and
topics related to that considered by the paper. It is also critical to contrast
your paper with the prior work, not just state what the prior work does. While
your research is not yet complete, you should have enough of a grasp on the
idea to contrast it with the prior work. You may also revise your related work
for the final written paper. Finally, during your related work investigation,
take note of how the related work section of those papers is written. Many
papers have poorly written related work sections.  Identify what makes a good
and bad related work section.



To receive 40 of the 50 points, the related work must be at least two full
columns of text (using the provided template) and contain at least 30
citations. Websites (i.e., not academic work) count as one-half a citation. The
remaining 10 points will be based on the quality of the document, including the
writing, quality of citations, number of missing well known citations, etc.
Going well beyond the minimum 30 citations will help achieve the full 50 points
for this milestone.

{% comment %}
**What to turn in:** compressed archive (`lastname-relwork.tar.gz` or
`lastname-relwork.zip`) of the related work containing the `.pdf`, `.tex`, and `.bib`
files for the document.

**Note about files:** Only `.tar.gz`, and `.zip` files will be accepted. Filenames must
follow the `lastname-` convention. If more than one student is on a project, the
file name should have the prefix `lastname1-lastname2-`, where the lastnames are
in alphabetical order. The paper must be written using LaTeX and citations must
be managed in one or more `.bib` files using BibTeX. Failure to comply with any
of these file format and naming requirements will result in an **automatic ten
point deduction** from the milestone grade.
{% endcomment %}

**What to turn in:** PDF of the related work (`lastname-relwork.pdf`) using the
provided [template]({% link hss/static_files/project/relwork-template.tar.gz %}).

**Note about files:** Only `.pdf` files generated from the provided template
using LaTeX may be submitted. Failure to comply with any of these file format
and naming requirements will result in an **automatic ten point deduction** from
the milestone grade.

## Milestone 3: Research Plan (75 points)

**Due:** {{ site.data.project.research-project.ms3.date | date: site.dateformat }}

At this point, you have identified a problem and have at least a vague idea of
your solution or approach to answer an empirical research question. An idea is
of little value if it is not evaluated. For this milestone, you will report on
how you plan to evaluate your idea.  You must describe the following:

* **Problem Statement (10 points):** A short description (one paragraph of
  less) of the problem you trying to solve. Note that the problem may have been
  refined from previous milestones. If there are significant changes, please
  discuss with the instructor.
* **Solution Idea / Study Goal (10 points):** If your project is to propose a
  solution to a problem, name this section "Solution Idea" and provide a short
  description (one or two paragraphs) of how you propose to solve the problem.
  If your project is an empirical evaluation of some sort, name this section
  "Study Goal" and describe the significance of it. Note that the idea may have
  been refined from the previous milestones. If there are significant changes,
  please discuss with the instructor.
* **Threat Model (10 points):** A description (at least several paragraphs)
  describing the security assumptions for your solution idea. A good threat
  model should describe: (a) who is the adversary, (b) what are the goals of
  the adversary, (c) what are the capabilities of the adversary, and (d) what
  is the trusted computing base (TCB). Note, when describing the adversary
  capabilities, if is often useful to describe assumptions of what the
  adversary cannot do (e.g., does not have physical access to a device). Even
  if you are performing an empirical study, you should strive to describe a
  threat model under which the study is valid. If you have questions, please
  see the instructor.
* **Research Questions (15 points):** A list of at least three (more desired)
  research questions that inquire about the problem and/or solution idea.
  Research questions should be specific, concrete, and unambiguous questions.
  For example, research questions may inquire about protection against specific
  threats, performance overhead, scalability, and usability.
* **Methodology (10 points):** A high level description of how you plan to
  answer the research questions (at least a paragraph for each). For example, a
  project might design and implement a protection and then empirically evaluate
  the protection in some way.
* **Evaluation Plan (20 points):** A description of how you plan to answer the
  research questions. The evaluation plan may mirror the research questions, or
  multiple research questions may be answered by a single part of the
  evaluation. The proposed evaluation may be split into both the design and a
  more formal evaluation section.  For each experiment, you should describe:
  (a) experimental setup (e.g., hardware, software, and datasets used), (b)
  specific measurements and metrics you plan to use, and (c) what constitutes
  success. If graphs or tables are appropriate, provide mock versions that you
  expect to have in the final paper.

  **Note:** In system security research papers, the design section often
  provides a form of evaluation by describing how the solution defends against
  potential attacks. As such, think of your design section as if it provides an
  argumentative evaluation. For example, the sub-sections of your design are
  the specific security properities that your design needs to achieve. Each
  sub-section then makes makes an argument (though the design description,
  referencing the threat model where appropriate) for the specific security
  property. The evaluation section can then argue why the composition of the
  individual security properties is secure. Your evaluation plan should make an
  initial attept at this high level structure so that you may receive feedback
  before the final paper. Finally, systems security papers also have more
  explicit evaluation sections that consist of several experiments (e.g.,
  performance, compatibility, usability).


**What to turn in:** PDF of the research plan (`lastname-plan.pdf`) using the
provided [template]({% link hss/static_files/project/plan-template.tar.gz %}).

**Note about files:** Only `.pdf` files generated from the provided template
using LaTeX may be submitted. Failure to comply with any of these file format
and naming requirements will result in an **automatic ten point deduction** from
the milestone grade.

## Milestone 4: Abstract/Intro (25 points)

**Due:** {{ site.data.project.research-project.ms4.date | date: site.dateformat }}

The abstract and introduction are crucial to a paper. This is where you
motivate and pitch your idea and present the high-level results. If you fail to
get the reviewer's interest in the abstract and introduction, it is hard to
recover. Furthermore, the abstract and introduction are the most-read parts of
published paper.

Abstracts should be relatively short: one paragraph, around 200 words. A
wandering and off topic abstract can confuse the reader. Consider the following
template for writing an abstract (approximately one sentence per point):

* Area
* Problem
* Solution Idea
* Methodology
* Results
* Take-away

An introduction is a longer version of this same outline, often dedicating
about a paragraph per point. A good outline for your introduction follows
(approximately one paragraph per point):

* General technology area and high level problem (sometimes two paragraphs)
* Most important related work and why it fails to fully address the problem
* High level goal or vision for the paper (sometimes broader than the specific provided solution)
* "In this paper, ..." (specifics for this paper)
* Major results
* "This paper makes the following contributions:" and three bullet points
* "The remainder of this paper proceeds as follows. Section 2 ... Section 3 ..."

The abstract/intro document should be between 1 and 1.5 pages using this
format, including the title and author block.

**What to turn in:** PDF of the abstract and intro (`lastname-intro.pdf`). Use
the [final paper template]({% link hss/static_files/project/latex-starter.tar.gz%}), commenting out the `\input` commands for the other sections in the
skeleton file.

**Note about files:** Only `.pdf` files generated from the provided template
using LaTeX may be submitted. Failure to comply with any of these file format
and naming requirements will result in an **automatic five point deduction** from
the milestone grade.

## Milestone 5: Presentation (25 points)

**Due:** {{ site.data.project.research-project.ms5.date | date: site.dateformat }}

During the last class of the semester, students electing the research track
will present their work to the class. The duration of the presentation will
depend on the total number of projects. The presentation should use slides
(e.g., via PowerPoint, Keynote, Beamer). The presentation may also be required
to include a demo (confirm with the instructor). While live demos are nice,
recorded demos are more reliable.

**What to turn in:** PDF of the presentation slides (lastname-presentation.pdf).

## Milestone 6: Final Written Paper (200 points)

**Due:** {{ site.data.project.research-project.ms6.date | date: site.dateformat }}

The written version of the final project is a conference-quality
report, consisting of 8–10 pages (not including references), 1-inch margins,
two column, 10-pt font. 

* Abstract (around 200 words)
* Introduction (includes references to highly-relevant related work, i.e., state of the art for the problem you are trying to solve)
* Overview of Approach (a nice and accessible "English" description of your approach, often including a "fluffly diagram" to orient the reader)
* Protocol/Architecture/Design/...
* Evaluation (don't forget to interpret your data)
* Discussion (discuss some of the important simplifying assumptions, and suggest possibilities for future work)
* Related Work ("somewhat related" work goes here; directly related work goes into the Introduction)
* Conclusions (don't summarize your work here. That's what the abstract was for. Instead provide some philosophical ruminations of your work and future possibilities, i.e., conclusions that you have arrived at as a result of your work.)
* References

**What to turn in:** PDF of the final paper (lastname-paper.pdf) using the
provided [template]({% link hss/static_files/project/latex-starter.tar.gz %}).

**Note about files:** Only `.pdf` files generated from the provided template
using LaTeX may be submitted. Failure to comply with any of these file format
and naming requirements will result in an **automatic 20 point deduction** from
the milestone grade.