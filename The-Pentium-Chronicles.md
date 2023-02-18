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
* 
