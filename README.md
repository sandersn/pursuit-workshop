# Pursuit Typescript Open Source Workshop

## Overview Notes

1. Small -- probably 4 participants per TS team member. Maybe 5?
2. Choose issues ahead of time, ask others to stay away from them, pre-solve them.
3. TSJS-lib-generator was a good option (with the above caveats). Typescript website too.
4. Target audience is alumni, who have finished the course.
5. Maybe 3-4 hours long, 3/4 hour presentation + 3 hours of hands-on.

## Prerequisites

1. Javascript (and/or Typescript)
2. git (github helps, but we'll cover it)

## Presentation

### Notes

- what will you learn from contributing to open source (hint: it's mostly non-technical)
- TS team philosophy of open source
- how to choose which project to contribute to
- the TS team's ideal bug
- how to choose and fix an issue
- how to set up a build from scratch
- how to ask for help

### Intro

### What You Get From Contributing to Open Source

Something great for your resume! Specifically:

- Working with people to find the right fix to a bug
- Jumping into new code that you don't know.
- Asking people for help when you need it
- Learn how code is structured
- Learn how projects are run, technically AND socially
- Use a build system

These are all basic software engineering skills that are hard to teach in the classroom.
So open source is a great way to round out an education, and companies know this.

### Why open source

#### Personal (Nathan)

- Work is its own reward; our society really obscures that. Open source provides a different set of incentives than money.
- Side-note: Compatible with societies that reward work in different ways.
- Encourages co-operation and community.
- Importance of attribution means that authors have a better chance to benefit from their work, even when it's owned by the corporation that paid them for it.
- The flip side: "Building your personal brand" is 21st-century-dystopian. But there's a chance it might turn into something non-horrible in the next few generations.
- You get a chance to fix bugs that You really care about.
- You get a chance to work on things you really care about.
- Makes it easier for you to learn by copying.
- More direct, and by analogy more democratic.

#### Companies

- Source code is usually less valuable than the product's direction and its ecosystem.

- Things are easier when you're open by default:
- Open source dependencies are more reliable since you can submit fixes and make forks.
- Open source dependencies are more efficient since there's much less temptation to make private clones.
- New areas don't necessarily have less competition, either.
- It *is* better for infrastructure, though, since that's less often what a company competes on.
- It's easier to build up fans for a product, which means that you can get ideas and suggestions more easily.

#### Technical

- Open source ecosystems result in an overwhelming number of small projects communicating to each other.
- This can be less efficient at runtime.
- And can be hard to set up.
- But each project's code ends up much simpler, and bugs are usually much easier to fix than closed-source.
- That means there are certain kinds of software that open source is not good at (but continually tries anyway), in the same way that there are kinds of software that closed source is not good at (but continually tries anyway)

### How to choose a project

- Choose something you use(d)
- In the language and ecosystem you you know best
- Small and new is better because the code will be simpler
- Now let's look at Typescript, an 8-year-old compiler with one file that's 35,000 lines long!

### How to get started

- Find the README and CONTRIBUTING files
- Install all the prerequisites and do a build and test run. Make sure everything works.
   If it doesn't, start asking for help, more on that in a minute.
- Find tests and deface one. Rebuild and test, make sure it fails.
- Find the source and search for words that sound like your desired feature.
  This sounds stupid but it's how it works.
  Well, start with README and CONTRIBUTING since they'll help direct your search.
- Look through the list of likely places and choose the most likely.
- Deface the source and make sure tests fail.
  There might not be enough test coverage, in which case: boo.
- Now go back to the test and modify it to test your case.
- Go back to the source and try to make your change.
- Repeat testing and changing code until the test passes.
- Create a new test, revert the changes to the old test and make sure all tests pass.

### How to ask for help

- I would say discord, github comment on the issue, then twitter (possibly DMs)
- Not sure what the right answer is.
- State what you're trying to do
- Copy links to what you read for help (this means you'll have to keep the tabs open)
- Copy commands that you ran or code you wrote
- Show the bad output, along with what you expected to see

## Hands-on

- Split into groups (maybe sign up beforehand)
- Walk through set up for the repo
- Choose an example bug? Or maybe each choose a bug.
- Consider working in groups
- Ask for help in common chat

### Repos

- Typescript compiler
- Typescript browser (DOM) types
- Typescript web site
