# Working in a repository of ours

Everything we build is meant to be inherited, so a repository of ours is set out for whoever comes next, and a change to it is made so the next person can follow it. This is how.

- **A branch for each change, from `main`, and a pull request for each branch.** Never a branch on another branch: if a change needs another first, the first lands first.
- **The checks pass before it merges.** Where a repository has tests, a change to what a reader sees or a program does comes with the test that holds it.
- **Commits are signed**, and the message says what changed, in a sentence a reader can follow, not what was done to the files.
- **Names use whole words**, in the vocabulary of the thing. A file is named for what it is or what it does, and its folder sets the rule.
- **The reason goes beside the change**: in the commit, in a comment where the code can’t say it, and in the notes handed over at the end of the job.
- **No secrets in a repository.** They live where the service reads them, and the repository’s own README says where.
- **Nothing scratch gets committed.** Stage files by name.

If a job of ours has become yours, the notes you were handed say how the thing is set up and why. This page is only how we work in the files. Ask us anything the notes don’t answer.
