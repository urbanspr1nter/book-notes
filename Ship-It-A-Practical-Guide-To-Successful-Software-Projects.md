# Ship It! A Practical Guide to Successful Software Projects

2023-04-02

- Use source control. Don't be the shop that juggles files around and has no source of truth of the project.
- Have an automated build system. On developer machines, it should be easy to build the project and debug. On a build machine, it should be easy to build a release version of the project. If there is no automated script for this, write it. Learn all the steps in how to build a release version and incrementally figure out how to automate the manual steps.
- Continuous Integration (CI) allows for product to constantly be built with latest changes. Automating it results in higher development velocity.
- Have automated tests running in CI to prevent regressions.
- Have some method to allow results of a CI build to be presented. Use what works: email, web page, RSS feed, etc.
- Track issues using a bug tracker. Reported issues will be forgotten if not tracked properly. If a bug tracker currently does not exist, create one and don't wait for it to be populated with the existing issues before using it. Use it right away. Put the new issues in there and train everyone in the organization to use it!
- Don't confuse feature requests as bugs. Some Product Managers will treat feature requests as "top priority" and will confuse categorization as being bugs. Reclassify when needed.
- Make sure there are automated tests running within the CI system. Using a common and well-known test framework allows for tests to be written and run in an automated fashion conveniently. If no tests exists, first choose a test framework and then prioritize writing tests for known problematic areas in the code base.
- When creating the CI/build system, don't treat it as a _hobby project_ and choose technologies that seem cool. Instead, base it on a familiar technology, or language that the entire team knows. The technology should also fit well with the product. For example, use a well-known set of tools to build a JavaScript project rather than a "Python script". Python doesn't know anything about JavaScript, but a JavaScript tool may. :)
- Prioritize work through some commonly accessed document. We call this **The List**. It contains all the most important tasks to be done that will drive the direction of the product.
- Items in **The List** should be concrete -- as to be able to communicate the definition of "done".
- Your Tech Lead is the interface between the development team and manager/product managers. They have a technical background, and understand the complexities of the development process of the product.
- Tech Lead's job is to set direction for team members, priotize the project work and also product the team from unnecessary happenings.
- Let a Tech Lead, lead.
- Have frequent daily meetings. They should be timeboxed. Think about the "burn rate" -- the amount of money being spent when work is or is not getting done.
- Have code reviews frequently. Smaller and frequent code reviews can help improve product and the developers.
- Use tracer bullet development techniques to always be in a state where code can be shipped by having a defined interface and stubbed out functions.
- Stubbed out functions are useful because they let the team continue their development without having to worry about the codebase breaking due to some implementation change.
- Allows for opportunities to be able to demo to a customer E2E if stubbed out functions return mocked data.
- If a code base is difficult to manage due to it being complex, or legacy, consider diving into learning it by writing lots of tests for it. 
- Leverage the teams list of tasks to keep the Manager and Customer expectations in check. If Manager or customer is always asking for status update, then train them to look at **The List**.
- How to make sure that there are tests? If the project is already well under way and there are no tests, the best way to start adding tests is to add new tests that correspond to code that fixes bugs!
