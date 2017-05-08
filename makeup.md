I was out this day and I'm trying to do this group project on my own, on Friday of this assignment I couldn't make it in because my car broke down on my way to school. I had to talk to my partners that where apart of my group to know what was going on.




- A first error point might be that Bob and Carol were working on their feature from Bob's laptop and then they do an ACP from Carol's laptop. Not sure how or why they would do this, but it would seem it would leave uncommitted changes on Bob's laptop and potentially leave out changes that hadn't been made to Carol's version.

- The next issue is that Ted and Alice only to a git pull origin master onto Ted's laptop, leaving Alice without an up to date version of master. They're also working on a feature branch that is behind master by whatever Bob and Carol did.

- Next it says Bob/Carol switch to Bob's computer (which they were already working on except for the ACP, apparently). They start a new branch but don't do a git pull origin master to ensure they're on the most up to date version.

- Then, rather than reviewing PRs one at a time together, they review each others and merge across one another.

- Next Bob/Alice start working together directly in the master branch -- a no, no. Should've been working on a new branch.
