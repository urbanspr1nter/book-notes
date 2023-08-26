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
* 