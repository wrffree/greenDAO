Contributing to greenDAO
========================

Development Setup
-----------------
To build the project locally you need:

* JDK 8 or higher
* Android SDK with `compileSdkVersion` 25 and build tools `25.0.2`
* Gradle (the wrapper `./gradlew` is included — no separate installation needed)

Clone the repository and import it into Android Studio or build from the command line:

```bash
git clone https://github.com/greenrobot/greenDAO.git
cd greenDAO
./gradlew assemble
```

To run the tests:

```bash
./gradlew test
```

Code Style
----------
Please follow the existing code style when contributing:

* Use 4 spaces for indentation (no tabs)
* Follow standard Java naming conventions (camelCase for methods and fields, PascalCase for classes)
* Keep lines to a reasonable length (120 characters max)
* Add Javadoc comments to all public API methods and classes
* Write unit tests for new functionality

Pull Requests
-------------
Before submitting a pull request:

1. **Fork** the repository and create your branch from `master`
2. **Write tests** — all new functionality should be accompanied by unit tests
3. **Ensure tests pass** — run `./gradlew test` and verify there are no failures
4. **Keep it focused** — one pull request per feature or bug fix
5. **Describe your change** — fill in the pull request description with context, motivation, and a summary of what changed

Branch naming conventions:

* `fix/short-description` for bug fixes
* `feature/short-description` for new features
* `docs/short-description` for documentation updates

Before you create an Issue...
=============================

There are better Places for Support
-----------------------------------
We want your question to be answered, so it is important that you ask at the right place. Be aware that an issue tracker is not the best place to ask for support. An issue tracker is used to track issues (bugs or feature requests).
Instead, please use [stackoverflow.com](http://stackoverflow.com/questions/tagged/greendao?sort=frequent) and use the tag [greendao](http://stackoverflow.com/tags/greendao/info) for your question.

If you want professional support, check http://greenrobot.org/contact-support/.

Examples for support questions that are more likely to be answered on StackOverflow:

* Asking how something works
* Asking how to use greenDAO in a specific scenario
* Your app crashes/misbehaves and you are not sure why

The perfect Issue Report
------------------------
A couple of simple steps can save time for everyone.

Check before reporting:

* It's not a support inquiry
* You have read the docs
* You searched the web and stackoverflow
* You searched existing issues to avoid duplicates

Reporting bugs:

 * Please investigate if the bug is really caused by the library. Isolate the issue: what's the minimal code to reproduce the bug?
 * Bonus steps to gain extra karma points: once you isolated and identified the issue, you can prepare a pull request. Submit a unit test causing the bug, and ideally a fix for the bug.

Requesting features:

 * Ask yourself: is the feature useful for a majority of users? One of our major goals is to keep the API simple and concise. We do not want to cover all possible use cases, but those that make 80% of users happy.

Thanks for reading!
===================
It's your feedback that makes maintaining this library fun.
