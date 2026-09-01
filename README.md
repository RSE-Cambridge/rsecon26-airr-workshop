# LLMs on Zenith

During this workshop, we will:

- Get an API Key from your available resources on the AIRR Portal  
- Use the API Key to explore a number of available endpoints
- Play around with some LLMs and image models

## Clone this repository

```bash
git clone ...
cd ...
```

This repository uses UV to manage environments, so if you don't have it:

```bash
curl -LsSf https://astral.sh/uv/install.sh | sh
```

More details of installation can be found on the Installing UV page.

Syncing will automatically create a virtual environment and install the packages required for this workshop

```bash
uv sync
```

## Getting your API Key

You should have already received an invite to sign up to our online Waldur portal. We have automatically created a resource for you. 

```bash
cp .env.example .env
```

and just put your API Key in here. We use `dotenv` to load the `base_url` and `api_key`.

## Running the workshop

There are two notebooks available here to play with.

- `example-calls.ipynb` is an intrdduction to some of the basic calls available.  
- `llm-judging.ipynb` sets up an example where we use LLMs to judge the correctness of medical statements.