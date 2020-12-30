# Welcome to Scoutify!

Scoutify is a simple Python library for [Spotify Web API](https://developer.spotify.com/documentation/web-api/).

Please make an app from Spotify developer's page first before using this library
and keep in mind that Spotify requires authentication before using their API.

## Installation

Install or upgrade scoutify with:
```bash
pip install scoutify --upgrade
```

## Getting Started
Usage example

```python
from scoutify import Scoutify
sp = Scoutify(
    client_id='YOUR_CLIENT_ID',
    client_secret='YOUR_CLIENT_SECRET',
    redirect_url='your_callback_url'
)
sp.set_access_token('OBTAINED ACCESS TOKEN')
result = sp.search(search_type="artist", q="blackpink")
print(result)
```


