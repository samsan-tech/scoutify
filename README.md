# Scoutify

|Downloads| |Downloads_month| |PyPI version| |GitHub contributors|

.. |Downloads| image:: https://pepy.tech/badge/scoutify
   :target: https://pepy.tech/project/scoutify
.. |Downloads_month| image:: https://pepy.tech/badge/scoutify/month
   :target: https://pepy.tech/project/scoutify/month
.. |PyPI version| image:: https://badge.fury.io/py/scoutify.svg
   :target: https://badge.fury.io/py/scoutify
.. |GitHub contributors| image:: https://img.shields.io/github/contributors/samsan-tech/scoutify.svg
   :target: https://github.com/samsan-tech/scoutify/graphs/contributors



## Installation

```bash
pip install spotipy
```

or upgrade

```bash
pip install spotipy --upgrade
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
