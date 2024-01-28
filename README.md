## Django 5.0.1 example for Coolify deployment.

# The following steps

1. Setup your GitHub account in Coolify
2. Create a new project
3. Choose the environments test or production
4. Add a new resource from choosen public or private github repository
- in the newly created app, make sure to choose Nixpcks for Build Pack
- add your domain, and don't forget to set in django_coolify_example/settings.py as well in allowed_host array.

> [!NOTE]
> In case you receive Bad Gateway message instead of your django page, you have to increase the default 30 timeout to 3000.
> /virtual/venv/lib/python3.9/site-packages/gunicorn/config.py