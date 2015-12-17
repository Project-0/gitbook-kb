Project[0] Documents
====================

First things first: what is Project[0], how do you contact us, and what are we about.

The Project
-----------

The goal of this project is to collaborate with others to set up a single server capable of managing all of the software tools that get put in place to manage a software development project.  For the purposes of this iteration, we make these assumptions going forward about our process and team.  All decisions on tools or methods _must_ support our current team structure or improve it, fundamentally.  These assumptions are:

*  The team is distributed and the tool choices must support a distributed team
*  Collaboration is provided in an as-available method.  Contributors to the project are interested individuals; not employees on a schedule
*  This is a Free Open Source project and all contributions must meet those policies.  While forks with closed-source or proprietary specializations are encouraged (and I would love to maintain a list of those for interested individuals somewhere), it is beyond the scope of this core principal and cannot be considered canon.

Purpose
-------

The reason I want to do this, is to solve what I have to believe is a very common problem among software developers.  We have pet projects.  Lots of them.  And we want to work on them with our friends or maybe just collaborate a bit with subject matter experts, whatever, but we don't want to write them in a vacuum.  There are two fundamental problems at work here: the first is that setting up a distributed project such that others can really make meaningful contributes can take a lot of set up and the second is that communication can be difficult to manage.

The Recursive Model
+++++++++++++++++++

Project[0] aims to build a solution to the first problem by providing a public server where all of these things can live and membership or setup is as easy as registering an account.  This means that we intend for the server to host commonly used software development tools like VCS, Vagrant baseboxes, provisioning tools and automatic updates so that distributed teams can stay synchronized.   This is the first iteration.  Build it.

While we do that, I want to take copious notes because the next phase of the project will be to assemble a toolkit of sorts aimed at recreating our solution.  These are our first-tier projects.  We set up git on the server; cool.  Now we provide software that a user can install to turn their machine into an architectural clone of this one.  I would like to see private instances of this solution popping up all over the place so that we can see the first problem (above) solved.   Setting up a project that is little more than a collection of thoughts right now, needs to be painless enough that you don't loose your creative momentum trying to set the thing up.   Second iteration.  Make the solution repeatable.

After that we will continue to improve the coverage and flexibility of the toolkit, and interface, solidify networking (I want this to eventually become a peer-to-peer network of these things) while we focus on the second problem: managing the communication.  So iteration 3 is to identify the next phase for improvement.

And that's the principal development pattern.   And with each iteration, we try to include the previous ones such that the solutions too the problems identified as belonging to the next iteration to solve _always better solve our current needs_.  We are building what we use and offering it to the Open Source Community.  We do not try to productize a solution; we commoditize one.

Contact, Questions or Support
-----------------------------

The place to reach us here, on GitHub, for the moment.  Obviously, our server, once built, will eventually supply us with better touchpoints, but for now, I encourage comments on documents, issues or emails.  I am @kvorak and can be reached at kvorak@gmail.com
