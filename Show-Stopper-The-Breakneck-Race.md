# Show Stopper!: The Breakneck Race to Create Windows NT and the Next Generation at Microsoft

### G. Pascal Zachary

2023-02-11

## Summary
* David Cutler grew up in the mid-west and was a talented athlete. Broke his leg, and then ended up just getting good at math.
* Didn't like computers at first. But got really interested after being sent off to a training.
* Hired at DEC to create an operating system for VMS. The OS was really successful, and prompted a lot of interest in the company internally after its release.
* Was going to work on successor (PRISMA, MICA), and relocated to Seattle area to form a team to work on it.
* Differences between corporate office and his team lead to him leaving for Microsoft.
* Took a number of people in his team with him.
* David Cutler tasked to create an operating system that would succeed both DOS-Windows and OS/2. 
* Ultimately would be called Windows NT.
* Idea of the OS is for it to be able to able to run multiple personalities. (OS/2, Windows, etc.)
* Client/Server based model. User applications were "clients" while invoking service calls to the kernel. (server)
* Windows NT initially developed for the Intel i860, but also x86, and MIPS version in parallel development.
  * Became just the x86 and MIPS version by the end of the development cycle
* Windows NT initially expected to use a lot of memory due to the many services running at once
* Initially no GUI, but then briefly had a OS/2 "personality" on top, but switched to Windows personality once it became clear that Windows dominating the market.
* IBM and Microsoft relationship severed because of this. OS/2 would continue to go on being developed by IBM.
* Networking - 2 teams developing it. Novell was the main competitor in this space.
* Security an afterthought. Trusted domain concept as a deciding implementation.
* Filesystem (NTFS) also developed later. Performance issue due to lazy-cache mechanism. NTFS was actually on the verge on not being planned for the initial release of Windows NT. Main developer was also juggling maintenance of legacy file systems used by DOS and OS/2. 
* Windows NT had many delays. Initially starting development in 1988, it was planned to be released in 1991, but then pushed to 1992 due to quality concerns. Then finally pushed to 1993 due to performance issues.
* Fun fact: **Mazda Miata NA** was seen as the "company car" -- Many people in the Windows NT team had a Miata.
* "Eat your own dogfood" - Developers initially coded in OS/2 systems, but then eventually moved to _using_ Windows NT for their day-to-day. Initially without a UI, then with UI.
* Graphics in Windows NT was a struggle. Team went through a lot of turnover, and Cutler did not really "get along" with the graphics team as he didn't seem to care about graphics development. 
* Graphics team eventually was able to hire **Michael Abrash**, who would help with tuning the performance of the graphics rendering of Windows NT. 
* Cutler's development philosophy was to avoid assembly code as much as possible because assembly code is tied specifically to the platform. His goal was to have Windows NT be able to run on different platforms and writing machine-specific code would tie NT too closely to that platform.
* As it turns out, assembly is unavoidable and some needed to be written for performance reasons.
* Billg review was critical. Billg stressed the importance of performance and began to question why NT was so slow. 
* The aim was for Windows NT to use **8 megabytes** of RAM. However, the team was pretty much convinced that the operating system would run on **16 megabytes** instead... to which did not make Billg happy at all.
* Eventually Billg would come to be satisfied with the progress and performance gains made in early 1993. Green-lighted for release. Although Cutler pushed to have more time spent on performance through to the original planned release date of May 1993. 
* The priority was performance in later stages of the development process. Check-ins were mainly bug fixes and performance tweaks.
* WinChat was ported to Windows NT. Dave Cutler did not like the application and saw it as a source for people to waste their time when they should be fixing NT. 
* Lead developer reasoned that if WinChat is to ship in NT, then it must be used and tested. Cutler eventually agreed.
* Showstopper and P1 bugs just kept coming, and eventually Cutler decides to extend the ship date to July 1993 instead.
* Last showstopper bug: Printing but in Aldus Pagemaker 5. Turns out it was 2 bugs -- one on NT graphics and the other on Pagemaker itself.
* Cutler eventually went on to develop Daytona (Windows NT 3.5) and had a lead on the failed Cairo project.
