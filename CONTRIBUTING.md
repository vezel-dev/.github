# Contributing

Before opening an issue or submitting a pull request, please read through this
document to familiarize yourself with the development process.

## Issue Tracker

The [GitHub Issues](https://docs.github.com/en/issues) tracker is where all bug
reports and feature requests should be posted. Other community areas are not
appropriate for these as issues raised there are likely to be lost or forgotten.

Please respect the following points when posting on the issue tracker:

* Do not post support requests or questions. Instead, check our
  [support channels](SUPPORT.md).
* Do not post security issues. See our [security policy](SECURITY.md).
* Do not violate
  [GitHub's various site policies](https://docs.github.com/en/github/site-policy).
* Do not post off-topic comments or otherwise derail a discussion.

Issues and/or comments violating these rules may be deleted. Repeated violations
may lead to
[interaction limits](https://docs.github.com/en/communities/moderating-comments-and-conversations/limiting-interactions-in-your-repository)
being enacted.

### Bug Reports

The ideal bug report is one that is immediately actionable by a person looking
to resolve it. To that end, a bug report should include:

* The version(s) of all software.
* A self-contained test case that reproduces the issue, along with instructions
  to trigger the issue.
* A detailed description of current behavior (including stack traces(s) if
  applicable) and expected behavior.

Basically, try your best to ensure that fixing the bug will not require us to
ask you for further information. This makes it more likely for the bug to be
fixed in a timely fashion. Of course, in some cases, clarification and
discussion is necessary due to unexpected factors or sheer complexity.

### Feature Requests

Feature requests are welcome, but please note the following:

* Take a moment to consider whether the feature really makes sense for the core
  project. Many features can live as community NuGet packages.
* It is up to you to convince the maintainers that the feature should be
  included. You will need to make a strong case as the bar for new features is
  fairly high.
* Be as detailed as possible when describing the proposed feature. Explore
  benefits and drawbacks. Consider which alternatives are available, and explain
  why you believe they are insufficient.

At the end of the day, whether a feature request is accepted is up to the
maintainers. There is no guarantee that a feature request will be accepted, no
matter how detailed it is. Also, the maintainers do not necessarily commit to
implementing a feature request when accepting it; acceptance just means that
anyone can implement it and submit a pull request in the knowledge that the
feature is a welcome addition.

## Pull Requests

[GitHub pull requests](https://docs.github.com/en/pull-requests) are a great way
to contribute, whether it be code or documentation improvements. It is a good
idea to check the issue tracker to see if someone else is already working on
something before you start working on it. For feature additions, it is also
important to open a feature request on the issue tracker to see if the
maintainers are actually interested in merging it.

### Etiquette

While pull requests to clean up messy/hacky code (i.e. refactoring) are welcome,
we are not likely to accept pull requests that just change code style. Further,
please make sure that any code you contribute adheres to the style of the
surrounding code.

Please try to keep your pull request free of unrelated changes. If you need to
fix another bug in order to make your pull request work, please submit that bug
fix as a separate pull request.

Never create merge commits in your pull request. Instead, use
[Git's rebasing functionality](https://docs.github.com/en/get-started/using-git/about-git-rebase).

### Licensing & Copyright

When you contribute code or documentation, you agree to make it available under
the project's licensing terms.

Copyright assignment is not necessary when contributing; individual contributors
retain copyrights for their contributed code.

### Inactivity

If a pull request has been sitting for months with no updates from the author,
we may choose to close it. This is to avoid cluttering the pull request queue,
which could lead to other pull requests being lost. If your pull request is
closed due to inactivity, you are always welcome to reopen it if/when you have
time to address any issues that were brought up on it.

We do our best to review all pull requests in a timely fashion, but since the
maintainers have limited time, we may sometimes take a while to review a pull
request. If your pull request has not received a review for a week or more, feel
free to ping relevant individuals on the pull request.
