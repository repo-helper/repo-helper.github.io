# repo-helper

`repo-helper` is a tool to manage configuration files, build scripts etc. across multiple projects. It provides a set of templates, which are populated using per-repository configuration values to create a set of files for each repository.

`repo-helper` configures the following tools and services:

* [GitHub Actions](https://github.com/features/actions)
* [Dependabot](https://dependabot.com/)
* [ImgBot](https://imgbot.net/)
* [Conda](https://docs.conda.io/en/latest/)
* [tox](https://tox.readthedocs.io/en/latest/)
* [pytest](https://docs.pytest.org/en/latest/)
* [mypy](http://mypy-lang.org/)
* [yapf-isort](https://github.com/domdfcoding/yapf-isort)


While targeted at Python projects using a particular workflow, `repo-helper` can also be used to build custom tools to suit your requirements.


`repo-helper` also includes a complementary suite of tools for:

* [Creating tagged releases](https://docs.repo-helper.uk/en/latest/usage/release.html)
* [Building Python distributions](https://docs.repo-helper.uk/en/latest/usage/build.html)
* [Displaying Python requirements](https://docs.repo-helper.uk/en/latest/usage/show.html#repo-helper-show-requiremen)
* [Suggesting Trove Classifiers](https://docs.repo-helper.uk/en/latest/usage/suggest.html#repo-helper-suggest-classifiers)

There is also a [GitHub bot](https://github.com/apps/repo-helper), which can keep your configuration files up to date via pull requests.
