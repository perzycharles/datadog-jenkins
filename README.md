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

![System  Jenkins  2023-11-21 at 1 19 37 PM](https://github.com/perzycharles/datadog-jenkins/assets/37419121/e75c9367-4ca6-43f3-bab3-9a842cd6d87a)

## step 5: build pipeline datadog-pipeline several times
![datadog-pipeline  Jenkins  2023-11-21 at 1 29 43 PM](https://github.com/perzycharles/datadog-jenkins/assets/37419121/80e6ee83-3f24-4ddf-8927-7ba9150b4dfa)

## step 6: verify metrics, logs, infrastructure list, CI in your sandbox
