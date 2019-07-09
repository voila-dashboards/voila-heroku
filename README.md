# Voila application deployed on Heroku

This is an example of Voila deployed on Heroku, try it out: https://voila-bqplot.herokuapp.com/

## How to deploy your own?

1. First, create an Heroku account (free account is fine for testing)

2. Install Heroku on your machine: https://devcenter.heroku.com/articles/getting-started-with-python#set-up

2. Clone this repository, or create your own repository that follows the same structure:

```bash
git clone https://github.com/martinRenou/voila_heroku
cd voila_heroku
```

3. Create your Notebook and put it in the `notebooks` directory

5. Add the dependencies needed for running your Notebook in the `requirements.txt` file

6. Edit the `Procfile` file by replacing `notebooks/bqplot.ipynb` by the path to your awesome Notebook

7. Commit everything

```bash
git commit -m "My awesome app on Heroku!"
```

8. Create the Heroku app:

```bash
heroku create
```

9. Now deploy your code:

```bash
git push heroku master
```

10. That's it! Easy right? Now you can open your app using:

```bash

heroku open
```

Note that this last command is only a handy shortcut for opening your browser following the right url, you can also do that manually.
