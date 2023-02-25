# The Pentium Chronicles - The People, Passion, and Politics Behind Intel's Landmark Chips

### Robert P. Crowell

2023-02-12

## Chapter 1
* **P6 Project** - Pentium Pro, which eventually became Pentium II, Pentium III, and then forked to become Centrino, Xeon, and Core processors.
* Initial challenge in 1990 was to create a CPU that was 2x as fast as the P5 (Pentium)
* CPU architectures get performance improvement for free when simply having a better process (smaller transistors, etc)
* Most improvement though, come from how a team designs to utilize the transistors. 
* **Proliferation Thinking** - First generation of some product is most likely going to not be economical. Lots of research and development costs, and things are a bit inefficient.
  * It is the 2nd, 3rd, and subsequent generations where the design matures and starts to bring ROI. 
* Big ideas - Come from brain storm, then best idea is picked through refinement.
* **4 project phases** - Concept, Refinement, Realization, Production
  * Each project phase overlaps.
  * Concept - brainstorming. Anything goes
  * Refinement - best ideas from concept stage are chosen
  * Realization - develop the idea
  * Production - driving what you've created and seeing it produced at high volume.
* Do whatever it takes to see things through.

## Chapter 2 - Concept Phase
* Must not artificially constrain the "solution space" during the **Concept Phase**.
* Concept phase is a time to just brainstorm for as many ideas as possible, and then narrow down to feasable solutions.
* Consider minor ideas to possibly result in being major selling points. "Small Things Considered"
* Start with _very clear_ goals during the concept phase. If the project doesn't have clear goals, then absolutely **DO NOT** continue with the hope of the idea in that "someone will come up with something". 
  * "A team lanched into the void with no compass and no map will succeed only at floundering and wasting time."
  * A waste of money.
* P6 project's primary starting goal was all about performance. The goal was to double the P5 (Pentium)'s performance.
* Primary goal to engineer the solution, but other solutions can come along the way.
* However, keep in mind that even if solutions to other problems are solved, if the primary objective isn't fulfilled, then the project isn't successful.
* Must be able to answer quickly: "Quick! What constitutes success for this project?"
* **POR** - Project-wide Plan-Of-Record (POR). POR contains:
  * An overall roadmap.
  * Schedules, required headcount, tools, and competition likely offerings
  * General project design
* POR changed throughout the project, but always guaranteed to include changes that were only established and agreed-on by the team.
* Senior team and leadership team must be strong. Most decisions made at the leadership level will threaten one or more key project goals. Avoid having important team members be only "talkers". It is important to be able to get things done.
* Data-driven culture. Tooling was necessary to be able to determine if somethingw as possible. P6 project made use of an internally developed tool called the DFA or "data-flow analyzer" that would "simulate" how data would be processed/computed using some concept being designed by the P6. 
* DFA was able to clarify some concepts, and quickly helped solved some potential problems early on. _It is still important to scrutinize the tool._
* Take measurements. Be able to benchmark and see if the direction being taken is the right direction. For example, P6 goal was performance. So benchmarking was a common thing to do. However one challenge was that one change in P6 would cause significant performance increase in one benchmark, but significantly decrease performance in another benchmark. Challenge here is in terms of what to do next. Four things:
  1. Back out the heroic measure and try to fix benchmark X some other way. (The benchmark that increased performance)
  2. Leave the heroic measures in and try to fix only the worst of the collateral damage. (Fix the benchmarks that significantly regressed.)
  3. Reconsider the benchmark suite and ask how important benchmark X is versus benchmark Y.
  4. Intensively analyze benchmark Y to find out why a seemingly innocuous change like the fix for X should have had such surprising impact on Y. 
* Treat teams in a way that leverages their strengths, or even accommodates their weakness. Don't treat all teams the same. If you treat a strong team the same way you treat a weaker team, then you are crippling the potential of the strong team. Conversely, expecting a lot from a weaker team will damage morale and will ensure failure.
* Overpromise or overdeliver? Is it better to "overdeliver"? It depends. To the customer you will be just doing the minimum. But to management, it looks great. 
* Test work as early as possible as to not have a hard time fixing things later on.

## Chapter 3 - Refinement Phase
* Consumers of your product will usually not care about the details of your "slick design". They just care if it works and performs as expected.
* Meet the project goals and make sure it aligns with the plan-of-record (POR).
* Try not to change the project's goals in the middle of the development. Will cause delays and misaligned vision amongst team members.
  * How about ideas that crop up midstream? The group must agree to pick it up and sign off.
* Have formal change requests. Require multiple signatures from various levels. Will serve as agreement by all parties change should take place.
* Change requests that impact entire project must go through a very thorough review panel.
* "Designers make mistakes, but good designers strive to avoid making the same mistake twice".
  * Conduct design reviews.
  * Aggregate documentation (central web site)
* Really hard to determine which bug to fix, vs which bug to accept and go out in the wild.

## Chapter 4 - Realization Phase
* Engineering is all about trade-offs. Understand this.
* Architects should stay for the duration of the project. Pipelining them where they are involved in the beginning and then leave for another project once concept+refinement phase is done won't allow them to observe the rights and wrongs of their design choices.
* Always consider providing testability hooks into the product. You may never know when you're going to need it -- will make it easier to debug and modify rather than trying to rebuild it (fab again).
* Remember that validation is not the one that create bugs, they just find it. 
* Monetary rewards is something that always works, but some people also want things that can serve as an alternative. For example, giving more convenience.
* It is hard to figure out who to give out prestigious awards to. Someone will always feel left out. Need thick skin to accept this will always be the case.
* Some people are good at looking like they are fixing problems all the time, but be careful and think whether they are also creating the problems. Try not to reward the arsonists who double-serve as fire fighters.
* Executives must provide the necessary motivation on the workers' own terms.
* Sometimes the data shows no progress due to always discovering new problems. May be a sign to revisit how team productivity metrics are evaluated.
* Keep design as simple as possible. Complexity costs.

## Chapter 5 - Production Phase
* Validation is very important, but usually can only happen much later in the project. Sometimes appropriate credit not given on time.
* Microcode patch space is valuable. Use sparingly.
* It was not an oversight P6 was not as performant as expected with 16-bit code. It was an engineering trade-off.
* Make sure you are able to communicate the purpose of the project as a pitch with a very good example (analogy). For the P6 the out of order execution was described as having multiple shopping carts, and having helpers to just grab items and check to see if the items are correct later. Executives loved it.
* Probably not a good idea to decide to use a completely different technology stack in the middle of a project. (Switching from Unix to Windows NT)

## Chapter 6 - The People Factor
* Those who go above and beyond will be looked at for promotion. As it turns out, it matters less where you went to school.
* Unnecessary and unreasonable policies can really hurt productivity.
* If you have the opportunity to fight against an unreasonable policy, try to do so. Sometimes policies can hinder productivity.
* When defining goals, it is to make sure the team knows what tasks to get done. It is okay to not be able to achieve all of them by the end of the quarter. Planning is helpful because it forces us to think what is actually important vs. not.
* Burnout occurs when employee doesn't care about the work anymore. If employee is passionate about project, they will naturally work hard.

## Chapter 7 - Inquiring Minds Like Yours
* P6 project was not affected by the FDIV bug. In fact, the project likely _discovered_ the bug.
* Pentium FDIV bug came from the fact that no validation was done on the modified area in die. FDIV came from the motivation to decrease die space, although it didn't decrease at all. (Taking Kansas out of the US example)
* A lot of hype around the Itanium CPU. Goal was to transition to 64-bit processors by 1999. Itanium was a partnership between Intel and HP. Team in Santa Clara, CA worked with HP on the Itanium Processor Family. This team was particularly siloed and wasn't great for company culture. IPF team believed they were the future. Asked other x86 teams to slow down in continuing architectural improvements as it was hard for them to keep up. In hindsight, IPF should've started out as a research project to prove out ideas before persuading management to go all-in. Would have been able to know what worked and not.
* Do good work, and your career will advance with the same thought and passion you put into the work. No cookie-cutter path to being a successful career. The key is to just focus on delivering -- always.
* Robert Crowell left Intel due to frustration. Disagreed on the continuing strategy of high clock-rate CPUs (Pentium 4). Felt next step was to focus on mobile computing.