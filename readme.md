#Chapter 1. A Pragmatic Philosophy
**Tip 1: Care About Your Craft**

**Tip 2: Think! About Your Work**

##1.-The Cat Ate My Source Code
**Tip 3: Provide Options, Don't Make Lame Excuses**

Instead of excuses, provide options. Don't say it can't be done; explain what can be done to salvage the situation.

###Challenges
How do you react when someone such as a bank teller, an auto mechanic, or a clerk—comes to you with a lame excuse? What do you think of them and their company as a result?

##2.-Software Entropy
One broken window, left unrepaired for any substantial length of time, instills in the inhabitants of the building a sense of abandonment—a sense that the powers that be don't care about the building. So another window gets broken. People start littering. Graffiti appears. Serious structural damage begins. In a relatively short space of time, the building becomes damaged beyond the owner's desire to fix it, and the sense of abandonment becomes reality.    

**Tip 4: Don't Live with Broken Windows**   

Don't mess up the carpet when fixing the broken window.

###Challenges

* Help strengthen your team by surveying your computing "neighborhood." Choose two or three "broken windows" and discuss with your colleagues what the problems are and what could be done to fix them.
* Can you tell when a window first gets broken? What is your reaction? If it was the result of someone else's decision, or a management edict, what can you do about it?

##3.-Stone Soup and Boiled Frogs
It's time to bring out the stones. Work out what you can reasonably ask for. Develop it well. Once you've got it, show people, and let them marvel. Then say "of course, it would be better if we added…."

_People find it easier to join an ongoing success._

**Tip 5: Be a Catalyst for Change**   

Most software disasters start out too small to notice, and most project overruns happen a day at a time. 
 
If you take a frog and drop it into boiling water, it will jump straight back out again. However, if you place the frog in a pan of cold water, then gradually heat it, the frog won't notice the slow increase in temperature and will stay put until cooked.

Don't be like the frog. Keep an eye on the big picture. 

**Tip 6: Remember the Big Picture**   

###Challenges
Can you determine whether you're making stone soup or frog soup when you try to catalyze change? Is the decision subjective or objective?

##4.-Good enough soup
The scope and quality of the system you produce should be specified as part of that system's requirements.

**Tip 7: Make Quality a Requirements Issue**

Great software today is often preferable to perfect software tomorrow. **Know When to Stop**

###Challenges

* Look at the manufacturers of the software tools and operating systems that you use. Can you find any evidence that these companies are comfortable shipping software they know is not perfect? As a user, would you rather (1) wait for hem to get all the bugs out, (2) have complex software and accept some bugs, or (3) opt for simpler software with fewer defects?
* Consider the effect of modularization on the delivery of software. Will it take more or less time to get a monolithic block of software to the required quality compared with a system designed in modules? Can you find commercial examples?

##5.-Your Knowledge Portfolio
_An investment in knowledge always pays the best interest._

* 1. Serious investors invest regularly—as a habit.
* 2. Diversification is the key to long-term success.
* 3. Smart investors balance their portfolios between conservative and high-risk,high-reward investments.
* 4. Investors try to buy low and sell high for maximum return.
* 5. Portfolios should be reviewed and rebalanced periodically


###Building Your Portfolio
* Invest regularly
* Diversify
* Manage risk
* Buy low, sell High
* Review and rebalance

**Tip 8: Invest Regularly in Your Knowledge Portfolio**

###Goals
* Learn at least one new language every year.
* Read a technical book each quarter.
* Read nontechnical books, too. 
* Take classes. 
* Participate in local user groups. 
* Experiment with different environments. 
* Stay current.
* Get wired.

You need to ensure that the knowledge in your portfolio is accurate and unswayed by either vendor or media hype. 
**Tip 9: Critically Analyze What You Read and Hear**

###Challenges
* Start learning a new language this week. 
* Start reading a new book (but finish this one first') If you are doing very detailed implementation and coding, read a book on design and architecture. If you are doing high-level design, read a book on coding techniques.
* Get out and talk technology with people who aren't Involved in your current project.

##6.-Communicate
* Know what you want to say. Plan what you want to say. Write an outline. 
* Know your audience. (WISDOM acrostic)
  * What they **Want**?
  * What is their **Interest**?
  * How **Sophisticated** are they?
  * How much **Detail** they want?
  * Who do you want to **Own** the information?
  * How can you **Motivate** them to listen)
* Choose your moment:  Understanding when your audience needs to hear your information.
* Choose a style:  Just the facts, large bound reports, a simple memo.
* Make it look good: Add good-looking vehicle to your important ideas and engage your audience.
* Involve your audience:  Get their feedback, and pick their brains. 
* Be a listener: Encourage people to talk by asking questions.
* Get back to people: Keep people informed afterwards.
**Tip 10: It's Both What You Say and the Way You Say It**

###Challenges
* There are several good books that contain sections on communications Try to read some of them.
* The next time you have to give a presentation, or write a memo advocating some position, try working through the wisdom acrostic before you start. See if it helps you understand how to position what you say. If appropriate, talk to your audience afterward and see how accurate your assessment of their needs was.

#Chapter 2. A Pragmatic Approach

##7.-The Evils of Duplication
The problem arises when you need to change a representation of things that are across all the code base.       
Every piece of knowledge must have a single, unambiguous, authoritative representation within a system.   

**Tip 11: DRY—Don't Repeat Yourself**

Types of duplication:

* **Imposed duplication** Developers feel they have no choice—the environment seems to require duplication.
* **Inadvertent duplication** Developers don't realize that they are duplicating information.
* **Impatient duplication** Developers get lazy and duplicate because it seems easier.
* **Interdeveloper duplication** Multiple people on a team (or on different teams) duplicate a piece of information.

**Tip 12: Male it easy to reuse**

##8.-Orthogonality

Two or more things are orthogonal if changes in one do not affect any of the others. Also called *cohesion*.
Write "shy" code.   

**Tip 13: Eliminate Effects Between Unrelated Things**

Benefits:

* Gain Productivity
	* Changes are localized
	* Promotes reuse
	* M x N orthogonal components do more than M x N non orthogonal components
* Reduce Risk
	* Diseased sections or code are isolated
	* Are better tested
	* Not tied to a product or platform
* Project Teams: Functionality is divided 
* Design: Easier to design a complete project through its components
* Toolkits and Libraries: Choose wisely to keep orthogonality
* Coding: In order to keep orthogonality when adding code do:
	* Keep your code decoupled
	* Avoid  global data
	* Avoid similar functions
* Testing: Orthogonal systems are easier to test.
* Documentation: Also gain quality

###Challenges

* What feels better a large GUI-oriented tools or a small but combinable command line utilities. Which is easier to use? Which set is easier to combine?

*  Multiple inheritance, multiple interfaces. What impact does it have in orthogonality? What is the difference between using multiple inheritance and multiple interfaces? Is there a difference between using delegation or inheritance?

##9.-Reversibility
Be prepared for changes.

**Tip 14: There are no Final Decisions.**

##10-Tracer Bullets
In new projects your users requirements may be vague. Use of new algorithms, techniques, languages, or libraries unknowns will come. And environment will change over time before you are done.   
We're looking for something that gets us from a requirement to some aspect of the final system quickly, visibly, and repeatably.

**Tip 15: Use Tracer Bullets to Find the Target**

Advantages:

* Users get to see something working early
* Developers build a structure to work in
* You have an integration platform
* You have something to demonstrate
* You have a better feel for progress

###Tracer Bullets Don't Always Hit Their Target
Tracer bullets show what you're hitting. This may not always be the target. You then adjust your aim until they're on target. That's the point.


### Tracer Code versus Prototyping
With a prototype, you're aiming to explore specific aspects of the final system.    
Tracer code is used to know how the application as a whole hangs together.   

Prototyping generates disposable code.   
Tracer code is lean but complete, and forms part of the skeleton of the final system.

##11.-Prototypes and Post-it Notes
We build software prototypes to analyze and expose risk, and to offer chances for correction at a greatly reduced cost.   

Prototype anything that: 

* carries risk
* hasn't been tried before
* is absolutely critical to the final system
* is unproven 
* is experimental
* is doubtful

Samples:

* Architecture
* New functionality in an existing system
* Structure or contents of external data
* Third-party tools or components
* Performance issues
* User interface design   


**Tip 16: Prototype to Learn**


Avoid details:

* Correctness
* Completeness
* Robustness
* Style

Prototyping Architecture:

* Are the responsibilities of the major components well defined and appropriate?
* Are the collaborations between major components well defined?
* Is coupling minimized?
* Can you identify potential sources of duplication?
* Are interface definitions and constraints acceptable?
* Does every module have an access path to the data it needs during execution?

**Never deploy the prototype**

##12.-Domain Languages

**Tip 17: Program Close to the Problem domain**

##13.-Estimating
**Tip 18: Estimate to Avoid Surprises**

###How Accurate Is Accurate Enough?
**First:** Do they need high accuracy, or are they looking for a ballpark figure?

**Second:** Scale time estimates properly

| Duration   	| Quote estimate in                    	|
|------------	|--------------------------------------	|
| 1-15 days  	| days                                 	|
| 3-8 weeks  	| weeks                                	|
| 8-30 weeks 	| months                               	|
| 30+ weeks  	| think hard before giving an estimate 	|

###Where Do Estimates Come From?
Ask someone who's been in a similar situation in the past.

* Understand What's Being Asked
* Build a Model of the System
* Break the Model into Components
* Give Each Parameter a Value
* Calculate the Answers
* Keep Track of Your Estimating Prowess

###Estimating Project Schedules
The only way to determine the timetable for a project is by gaining experience on that same project.
Practice incremental development, repeating the following steps: 

* Guess estimation
* Check requirements
* Analyze risk
* Design, implement, integrate
* Validate with the users
* Repeat

The refinement and confidence in the schedule gets better and better each iteration

**Tip 19: Iterate the Schedule with the Code**

###What to Say When Asked for an Estimate
**"I'll get back to you."**

###Challenges
Start keeping a log of your estimates. For each, track how accurate you turned out to be. If your error was greater than 50%, try to find out where your estimate went wrong.


#Chapter 3. The Basic Tools
**Tip 20: Keep Knowledge in plain text**

##14.-The Power of Plain Text

###Drawbacks
* more space
* computationally more expensive

###The Power of Text
* Insurance against obsolescence: you will always have a chance to be able to use text.
* Leverage: Virtually every tool in the computing can operate on plain text.
* Easier testing

##15.-Shell Games
**Tip 21: Use the power of command Shells**

Can't you do everything equally well by pointing and clicking in a GUI?
**No**. A benefit of GUIs is _WYSIWYG_—what you see is what you get. The disadvantage is _WYSIAYG_—what you see is all you get.

##16.-Power Editing
**Tip 22: Use a Single Editor Well**

###Editor "must" features
* Configurable
* Extensible
* Programmable
* Syntax highlighting
* Auto-completion
* Auto-indentation
* Initial code or document boilerplate
* Tie-in to help systems
* IDE-like features (compile, debug, and so on)

##17.-Source Code Control
**Tip 23: Always Use Source Code Control**

##18.-Debugging 
**Tip 24: Fix the Problem, Not the Blame**   
**Tip 25: Don't Panic**

###A Debugging Mindset
Don't waste a single neuron on the train of thought that begins "but that can't happen" because quite clearly it can, and has.  
Try to discover the root cause of a problem, not just this particular appearance of it.  

###Where to Start
* Before you start, check the warnings or better remove all of them.  
* You first need to be accurate in your observations and data.

###Debugging Strategies
####Bug Reproduction
* The best way to start fixing a bug is to make it reproducible.
* The second best way is to make it reproducible with a _single command_.  

#####Visualize Your Data 
Use the tools that the debugger offers you. Pen and paper can also help.
#####Tracing
Now what happens before and after.
####Rubber Ducking
Explain the bug to someone else.
####Process of Elimination
It is possible that a bug exists in the OS, the compiler, or a third-party product—but this should not be your first thought.
**Tip 26: "select" Isn't Broken**

###The Element of Surprise
**Tip 27: Don't Assume It—Prove It**

###Debugging Checklist
* Is the problem being reported a direct result of the underlying bug, or merely asymptom?
* Is the bug really in the compiler? Is it in the OS? Or is it in your code?
* If you explained this problem in detail to a coworker, what would you say?
* If the suspect code passes its unit tests, are the tests complete enough? Whathappens if you run the unit test with this data?
* Do the conditions that caused this bug exist anywhere else in the system?

##19.-Text Manipulation
**Tip 28: Learn a Text Manipulation Language**
##20.-Code Generators
**Tip 29: Write Code That Writes Code**
Two main types of code generators:

* **Passive code generators** are run once to produce a result. They are basically parameterized templates, generating a given output from a set of inputs.
* **Active code generators** are used each time their results are required. Take a single representation of some piece of knowledge and convert it into all the forms your application needs.

###Code Generators Needn't Be Complex
Keep the input format simple, and the code generator becomes simple.
###Code Generators Needn't Generate Code
You can use code generators to write just about any output: HTML, XML, plain text - any text that might be an input somewhere
else in your project.
#Chapter 4. A Pragmatic Paranoia
**Tip 30: You can't write Perfect Software**
No one in the brief history of computing has ever written a piece of perfect software.  
Pragmatic Programmers don't trust themselves, either.  

##21.-Design by Contract
A correct program is one that does no more and no less than it claims to do.
Use: 

* Preconditions
* Postconditions
* Invariants


**Tip 31: Design with Contracts**

Write "lazy" code: be strict in what you will accept before you begin, and promise as little as possible in return.

###Implementing DBC
Simply enumerating at design time:

* what the input domain range is
* what the boundary conditions are
* what the routine promises to deliver (and what it doesn't)

###Assertions
You can use assertions to apply DBC in some range. (Assertions are not propagated in subclasses)

**DBC enforce Crashing Early**
###Invariants
* Loop Invariants: Is true before and during the loop therefore also when the loop finishes
* Semantic Invariants: ie the error should be on the side of not processing a transaction rather than processing a duplicate transaction.

##22.-Dead Programs Tell No Lies
All errors give you information. Pragmatic Programmers tell themselves that if there is an error, something very, very bad has happened.

**Tip 32: Crash Early**

`A dead program normally does a lot less damage than a crippled one.`

When your code discovers that something that was supposed to be impossible just happened, your
program is no longer viable.

##23.-Assertive Programming
**Tip 33: If It Can't Happen, Use Assertions to Ensure That It Won't**   

* Assertions are also useful checks on an algorithm's operation.   
* Don't use assertions in place of real error handling.   
* Leave Assertions Turned On, unless you have critical performance issues.

##24.-When to Use Exceptions
**Tip 34: Use Exceptions for Exceptional Problems**
###What Is Exceptional?
The program must run if I all the exception handlers are removed
If your code tries to open a file for reading and that file does not exist, should an exception be raised

* Yes: If the file should have been there
* No: If you have no idea whether the file should exist or not

##25.-How to Balance Resources
When managing resources: memory, transactions, threads, flies, timers—all kinds of things with limited availability, we have to close, finish, delete, deallocate them when we are done.
**Tip 35: Finish What You Start**
###Nest Allocations

* 1.-Deallocate resources in the opposite order to that in which you allocate them
* 2.-When allocating the same set of resources in different places in your code, always allocate them in the same order (prevent deadlocks)

###Objects and Exceptions
Use `finally` to free resources.

#Chapter 5. Bend or Break
##26.-Decoupling and the Law of Demeter
###Minimize Coupling
Be careful about how many other modules you interact with and, how you came to interact with them.

Traversing relationships between objects directly can quickly lead to a combinatorial explosion.
```java
	
	book.pages().last().text().
	
	// Instead, we're supposed to go with:
	
	book.textOfLastPage()
```
Symptoms:

1. Large projects where the command to link a unit test is longer than the test program itself
2. "Simple" changes to one module that propagate through unrelated modules in the system
3. Developers who are afraid to change code because they aren't sure what might be affected

###The Law of Demeter for Functions

The Law of Demeter for functions states that  any method of an object should call only methods  belonging to:
```

	class Demeter {
  		private A a;
  		void m(B b) {
  			a.hello(); 							//itself
    		b.hello(); 							//any parameters that were passed to the method
    		new Z().hello(); 					// any object it created
    		Singleton.INSTANCE.hello(); 		// any directly held component
  		}
	}
```
**Tip 36: Minimize Coupling Between Modules**

###Does It Really Make a Difference?
Using The Law of Demeter will make your code more adaptable and robust, but at a cost:   
you will be writing a large number of wrapper methods that simply forward the request on to a delegate. imposing both a runtime cost and a space overhead.  
Balance the pros and cons for your particular application.

##27.-Metaprogramming
"Out with the details!" Get them out of the code. While we're at it, we can make our code highly configurable and "soft"—that is, easily adaptable to changes.   
###Dynamic Configuration
**Tip 37: Configure, Don't Integrate**
###Metadata-Driven Applications
We want to configure and drive the application via metadata as much as possible.
_Program for the general case, and put the specifics somewhere else —outside the compiled code base_
**Tip 38: Put Abstractions in Code Details in Metadata**

Benefits:

* It forces you to decouple your design, which results in a more flexible and adaptable program.
* It forces you to create a more robust, abstract design by deferring details—deferring them all the way out of the program.
* You can customize the application without recompiling it.
* Metadata can be expressed in a manner that's much closer to the problem domain than a general-purpose programming language might be.
* You may even be able to implement several different projects using the same application engine, but with different metadata.

###When to Configure
A flexible approach is to write programs that can reload their configuration while they're running. 

* long-running server process:  provide some way to reread and apply metadata while the program is running.
* small client GUI application: if restarts quickly no problem.

##28.- Temporal Coupling
Two aspects of time:  

* Concurrency: things happening at the same time
* Ordering: the relative positions of things in time

We need to allow for concurrency and to think about decoupling any time or order dependencies.  
Reduce any time-based dependencies  

###Workflow

Use [activity diagrams](https://upload.wikimedia.org/wikipedia/commons/thumb/e/e7/Activity_conducting.svg/2000px-Activity_conducting.svg.png) to maximize parallelism by identifying activities that could be performed in parallel, but aren't.

**Tip 39: Analyze Workflow to Improve Concurrency**

###Architecture
Balance load among multiple consumer processes: **the hungry consumer model.**

In a hungry consumer model, you replace the central scheduler with a number of independent consumer tasks and a centralized work queue. Each consumer task grabs a piece from the work queue and goes on about the business of processing it. As each task finishes its work, it goes back to the queue for some more. This way, if any particular task gets bogged down, the others can pick up the slack, and each individual component can proceed at its own pace. Each component is temporally decoupled from the others.  

**Tip 40: Design Using Services**

##Design for Concurrency
Programming with threads imposes some design constraints—and that's a good thing.

* Global or static variables must be protected from concurrent access
* Check if you need a global variable in the first place.
* Consistent state information, regardless of the order of calls
* Objects must always be in a valid state when called, and they can be called at the most awkward times. Use class invariants, discussed in Design by Contract.

##Cleaner Interfaces
Thinking about concurrency and time-ordered dependencies can lead you to design cleaner interfaces as well.

**Tip 41: Always Design for Concurrency**

##Deployment
You can be flexible as to how the application is deployed: standalone, client-server, or n-tier.    

If we design to allow for concurrency, we can more easily meet scalability or performance requirements when the time comes—and if the time never comes, we still have the benefit of a cleaner design.  

##29 It's Just a View
##Publish/Subscribe
Objects should be able to register to receive only the events they need, and should never be sent events they don't need.

Use this publish/subscribe mechanism to implement a very important design concept: the separation of a model from views of the model.

##Model-View-Controller
Separates the model from both the GUI that represents it and the controls that manage the view.

Advantage:

* Support multiple views of the same data model.
* Use common viewers on many different data models.
* Support multiple controllers to provide nontraditional input mechanisms.

**Tip 42: Separate Views from Models**
##Beyond GUIs
The controller is more of a coordination mechanism, and doesn't have to be related to any sort of input device.

* **Model** The abstract data model representing the target object. The model has no direct knowledge of any views or controllers.
* **View** A way to interpret the model. It subscribes to changes in the model and logical events from the controller.
* **Controller** A way to control the view and provide the model with new data. It publishes events to both the model and the view.


##Blackboards
A blackboard system lets us decouple our objects from each other completely, providing a forum where knowledge consumers and producers can exchange data anonymously and asynchronously.
###Blackboard Implementations
With Blackboard systems, you can store active objects—not just data—on the blackboard, and retrieve them by partial matching of fields (via templates and wildcards) or by subtypes.

Functions that a Blackboard system should have: 

* **read** Search for and retrieve data from the space.
* **write** Put an item into the space.
* **take** Similar to read, but removes the item from the space as well.
* **notify** Set up a notification to occur whenever an object is written that matches the template.

Organizing Your Blackboard by partitioning it when working on large cases.

**Tip 43: Use Blackboards to Coordinate Workflow**
