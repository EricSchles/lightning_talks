* introduction to version control - I've met too many data scientists that don't do this and don't know how to do this

* feature scoping for data scientists - this is extremely hard and honestly I'm not always sure how to do this.  Web development is clear cut and so it's easy to scope out pieces of work, but the boundry between a feature of work and another in data science is so unclear.

* An introduction to software engineering best practice - I think thoughtful machine learning with Python's first chapter actually gets at some very good foundation, but then it just turns it into standard data science tropes.  I think if we reworked that chapter and then as an outgrowth thought through both the machine learning and software engineering pieces we'd be in good shape

* One of the issues brought up in the first chapter is data version control, but that doesn't get mentioned in the book basically at all.  We should either source or write a solution that does this

* I think the best way to teach this as an engineering + data science book is to do just that - each chapter focuses on an algorithm, like thoughtful machine learning with python does, except it also focuses on a real system that uses that algorithm.  So I think we'll need a few chapters introducing flask or at least one?  Then we show how the algorithm and the system cooperate together.  

* Reproducibility tools are key to being able to do data science well without needing a jupyter notebook.  I'm all for jupyter notebooks for experimentation, but I think we need to show how you can start with jupyter notebooks and then move to .py files when you are out of the prototyping phase.

* I want to include a section on cookie-cutter data science or some schema generating tool so that data science projects have some semblance of conventions.

* Something I've always wanted to see is a synthesis course on probability and statistics which shows them side by side.  This blog post does a fantastic job: https://towardsdatascience.com/probability-concepts-explained-maximum-likelihood-estimation-c7b4342fdbb1 

* I always teach my students the ability to go from math to psuedo code to code.  I badly want that in a book, because it isn't covered often enough and I think it would help open up a world of theory to students.  Even if they can't prove the mathematics, at least they can implement it.  And then don't have to wait around for their favorite library to implement the algorithm they want to try out, they can just go do it.

* Where to find the data and how to clean it - There are a lot of great resources on data cleaning, but almost no one talks about where to get data in books.  I know sites go away, but I think having a curated list of places to go would be very helpful.

* How to make a labeled dataset yourself - On my last engagement we used azure search to do "auto" labeling.  I've never seen this technique before, but active learning or "auto" labeling seems like it deserves some spotlight.

* Matching algorithms in depth - matching algorithms come up all the time in the real world, but I've never seen an introductory text give them any attention.  I think it would be great to have some treatment of this.  If good tooling doesn't exist, I'd be game to make a library that focuses on this.

* A chapter on profiling the performance of your algorithms - I think this gets at the heart of the divide between machine learning experts that prototype versus those that build production systems.