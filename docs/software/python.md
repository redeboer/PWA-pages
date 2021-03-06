# Python developer tools

```{warning}
These pages and are **under development**.
```

In the following sections, we'll go through some of the tools that have now
been installed.

## pre-commit hook

The [pre-commit](https://pre-commit.com/) tool helps you to automatize certain
formatter and linting checks locally whenever you make a Git commit. To
activate, run the following:

```shell
pre-commit install
```

Now, whenever you commit, all checks defined in the
{file}`.pre-commit-config.yaml` file will be run. If there are issues with
certain staged files, the commit will not proceed and you will be pointed out
what to change. Some checks even apply a fix automatically. In either case, you
have to stage the new changes and redo the commit once you're satisfied.

You can also first test all staged files with the command {command}`pre-commit`
or you can test specific files with
{command}`pre-commit run --file <some files>`.

If, you want to skip these checks upon committing, just run
{command}`git commit` with the flag {command}`--no-verify`, or {command}`-n`.

## tox automation

A tool that tests _all_ relevant files is {doc}`tox <tox:index>`. The tests
that {doc}`tox <tox:index>` runs are defined in the
[tox.ini](https://github.com/ComPWA/pycompwa/blob/master/tox.ini) file in the
main directory.
