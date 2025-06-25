# Azure_app_dep_basic
Basic_azure_ml_deployment

Notes:
Startup - Command on Azure - gunicorn --bind 0.0.0.0:80 -w 1 -k uvicorn.workers.UvicornWorker main:app

