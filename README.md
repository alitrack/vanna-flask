# vanna-flask
Web server for chatting with your database



https://github.com/vanna-ai/vanna-flask/assets/7146154/5794c523-0c99-4a53-a558-509fa72885b9



# Setup

## Set your environment variables
copy `.env.example` to `.env` and set your environment variables.
and here is an example of `.env`
```
VANNA_MODEL=chinook
VANNA_API_KEY=YOUR_VANNA_API_KEY
VANNA_SQLITE_URL=https://vanna.ai/Chinook.sqlite
GOOGLE_FONTS_CND=https://www.googlefonts.cn/
PORT=5000
HOST=127.0.0.1
DEBUG=False
```

## Install dependencies
```
pip install -r requirements.txt
```

## Run the server
```
python app.py
```

