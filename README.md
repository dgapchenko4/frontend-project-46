### Hexlet tests and linter status:
[![Actions Status](https://github.com/dgapchenko4/frontend-project-46/workflows/hexlet-check/badge.svg)](https://github.com/dgapchenko4/frontend-project-46/actions) [![Maintainability](https://api.codeclimate.com/v1/badges/c4d2c4250f0bfa36a786/maintainability)](https://codeclimate.com/github/dgapchenko4/frontend-project-46/maintainability) [![Test Coverage](https://api.codeclimate.com/v1/badges/c4d2c4250f0bfa36a786/test_coverage)](https://codeclimate.com/github/dgapchenko4/frontend-project-46/test_coverage) [![Testing](https://github.com/dgapchenko4/frontend-project-46/actions/workflows/node-check.yml/badge.svg)](https://github.com/dgapchenko4/frontend-project-46/actions/workflows/node-check.yml)

## Description:
**Generator of difference** is the CLI program that generate difference between two files. Supporting formats: JSON, YML, YAML.
## Install
```
git clone git@github.com:dgapchenko4/frontend-project-46.git
cd frontend-project-46
make install
```
## Setup genDiff

```
chmod +x bin/gendiff.js

make publish

sudo npm link
```

## Run tests

```make test```


## Run lint

```make lint```

## How to use:
```
gendiff [options] <filepath1> <filepath2>
```
For example:
```
gendiff file1.json file2.json
```

## genDiff Help

```
gendiff -h
```

gendiff file1.json file2.json
![Снимок экрана от 2024-06-17 19-38-54]
<a href="https://asciinema.org/a/VG16xIhX9PgDoc91L5GXddZfE" target="_blank"><img src="https://asciinema.org/a/VG16xIhX9PgDoc91L5GXddZfE.svg" /></a>

```
gendiff file1.yml file2.yml
```
![Снимок экрана от 2024-06-17 19-44-35](https://asciinema.org/a/HzxHuJLKwmLz399e9c2jjLx0v)
<a href="https://asciinema.org/a/HzxHuJLKwmLz399e9c2jjLx0v" target="_blank"><img src="https://asciinema.org/a/HzxHuJLKwmLz399e9c2jjLx0v.svg" /></a>

```
gendiff --format plain file1.json file2.json
```
![Снимок экрана от 2024-06-17 19-48-48](https://asciinema.org/a/NUpYFmB9KxkR26eqKo15JGtLh)

```
gendiff -f json file1.json file2.json
```
![изображение](https://asciinema.org/a/M0EFJny6u1K6IgbSMotlyulZ4)



