# Contributing to this repository <!-- omit in toc -->

## Getting started <!-- omit in toc -->

Before you begin:
- This site is powered by Node.js, Ruby Rails and HTML. Check to see if you're on the [version of node we support](contributing/development.md).
- Have you read the [code of conduct](CODE_OF_CONDUCT.md)?
- Check out the [existing issues](https://github.com/CraftyDevelopers/Github-Commands/issues) 

### Use the 'make a contribution' 

Before you make your changes, check to see if an [issue exists](https://github.com/CraftyDevelopers/Github-Commands/issues) already for the change you want to make.

### Don't see your issue? Open one

If you spot something new, open an issue using a [template](https://github.com/CraftyDevelopers/Github-Commands/issues/new/choose). We'll use the issue to have a conversation about the problem you want to fix.

### Ready to make a change? Fork the repo

Fork using GitHub Desktop:

- [Getting started with GitHub Desktop](https://docs.github.com/en/desktop/installing-and-configuring-github-desktop/getting-started-with-github-desktop) will guide you through setting up Desktop.
- Once Desktop is set up, you can use it to [fork the repo](https://docs.github.com/en/desktop/contributing-and-collaborating-using-github-desktop/cloning-and-forking-repositories-from-github-desktop)!

Fork using the command line:

- [Fork the repo](https://docs.github.com/en/github/getting-started-with-github/fork-a-repo#fork-an-example-repository) so that you can make your changes without affecting the original project until you're ready to merge them.

Fork with [Codesandbox](https://codesandbox.io):

- [Fork, edit, and preview](https://codesandbox.io/docs/faq) using [Codesandbox](https://codesandbox.io) without having to install and run the project locally.

### Make your update:
Make your changes to the file(s) you'd like to update. Here are some tips and tricks for [using the docs codebase](https://github.com/github/docs/blob/main/CONTRIBUTING.md#working-in-the-githubdocs-repository).
  - Are you making changes to the application code? You'll need at least **Node.js v14** to run the site locally. See [contributing/development.md](https://github.com/github/docs/blob/main/contributing/development.md).

### Open a pull request
When you're done making changes and you'd like to propose them for review, use the pull request template to open your PR (pull request).

### Submit your PR & get it reviewed
- Once you submit your PR, others from the Docs community will review it with you. The first thing you're going to want to do is a [self review](#self-review).
- After that, we may have questions, check back on your PR to keep up with the conversation.
- Did you have an issue, like a merge conflict? Check out our [git tutorial](https://lab.github.com/githubtraining/managing-merge-conflicts) on how to resolve merge conflicts and other issues.

### Your PR is merged!
Congratulations! Thanks to you. :sparkles:

<!--- Once your PR is merged, you will be proudly listed as a contributor in the [contributor chart](https://github.com/github/docs/graphs/contributors). --->

### Keep contributing 

Now that you're a part of the community, you can keep participating in many ways.

## Types of contributions :memo:
You can contribute to the content and site in several ways. This repo is a place to discuss and collaborate here! Our small, but mighty :muscle: web dev team is maintaining this repo, to preserve our bandwidth, off topic conversations will be closed.

### :mega: Discussions
Discussions are where we have conversations.

If you've found something in the content or the website that should be updated, search open issues to see if someone else has reported the same thing. If it's something new, open an issue using a [template](https://github.com/CraftyDevelopers/Github-Commands/issues/new/choose). We'll use the issue to have a conversation about the problem you want to fix.

### :hammer_and_wrench: Pull requests
A [pull request](https://docs.github.com/en/github/collaborating-with-issues-and-pull-requests/about-pull-requests) is a way to suggest changes in our repository.

When we merge those changes, they should be deployed to the live site within 24 hours. :earth_africa: To learn more about opening a pull request in this repo, see [Opening a pull request](#opening-a-pull-request) below.

### :question: Support
We are a small team working hard to keep up with the documentation demands of a continuously changing product. Unfortunately, we just can't help with support questions in this repository.

If you're having trouble with your GitHub account, contact [Support](https://support.github.com/contact).

### :earth_asia: Translations

This website is internationalized and available in multiple languages. The source content in this repository is written in English. We integrate with an external localization platform called [Crowdin](https://crowdin.com) and work with professional translators to localize the English content.

**We do not currently accept contributions for translated content**, but we hope to in the future.

### :balance_scale: Site Policy & Code of Conduct 
The [Code of Conduct](CODE_OF_CONDUCT.md) & policies are published here too!

If you find a typo in the site policy section, you can open a pull request to fix it. For anything else, see [the CONTRIBUTING guide in the site-policy repo](https://github.com/CraftyDevelopers/Github-Commands/CONTRIBUTING.md).

## Starting with an issue
You can browse existing issues to find something that needs help!

### Labels
Labels can help you find an issue you'd like to help with.
- The [`help wanted` label](https://github.com/CraftyDevelopers/Github-Commands/issues?q=is%3Aopen+is%3Aissue+label%3A%22help+wanted%22) is for problems or updates that anyone in the community can start working on.
- The [`good first issue` label](https://github.com/CraftyDevelopers/Github-Commands/issues?q=is%3Aopen+is%3Aissue+label%3A%22good+first+issue%22) is for problems or updates we think are ideal for beginners.
- The [`content` label](https://github.com/CraftyDevelopers/Github-Commands/issues?q=is%3Aopen+is%3Aissue+label%3Acontent) is for problems or updates in the content on docs.github.com. These will usually require some knowledge of Markdown.
- The [`engineering` label](https://github.com/CraftyDevelopers/Github-Commands/issues?q=is%3Aopen+is%3Aissue+label%3Aengineering) is for problems or updates in the website. These will usually require some knowledge of JavaScript/Node.js or YAML to fix.

## Opening a pull request
You can use the GitHub user interface :pencil2: for some small changes, like fixing a typo or updating a readme. You can also fork the repo and then clone it locally, to view changes and run your tests on your machine.

## Reviewing
We (usually the web dev team, but sometimes the product managers, engineers, or support too!) review every single PR. The purpose of reviews is to create the best content we can for people who use this repo or website.

:yellow_heart: Reviews are always respectful, acknowledging that everyone did the best possible job with the knowledge they had at the time.  
:yellow_heart: Reviews discuss content, not the person who created it.  
:yellow_heart: Reviews are constructive and start conversation around feedback.  

### Self review
You should always review your own PR first.

For content changes, make sure that you:
- [ ] Confirm that the changes address every part of the content design plan from your issue (if there are differences, explain them).
- [ ] Review the content for technical accuracy.
- [ ] Copy-edit the changes for grammar, spelling, and adherence to the style guide.
- [ ] Check new or updated Liquid statements to confirm that versioning is correct.
- [ ] Check that all of your changes render correctly in staging. Remember, that lists and tables can be tricky.
- [ ] If there are any failing checks in your PR, troubleshoot them until they're all passing.

### Pull request template
When you open a pull request, you must fill out the "Ready for review" template before we can review your PR. This template helps reviewers understand your changes and the purpose of your pull request.

## Windows

This site can be developed on Windows, however a few potential gotchas need to be kept in mind:

1. Regular Expressions: Windows uses `\r\n` for line endings, while Unix based systems use `\n`. Therefore when working on Regular Expressions, use `\r?\n` instead of `\n` in order to support both environments. The Node.js [`os.EOL`](https://nodejs.org/api/os.html#os_os_eol) property can be used to get an OS-specific end-of-line marker.
1. Paths: Windows systems use `\` for the path separator, which would be returned by `path.join` and others. You could use `path.posix`, `path.posix.join` etc and the [slash](https://ghub.io/slash) module, if you need forward slashes - like for constructing URLs - or ensure your code works with either.
1. Bash: Not every Windows developer has a terminal that fully supports Bash, so it's generally preferred to write [scripts](/script) in JavaScript instead of Bash.
