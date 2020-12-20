# Scoutify
<!-- ALL-CONTRIBUTORS-BADGE:START - Do not remove or modify this section -->
[![All Contributors](https://img.shields.io/badge/all_contributors-1-orange.svg?style=flat-square)](#contributors-)
<!-- ALL-CONTRIBUTORS-BADGE:END -->

![PyPI](https://img.shields.io/pypi/v/scoutify)
![PyPI - Downloads](https://img.shields.io/pypi/dm/scoutify)
![GitHub](https://img.shields.io/github/license/samsan-tech/scoutify)



## Installation

```bash
pip install scoutify
```

or upgrade

```bash
pip install scoutify --upgrade
```

## Quick Start

To get started, first create an app on https://developers.spotify.com/ to get you ID and SECRET.

### Usage example

```python
from scoutify import Scoutify
sp = Scoutify(client_id="YOUR_CLIENT_ID",
              client_secret="YOUR_CLIENT_SECRET",
              redirect_url="YOUR_REDIRECT_URI")
sp.set_access_token("YOUR_ACCESS_TOKEN")
result = sp.search(search_type="artist", q="blackpink")
print(result)
```


If you have suggestions, bugs or other issues specific to this library,
file them [here](https://github.com/samsan-tech/scoutify/issues).
Or just send a pull request.

## Contributors ✨

Thanks goes to these wonderful people ([emoji key](https://allcontributors.org/docs/en/emoji-key)):

<!-- ALL-CONTRIBUTORS-LIST:START - Do not remove or modify this section -->
<!-- prettier-ignore-start -->
<!-- markdownlint-disable -->
<table>
  <tr>
    <td align="center"><a href="https://github.com/fijar-lazuardy"><img src="https://avatars0.githubusercontent.com/u/32705957?v=4" width="100px;" alt=""/><br /><sub><b>Fijar Lazuardy</b></sub></a><br /><a href="#infra-fijar-lazuardy" title="Infrastructure (Hosting, Build-Tools, etc)">🚇</a> <a href="https://github.com/samsan-tech/scoutify/commits?author=fijar-lazuardy" title="Code">💻</a></td>
  </tr>
</table>

<!-- markdownlint-enable -->
<!-- prettier-ignore-end -->
<!-- ALL-CONTRIBUTORS-LIST:END -->

This project follows the [all-contributors](https://github.com/all-contributors/all-contributors) specification. Contributions of any kind welcome!