---
layout: post
---

### The Technical Screen

**Interview length: 45 minutes to 1 hour**

This portion of the interview usually done with a senior IC or potentially a
manager of a data science team. Don't worry if the person interviewing you isn't
on a team that works on what you're interested in, at many large tech companies,
the interview process is standardized and so any data scientist can give you a
standardized set of questions. It doesn't mean you have to join that team, nor
will the question necessarily be specific to what they're working on.

The interview will be done remotely and typically using an interactive environment
like <a href="coderpad.io"> coderpad</a>. I've also participated in ones were it
was just over the phone.

The point of the interview is to assess if you meet the minimum technical bar to
perform the data science role at the company. This can be the scariest part of
the interview process but arguably the easiest one to prepare for. Typically, this
assessment is split into two parts, one on **data transformation** and then one on
a **data case study**.

##### Data Transformation
The company wants to know if you have the technical chops to transform given input
data into the desired output format for analysis. This is going to be the backbone
of your role as a data scientist so it's critical for you to meet the bar here.
Most of the time, companies will ask you to perform this in SQL because it's the
most common way of working with data and also typically the most performant. The
company likely still allows and uses R and Python but only in cases where the data
is small enough and you still have to pull in the data from the database via SQL.

If you come from an academic background and only know R, Python, or Matlab, I would
highly suggest you learn SQL and do the interview in SQL. While companies typically
will still allow you to use the language of your choice, you're fighting an uphill
battle because the companies want to see that you can quickly work with big-data
in a database and you don't want any doubt in your capabilities.

You will be given some input tables and asked a series of questions that require
transforming and combining the tables to answer the questions with SQL. An example
question is that you have data on Amazon sales and you have a table of sales of
pencils and a table of customer locations. You may be asked to write a query to
show the top 3 customer locations for pencil sales by dollar amount.

Here is a link to a post where I run through this example question.

The key here is to do as many of the questions as possible within the given time.
The best way to practice is to go to a question aggregator site such as
<a href="leetcode.com"> leetcode.com </a> and work through the medium and hard
database questions. You should set a timer and try to get under 5 minutes for a
medium question and under 10 minutes for a hard question.

##### Data Case Study
The company also wants to know if you have the critical thinking skills to connect
existing data to answering business and product questions. It doesn't matter if  
you have excellent technical capabilities if you aren't able to use those skills
effectively to add value to the company.

The nature of the question depends on the type of data science role you're heading
into. If it's more of a modeling/machine learning type of role, you might be asked
a question like how would you predict loan defaults when trying to build a model
to determine if someone should get a loan? If your role is closer to business or
product analytics, you may be asked a question like, Lyft management wants to encourage
users to use Lyft Line more and will be sending targeted notifications. How would
you find a target audience and could you design an experiment to test the effectiveness?

You'll be asked to come up with the data sets you would need to answer the questions
as well as how you would actually process the data to get the answers.

For the modeling question you would give your ideas on what features you would need to
collect, such as credit score, past loan history and then explain what your outcome
variable is and what model you would use. You'll likely also be asked how to evaluate
your model (think MSE, misclassification, etc.) and also how to use model results
to impact the business.

For the product question you'll also be asked similarly to come up with data such
as proximity to other riders, past history with using Lyft Line, time and cost data
associated with riding alone vs Line, etc. You'll probably also be asked to design
an a/b test (experiment) which means you will need to pick a KPI (key performance indicator)
such as average number of Lyft Line usage and evaluate whether the targeted
notifications are working and should be launched at scale.
