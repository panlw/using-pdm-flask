# Using PDM + Flask

## pdm config

> https://pdm.fming.dev/

```shell
pdm config pypi.url https://pypi.tuna.tsinghua.edu.cn/simple
pdm config cache_dir ~/opt/pdm/cache
pdm config venv.location ~/opt/pdm/venvs
pdm config global_project.path ~/opt/pdm/global
pdm config install.cache on```
```

## pdm project

> - https://code.visualstudio.com/docs/python/tutorial-flask
> - https://flask.palletsprojects.com/

```shell
pdm init

# python file formatter
pdm add autopep8 

# using .env .flaskenv files
pdm add python-dotenv

# using flask
pdm add flask 

# export requirements
pdm export -o requirements.txt
```

## .env files

```.flashenv
FLASK_DEBUG=1
```

```.env
FOO=bar
```
