# Contribution Guidelines

This project has a [Contributor Code of Conduct](code-of-conduct.md).
By taking part in this project you agree to follow it.

This is a curated list. An entry is accepted when it helps people test Python code.
An entry is not accepted only because it exists or because its author wants to promote it.

## What will be accepted

- **Python testing tools.** Libraries, pytest plugins, and command-line tools that are written in Python,
  or that are made mainly to test Python code.
- **Open source software.** The project uses an [OSI-approved license](https://opensource.org/licenses)
  (for example MIT, BSD, Apache-2.0, or GPL), and you can install it without an account or an API key.
- **Mature, maintained projects.** The project has documentation and a release, preferably on PyPI.
  It has recent activity and people other than its author use it.
- **Good resources.** Articles, books, talks, and tutorials that teach something useful about
  testing Python code.

## What will not be accepted

- **Commercial SaaS and hosted platforms.** This includes paid or "freemium" services,
  and SDKs, plugins, or clients whose main purpose is to connect to such a service.
  An open-core package is not accepted when its useful features need a paid service.
- **Projects that are not about Python.** For example, Node.js packages,
  or tools for other languages that also have Python support.
- **Projects that are too new or not ready.** For example, projects without users, without
  documentation, without a release, or that are not maintained.
- **Projects without a license** or with a license that is not open source.
- **Promotional content.** For example, marketing blog posts, product pages,
  and pull requests made mainly to promote a product.
- **Duplicates.** Projects that are already in the list, or that do the same thing as an
  entry in the list and do not do it better.

If a project that is in the list is deleted, archived, or no longer maintained, it will be removed.

## How to submit

1. Add **one** entry per pull request. If you want to add more entries, open more pull requests.
2. Put the entry in the correct section, in alphabetical order.
3. Use this format:

   ```markdown
   - [name](https://link-to-the-project) - A short description that ends with a period.
   ```

4. Link to the source repository or to the official documentation, not to a landing page.
5. Write a description that is factual. Do not use marketing language such as
   "blazing fast", "revolutionary", or "AI-powered".
6. Complete the pull request template. Give the link to the project, the license, and the section.
   If you are the author or maintainer of the project, say so.
7. Make sure that the checks pass (dead links, Markdown lint, and spelling).
   You can run them on your computer with [pre-commit](https://pre-commit.com/): `pre-commit run --all-files`.

Pull requests that do not follow these guidelines will be closed without comment.

## Updating your pull request

A maintainer can ask you to change your pull request before it is merged.
Push more commits to the same branch. Do not open a new pull request.
