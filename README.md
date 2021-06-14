<!-- markdownlint-disable MD032 MD033-->
# Github Project Template**

* All the markdown follows [MarkdownLint rules](https://github.com/DavidAnson/markdownlint).

## 📚 **What does it include?**

   1. A README template file with a default template to start documenting your project. (it includes personalized badges and text with your project details)
   1. A CHANGELOG template file based on [Keep a Changelog](https://keepachangelog.com/en/1.0.0/).
   1. An [issue_label_bot.yaml](/.github/issue_label_bot.yaml) file to use the issue adder Github bot. [Activate it or check its documentation](https://github.com/marketplace/issue-label-bot).
   1. A [config.yml](/.github/config.yml) file to modify multiple bot's behaviours.
   1. A [settings.yml](/.github/settings.yml) file to use the popular settings Github bot. [Activate it or check its documentation](https://probot.github.io/apps/settings/).
   1. A [CONTRIBUTING](/.github/CONTRIBUTING.md) explaining how to contribute to the project. [Learn more with the Github guide](https://docs.github.com/en/github/building-a-strong-community/setting-guidelines-for-repository-contributors).
   1. A [SUPPORT](/.github/SUPPORT.md) explaining how to support the project. [Learn more with the Github guide](https://docs.github.com/en/github/building-a-strong-community/adding-support-resources-to-your-project).
   1. A [SECURITY](/.github/SECURITY.md) with a guide on how to post a security issue. [Learn more with the Github guide](https://docs.github.com/es/github/managing-security-vulnerabilities/adding-a-security-policy-to-your-repository).
   1. A [CODEOWNERS](/.github/CODEOWNERS) with the new user as the main owner. [Learn more with the Github guide](https://docs.github.com/en/github/creating-cloning-and-archiving-repositories/about-code-owners).
   1. A [CODE_OF_CONDUCT](/.github/CODE_OF_CONDUCT.md) with a basic code of conduct. [Learn more with the Github guide](https://docs.github.com/en/github/building-a-strong-community/adding-a-code-of-conduct-to-your-project).
   1. A [PULL_REQUEST_TEMPLATE](/.github/pull_request_template.md) with a template for your pull request that closes issues with keywords. [Learn more with the Github guide](https://docs.github.com/es/github/building-a-strong-community/creating-a-pull-request-template-for-your-repository).
   1. Multiple [issues templates](/.github/ISSUE_TEMPLATE). [Learn more with the Github guide](https://docs.github.com/en/github/building-a-strong-community/configuring-issue-templates-for-your-repository).
        1. A [config.yml](/.github/ISSUE_TEMPLATE/config.yml) with the config and information about the issue templates.
        1. A [Blank issue template](/.github/ISSUE_TEMPLATE) with the super basic stuff, all the issues should contain.
        1. A [Bug issue template](/.github/ISSUE_TEMPLATE/1-bug-report.md).
        1. A [Failing test issue template](/.github/ISSUE_TEMPLATE/2-failing-test.md).
        1. A [Documentation issue template](/.github/ISSUE_TEMPLATE/3-docs-bug.md).
        1. A [Feature request issue template](/.github/ISSUE_TEMPLATE/4-feature-request.md).
        1. A [Security report issue template](/.github/ISSUE_TEMPLATE/5-security-report.md).
        1. A [Question or support issue template](/.github/ISSUE_TEMPLATE/6-question-support.md).

---

### 🌲 **Project tree**

```text
.
├── CHANGELOG.md
├── .github
│   ├── CODE_OF_CONDUCT.md
│   ├── CODEOWNERS
│   ├── CONTRIBUTING.md
│   ├── FUNDING.yml
│   ├── issue_label_bot.yaml
│   ├── config.yml
│   ├── ISSUE_TEMPLATE
│   │   ├── 1-bug-report.md
│   │   ├── 2-failing-test.md
│   │   ├── 3-docs-bug.md
│   │   ├── 4-feature-request.md
│   │   ├── 5-enhancement-request.md
│   │   ├── 6-security-report.md
│   │   ├── 7-question-support.md
│   │   └── config.yml
│   ├── ISSUE_TEMPLATE.md
│   ├── pull_request_template.md
│   ├── SECURITY.md
│   ├── settings.yml
│   └── SUPPORT.md
├── .gitignore
└── README.md

2 directories, 21 files
```

### 🤖 **Used Github bots**

These are recommended bots that are prepared and configured for this template. If you install them your coding experience will probably be much better.
We deeply recommend at least installing the [issue label bot](https://github.com/marketplace/issue-label-bot) as this bot is the one that adds all the labels used in the issue templates.

1. The `issue_label_bot.yaml` file depends on the **[issue label bot](https://github.com/marketplace/issue-label-bot)**.
2. The `settings.yml` file depends on the **[settings label bot](https://probot.github.io/apps/settings/)**.
3. The `config.yml` file depends on the bot **[welcome bot](https://probot.github.io/apps/welcome/)** and **[todo bot](https://probot.github.io/apps/todo/)**
