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

For the past couple of weeks, we have been starting to implement testing into our coding practice. We set up a testing service called [Travis CI](https://travis-ci.org/) integrated with GitHub to monitor our homework branches in the learning_by_doing repository. We also set up a testing tool called `cucumber` that can be initiated manually whenever we like, but we usually did so after coding. Rubocop enforced code formatting conventions during code entry that were mostly annoying, yet often caught typos that explained why a program was not operating as we expected.

This week in class we dove into the details of test driven development (TDD)  and expanded upon the software development techniques that we were exposed to in earlier weeks. We talked about the steps that need to be taken in order to meet best practices for TDD and we covered what makes TDD successful. We also learned about creating a test and then building an application around that test. Additionally we learned how to use common testing tools such as rspec, guard, and a practice application called [exercism](http://exercism.io/). We used exercism to practice testing applications and in particular we used the minitest gem to test out the HelloWorld class we created. Exercism is an application that has predefined tests that you must develop a program around. This kind of practice gives us great exposure to test driven development and helps with creating well-built Ruby applications.

To learn Test Driven Design this week, we practiced the “Generation” style of learning reviewed at the beginning of this course in the “Making it Stick” set of slides. Here is what happened.. We went over Rspec in detail for our Monday lecture, THEN we were introduced to the Test Driven Design methodology (that Rspec uses heavily) for our Friday lecture. It was rewarding to learn the “why” after learning the “what” in great detail. Now we are revisiting the “what” in new homework exercises. That’s our “Spaced Retrieval Practice” at work.

This week we had our first assessment for the class. These assessments are a way for us to calibrate ourselves and gain some insight into our development as coders. The assessment is also a great way for our teacher to gauge the level of learning that has taken place in the classroom. We were tested to see if we could create a new Git repository and manage the normal setup for a ruby project such as the  setup for ruby version manager (RVM), guard, and Gemfiles. The assessment also tested our ability to read output from guard using the rubocop gem output. For example, we were asked to create a method using `def` that simply assigned the value of an instance variable. When rubocop raised a warning about this method, we were expected to use `attr_reader` for those assignments instead. After the initial setup, we were instructed to build a Ruby class and fill it with various methods and variables. These methods needed to pass Rubocop’s tests and also return the correct output. This was the most difficult section of the assessment and the part that took the longest to complete depending on how many errors you had. Finally, we were given the assignment of cloning the repository to our local machine, and then adding additional instance methods to the class. Once we completed this we were instructed to upload our final repository to Github and then issue a pull request. Although, in retrospect, the assessment itself was simple, many of us were nervous about being put on the spot and having to recall the process from scratch. Fortunately, this served as a taste the of pressure we might face in jobs and job interviews.

Sincerely,

Boole posse, t3-2015

Tim Park,
Danny Debevec,
Sue Uyetake,
Matt Michnal,
Riley Jones

