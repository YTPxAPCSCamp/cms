# Contributing and pull request process

To contribute, please send an email to contestms-discuss@googlegroups.com, or ping us on gitter with what you plan to do (unless uncontroversial and/or small), so that we can agree on the best way to implement it.

We appreciate small commits that do one thing, but also that, when possible, each commit doesn't break the master branch. Please use your best judgement for the size of the commit according to these guidelines. If a commit breaks master, we at least require to push together all commits until master is fixed.

We also appreciate a tidy history, so after you write all your code, consider tidying up the commits to reflect what you did at the end, which is usually a simplified version of the process that you followed to reach the final state. Moreover, each commit should not have PEP 8 or pyflakes warnings (see below for how to make sure you don't introduce any).

If your change involves more than one commit, please create a PR for each of them, unless for very small and obvious commits (read: fixing typos, comments, a few obvious lines), or unless some commit breaks master.

During the review, please address all comments by creating one or more 'fixup' commits on top of the branch (no forced push). At the end, either you or one of the owners can squash appropriately the fixups.