[![Forks][forks-shield]][forks-url]
[![Stargazers][stars-shield]][stars-url]
[![Issues][issues-shield]][issues-url]
[![Total Downloads](https://static.pepy.tech/badge/OMOIKA)](https://pepy.tech/project/OMOIKA)
[![Downloads](https://static.pepy.tech/badge/OMOIKA/week)](https://pepy.tech/project/OMOIKA)

<p>
  <a href="https://github.com/OMOIKA/OMOIKA">
    <img src="./watermark.svg" height="360px" alt="Logo">
  </a>

> _I have no data yet. It is a capital mistake to theorize before one has data. Insensibly
> one begins to twist facts to suit theories, instead of theories to suit facts._

---

# OMOIKA Releases & Community Registry

This repository hosts public OMOIKA releases plus the community plugin and theme registries.
It does not contain the OMOIKA application source code.

## Community

OMOIKA is currently developed by an individual aiming to grow into a small focused team.  
There is no open contribution process as of now however you may contribute plugins to this repo or in time, themes too.

- **Website**: https://omoika.institute
- **Email**: omoika-institute@proton.me
- **Discord**: [Join our community](https://discord.gg/b8vW4J4skv) for discussions and support.
- **PyPi**: [Install the package](https://pypi.org/project/OMOIKA/) to get started.
- **Public plugin registry**: _You are here._

## Submissions

1. Fork this repo and open a PR.
2. Append your entry to the end of the relevant JSON list.
3. Keep entries in the order submitted; do not reorder existing entries.

### Community Plugins format

Required fields:

- `id`: unique, lowercase slug (letters, numbers, dashes)
- `name`: display name
- `author`: author or org name
- `description`: short one-line description
- `repo`: GitHub `owner/repo`

Optional fields:

- `license`
- `tags`
- `min_app_version`
- `homepage`
<!--

### Community Themes format

Required fields:

- `name`
- `author`
- `repo`
- `screenshot`: path to screenshot in the theme repo
- `modes`: `['dark']`, `['light']`, or `['dark','light']`

Optional fields:

- `version`
- `tags`
- `publish`: boolean for themes compatible with OMOIKA Publish (if/when supported) -->

## Policies

All submissions must conform with our [developer policies](./DEVELOPER_POLICIES.md). To summarize:

- You must have the rights to distribute the plugin or theme.
- No malicious, deceptive, or privacy-invasive behavior.
- Clearly disclose network calls and data collection.
- For OMOIKA plugin issues, use: https://github.com/omoika-institute/omoika/issues

[forks-shield]: https://img.shields.io/github/forks/omoika-institute/omoika.svg?style=for-the-badge
[forks-url]: https://github.com/omoika-institute/omoika/network/members
[stars-shield]: https://img.shields.io/github/stars/omoika-institute/OMOIKA.svg?style=for-the-badge
[stars-url]: https://github.com/omoika-institute/omoika/stargazers
[issues-shield]: https://img.shields.io/github/issues/omoika-institute/OMOIKA.svg?style=for-the-badge
[issues-url]: https://github.com/omoika-institute/omoika/issues
