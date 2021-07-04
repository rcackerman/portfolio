---
layout: post
title: Casebook
workplace: Case Commons
description_less: Promoting best practices in child welfare through human-centered software.
description_more: Case Commons wanted to make sure the Casebook, their commercial off-the-shelf case management system, was promoting best practices in child welfare, such as frequent safety visits to foster homes and collaborative case planning, as well as providing a system where caseworkers could do their work effectively and efficiently. On the Data Science & Policy team, I worked collaboratively with product teams to inform design and infrastructure decisions.
tags: [quantitative]
splash_img_source: 
splash_img_caption: 
---

### Overview
Case Commons wanted to make sure the Casebook, their commercial off-the-shelf case management system, was promoting best practices in child welfare, such as frequent safety visits to foster homes and collaborative case planning, as well as providing a system where caseworkers could do their work effectively and efficiently. On the Data Science & Policy team, I worked collaboratively with product teams to inform design and infrastructure decisions.

### Methods

* Log analysis
* Regression analysis
* Basic quantitative analysis

### Specific Projects
**Educating clients about best practices for data collection.** We successfully pushed for more flexible data input user flows, so caseworkers could input information as they received it, without having to input junk data to get past required fields.

**Creating a case intake data model that did not produce duplicate records of children, a major safety issue.** I worked with the Intake Product Manager and technical lead to develop a model that would allow intake staff to create placeholder participants, which later caseworkers could replace with people in the system, as the investigation progressed. I then developed metrics to track whether this system was in fact preventing duplicates from being created.

**Performing log analysis on almost 10 years of log data to understand sources of data inconsistencies.** These analyses showed that some incoming API requests were overwriting data incorrectly, allowing our technical staff to quickly implement bug fixes. They also provided insight into data points that were frequently overwritten by staff, showing us what information to prioritize in the user interface.

**How could the design encourage quality data collection to improve our understanding of child welfare outcomes?** Using previous research and working with state data analysts, the Data Science and Policy team found areas of the UI that were consistently collecting data with high (and unexplained) variability. We then targeted those areas of the UI for more intensive usability testing to improve data quality. I also introduced using validated survey instrument language in the user interface.
