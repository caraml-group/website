# CaRAML Website

This repository houses the content for the CaRAML group website.
All content is primarily in Markdown and converted into webpages via Hugo.
The website is deployed publicly via GitHub pages (see [`caraml-group.github.io`](https://github.com/caraml-group/caraml-group.github.io)).

Quick Links:
- **Template**: [Link](https://wowchemy.com/hugo-themes/)
- **Documentation**: [Link](https://wowchemy.com/docs/)

### Adding a new profile or creating content

If you want to add a new **profile** or **blogpost/other content**, it may be easiest to follow this workflow: 
- Fork this repository.
- Write in markdown, following the folder structure (place things in the appropriate folders under `content/authors/` or `content/post/`).
  - For e.g., if you want to create a new profile for 'John Doe', you will create a new folder `content/authors/john-doe` and create a file titled `_index.md` under it. You can then copy the contents from [here](https://github.com/caraml-group/website/blob/main/content/authors/chaitanya-joshi/_index.md) into the newly created `_index.md` and update the contents to those of John Doe. Optionally, add a profile picture titled `featured.jpg` or `featured.png` under the same folder.
- Create a Pull Request in the original repository for review (an administrator will help you deploy).

This way, you will not need to install anything.


### Local development and public deployment

For local development, please follow the instructions for the [Academic theme](https://wowchemy.com/docs/getting-started/install-hugo-extended/).

For deploying to publicly to .github.io, follow the instructions [here](https://wowchemy.com/docs/hugo-tutorials/deployment/#github-pages).

You may need to ensure that you are installing the exact versions of Hugo and the Academic theme when deploying to .github.io:
- Hugo: 0.93.1
- Theme: 5.0.0

### Contribution Guidelines

- Follow the [GitHub Flow](https://guides.github.com/introduction/flow/).
    - Branch/Fork → Commit → Pull Request [→ Merge]
- Commit messages should be in title case and descriptive.
- Maintain consistent coding style.
- Comment out or delete debug statements when committing.
- Make sure you haven't broken anything that was previously working.
