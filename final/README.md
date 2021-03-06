# Final Project

## Schedule

* Tue. 11/08 - Proposal Presentation (in class) (5 min)
  * Wed. 11/09 - Proposal Writeup (PDF via Canvas)
* Tue. 11/15 - Milestone 1 Presentation (in class) (3-5 min)
* Tue. 11/29 - Milestone 2 Presentation (in class) (3-5 min)
* Tue. 12/06 - Final Presentation (in class) (10 min)
  * Wed. 12/07 - Final Report (README)

## Grading

This project is worth 40% of the final course grade.

* 15%: Proposal and Presentation
* 20%: Milestone 1 Presentation and Status
* 20%: Milestone 2 Presentation and Status
* 45%: Final Presentation, Status, and Report

**Important:** "Status" grading will be based primarily on your documentation.
Spend time on this and write in-depth documentation!
You'll need to use rustdoc to generate documentation before each presentation
(see below: [Documentation](#documentation)).

## Project Guidelines

* Groups may be 1-2 people.

* You can either make your own project or contribute to an existing open-source
  project. If you do the latter, you should speak to the project maintainers
  first, and make sure you're able to finish your project :)

* If you start a new project, we would love to see stuff that hasn't been done in
  Rust before!

* We expect you to do about (4 weeks * 0.5 credit) worth of work per person -
  but what that means is subjective. More work will mean a more impressive
  project - but it's much more important that you finish!

* If your idea is in danger of being too big, you need to have a plan for how
  to scale it back. Carve out a reasonable subset of the idea as your baseline,
  and have additional goals on top of that.

* We would really like your project to be open-source!
  You don't need to pick licensing immediately, but consider Apache and MIT.

## Suggestions

### Libraries

* Piston (GUI toolkit)
* nix (libc wrapper)
* nom (byte-level parser combinator)
* future.rs (futures & streams)

### Projects Looking for Contributors

(From the Rust Belt Rust conference)

* Iron
* Tokio
* intermezzOS
* Pijul
* servo
* nom
* clap
* Habitat

### Possible ideas

* Rewriting slow parts of other programs (e.g. Python/Ruby)
* Distributed system / networking
    * Implementing a communication protocol stack or library
    * Distributed server
* Write a server for a particular protocol (ssh, ntp, ftp, http)
* Games
    * Contributing to Piston
    * Console emulator
* Take a look at the [2017 Rust
  Roadmap](https://internals.rust-lang.org/t/setting-our-vision-for-the-2017-cycle/3958)
  for libraries that are wanted.

## Proposal Document

* Your proposal document should be about 1 page. Submit as a PDF on Canvas.

* List your group members.

* Abstract: Your idea in a sentence or two.

* Open-source or not. If not, why?
  You don't need to pick a license right now, but Apache and MIT are good.

* Project outline: Your minimal goals, expected goals, and stretch goals.
    * This should be detailed enough that we can judge the complexity and merit.
    * Include appropriate technical details of each goal.

* Tentative Schedule: Which goals do you want to finish each week? Milestone
  presentations will be at the beginning of class each week.
    * You don't need to stick strictly to this schedule, but it's good to have a

## Milestone Presentations

These will be very quick (3-5 min). Update us on your progress: have you learned
anything interesting? Completed a major part of your project? Come across an
unexpected problem?

All of your work must be in your repository by class time, including
rustdoc documentation for the work you're presenting (see below).
If you're contributing, this means it should be in your fork.

## Final Report

Write your report in markdown, and save it as `REPORT.md` in your repository
root, and we'll find it there. If you don't have a dedicated repository for this
project (e.g. you are forking another project) or you plan to immediately
publicize your project, you can submit via Canvas. If you have screenshots or
images, save them in the repo and embed them in `REPORT.md`.

We'll expect about 2-3 printed-pages-worth of info. Include whatever is
appropriate or important for your project, such as:

* Summary
* Accomplishments
* Components, structure, design decisions
* Testing approach and results
* Benchmarks
* Limitations
* Postmortem
    * What went well
    * What you would do differently
* etc.

Keep in mind that if your repo is public, your report will be as well.
If you have any private feedback, email us.
