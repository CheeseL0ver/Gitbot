# Gitbot
#### A Python based alert bot for source pushes.

## Overview
This bot will create a message in the specified chats to alert other team memebers when a "push" has been proformed on a specified Github respository.

## Deploy
[![Deploy](https://www.herokucdn.com/deploy/button.svg)](https://heroku.com/deploy)

## Run
#### Locally
After cloning the repo simply run:
```
$ heroku local web
```
This will start the Heroku app locally on port 5000.

#### Docker (Recommended)
If you want to keep the app contained in a Docker image use the following process:

```
$ ./run.sh
```
This will create the image and place you into an interactive shell of the runnin container. Next run:
```
$ heroku local web
```
**NOTE**
> Inside of the container the application will be use port **5000**, however to the actual machine the image is running on the port being used is port **5001**.
