## Objectives

* Explain the benefits of Pair Programming
* Demonstrate Ping-Pong Pairing to solve programming problems

### What is Pair Programming?


From [c2.com, "Pair Programming"](http://c2.com/cgi/wiki?PairProgramming) is:

> An Extreme Programming practice in which two engineers participate in one development effort at one workstation. Each member performs the action the other is not currently doing: While one types in Unit Tests the other thinks about the class that will satisfy the test, for example.

Put another way:

> If code reviews are good, then let's do code review all the time. Or, let's turn code review up to 11.

The general idea is that you have two people working on the same piece of code at the same computer, at the same time - ***one person is typing and the other person is actively engaged in thinking about the problem.***

The person typing:
  * thinks about syntax
  * tries to get the code to work
  * worries about how to get the current test to pass

The person thinking:
  * thinks about the overall class/structure/architecture
  * looks at the bigger picture and how/where the code could be refactored
  * ensures that the method being developed fits into the greater software design

### Why Pair?


Some reasons to pair include:

  * Increased code quality
  * Decreased bugs
  * Cleaner code
  * Faster learning and increased skill acquisition
  * Decreases ["bus factor"](https://en.wikipedia.org/wiki/Bus_factor)
  * Decreases code silos and helps promote team code ownership

Are there any others that are not listed here? How does pair programming change how developers communicate? How about how developers communicate with Product Managers?


### Pros and Cons


We have seen a number of arguments in favor of Pair Programming. As an exercise, provide arguments _against_ pair programming, in sales these are referred to as "objections". Given each objection to pair programming, provide a response to the objection that is in favor of Pair Programming.

### Pairing Techniques

Here are a few different pairing techniques to try.

**Ping-Pong Pairing**

The easiest technique for developers new to pairing to use when starting out. This technique mimics a game of ping-pong (table tennis) with the code and tests going back and forth between the two developers. Here is the basic technique:

  * Pair 1 writes enough of a test to fail
  * Pair 2 writes enough production code for the test to pass
  * Pair 2 then writes enough of a test to fail and
  * Pair 1 writes enough production code to get the test to pass.
  * Repeat


**Driver/Navigator**

The idea here is that one pair uses the keyboard to write code while the other pair thinks about what is being written. After a given amount of time, decided on by the pair, they switch roles. This technique is also embedded in a technique like Ping Pong as the person who is not typing acts as a Navigator.


**Debugging Theory**

When there is a bug, it is the navigator's job to come up with a theory as to why the bug is occurring. Then the driver has to come up with a (manual or automated) test to prove or disprove the navigator's theory. The cycle continues until the unexpected behavior is explained and corrected.

### How to pair if...

* **You are new to a team/technology/software development**


  As a new developer to a team, your job is to learn about the codebase, product, and ask lots of questions. The application's test suite should help inform you of the application's behaviors, but nothing is better than face-to-face communication via pairing to learn about a codebase.

* **You are a Senior Developer working with a Junior Developer**


  As a Senior Developer working with a Junior Developer, your job is to teach and mentor. In this scenario, the goal is not to get things done as quickly as possible, but instead to make sure the Junior developer is aware of what is happening.

  So, slow down explain what you are doing and let the Junior Developer do most of the typing. Remember that a new developer, when working with a Senior Developer, may be uncertain or intimidated. You will need to be empathetic and patient. Create an atmosphere where it is acceptable to make mistakes and easy to learn.

  You will be surprised at how much you learn from the Junior Developer if you are open to it. Just because their method is different or not what you may have imagined, that does **not** make it wrong. Junior Developers do not "know the rules", so they often have the ability to find different, creative methods of solving problems.

* **You are a Junior Developer working with a Senior Developer**


  As a Junior Developer working with someone more experienced, your top priority is to learn. The best method of learning is by doing, so try to do most of the typing.

  Another method of learning is by making mistakes. So experiment with new things, get them wrong and try again. ***This is your time to learn, so make the most of it.***

  If the Senior Developer you are working with dominates the keyboard or is telling you what to type character by character, be courageous and ask them for an opportunity to type. While difficult, it is necessary to have a respectful conversation about how you are working together.

## Bad Behaviors

* One person using the keyboard all day long (unless that person is a Junior Developer pairing with a Senior Developer)
* Correcting every. single. one. of. the. driver's. mistakes.
  * The navigator has other things to think about than _just_ syntax mistakes
* Telling the driver what to type character by character (human keyboard)
  * Let the driver think and let them make mistakes, you may learn something
* Intractable Argument - Each pair has a different idea about where to go and neither will surrender ground
  * Spend a fixed amount of minutes on each solution, then compare and decide which to go with. If you still cannot decide at that point, flip a coin or get a third opinion
  * The other pair may not be explaining what they are doing enough to keep the both people involved, so try to dig into the details of the proposed approach
  * Switch who is typing more often or use ping-pong pairing to set the pace for switching
* Going silent
  * Both parties should always be having a conversation about what they are thinking
* Commandeering Control
  * Don't steal the keyboard
* Disappearing
  * If you need to take a break, get more caffeine, or leave for any reason, let your pair know. Don't just walk away.
* Sleeping Navigator
  * If you are navigating, navigate. Don't zone off and stare at your phone.
* Personal space
  * There are two monitors for a reason. Talk about code using academic language, don't point at your pair's screen.
  
## Good Behaviors

* Split screen
  * When you drive, be sure to display the test and the code so your pair can see both. Turn on line numbers so you can talk about code.
* One hand on the mouse
  * It should become instinctual for you to remove your hand from your mouse whenever you see your pair's hand reach for their's
* Thinking out loud
  * Have a "stream of consciousness" conversation continually narrating throughout the day
* Getting unstuck
  * If neither person knows what to do, but both have theories they want to try, and progress is limited, split up! Each of you can go try your theory and pair back up once you find something that works. Bring the idea back, not the code.
* Asking questions
  * If there is something you don't understand, ask your pair.  It can be intimidating to question a more experienced developer, but it is their job to share knowledge.  Be courageous and communicate to your pair when you don't understand.

## A Note about What Developers Actually Do


One misconception about software developers is that their job is to write lines of code (LOC). In fact, writing LOC is done the least! The developer's job is to understand problems. Code is simply a language in which we express our understanding of a problem.

One such mechanism for exploring and understanding a problem is Test Driven Development. Pair Programming also allows us to explore a problem by getting immediate feedback from our pair about their understanding of the problem at hand.

## Reflecting

Like anything else, after pairing for a while you may ask, "how do I know I'm doing this correctly?" The reflection points below will help you know if you did a good job:

***Use this rubric to reflect on your pairing behavior:***
  
 ![Pairing Rubric](../img/pairing_rubric.png)
