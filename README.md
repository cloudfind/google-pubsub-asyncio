# google-pubsub-asyncio

An example program which uses the asynchronous Google Pub/Sub client with Python's `asyncio` capability.

Publishes messages to a Pub/Sub topic, subscribes to it and prints the messages.

## Usage

Create a virtualenv and install the dependencies:

```sh
virtualenv -p python3 venv
. venv/bin/activate
pip install -r requirements.txt
```

Now set some environment variables:

```sh
export GOOGLE_CLOUD_PROJECT=
export TOPIC=
```

Now run the app

```sh
python app.py
```
