# Systems Performance
2023-08-26

## Chapter 1
* Workload analysis and resource analysis approaches the software stack in 2 different directions
    * Resource analysis - starts from the hardware and goes up the stack to the application
    * Workload analysis - starts from the software and goes down the stack to the hardware
* Various ways to instrument: profiling, flame charts, counters, etc.
* Keep in mind that performance is subjective. If there is no base measurement, how do we know what is fast? 
    * Is a disk access of 1ms good, or bad performance?
    * In context to what?
* Performance investigation requires a solid plan. If you don't have one, it will be like fishing  and can lead to nowhere.
    * **Methodologies** is an important concept.
* Use right tool for the job. Very complex tools can discourage a performance investigation.
* Take lots of notes and make note of everything that can progress investigation. Performance analysis can be time consuming, but it is very helpful to know where you are in the process.
* Sometimes tooling can be flawed too! Ex. Case study on 1.11.2 where Pamela investigated a software regression. Tooling used for diagnostic to simulate workload and measure requests per second was only **single-threaded**.

## Chapter 2
* We have a bunch fo metrics, commands and various technologies we can use to help with performance diagnostics. But for those who are less experienced, what do we do with them?
* **Latency** - The time spent waiting for an _operation to be performed_. Latency is subjective and ambiguous, so it is best to include any qualifying characteristics and terminology associated with it during discussions.
* Performance recommendations generally tend to be valid for that point in time. The best advice for performance given is in context to the world at that moment. Things change, and the advice will too -- especially after a software or hardware upgrade/change.
* Queueing may degrade performance if the system is at 100% capacity. Any more load can cause the system to do more work in managing the queue than getting actual work done.
    * The point where linear scalability becomes a degradation is called the _knee point_.
* 100% busy does not mean 100% capacity
    * 100% utilization means there is no idle time
    * _utilization_, in this context is time-based. It is the amount of work being processed with idle time available at that moment.
* Performance increases as cache hit ratio increases. It is exponential. The difference between 98% to 99% is much greater than the difference from 10% to 11%.

### Methodologies
* **Streetlight Anti-method** - Using tools that don't make sense for an investigation because you don't know how to use any other tools.
* **Random Change Anti-method** - Randomly making changes and testing performance to see if it improved. Dangerous as you will not know the problems introduced by changing randomly, and also it is time consuming.
* **Blame someone else anti-method** - Quickly trying to play hot-potato with an issue by pointing to another team without investigation.
* **Ad-hoc Checklist Method** - A list of common checks to validate the health of the system's performance. Is very good in helping rule out common problems. But it must kept be up-to-date and be written in a clear and prescriptive manner.
* **Problem statement** - Ask a few questions such as if the system eve rperformed well, and if anything changed recently.
* **Scientific method** - Helps with solving problem statements and generating new ones
* **Tools method** - A prescriptive list of tools which can be used to validate metrics and check for any performance issues along with anything which can be tuned
* 