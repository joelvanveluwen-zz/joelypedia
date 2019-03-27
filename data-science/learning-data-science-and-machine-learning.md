# Learning data science and machine learning

I often get asked how to get started in data science and machine learning. Here are some resources that will get you in the right direction.

The field is giant and complex and suffers from massive title inflation so I typically direct people to get some understanding of the problems they can solve with data science methodologies. 

## Initial readings

[Jason Maye's Machine Learning 101](https://docs.google.com/presentation/d/1kSuQyW5DTnkVaZEjGYCkfOxvzCqGEFzWBy4e9Uedd9k/preview?imm_mid=0f9b7e&cmp=em-data-na-na-newsltr_20171213&slide=id.g168a3288f7_0_58) \(from Google product team\) is a nice start. It gets bonus points on nailing some of the core aspects but also is very heavy on some of the most complicated applications of machine learning \(which in reality most people just don't do\). 

* I found this useful for non-technical audiences:
  * Machine learning takes some data
  * It learns patterns in said data
  * It classifies new data it has not seen before based on the knowledge from the above learning
* I also found this statement very useful for people who think machine learning is magic
  * An ML system cannot predict stuff about a system it does not know about

After you've covered all the stuff you think is amazing by Google it is probably worth reflecting that most of the time _you're not really doing that kind of work_. Which is why it is useful to regress to some more fundamental but useful work. [An Introduction to Statistical Learning](https://www-bcf.usc.edu/~gareth/ISL/ISLR%20Seventh%20Printing.pdf) is probably the best entry level book you can read. 

In just a few pages you cover:

* Supervised and unsupervised learning;
* Predictive and inferential models
* Model flexibility and interpretability tradeoffs \(you're super cool crazy decision tree is hard to understand\). 

If you're a sadist or love maths the books more influential older brother [Elements of Statistical Learning](https://web.stanford.edu/~hastie/Papers/ESLII.pdf) is also available for free and helps you understand what you're doing half the time. 

Both these books encourage you to code exercises in [R](https://www.r-project.org/). I wouldn't but you can easily replicate the exercises in Python or Julia \(and it is a good excuse to learn those languages instead\). 

There is a wealth of MOOCs, other books and content available here so I'd chase something that suits your learning style.

## Get hands on

Once you've got your preliminary reading out of the way I would highly advise projects and applications as a way to turn that knowledge into something more valuable - experience. [Kaggle](https://www.kaggle.com/) is a no brainer and [it gets heaps of shit for training people to build models](https://towardsdatascience.com/why-kaggle-will-not-make-you-a-great-data-scientist-a2c2f506a23f) that lack business savvy or aren't viable to put into production. It is however, a great place to get a feel for peoples analytical methods, looking at end-to-end data science projects and learning core skills in a safe place.

I was lucky to work on some very cool machine learning problems early in my career and some of the analytical and creative thinking skills required will almost only ever come from on the job skills, but getting a hold of data science workflows and comfortable with data in general will make a huge difference. Heck, you might even win a [regional Kaggle competition](https://actuaries.asn.au/Library/Miscellaneous/2017/March2017PDF.pdf).

## Forever learning

Pray you like jargon, have your skills outdated in months, breaking things and reading an article that solved your problem 10x better than something you just deployed to production because that is pretty normal in the data science field. 

The good news is there are some great aggregate sources to keep you in the loop. Areas you should crawl for content: 

* [O'Reilly Data](https://www.oreilly.com/data/newsletter.html) and [Artificial Intelligence](https://www.oreilly.com/ai/newsletter.html) Newsletters
* [Toward's Data Science](https://towardsdatascience.com/) on Medium
* Your mileage may vary but following influencers and credible data scientists on LinkedIn and Twitter
  * **Cassie Kozyrkov Chief Decision Scientist at Google shares some great content**
  * Brandon Rohrer \(who's article on imposter syndrome in data science went viral\) at Facebook does some very cool instructional content
  * I connect or follow \(LinkedIn has a follow feature!\) with most of the senior data scientists at my company \(which happens to be LinkedIn\) but I get some incredible insight around what content they engage with and what they perceive to be the latest trends.

The other thing I would advise \(hands on _continued\)_ is just keep tinkering. I'm currently deploying Tensorflow on edge computing boards not because it is directly relevant to my day job but because it is cutting edge and could make a huge difference to my next career move \(or none at all\). 

