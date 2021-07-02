---
title: 'Self-evaluation Interventions: Impact on Self-efficacy and Performance in
  Introductory Programming'
author: Alex
date: '2021-07-01'
slug: self-evaluation-interventions-impact-on-self-efficacy-and-performance-in-introductory-programming
categories:
  - publications
tags: []
subtitle: ''
summary: ''
authors: []
lastmod: '2021-07-01T15:40:12-04:00'
featured: no
image:
  caption: ''
  focal_point: ''
  preview_only: no
projects: []
---
I'm very excited to say that my paper, called "Self-evaluation Interventions: Impact on Self-efficacy and Performance in Introductory Programming" has finally been published in ACM TOCE! This paper was a whole thing, and it took over 3 years to go from the initial version that I submitted to ICER in 2018, to the final version that is appearing now in ACM TOCE. Through the initial rejection and feedback from ICER, to multiple rounds of revisions for TOCE, this paper is quite a bit different, and I must say better than the initial version. 

This paper comes from the work that I did on my dissertation. As part of my research program for my dissertation, I worked with the CS1 classes at MSU. In my final semester of data collection, I wanted to take what I had learned about the importance of self-efficacy from the previous semesters, and try to test out an actual intervention. I looked through some of the prior literature on interventions designed to improve self-efficacy, and I found some promising literature on self-evaluation. Self-evaluation, or self-assessment, as it is alternatively known, refers to a range of practices where students judge their own work. The basic underlying premise with a self-evaluation intervention is that if you can get students to engage with a self-evaluation task, you can get them to engage in self-regulated learning behaviors that will in turn lead to greater learning. There are many different versions of this that have been tried, but what we did in this test was we asked students to engage with the task of reviewing feedback that they got on a programming project, and asked them to self-identify what had gone well and what had not gone well with that particular project. We collected the answers that students gave for these questions, but the key to the intervention was that they simply engage with the task.

Initially for my dissertation this intervention was simply evaluated by looking at the intervention group vs the control group being all of the students who didn't take part. But we always knew that there was a selection bias issue and I wanted to dive deeper into looking at this comparison with more sophisticated methods, but there was already enough going on in my dissertation that this would have been too much to add on, and I wanted to get my dissertation done. So I knew the first thing I was going to do with publishing from my dissertation was to take this data from this pilot intervention test, and apply propensity score adjustments to see if there really was an effect of the intervention if I could reduce the selection bias. Upon doing these adjustments, mostly the differences went away, but there was still a significant effect of the intervention on students' programming project grades while they were doing the intervention, although no such effect existed for their self-efficacy. Then later on in the revision process I also felt confident enough with using multiple imputation techniques to add that to the analysis, as there was a fair bit of missing data. When using multiple imputation, some effects on self-efficacy began to come out again, although these effects were weaker than those for students' grades, and they depended on which propensity score model that I used.

In the end, we found that there were some significant effects of doing a self-evaluation task as far as we could tell given the limits of propensity score adjustments, and this is significant because the intervention was not particularly involved, taking students just a few minutes each week. Going forward we hope to look further into exactly what the intervention should look like to produce the greatest effects for both self-efficacy and learning, as the literature on self-assessment has not settled what are the components that make the task effective, and this may be different in the context of CS.