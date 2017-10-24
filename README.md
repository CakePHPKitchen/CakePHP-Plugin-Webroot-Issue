# CakePHP Webroot Plugin Issue

In case you want to use a custom app dir name (e.g. `/myapp/`):

```bash
git clone https://github.com/jeffreyroberts/CakePHP-Plugin-Webroot-Issue.git
```

You can now either use your machine's webserver to view the default home page, or start
up the built-in webserver with:

```bash
bin/cake server -p 8765
```

Then visit `http://localhost:8765/bingo.txt` to see the error page.
