# workflows

A set of reusable workflows for atomyze organization repositories

## Table of Contents
- [workflows](#workflows)
  - [Table of Contents](#table-of-contents)
  - [Description](#description)
  - [Links](#links)
  - [Debug](#debug)
  - [Develop](#develop)
  - [License](#license)

## Description

A set of reusable workflows for Atomyze projects. It includes basic routines for:

* Go library checks
* Go service checks
* Go service build and push
* Automation routines for integration tests
* Routines for workflow validation and verification
* Routines for building and checking chaincodes
* Various SAST (Static Application Security Testing) and DAST (Dynamic Application Security Testing) checks

## Links

* https://docs.github.com/en/actions/using-workflows/reusing-workflows
* https://dev.to/n3wt0n/avoid-duplication-github-actions-reusable-workflows-3ae8
* https://github.blog/2022-02-10-using-reusable-workflows-github-actions/
* https://infosecwriteups.com/build-centralized-security-workflows-in-github-a-tale-of-reusable-workflows-757963c3f1ec
* https://www.linkedin.com/pulse/reusable-workflows-github-actions-iustin-alexandru-achitenei

## Debug

* https://blog.harshcasper.com/debugging-github-actions-workflows-effectively

* Simple way to debug with ssh on runner
```
- name: Setup tmate session
  uses: mxschmitt/action-tmate@v3
```

## Develop

* https://marketplace.visualstudio.com/items?itemName=GitHub.vscode-github-actions

## License

[Default License](LICENSE)