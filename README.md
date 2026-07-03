[![Forks][forks-shield]][forks-url]
[![Stargazers][stars-shield]][stars-url]
[![Issues][issues-shield]][issues-url]
[![Total Downloads](https://static.pepy.tech/badge/OMOIKA)](https://pepy.tech/project/OMOIKA)
[![Downloads](https://static.pepy.tech/badge/OMOIKA/week)](https://pepy.tech/project/OMOIKA)
![hits](https://komarev.com/ghpvc/?username=omoika-institute-omoika007-framework&label=hits)

<p>
  <a href="https://github.com/OMOIKA/OMOIKA">
    <img src="./watermark.svg" height="360px" alt="Logo">
  </a>

> _I have no data yet. It is a capital mistake to theorize before one has data. Insensibly
> one begins to twist facts to suit theories, instead of theories to suit facts._

<details>   <summary>📼 <i>Click to watch the <b>OMOIKA</b> demo...</i></summary>

[demo.mp4](https://github.com/user-attachments/assets/30659b76-a558-4b92-a89a-b51c11d7137e)

</details>

---

<details>   <summary><i>Click to view screenshots of <b>OMOIKA</b>...</i></summary>

<img width="1919" height="1080" alt="image" src="https://github.com/user-attachments/assets/3c9ddb00-18e2-4457-b34c-55e7420bf04a" />
<img width="1919" height="1080" alt="image" src="https://github.com/user-attachments/assets/916cbdff-6b27-487e-b497-dfea921aef7a" />
<img width="1919" height="1080" alt="image" src="https://github.com/user-attachments/assets/194839be-30a7-4a88-b12d-6ba8ee9a1dac" />
<img width="1919" height="1080" alt="image" src="https://github.com/user-attachments/assets/41ceb8e1-eafa-4471-9b0d-1bd4124f1993" />
<img width="1918" height="1078" alt="image" src="https://github.com/user-attachments/assets/a9f0e3d4-327e-4ad1-8ed9-129dfbfe998f" />

  </details>

---

# OMOIKA Releases & Community Registry

This repository hosts public OMOIKA releases plus the community plugin and theme registries.
It does not contain the OMOIKA application source code.

Welcome to the **OMOIKA** project where you can connect, combine, and get insight from unstructured and public data as results that can be explored step-by-step. An easy-to-use plugin system allows any developer to quickly integrate new data sources so you can focus on discovering, interacting, and visualizing what's important to you.

---

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


## Initial release **v0.42.0** is featuring:

- Bundled Python plugin system
- Graph workspace
- i18n/Multiple languages
- Community Marketplace
- Plugin configuration settings
- Graph workspace history timeline

