# Simulator4AuthSvc
Simulate token expiration for a oAuth secured Service

# deployment (Azure)
to run this project in your own, public, Azure instance follow the guide [Bereitstellen von einem lokalen Git mit Kudu-Builds](https://docs.microsoft.com/de-de/azure/app-service/app-service-deploy-local-git#deploy-from-local-git-with-kudu-builds).
after setup, a simple `git push azure master` is sufficient to update your instance.

# changes
ship static files, first file is ./static/index.html which contains service description