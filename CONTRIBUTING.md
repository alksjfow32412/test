# Contributing to Excelente

thank you for helping us to grow and for interest on how to contributing ️️💞🚀, this document will explain necessary topics for contributing.

[comment]: <> (will continue this file later...)

# Code of Conduct

Excelente has adopted the [Contributor Covenant](https://www.contributor-covenant.org/) as its Code of Conduct, and we expect project participants to adhere to it.
Please read [the full text](./CODE_OF_CONDUCT.md) so that you can understand what actions will and will not be tolerated.

# how you can help Excelente

you can help us in lots of ways which could be one of the following:

- improving the documentation
- opening issue for any topic that will improve Excelente
- give us feedback
- review [pull requests](https://github.com/FOSSgeek/Excelente/pulls)
- code improvement
- tell your team and friends about us

# understanding Excelente repo

we use specific workflow and repo which you should understand if you want to contribute to Excelente ( we appreciate your kindness ❤️), the most important concept that we use everyday is [**monorepo**](https://en.wikipedia.org/wiki/Monorepo),
our monorepo have three main folders :

- packages/components, which is where Excelente components and all UI components live in
- docs, our official docs which use docusaurus
- packages/icons, which is where Excelente Icons and all related Icons stuff live in

# pull request

Working on your first Pull Request? You can learn how from this free video series:
[How to Contribute to an Open Source Project on GitHub](https://egghead.io/courses/how-to-contribute-to-an-open-source-project-on-github)

If you decide to fix an issue, please be sure to check the comment thread in case somebody is already working on a fix. If nobody is working on it at the moment, please leave a comment stating that you have started to work on it so other people don't accidentally duplicate your effort.

If somebody claims an issue but doesn't follow up for more than a week, it's fine to take it over but you should still leave a comment. If there has been no activity on the issue for 7 to 14 days, it is safe to assume that nobody is working on it.

Excelente is a community project, so Pull Requests are always welcome, but, before working on a large change, it is best to open an issue first to discuss it with the maintainers.

When in doubt, keep your Pull Requests small. To give a Pull Request the best chance of getting accepted, don't bundle more than one feature or bug fix per Pull Request. It's often best to create two smaller Pull Requests than one big one.

are your ready now for your next pull request? then follow the below steps, lets goooo 🚀:

1. fork Excelente to your own repo

2. clone your repo (your fork of Excelente) to your local pc/machine

```sh
git clone https://github.com/<your username>/Excelente.git
cd Excelente
git remote add upstream https://github.com/FOSSgeek/Excelente.git
```

3. install all dependencies with npm:

```sh
npm i
```

4. Create a new branch out of the main branch. We follow the convention [type/scope]. For example fix/accordion-hook or docs/menu-typo. type can be either docs, fix, feat, build, or any other conventional commit type. scope is just a short id that describes the scope of work.

```sh
git checkout -b fix/doc-typo
```

5. Make changes, commit and push to your fork:

```sh
git push -u origin HEAD
```

6. test the final code and make sure everything is Excelente

7. Go to the [repository](https://github.com/FOSSgeek/Excelente) and make a Pull Request.

We and the community will review your Pull Request and either merge it, request changes to it, or close it with an explanation.

# License

By contributing your code to the Excelente GitHub [repository](https://github.com/FOSSgeek/Excelente), you agree to license your contribution under the [**MIT** license](https://github.com/FOSSgeek/Excelente/blob/main/LICENSE)
