---
date: 2021-06-11T11:03:32-04:00
description: "A tool that estimates data science salaries"
featured_image: "/images/positions_by_state.png"
tags: ["classification"]
title: "Project 1: Data Science Salary Estimator"
---

* Created a tool that estimates data science salaries (MAE ~ $ 11K) to help data scientists 
* negotiate their income when they get a job.
* Scraped over 1000 job descriptions from glassdoor using python and selenium
* Engineered features from the text of each job description to quantify the value companies put on python, excel, aws, and spark.
* Optimized Linear, Lasso, and Random Forest Regressors using GridsearchCV to reach the best model.
* Built a client facing API using flask

{{< figure src="/images/positions_by_state.png" >}}

[This Projects GitHub Repository](https://github.com/PlayingNumbers/ds_salary_proj)