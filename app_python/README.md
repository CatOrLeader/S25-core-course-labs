# PyWatch

How many times you check the time on your laptop and think something like 'O-oh, this kind of boring...'?
Exactly, a lot of times! And now, the time has come... Literally and theoretically. Welcome to the
new era of watches: python web-application watch!

* You can start the application locally, by simply adding the `.env` file like this:

```.env
### DEVELOPMENT PROPERTIES ###
FLASK_DEBUG=False

### WEB APPLICATION SETTINGS ###
PORT=5000
```

* And run the command in your CLI (from the `app_python` folder)

```bash
docker build -t python-watch .
docker run -d -p 5000:5000 --name watch python-watch
```

* if you want to stop the application, just type

```bash
docker stop watch
```

That's all! By this, you receive the _great_ watch on your laptop, not the boring ones you have
in the bottom-right corner.

![img.png](res/cowboy.png)