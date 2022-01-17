# Smart Contracts Lottery

Lottery using Smart Contracts

Main functionality:

- Users can enter lottery with ETH/USD
- An admin will choose when the lottery is over
- The lottery select a random winner

- Python 3
- NodeJS ^12.0
- Infura project id
- Ether Scan Token

# Env Setup

Create python env

```bash
$ python3 -m venv .env-brownie
```

Install Ganache CLI

```bash
$ npm i -g ganache-cli@6.12.2
```

Install python dependencies

```bash
$ pip install -r requirements.dev.txt
$ pip install -r requirements.txt
```

Create new account

> **NOTE:** When asked for your private key, make sure to add the prefix `0x`, for example: `0x<private-key>`.

```bash
brownie accounts new lottery-account
```

Open `.vscode/settings.json` and change `<brownie-folder-path>` with the correct absolute path to the `.brownie` folder in your machine.

# Deployment

**TODO**
