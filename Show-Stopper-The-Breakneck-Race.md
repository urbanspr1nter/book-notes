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
* Windows NT initially expected to use a lot of memory due to the many services running at once
* Initially no GUI, but then briefly had a OS/2 "personality" on top, but switched to Windows personality once it became clear that Windows dominating the market.
* IBM and Microsoft relationship severed because of this. OS/2 would continue to go on being developed by IBM.
* Networking - 2 teams developing it. Novell was the main competitor in this space.
* Security an afterthought. Trusted domain concept as a deciding implementation.
* Filesystem (NTFS) also developed later. Performance issue due to lazy-cache mechanism. NTFS was actually on the verge on not being planned for the initial release of Windows NT. Main developer was also juggling maintenance of legacy file systems used by DOS and OS/2. 
* Windows NT had many delays. Initially starting development in 1988, it was planned to be released in 1991, but then pushed to 1992 due to quality concerns. Then finally pushed to 1993 due to performance issues.
* Fun fact: **Mazda Miata NA** was seen as the "company car" -- Many people in the Windows NT team had a Miata.
* Graphics in Windows NT was a struggle. Team went through a lot of turnover, and Cutler did not really "get along" with the graphics team as he didn't seem to care about graphics development. 
* Graphics team eventually was able to hire **Michael Abrash**, who would help with tuning the performance of the graphics rendering of Windows NT. 
* Cutler's development philosophy was to avoid assembly code as much as possible because assembly code is tied specifically to the platform. His goal was to have Windows NT be able to run on different platforms and writing machine-specific code would tie NT too closely to that platform.
* As it turns out, assembly is unavoidable and some needed to be written for performance reasons.
