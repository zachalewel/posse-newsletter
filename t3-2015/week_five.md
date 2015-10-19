## RubyOnRails - Week 5 Newsletter

### Upcoming Events

* Saturday Oct 24th, 8:15 am - 12:30 pm, Free Coding Workshop: Investigating Data with Python + Pandas 

* Saturday Nov 7th, 8:00am - 12:00pm,  Weekend Workshop: Introduction to Data Science with R Programming Language 

### Shoutouts

> * Nyla  - Very big shoutout to Jason for accommodating my missed assessment on Wednesday by holding a special screenhero session and for being an awesome teacher in general. Also, shoutout to Tim and Zach for extra help.

> * Sue - Kudos to Zach for helping me work a problem with detached heads in github. His prior experience in his own work helped me find a pattern that solved my multiple branch issue. Kudos to Jason for sitting in the conference room all Saturday while we came and went with questions and conversation. The conversations around code is what helps me the most.

> * Ryan Spittler helped Sue with formatting issues in a blog post about detached HEADS.

> * Tim - Shoutout to [git-scm](https://git-scm.com/) for giving me extremely insightful bedtime reading to get me more familiar with Git

> * Riley - Thank you Tim for helping me correct obscure beginner problems that I created with my Git repo

### Week 5 - In Review

For the past couple of weeks, we have been starting to implement testing into our coding practice. We set up a testing service called [Travis CI](https://travis-ci.org/) that is integrated with GitHub to monitor our homework branches in the learning_by_doing repository. We also set up a testing tool called `cucumber` that can be initiated manually whenever we like, but we usually did so after coding. Rubocop enforced code formatting conventions during code entry that were mostly annoying, yet often caught typos that explained why a program was not operating as we expected.

This week in class we dove into the details test driven development (TDD)  and expanded upon the software development techniques that we were exposed to in earlier weeks. We learned to use common testing tools such as rspec and guard, and learned how to use a practice application called [exercism](http://exercism.io/). Specifically, we used exercism and the minitest gem to make a HelloWorld class and were exposed to the way that the testing application can be used to practice solving problems in Ruby.

To learn Test Driven Design this week, we practiced the “Generation” style of learning reviewed at the beginning of this course in the “Making it Stick” set of slides. Here is what happened.. We went over Rspec in detail for our Monday lecture, THEN we were introduced to the Test Driven Design methodology (that Rspec uses heavily) for our Friday lecture. It was rewarding to learn the “why” after learning the “what” in great detail. Now we are revisiting the “what” in new homework exercises. That’s our “Spaced Retrieval Practice” at work.

In addition, we had our first assessment for the class. These assessments are a way for us to calibrate ourselves and gain some insight into our development as coders. Our assessment tested to see if we could create a new  Git repository and manage the normal setup for a ruby project such as the  setup for ruby version manager (RVM), guard, and Gemfiles. Then, we created a class and several  instance methods and instance variables. The assessment also tested our ability to read output from guard using the rubocop gem. For example, we were asked to create a method using `def` that simply printed out the value of an instance variable. When rubocop raised a warning about this method, we were expected to use `attr_reader` instead. Although, in retrospect, the assessment itself was simple, many of us were nervous about being put on the spot and having to recall the process from scratch. Fortunately, this served as a taste the of pressure we might face in job interviews, for example.

Sincerely,

Boole posse, t3-2015

Tim Park,
Danny Debevec,
Sue Uyetake,
Matt Michnal,
Riley Jones

