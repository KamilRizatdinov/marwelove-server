<p>
<img src="./images/logo.png" width="600px" alt="mar-we-love-logo"/>&nbsp;
</p>

[![Maintenance](https://img.shields.io/maintenance/yes/2021?style=for-the-badge)]()
[![GitHub contributors](https://img.shields.io/github/contributors/KamilRizatdinov/marwelove-server?style=for-the-badge)](https://github.com/KamilRizatdinov/marwelove-server/graphs/contributors)
[![GitHub license](https://img.shields.io/badge/license-mit-orange.svg?style=for-the-badge)](https://github.com/KamilRizatdinov/marwelove-server/blob/master/LICENSE)

# MarweLove-server

## Overview

This is backend web app written using [Python](https://www.python.org/) handling api calls to [MarvelAPI](https://developer.marvel.com).

## Prerequisites

1. Create virtualenv:
   ```bash
   python -m virtualenv venv
   ```
2. Activate it:
   ```bash
   source venv/bin/activate
   ```
3. Install dependencies:
   ```bash
   pip install -r requirements.txt
   ```
4. Create `.env` file with keys:
   ```
   PUBLIC_KEY="<public key for MarvelApi>"
   PRIVATE_KEY="<private key for MarvelApi>"
   ```

## How to run

```bash
cd marvelowe-server
uvicorn main:app  --reload --host 0.0.0.0 --port 8000
```

## Contacts

If you have any questions or ideas, write us in [Telegram](https://telegram.org):

- [@MatInd0](https://t.me/MatInd0/)
- [@rufusnufus](https://t.me/rufusnufus/)
