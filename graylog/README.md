# Graylog
<br>
I've provided some basic files to make your life easier on initial deployment, feel free to change/delete/modify them in any way that is useful to you, but DO NOT skip the next step.

## Pre-Deployment

Graylog container runs as the graylog user with UUID 1100, for this files to be recognized once the container is deployed you need to modify file ownership before starting the container.
```
sudo chown 1100:1100 *
```
If you have any other files you would like pass onto your Graylog instance, they would also have to go through the same process for Graylog to be able to use them.
