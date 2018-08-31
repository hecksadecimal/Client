# Contributing to the Fish Orientation Tracking System

Hello there! Thanks for coming by. You'll always be welcome regardless no matter what.

This document is a set of guidelines for contributing to the project. 
These are just guidelines, but they are here to ensure an efficient and fool proof workflow. 
Use your best judgement if in doubt, or just ask on the [Discord Server]()

This whole document is derived from the [Atom CONTRIBUTING.md](https://github.com/atom/atom/blob/master/CONTRIBUTING.md)

### Table Of Contents

[Code of Conduct](#code-of-conduct)

[I Just Have A Question](#i-just-have-a-question)

[I'm New. What Do I Need To Know?](#im-new-what-do-i-need-to-know)
  * [A Brief History Of Space Station 13](#a-brief-history-of-space-station-13)
  * [Game Design Document](#game-design-document)

[How To Contribute](#how-to-contribute)
  * [Reporting Bugs](#reporting-bugs)
  * [Suggesting Enhancements](#suggesting-enhancements)
  * [Code or Asset Contributions](#code-or-asset-contributions)
  * [Pull Requests](#pull-requests)

[Styleguides](#styleguides)
  * [Git Commit Messages](#git-commit-messages)
  * [C# Styleguide](#c-sharp-styleguide)

## Code of Conduct

This project and everyone participating in it is governed by the [Code of Conduct](CODE_OF_CONDUCT.md). 
By participating, you are expected to uphold this code. 
Please report unacceptable behavior to an admin.

## I Just Have A Question

> **Note:** Please don't file an issue to ask a question. You'll get faster results by using the resources below.

There is a discord server with plenty helpful people [right over here]()

## I'm New. What Do I Need To Know?

### A Brief History Of Space Station 13

Space Station 13 is a community developed, multiplayer round-based role playing game, where players assume the role of a crewmember on a space station. 
Together they must keep the station running smoothly, whilst dealing with antagonistic forces who threaten to sabotage the mission.

At the beginning of each round, players select a crew member role on the station. 
These range from high up positions like the captain and heads of staff, to engineers, scientists, medical doctors, security officers, all the way down to the lower responsibility roles such as the janitor and lowly assistant. 
At round start, one or more players will be given an antagonistic role at random, and a secret objective that’s very likely to cause disruption to the mission at hand.

When the crew aren’t turning on each other through sheer paranoia, they will face various dangers depending on the round: Sleeper agents hell bent on sabotage, shape-shifting aliens, RPG toting syndicate operatives and more. 
Not to mention the occupational hazards of working in space, such as decompression, meteor showers, radiation storms, airlock mishaps, rogue AI and catastrophic engine failure.

### Game Design Document

Someone needs to link the game design document here

## How To Contribute

### Reporting Bugs

Reporting bugs might be one of the easiest and most essential thing you can do. This section will outline what a good bug report looks lik.
The maintainers (and other people like you) need understand your report, be able to reproduce the behavior, and find related reports easily.
If all three of those condition are met, your bug report will be quickly and efficiently be handled, and you will have directly improved the experience for others.

Before creating a bug report, please check [this list](#before-submitting-a-bug-report) as you might find out that you don't need to create one. 
When you are creating a bug report, please [include as many relevant details as possible](#how-do-i-submit-a-good-bug-report). Feel free to remove any non applicable junk.
Use [the template](ISSUE_TEMPLATE.md), as the information it asks for helps you help us help you more efficiently.

#### Before Submitting A Bug Report

* **Do a [quick search]()** to see if the problem has already been reported. 
* If it has **and the issue is still open**, add a comment to the existing issue instead of opening a new one.
* If you find a **Closed** issue that seems like it is the same thing that you're experiencing, open a new issue and include a **link** to the original issue in the body of your new one.

#### How Do I Submit A (Good) Bug Report?

Bugs are tracked as [GitHub issues](https://guides.github.com/features/issues/). 
Your first step in creating the issue is to use [the template](ISSUE_TEMPLATE.md).

Explain the problem clearly and include additional details to help maintainers reproduce the problem:

* **Use a clear and descriptive title** for the issue to identify the problem.
* **Describe the steps which reproduce the problem** in as many details as possible. Be specific as any detail might matter.
* **Describe the behavior you observed after following the steps** and point out what exactly is the problem with that behavior.
* **Explain which behavior you expected to see instead and why.**
* **Include screenshots and/or animated GIFs** which show you following the steps and clearly demonstrate the problem.
* **If you're reporting that the game crashed**, include a crash report with a stack trace from the operating system. I've gotta look up where to find that.
* **If the problem wasn't triggered by a specific action**, describe what you were doing before the problem happened.
* **Include which version of the game are you running?** The version number should be written on the first screen when you launch the game.

### Suggesting Enhancements

You may have a good idea on how to improve the game, whether it be a new feature or a minor improvement. We want those ideas.
Submitting suggestions is functionally similar to reporting bugs, but without all the boring stuff.

When you are creating an enhancement suggestion, please [include as many details as possible](#how-do-i-submit-a-good-enhancement-suggestion). 
Use [the template](ISSUE_TEMPLATE.md) as usual, including the steps that you imagine you would take if the feature you're requesting existed.

#### How Do I Submit A (Good) Enhancement Suggestion?

Enhancement suggestions are tracked as [GitHub issues](https://guides.github.com/features/issues/). After you've determined [which repository](#atom-and-packages) your enhancement suggestion is related to, create an issue on that repository and provide the following information:

* **Use a clear and descriptive title** for the issue to identify the suggestion.
* **Provide a step-by-step description of the suggested enhancement** in as many details as possible.
* **Describe the current behavior** and **explain which behavior you expected to see instead** and why.
* **Explain why this enhancement would be useful** to most Atom users and isn't something that can or should be implemented as a [community package](#atom-and-packages).

### Code or Asset Contributions

Making an actual change in the project is really admirable and also a simple but complicated process. This section will guide you through said process.

After reading through the next subsections don't forget to head over to the [Pull Requests](#pull-requests) on how to submit your changes.

#### Tools

Unity 2018.2.5 currently.

#### Git Flow

I'll do it tomorrow.

### Pull Requests

* Fill in [the template](PULL_REQUEST_TEMPLATE.md)
* Do not include issue numbers in the PR title
* Include screenshots and/or animated GIFs in your pull request whenever possible.

## Styleguides

Follow theses for good luck.

### Git Commit Messages

* These are just good habits. Pull requests take priority if you want to save your energy.
* Use the present tense ("Add feature" not "Added feature")
* Use the imperative mood ("Move cursor to..." not "Moves cursor to...")
* Limit the first line to 72 characters or less
* Reference issues and pull requests liberally after the first line
* Consider starting the commit message with an applicable emoji:
    * :art: `:art:` when improving the format/structure of the code
    * :racehorse: `:racehorse:` when improving performance
    * :non-potable_water: `:non-potable_water:` when plugging memory leaks
    * :memo: `:memo:` when writing docs
    * :penguin: `:penguin:` when fixing something on Linux
    * :apple: `:apple:` when fixing something on macOS
    * :checkered_flag: `:checkered_flag:` when fixing something on Windows
    * :bug: `:bug:` when fixing a bug
    * :fire: `:fire:` when removing code or files
    * :green_heart: `:green_heart:` when fixing the CI build
    * :white_check_mark: `:white_check_mark:` when adding tests
    * :lock: `:lock:` when dealing with security
    * :arrow_up: `:arrow_up:` when upgrading dependencies
    * :arrow_down: `:arrow_down:` when downgrading dependencies
    * :shirt: `:shirt:` when removing linter warnings

### C# Styleguide

All C# code should follow the [Style]().
