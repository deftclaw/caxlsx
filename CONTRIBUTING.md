# How to contribute to caxlsx

## Did you find a bug?

 * **Ensure the bug was not already reported** by searching on GitHub under [Issues](https://github.com/caxlsx/caxlsx/issues) and [Pull requests](https://github.com/caxlsx/caxlsx/pulls).

 * If you're unable to find an open issue or pull request addressing the problem, [create a new issue](https://github.com/caxlsx/caxlsx/issues/new) or – ideally – a new [pull request](https://github.com/caxlsx/caxlsx/pulls). Be sure to include a **title and clear description**, as much relevant information as possible, and a **code sample** or an **executable test case** demonstrating the expected behavior that is not occurring. It’s important that others can reproduce the problem easily.

 * A pull request must contain tests covering the behaviour added or modified by the pull request.


## Do you intend to add a new feature or change an existing one?

 * Refer to the guidelines mentioned above. Note that a feature request not accompanied by actual code (in form of a pull request) is rather unlikely to be implemented.


## Helping to resolve existing issues

There are two main ways you can help the community to resolve existing issues: **Triaging new issues**, and **fixing known bugs**.

If you have any questions about contributing, or need some help: Feel free to [join the Caxlsx Slack channel](https://join.slack.com/t/caxlsx/shared_invite/enQtOTI5OTM0MzI1Njk5LTBlMDQzNDk2YzkwODMxMmVkODMyYzJiZGU5NTQ3YTg5NTBlN2IwZTlmNTRjNzhiY2E0MDY2OTEyYmFlODI5NjA)! 


### Triaging new issues

Triaging issues can be very time-consuming, so we especially appreciate any help in this area!

Start by looking for [issues labelled “needs triage”](https://github.com/caxlsx/caxlsx/issues?q=label%3A%22needs+triage%22). Choose one of these issues, then perform the following checks:

 * Is the issue still relevant? It may have been fixed or made obsolete in the meantime.
 * Can the issue be reproduced? If necessary, ask the person who reported the issue originally to provide more information.
 * If an issue is very vague, can you help narrow it down to something more specific? Maybe you can provide additional information to help reproduce a bug, or help by eliminating needless steps that aren't required to demonstrate the problem.
 * Is it clear which portion of the caxlsx code is causing the issue? If not, try to determine the relevant code.
 * How did the relevant code came into the state causing the issue? Has it been there since the beginning, or is it the result of some later change?
 
Add comments to the issue to share your findings. Anything you can do to make bug reports more succinct or easier to reproduce helps folks trying to write code to fix those bugs - whether you end up writing the code yourself or not.

### Fixing known bugs

Look for [issues labelled “known bug”](https://github.com/caxlsx/caxlsx/issues?q=label%3A%22known+bug%22). Choose one, and try to come up with a fix.


---

_A lot of the content in this document was ~~inspired by~~ copied from the [Ruby on Rails Contributing Guidelines](https://github.com/rails/rails/blob/master/CONTRIBUTING.md)_
