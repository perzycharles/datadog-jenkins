# Datadog jenkins monitoring
This is a docker environment for jenkins monitoring

https://docs.datadoghq.com/integrations/jenkins/#plugin-user-interface

## Step 1: build images
```
$ docker-compose build
```
## step 2: spin up containers
```
$ docker-compose up -d
```

## step 3: log in to jenkins management console
http://localhost:8080/
```
username: admin
password: admin
```

## step 4: set the correct API Key and Datadog endpoints

![System  Jenkins  2023-11-21 at 1 19 37 PM](https://github.com/perzycharles/datadog-jenkins/assets/37419121/37e69698-86b6-4f82-91d7-558f1e6a4347)

## step 5: build pipeline datadog-pipeline several times
![datadog-pipeline  Jenkins  2023-11-21 at 1 29 43 PM](https://github.com/perzycharles/datadog-jenkins/assets/37419121/f041e169-16cd-49c3-8676-55556c0cd8f1)

## step 6: verify metrics, logs, infrastructure list, CI in your sandbox
