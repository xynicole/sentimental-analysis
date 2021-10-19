# sentimental-analysis

## Docker Hub images
1. https://hub.docker.com/r/xynicole/sentiment-analysis-frontend
2. https://hub.docker.com/r/xynicole/sentiment-analysis-logic
3. https://hub.docker.com/r/xynicole/sentiment-analysis-web-app


## Steps
1. clone the repo https://github.com/rinormaloku/k8s-mastery
2. build docker images for frontend, logic, and web-app and push to docker hub
3. go to GCP, and create the project
4. click hamburger button and go to Container Regisrty 
5. open the cloud shell and pull, tag and push all images from docker hub
6. click hamburger button and go to Kubernets Engine, Clusters
7. create a cluster with GKE standard 
8. click cluster and click deploy, deploy containers with existing images (step 5)
9. go to workload, and click action, expose to create a load balance for all
10. go to service, find the external IP for web app
11. go to forntend,find app.js, change the IP to web app external IP, and build, push image again
12. change image name in YAML file
13. 
