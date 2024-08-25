# Kodecloud
Kodecloud
To create a deployment named httpd that uses the httpd:latest image, you can use the following kubectl command:<br/>
```kubectl create deployment httpd --image=httpd:latest```
**Execute a rolling update for this application, integrating the nginx:1.19 image. The deployment is named nginx-deployment.**<br/>

```kubectl set image deployment nginx-deployment nginx-container=nginx:1.19```