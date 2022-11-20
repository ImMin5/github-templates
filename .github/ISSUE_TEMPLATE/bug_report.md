---
name: Bug report
about: Create a report to help us improve
title: ''
labels: 'bug'
assignees: ''
---

body:
  - type: markdown
    attributes:
      value: | 
          If you are trying to resolve an environment-specific issue or have a one-off question about the edge case that does not require a feature then please consider asking a question in argocd slack [channel](https://argoproj.github.io/community/join-slack).

  - type: checkboxes
    id: no-duplicate-issues
    attributes:
      label: 'Checklist:'
      options:
        - label: "I've searched in the [docs](https://cloudforet.io/docs/) and [QnA](https://github.com/cloudforet-io/community/discussions/categories/q-a) for my answer"
          required: true
        - label: " I've included steps to reproduce the bug."
          required: true
        - label: " I've pasted the output of `microservice version`."
          required: true

**Describe the bug**

<!-- A clear and concise description of what the bug is. -->

**To Reproduce**

<!-- A list of the steps required to reproduce the issue. Best of all, give us the URL to a repository that exhibits this issue. -->

**Expected behavior**

<!-- A clear and concise description of what you expected to happen. -->

**Screenshots**

<!-- If applicable, add screenshots to help explain your problem. -->

**Version and Enviroment**


```shell
Paste the output from `microservice version` here.
```

**Logs**

```
Paste any relevant application logs here.
```