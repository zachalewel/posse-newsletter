## RubyOnRails - Week 2 Newsletter

### Upcoming Events

* Denver Startup Week -- Week of Sep 28 -- [MORE INFO](http://www.denverstartupweek.org/schedule)

* Davinci Inventor Showcase -- Oct 10 10:00 AM to Oct 11 5:00 PM-- [MORE INFO](http://www.davinciinstitute.com/colorado-professional-workshops/inventor-showcase2015)

* Swift Developers Workshop -- Oct 17 - 8:00 AM to 12:30 PM -- [MORE INFO](http://www.davincicoders.com/calendar/learn-ios-development-colorado)

* Intro to Data Science using R Programming Language -- Nov 7 - 8:00 AM to 12:00 PM -- [MORE INFO](http://www.davinciinstitute.com/colorado-professional-workshops/data-science)

* Turing Demo Night -- October 1 - 5:30 PM to 8:00 PM -- [MORE INFO](http://www.meetup.com/Turing-Community-Events/events/225568066/)


### Shoutouts

Lucas H. - Shoutout to mentors @anthonyfalzetti and @wleborgne from von Neumann for meeting with us in the last couple weeks. Great advice from experienced members of the field!

Tim P. - Thanks @andrewlampert for  helping me feel more comfortable about the topics covered in class and my journey as a dev!

Nyla S. - Shoutout to Zach Alewal for his ongoing help, including the screenhero session that I slacked about last week. Also to Jason and Tim for their extensive help straightening out my git repositories the other day

Jon S. - Shout out to Bill from the von Neumann posse for helping us ‘git’ it tonight.

### Student Blogs

Danny Debevec - https://dannydebevec.wordpress.com/
David Jarrett - https://davejarrettblog.wordpress.com/
Jonathan Speek - http://speekruby.com/
Lucas Henderson - https://lucasjhblog.wordpress.com/
Matt Michnal - http://mattmichnal.me/
Nyla Logsden-Sackett - https://nlsackett.wordpress.com/
Reza Mamdani - http://blog.analogrez.io/
Richard Beasley - https://richardbeasleyblog.wordpress.com
Riley Jones - https://rileymjones.wordpress.com/
Ryan Nance - https://ryantnance.wordpress.com/
Sergey Skumatov - https://sskumatov.wordpress.com/
Sue Uyetake - https://suecodingblog.wordpress.com/
Tim Park - https://timsjpark.wordpress.com/
Zach Alewal - http://www.rubylabs.tk/

### Week 2 - In Review

This week in class, we continued to learn about the power of using Git as a Version Control System. Just a week ago, we initialized our first local git repository and pushed our changes to a remote repository on GitHub. Now, we are working on creating topic branches and learning how to manage them. To practice, we forked a GitHub repository into our own account and then cloned it onto our computers. It is a coding convention to call the main project repository ‘upstream’ and your own GitHub copy as the ‘origin.’ This  allows developers to work independently  on large projects without the risk of making unintended commits to the upstream master branch.

In addition, we also learned how to use the ‘git rebase’ command. Rebasing is a way to update your local repository to reflect the recent changes made in the upstream master branch. It’s important to do this so that your own commits will be made based on the most recent version of the master branch. Commonly, you will run into merge conflicts where the upstream master files and your files don’t match. In these cases, we learned that a command line tool called ‘MergeTool’ helps the user resolve these conflicts. After you finish resolving merge conflicts, the next logical step would be to push your commits to your own remote repository. Unfortunately, because of the changes that you rebased from the upstream master branch, you will have to force push them to Git as it’s the only way to move the changes to origin. In general, only topic branches should be force pushed to preserve the master branch.

One of the most important things to become comfortable with if you want to become a successful developer is the command line and it’s interface. The Terminal, as it’s called on Unix operating systems like OSX, is the heart of communication between you and your computer. The commands you run inside the terminal give you full control over the computer and all of it’s components. It’s important to learn these commands so that you not only have a deeper understanding of the connection between code and the computer, but you will also need these commands working as a developer professionally. 

So everyday, outside of class, we have all been reading about the commands that every programmer should know. When it comes to Git and managing projects, we have realized that some commands get used all the time, such as mkdir (make directory), while others such as pushd (push directory) require more independent repetition. The homework is great because it’s structured so that not only do we learn how to use the command line interface, but we also get simultaneous practice with Git and Pivotal Tracker. With all the iterations and homework, it’s assured we’ll be command line gurus by the end of class!

In between working in the terminal and learning about Git, we also took a lot of time to explore some of the theories of how to work effectively and become a part of the programming community. The first thing we covered was the idea of building your own brand; in other words, making a name for yourself. One of the ways that many people accomplish this is with a blog. As part of class we all created a blog to document the things we are learning throughout the course.Hopefully it will help others learn from our mistakes, and help us grow our professional brand at the same time. As of 2015, the blogging platform Wordpress is still the way to participate in blogging for most of us because of its convenience. Documenting our process in a blog is made easier by using Gist to include snippets of code directly into our posts.  Some of us have even been using video screen capture or the Skitch app to make things especially clear for our readers. Part of building a brand is documenting what you are doing and so any tools that help with that are valuable. 

Blogging also ties in nicely with the importance of mentorship for new developers. Often, developers rely on guidance and advice from mentors to accelerate their learning and challenge them to look at problems from different perspectives. Reading blogs helps us learn from the mistakes of others and think about why we do things a certain way - or not. Ultimately, the goal is to teach and learn from each other and experienced mentors can greatly help guide you in your path to becoming a full-fledged developer.

Another concept that we dove into this week was that of pair-programming and working directly with another developer to write code.  The idea of pair-programming involves a “driver” (someone writing the code) and a “navigator” (someone to help solve problems, give suggestions, keep track of the design, come up with tests, etc.)  Some of the benefits of this is increased productivity, more focus, less interruptions, better code.  Some of the main things to remember are  to talk often, switch roles, and collaborate.  Sometimes another person is not available to pair with or talk to, in these situations it’s absolutely essential to have a rubberduck to explain your coding issues to. OK, perhaps that was an exaggeration.  Nevertheless, the rubberduck method is therapeutic and surprisingly effective. 

Finally, we discussed the Agile style of development as an ideal to strive for. It is a collection of principles and best practices that work well in the modern development environment. The central idea is to rapidly come up with something, a prototype, based on the actual needs of the user and then rapidly iterate upon that. These iterations occur in intervals that are referred to as “sprints”. Pivotal Tracker is designed specifically to work in this way. The Agile method stresses the importance of feedback and building upon what is there and what is working, even if it is just a start. This is contrasted with the idea of trying to imagine everything in detail before hand and then having it not work out because the user wasn’t able to explain exactly what they needed or you weren’t able to imagine all the obstacles that would come up.

The overall theme of week two involved applying lessons about how coders can work together and exploring the best practices to ensure that developers are on the same branch, so to speak. While independence and building one’s personal repertoire and repository are essential, we see that there is tremendous value in collaboration done right. Through the use of coding conventions, the Git Version control system, the Agile development method and pair programming, budding programmers like us learn the habits that make us both efficient and able to work in harmony with shared goals of our individual projects. 

Sincerely,

Boole posse, t3-2015
Tim Park
Danny Debevec
Sue Uyetake
Matt Michnal
Riley Jones 

