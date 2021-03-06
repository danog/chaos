# Opening a PR
Once you open a pull request, ChaosBot will give it X seconds (where X is
determined by github\_api.voting.get\_voting\_window)
before collecting votes.  During this time, you should let people know about
your contribution, so that they may vote for it and ensure your hard work gets
merged in.  If you do not wish for ChaosBot to consider your PR for merging just
yet, add "WIP" somewhere in your PR title.  Remove it when you're ready for voting.

# Changing your PR
It is very important that you avoid updating your PR with new commits after it
has been created.  The reason for this is that ChaosBot will only consider votes
that were cast **after** the last code change timestamp.  So if you collect a
bunch of votes and PR, you have lost those votes.

# Merging your PR
At the end of the voting window, ChaosBot will review the votes, and if your PR
crosses a threshold, your changes will be merged in.  If your changes are not
merged in, take the time to consider the feedback you received, and create a new
PR with changes you believe people will be willing to vote for.
