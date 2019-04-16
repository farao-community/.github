# How to contribute to FARAO

Thanks for taking the time to contribute to FARAO community!

These are a few guidelines that we need contributors to follow. These are
not *rules*, feel free to propose changes to this document and use your best
judgment in any situation.

Contribution in FARAO community can take many forms:
- Discuss features proposition on [FARAO community Spectrum chat](https://spectrum.chat/farao-community)
- Reporting bug and suggestions via [GitHub issues](https://guides.github.com/features/issues/)
- Contributing code via [GitHub pull requests](https://help.github.com/en/articles/about-pull-requests)

## Code of conduct

Before any contribution, please be aware that anyone participating in FARAO community is expected to uphold
[FARAO Code of Conduct](https://github.com/farao-community/.github/blob/master/CODE_OF_CONDUCT.md).
Please report unacceptable behavior to [contact@farao-community.com](mailto:contact@farao-community.com).

## Contributing code

### Getting started

* Make sure you have a [GitHub account](https://github.com/signup/free)
* Submit a GitHub ticket for your issue if one does not already exist
  * Clearly describe the issue following the provided issue template
  * Make sure you fill in the earliest version that you know has the issue
  * Do not hesitate to discuss your proposition/contribution on [Spectrum](https://spectrum.chat/farao-community)
* Fork the repository on GitHub

### Making changes

Please follow these steps to have your contribution considered by the maintainers:

1. Follow all instructions in the template
2. Follow the styleguides
3. After you submit your pull request, verify that all status checks are passing
4. Request a GitHub review by one of the core developers (e.g. @murgeyseb @)
5. Follow their instructions or discuss about the requested changes. Please don't take criticism personally, it is normal to iterate on this step several times
6. Repeat step 5 until the pull request is merged !

Continuous integration is setup to run on all branches automatically and will often report problems,
so don't worry about getting everything perfect on the first try (SonarCloud Analysis is a notorious problem source).
Until you add a reviewer, you can trigger as many builds as you want by amending your commits.
The status checks enforce the following:
* All tests in the test suite pass
* Checkstyle and SonarCloud report no violations

## Styleguides

### Git Commit Messages

As usual, please start the commit message with a short line describing the commit, then leave a blank line,
then give more context and explanations. You can use GitHub's integrations, for exemple to link to existing issues.
In general, pull requests with more than one commits will be squashed when merged in master.

### Java StyleGuide

* The project uses modern java, feel free to use any new APIs provided by the current java version (currently java 8)
* New API classes and methods should be documented with javadoc. Write higher level documentation for classes and lower level documentation for methods
* User-facing configuration options and general design decisions should be documented in the website maintained at https://github.com/farao-community/farao-community.github.io
* We use standard configurations of well known tools like checkstyle and sonarqube to enforce a coherent coding style, please consult those tools for justifications on these rules
