---
name: Request new translation
about: Request to add a new translation
labels: language
---

<!--
Make sure there isn't an exist issue for the language you request to add.
-->

Language:

<!--
Replace this comment with a short introduction of yourself and your former experience with Flask or translation.
-->

<!--
To become a translation coordinator and create a translation for your language, please complete the following initial tasks in 30 days:
-->

Initial tasks:

- [ ] Generate a repository from [flaskcwg/translation-template](https://github.com/flaskcwg/translation-template), include all branches.
- [ ] Name your repository as `flask-docs-<lang code>`, for example, `flask-docs-es`.
- [ ] Setup ReadtheDocs to connect your repository, use `flask-<lang code>` as the subdomain, set the default version to the `main` branch and enable single version.
- [ ] Translate the README and the pull request template, update the title, clone URL, upstream URL, and folder name in the README. You can update README to add more format or translate tips for your language.
- [ ] Translate the `docs/index.rst` file.
- [ ] Translate the `docs/installation.rst` file.
- [ ] Translate the `docs/quickstart.rst` file.
- [ ] Translate the "Tutorial" part of the docs.
- [ ] Switch the repository into the flaskcwg organization.

<!--
When you finished the tasks above, leave a comment that includes your repository URL to ping us, we will switch your repository into the flaskcwg organization, then you can work on other chapters or call for other people to contribute.

After that:
-->

Tasks after the repository is switched into flaskcwg:

- [ ] Add a new language entry to [this issue template](https://github.com/flaskcwg/translation-coordination/blob/main/README.md).
- [ ] Add a new language entry to [the README](https://github.com/flaskcwg/translation-coordination/blob/main/README.md).
- [ ] Add a new language entry to [translations page](https://github.com/flaskcwg/flaskcwg.github.io/blob/source/templates/translations.html).


Tasks when the whole documentation is translated:

- [ ] Create a 2.0.x branch, set it as default version on ReadtheDocs.
- [ ] Pick all the issues labeled with `feature`, update them into main branch.
- [ ] Switch the docs into http://flask.palletsprojects.com/.