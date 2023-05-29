# Chatbot

<div align="center">
  <img src="https://github.com/akash-singh8/Chatbot/assets/85285176/1f66aa19-0a1f-4d22-864e-74b12e2adcdb" alt="Chatbot" width="280px">
</div>

<br>

## Initial Setup:

1. Clone repo

```bash
$ git clone https://github.com/akash-singh8/Chatbot.git
$ cd Chatbot
```

2. Install dependencies

```bash
$ pip install Flask torch torchvision nltk
```

3. Install nltk package

```python
$ python
>>> import nltk
>>> nltk.download('punkt')
```

<br>

Modify `intents.json` with different intents and responses for your Chatbot

<br>

Run the following command (will dump the data.pth file)
```
$ python train.py
```

To test it in the console, run
```
$ python chat.py
```


<br>

## Run Locally

1. Start the Flask server

```bash
$ cd backend
$ python app.py
```

(make sure it starts at localhost port 5000 - `http://127.0.0.1:5000`)

2. Simply open `bot.html` or run it using the live server.

<br>

## Credits:

<p>Followed this video tutorial to build the chatbot </p>
<a href="https://youtu.be/a37BL0stIuM"> <img src="https://img.youtube.com/vi/a37BL0stIuM/hqdefault.jpg" alt="thumbnail"> </a>
<p>This repo was used for the starter code: https://github.com/patrickloeber/chatbot-deployment </p>
<p>This repo was used for the frontend code: https://github.com/hitchcliff/front-end-chatjs </p>
