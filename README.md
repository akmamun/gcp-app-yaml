## Google Cloud Platform configure your App Engine app's settings in the app.yaml file
### Create a app.yaml file to root directory
### Node Js Application 
- [Node](node/app.yaml) 

### Python Application 
- [Python](python/app.yaml) 

### Now Initialize GCP
Initialize your gcp app
```sh
gcloud init
```
### Finally Deploy to GCP
```sh
gcloud app deploy
```

#### Note: Each service must have an app.yaml file in its root directory [learn more](https://cloud.google.com/appengine/docs/standard/python/configuration-files)