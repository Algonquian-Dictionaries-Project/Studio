# Command for launching the web API server for ReadAlongs-Studio on Heroku
web: gunicorn -w 8 -k uvicorn.workers.UvicornWorker readalongs.web_api:web_api_app
