Contributing to Mayan EDMS
==========================

Issues
------

- The issue system is for reporting problems with the program code. For
questions use the forum at: https://forum.mayan-edms.com/
- Do not open issues asking for **support or consulting**. For paid support
and consultation visit: https://www.mayan-edms.com/support/
- The issue must be related to the code only, do not open issues for problems
with databases, deployments, webservers, cloud providers, etc.
- Before submitting a new issue, check for **existing issues** first and
join the discussion.
- If your issue is not attended in a while, **be patient**, the core team is
small and the codebase big.
- Try to reproduce the issue using a **separate, clean installation**,
sometimes the issue can be caused by an error in a configuration file and
not with the code itself.
- **Do not upload** sensitive, private or classified information or files
with your issue. If the issue is triggered by a user file, create a dummy
file with the same properties that can trigger the issue and upload that
file instead.
- Add steps that trigger the issue in a **repeatable manner**.
- **Screenshots** go a long way in helping understand problems.

Code
----

1. Complete and mail, or scan and email the corresponding Contributor Assignment Agreement: [Mayan EDMS Individual Contributor Assignment Agreement](https://gitlab.com/mayan-edms/mayan-edms/-/blob/master/docs/chapters/development/caa_individual.txt) or [Mayan EDMS Entity Contributor Assignment Agreement](https://gitlab.com/mayan-edms/mayan-edms/-/blob/master/docs/chapters/development/caa_entity.txt).
1. Fork [the repository](http://gitlab.com/mayan-edms/mayan-edms).
1. Choose the version for which you want to develop. The code is divided in the
following branches:

    a. **master:** Current stable version.
    a. **series/X.Y:** There will be a **series** branch for each major version
    release (1.0, 2.0). The **master** branch will be in sync with the latest
    **series** branch.
    a. **development:** Unstable branch where the development for the next minor or
    major release is happening.
    a. **feature/X:** These are branches dealing with a specific bug or feature
    that is not yet ready to be merged.
    a. The **master** and **series** branches are stable and not braking changes
    must be submitted or merged. The **development** and **feature** branches
    are unstable and should not be used in production.

1. Start making your changes in your own separate branch.
1. Write a test which shows that the bug was fixed or that the feature works as
   expected.
1. Sign your work. Your signature certifies your submission according to the
   articles of the [Developer Certificate of Origin](https://gitlab.com/mayan-edms/mayan-edms/blob/master/DCO).
   The sign-off should be in the form:

    ````
    Signed-off-by: John Doe <john.doe@example.com>
    ````

    You must use your real name and email, pseudonyms or anonymous contributions
    are not allowed. If you set your user.name and user.email git configs, you can
    sign your commit automatically with git commit -s.
1. Submit a merge request for your changes.

Feature requests
----------------

- Opening issues to start a discussion around a new feature or idea are welcomed.
- Be explicit about your idea and provide a simple scenario, others need to really
understand the concepts behind your idea if it is to be implemented.
- Be realistic in your expectation and scope of your idea.

Translations
------------
- Translations are handled using [Transifex](https://www.transifex.com/rosarior/mayan-edms/).
- Join an existing team for the language to which you wish to contribute,
if there is no team for your language, request for one to be created.
- Don't request the creation of a new language and expect others to do all the
work. If you request the creation of a new language try to do some of the
translation. Language teams that don't see activity for a while are deleted.

Code style
----------
- Refer to the [Development](https://docs.mayan-edms.com/topics/development.html)
chapter for information and examples of the code style.
