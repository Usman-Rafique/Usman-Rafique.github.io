---
title: 'Reflections on Reviewing Computer Vision Papers'
date: 2023-01-20
permalink: /posts/cv_review/
tags:
  - peer review
  - computer vision
  - machine learning
  - cvpr
---

# Reflections on Reviewing Computer Vision Papers

[M. Usman Rafique](urafique.com/)

Jan 20, 2023


<img src="/images/blog_2023_1_2.png" alt="A picture of a garden with two benches, a paper can be seen in a corner" width="700"/>

Reviewing a CVPR paper at the scenic [State Botanical Garden of Kentucky](http://arboretum.ca.uky.edu/), December 2019, Lexington, KY.

&nbsp;

In this post, I am documenting my personal lessons on reviewing that I have learned over the last four years. There are many excellent guidelines for reviewing computer vision papers, such as this [great post by Amy Tabb](https://amytabb.com/tips/2019/06/09/how-to-review/) and [CVPR reviewer guidelines](https://cvpr.thecvf.com/Conferences/2023/ReviewerGuidelines). This is my personal guide to writing good reviews. Since I finished CVPR 2023 reviews recently, I thought this is a good time to document the rules that I follow. While these guidelines are related to computer vision, these might be generally applicable to other fields.

If you have any comments or suggestions, please feel free to reach out to me by [email](mailto:usman.rafique@uky.edu) or on [Twitter](https://twitter.com/m_usmanrafique).

### Before Reviewing

Planning is key. For large conferences, like CVPR, ICCV, and WACV, the reviewing timeline is known beforehand. I always try to plan ahead and make sure that I will have time to finish reviews in time. Understandably, sometimes it is not possible to complete reviews for a particular conference (or a journal). I have found it useful to decline review requests, or to ask for a reduced reviewing load. For BMVC 2022, I asked to review fewer papers due to my travel plans; program chairs promptly acted and assigned me fewer papers. (Of course, unexpected problems can also happen, more on that later.)

Reading a paper and absorbing it fully takes some time. I always leave a few days of a margin between the first reading of the paper and the final review submission. It is common to get more questions and ideas about a paper, *after* reading the paper. So it is important to read the paper, and maybe write an initial review, and still have time to revisit the paper and modify the review later.

## During Review

It is incredibly important to read the paper in detail. People have different preferred methods of reading papers. Some people like to first skim the paper, followed by a deeper read. Personally, I prefer to go through the paper from start to end, and follow the narrative and sequence of the paper.

##### Neutral reading

It is important to critique the method and novel contributions of the paper.

I realize that unfortunately, it is often hard to evaluate the significance of methods in computer vision because of (deep) learning-based approaches. The justification of many new designs is that it is working better, and often there are no systematic ways to evaluate neural network designs. This naturally leads to the conundrum: if the results are bad, then is the method not good enough for publication? I think our field of computer vision is facing this open question of how much reliance should be on quantitative results of a paper.

##### Critique of Method (and not results)

It is important to critique the method and novel contributions of the paper.

I realize that unfortunately, it is often hard to evaluate the significance of methods in computer vision because of (deep) learning-based approaches. The justification of many new designs is that it is working better, and often there are no systematic ways to evaluate neural network designs. This naturally leads to the conundrum: if the results are bad, then maybe the method not good enough for publication? I think our field of computer vision is facing this open question of how much reliance should be on quantitative results of a paper.

##### Which Papers to Accept
This seems to be the million-dollar question for computer vision and machine learning. There is a lot to be said about what is novel, what is a good contribution, and my least favorite: what is worthy of conference ABC. I will not go into detail about that. 

Personally, I favor papers that contribute to the field. The contribution could be through a new approach, but also it could be a new problem or task, a new dataset, or some new insights on existing approaches. In terms of results, I recommend papers that are completely revolutionary (even if results are not strictly SOTA) and papers with strong results (no matter how simple the approach seems).

Of course there are many caveats and details to be considered. I refer to [this excellent blog post on novelty by Michael Black](https://medium.com/@black_51980/novelty-in-science-8f1fd1a0a143).

##### Be Polite and Encourage Newcomers
Most reviewers can tell if the paper is from newcomers in the field. The vision community has a quite standard style of papers: there is an introductory figure, a section about the method, a few tables of results (on multiple datasets), some analysis plots, and a few qualitative results. It is effortless to spot a paper that is not from people who routinely submit to computer vision conferences. While it is a natural tendency to notice and push back against the expected mold of vision papers, I make an effort to focus on the positives and appreciate the unique strengths of such papers.

One pattern I have noticed, that I tend to defend, is that papers from some domains spend extensive effort on the problem and discussing qualitative results in great detail. For example, I have noticed that medical vision and remote sensing papers often provide detailed insights about the problem and the impact (and failures) of different solutions. Papers in these domains might not have results on 3+ datasets (as is common for most CVPR papers), but they often spend much more effort on qualitative analysis and failure cases. We are all winners if we get more interdisciplinary work in computer vision.

Naturally, some papers will not be suitable for core vision conferences, and there might be better alternative venues. While it is okay to not accept a paper, I always try to be polite and encouraging. It is easy to harshly reject such a paper by having long text under weaknesses and hardly stating any strengths. I try to keep my comments positive and highlight positive aspects of the paper 

### After Review
Most computer vision conferences have a rebuttal period followed by a discussion by reviewers and area chairs. It is important to read rebuttals with an open mind and increase your rating if the rebuttal answers some questions. Similarly, in discussions with the area chairs and other reviewers, I like having an open mind and I realize it is okay to change my rating. If my recommendation is to accept the paper, I try to explain my reasons to other reviewers.

### Acknowledgement
I have been incredibly fortunate to learn about paper review from my PhD advisor, [Prof. Nathan Jacobs](https://jacobsn.github.io/), who has been a great mentor. He actively coached me on how to write reviews. I have also learned a lot about reviewing practices from my former colleague, [Scott Workman](http://cs.uky.edu/~scott/), a great researcher who is frequently listed among outstanding reviewers in top vision conferences.
