README.md
=========

This repo has a set of issues to help us organize the Humble Release.

Each issue is for something that needs to be tested in Humble.
The tags tell you the operating system and what type of feature must be tested (e.g., `tutorial` or `installation`).

Once something has been tested and works, its issue should be closed.
If something doesn't work, the issue should be tagged with `bug` and any relevant notes should be added to the issue.

This is in place of using a real test case management software.
Using testcase management software has three main downsides:

- The open source options are poorly maintained, under documented, and require significant configuration before they can be used,
- The paid options are expensive (~40 USD/person/month)
- Most options don't have good APIs or ways of programmatically generating test cases, which means it will be a lot of manual work

In Audrow's opinion it would be good to use testcase management software only if we were going to use it full-time, rather than just on our releases, as the expenses, setup time, and learning required from everyone make it challenging to use just for releases.
