## Minikube

Mount local driver to the Minikube

```
minikube mount c:\User\<bla>\minikube_shared:/mounted_drive
```

Expose service from minikube

```
# opens default browser
minikube expose <SERVICE_NAME>

# get only url
minikube service <SERVICE_NAME> --url
```

## Kubectl