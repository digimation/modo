# Onboarding

This document is an outline of the things we tell new Collaborators at their
onboarding session.

## One week before the onboarding session

* If the new Collaborator is not yet a member of the Beautiful Patterns GitHub organization, confirm that they have SSH keys. It will not be possible to add them to the organization if they are not using SSH keys. 
* Announce the accepted nomination in a meeting and in the  mailing list.

## Fifteen minutes before the onboarding session

* Prior to the onboarding session, add the new Collaborator to [the Collaborators team].

## Onboarding session

* This session will cover:
  * [local setup](#local-setup)
  * [project goals & values](#project-goals--values)
  * [managing the issue tracker](#managing-the-issue-tracker)
  * [reviewing PRs](#reviewing-prs)

## Local setup

* GitHub:
  * Make sure you have whitespace=fix: `git config --global --add
    apply.whitespace fix`
  * Always continue to PR from your own GitHub fork
  * Update from `upstream`:
  * Make a new branch for each PR you submit.
  * Membership: Consider making your membership in the GitHub organization public. This makes it easier to identify Collaborators. 

* Notifications:
  * Use [https://github.com/notifications](https://github.com/notifications) or
    set up email
  * Watching the main repo will flood your inbox (several hundred notifications
    per month), so be prepared

The project has one venues for real-time discussion:
* forum (https://forum.beautifulpatterns.org)

## Project goals & values

* Collaborators are the collective owners of the project
  * The project has the goals of its contributors

* There are some higher-level goals and values
  * Empathy towards users matters (this is in part why we onboard people)
  * Generally: try to be nice to people!
  * The best outcome is for people who come to our issue tracker to feel like
    they can come back again.

* You are expected to follow *and* hold others accountable to the
  [Code of Conduct][].

## Managing the issue tracker

* You have (mostly) free rein; don't hesitate to close an issue if you are
  confident that it should be closed
  * Be nice about closing issues! Let people know why, and that issues and PRs
    can be reopened if necessary

* See [Who to CC in the issue tracker][who-to-cc].
  * This will come more naturally over time
  * For many of the teams listed there, you can ask to be added if you are
    interested

## Reviewing PRs

* The primary goal is for the codebase to improve.
* Secondary (but not far off) is for the person submitting code to succeed. A
  pull request from a new contributor is an opportunity to grow the community.
* Review a bit at a time. Do not overwhelm new contributors.
  * It is tempting to micro-optimize. Don't succumb to that temptation. 
    Techniques that provide improved performance today may be
    unnecessary in the future.
* Be aware: Your opinion carries a lot of weight!
* Nits (requests for small changes that are not essential) are fine, but try to
  avoid stalling the pull request.
  * Identify them as nits when you comment: `Nit: change foo() to bar().`
  * If they are stalling the pull request, fix them yourself on merge.
* Insofar as possible, issues should be identified by tools rather than human
  reviewers. If you are leaving comments about issues that could be identified
  by tools but are not, consider implementing the necessary tooling.
* Minimum wait for comments time
  * There is a minimum waiting time which we try to respect for non-trivial
    changes so that people who may have important input in such a distributed
    project are able to respond.
  * For non-trivial changes, leave the pull request open for at least 48 hours.
  * If a pull request is abandoned, check if they'd mind if you took it over
    (especially if it just has nits left).
* Approving a change
  * Collaborators indicate that they have reviewed and approve of the changes in
    a pull request using GitHub’s approval interface
  * Some people like to comment `LGTM` (“Looks Good To Me”)
  * You have the authority to approve any other collaborator’s work.
  * You cannot approve your own pull requests.
  * When explicitly using `Changes requested`, show empathy – comments will
    usually be addressed even if you don’t use it.
    * If you do, it is nice if you are available later to check whether your
      comments have been addressed
    * If you see that the requested changes have been made, you can clear
      another collaborator's `Changes requested` review.
    * Use `Changes requested` to indicate that you are considering some of your
      comments to block the PR from landing.


## Final notes

* Don't worry about making mistakes: everybody makes them, there's a lot to
  internalize and that takes time (and we recognize that!)
* Almost any mistake you could make can be fixed or reverted.
* The existing Collaborators trust you and are grateful for your help!
