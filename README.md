# ApplyAI-G2-PopularGames
Project of applyAI group 2 (2023): The correlation between the statistics of a published game (user played, ratings, etc.) to the popularity of the game.

*I'm setting this project up with ubuntu, so if you are using Windows and things doesn't run, consider using WSL. Mac and Linux should be fine.*

## Getting started
This projects uses poetry to manage python packages and virtualEnv. To get started, [install poetry]("https://python-poetry.org/docs/"). I used in-project virtualenv for easier removing of the project with the command:

```bash
$ poetry config virtualenvs.in-project true
```
<br/>
Before running, install dependencies (check [here](https://python-poetry.org/docs/basic-usage/) for more docs)

```
$ poetry install
```

And to run, do
```
$ poetry run python3 <your script name>.py
```