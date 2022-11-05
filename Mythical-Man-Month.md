Mythical Man Month

2022-11-05

The Tar Pit
Why aren't all programs created in a garage taking over?
It is easy to create programs for individual use. But complexity is introduced when it is productized.
Pillars:
Program - The hyperproductive program created in the garage
Programming Product - The program which also includes tests and documentation. This brings 3x more cost and effort.
Programming System - Interfaces and system integration is possible with the program. This brings 3x more cost and effort in addition.
Programming Product System - All of the above, and brings in 9x more cost and effort!
That is why you can't do better than a big company. :)
The fear is that by the time you're done writing your program the competitor already has something better.
This is not as bad as it seems. Most of the time, the new thing is not generally available -- it is merely spoken about.
The Mythical Man-Month
Software projects go awry from the lack of calendar time (e.g. poor schedule)
Schedules are usually created in the context with the assumption that all will go well without consideration of what will go wrong.
Assumption that effort === progress, and that adding more developers will yield less time overall. (This assumes that men/women and months are interchangeable)
There is usually no discipline in adhering to basic techniques in monitoring projects.
When a sense of project slippage happens, the general tendency is to want to add more devs to make up for lost time.
This will usually not work because most tasks are not partitionable in that manner.
Consider the cost in training more staff.
Adding more staff means taking someone out of the current staff to train. Meaning more lost time.
Some projects have time made up by doing less testing. This is bad.
The best possible solution is to reschedule and add more time. However, the risk here is product obsolescence.
Adding manpower to a late software project just only makes it later!
The Surgical Team
This is a smaller team with individuals who have dedicated responsibilities. This team is said to be pretty productive.
Productive people can produce (possibly) a magnitude of more work with just a little more cost (salary)
Go with the "surgeon-copilot" model. Have 1 person "know it all" and call the shots.
The copilot backs up the surgeon but surgeon always makes the final call.
Achieving Conceptual Integrity
Example: European cathedrals show differences in plan or architectural style between parts as they may have been built over different generations by different builders.
Builders attempt to "improve" upon the designs of earlier ones to reflect both changes in fashion and in taste.
Conceptual integrity -> This is the most important consideration in system design.
It is better to have a system reflect one set of design ideas than to have one that contains many good, but independent and uncoordinated ideas.
Conceptual integrity requires a system to reflect a single philosophy and that the specification as seen by the user flow from a few minds
The Second System Effect
Tendency to overdo a second system when presented the opportunity
All the embellishment may not be needed
Passing the Word
Documentation should be very concise and informative
Describe how something is done, but not the exact implementation
Describe what is seen.
Why Did the Tower of Babel Fail?
Lack of communication between teams is a common failure point for projects.
Lack of common documentation
In the System/360 project, the documentation was kept up to date. It was manually updated daily for everyone.
The project manual should have interfaces completely and precisely defined, but don't need to worry about being perfect. It is expected to have corrections. Documentation is always assumed to be updated.
It is easiest to maintain communication across teams when there is traditional org structure.
However, who is the boss? The producer or technical architect?
It is not good if it is the same person (it may not result in productivity)
It is better if the producer is the boss and tech architecture is the "right-hand". But many things must be agreed with.
Better if the technical architect is boss and producer is left to do "everything "else"
Calling the Shot
Estimation - one doesn't estimate the entire task through coding portion and only applying ratios to estimate the entire project.
Remember, coding is only 1/6th of the problem.
Extrapolating previous "smaller" work estimates time needed for larger work will simply not work.
Ex. 100m sprint in 10s -> Then I can run a mile in less than 3min?
However consider that we can be more productive with better tooling and high-level languages.
The Documentary Hypothesis
Objectives, specifications, schedule, budget, organization chart, space allocations, etc should be documented.
Only handful of critical documents are needed. Those few will generally meet a lot of needs for the team.
Plan to Throw One Away
Plan to throw away the first implementation
Usually it is a prototype. Don't try to ship a prototype to customers as a way to buy time.
It will give them a bad experience.
Sharp Tools
Invest in having the right tools for the project.
It is ok to write new tools that target productivity for the project.
Make sure there are enough machines to debug on.
Have performance tests and simulators ready and start early!
Have good documentation tools.
The Whole and the Parts
Build test beds early. Provide mocks
Have some "source control" to log changes
"source control" allows for different snapshots of codebases.
The Other Face
Create self-documenting programs. They will naturally stay up to date as compared with paper documents.
Overall, there will be less documentation floating around even though it seems like there is more typing involved.
Flow charts should only communicate a subset of a program and must be at most able to fit in a page.
Anything more becomes unreadable.
No Silver Bullet
No single tech, process, methodology, etc that is available today (1986) that can make software development over an order of magnitude easier.
Software productivity advancements just doesn't grow at the pace of hardware performance and lowering of costs
There is a reason for why it is difficult to find the "one solution" for software productivity -- It is essential complexity.
Essential Complexity refers to the problems resulting with the requirements of the software
If you have 10 problems to be solved then you have to account for those 10 things.
Accidental complexity. This is just complexity introduced by the development process in trying to create software. Ex. Debugging, optimizing, tools, etc.
If we reduce the accidental complexity down to 0, the essential complexity still takes a lot of time and effort.
High level languages have helped in improvement developer's ability to tackle essential complexity
So is buying off the shelf rather than building from scratch
So is rapid prototyping.
