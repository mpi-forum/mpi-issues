# Introduction

This repository is for filing issues that need to be discussed by the full MPI Forum. If you are working on an issue that is being considered only by a working group or have something on a wish list, you might consider discussing your idea elsewhere, such as on a mailing list or other [working group repository](https://github.com/mpi-forum/mpi-issues/wiki#working-groups).

# Creating an Issue

If this is your first time creating an issue for the MPI Forum, please try to include the following things in your description:

* General Description of Proposal
* Impact on Users
* Impact on Implementors


Also, please update the tags for the pull request:

1. Add the appropriate working group tag (if applicable).
1. Add the target MPI Standard version tag.
1. Add the errata tag (if applicable).
1. Add the current status of the issue.
    * This will probably start with "not ready".
    * This should be updated as the issue goes through the MPI Forum process:
        1. Not Ready
        1. Scheduled Reading
        1. Had Reading
        1. Passed First Vote
        1. Passed Second Vote
1. Add the milestone for the next face-to-face meeting where this issue will be acted on by the forum (either read or voted upon).
    * This should also be updated as the issue goes through the MPI Forum process.

# Creating a Pull Request

After creating an issue, you will need to create a pull request to demonstrate the text changes for your proposal. This is required in order to present a reading to the MPI Forum.

Your pull request should include:
* All changes necessary to correctly implement your proposal.
* Other chapters which may be impacted by your proposal.
* Any constants which are impacted by your proposal should be updated/added/removed.
* The change log must be updated to include an entry for the proposal
* Any applicable appendixes must be updated
* The general index should be updated (should be automatic)
* Other indexes in the back (should be automatic)
* New terms should be added to the terms chapter
* Changed semantics in introduction should be updated