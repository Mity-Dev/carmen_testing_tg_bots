# carmen_testing_tg_bots

## Python setup

### Install Python and Pip

### Install Virtual Environment (Optional but Recommended)

Install virtualenv if you necessary

```bash
pip install virtualenv
```

```bash
virtualenv venv
```

```bash
source venv/bin/activate
```

### Install Flask

```bash
pip install Flask
```

### Run the Flask App

```bash
export FLASK_APP=app
flask run
```

## Get local web server running on port 5000 to the internet

### Install ngrok

```bash
 brew install ngrok/ngrok/ngrok
```

### Add ngrok to PATH

```bash
export PATH=$PATH:/path/to/ngrok/directory
```

### Get links

```bash
ngrok http 5000
```

## Webhook

### Set a Webhook

You can do it by running the link in your browser

```bash
https://api.telegram.org/bot<BOT_TOKEN>/setWebhook?url=<HTTPS_URL_FROM_NGROK>
```
