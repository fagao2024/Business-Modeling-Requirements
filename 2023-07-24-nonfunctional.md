---
layout: post
title: "我的第一篇博客"
date: 2023-07-24
---
Is "non-functional requirement" a vague term?
"Non-functional requirement" is indeed a vague term, but this vagueness is in expression, stemming from historical convention. Continuing to use it causes less harm than terms like "functional module" or "user requirement".
The vagueness lies in that, for the set of "requirements," "functional requirements" is a subset, and the literal meaning of "non-functional requirements" is the complement of "functional requirements." Therefore, the union of these two is the universal set. The statement "requirements are divided into functional requirements, non-functional requirements, and design constraints" is not rigorous.
However, the way of stating functional requirements + non-functional requirements + design constraints has been in use for a long time. I myself started using this expression around 2002. Of course, I must have seen it in textbooks, but I can't remember exactly which one. In fact, many books still express it this way over the years, and some are even more confusing: 
 
Software Engineering: Theory and Practice, Shari Lawrence Pfleeger, Joanne M. Atlee, 2009

[Image Description](notfun.png)
 
The Requirements Engineering Handbook, Ralph R. Young, 2003

 
Aspect-oriented software development with use cases, Ivar Jacobson, Pan-Wei Ng, 2005

To be more rigorous in expression, the approaches can be:
(1) Design constraints are not requirements. This is inappropriate. Putting them together indicates they belong to the same category, whether it's called "requirements" or "A Cat" or "A Dog." They all fall under "the system must be this way; otherwise, it will harm stakeholders' interests."
(2) Design constraints are a kind of non-functional requirement. This is acceptable, but conventionally, when "non-functional requirements" are mentioned, speed, reliability, etc., come to mind. This also causes the vague expression.
(3) Rename "non-functional requirements". Such a catch-all naming as "non-functional requirements" is inherently inappropriate. For example, it can be renamed to the expression used in Pfleeger's book  — "quality requirements." However, the term "quality" is also quite vague.

"Requirements are divided into functional requirements, quality requirements, and design constraints" is still not appropriate. Why do the first two end with the word "requirements" while the last one doesn't? We could remove the "requirements" suffix altogether - requirements are divided into three types: functionality, performance, and design constraints.

