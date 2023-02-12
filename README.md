# helm-app

helm create .

To create the chart structure

Edit the values.yaml file to specify any configurable settings for your application.

Create a templates directory and add a deployment.yaml file to define the Kubernetes deployment for your application.

Create a service.yaml file in the templates directory to define the Kubernetes service for your application:
package your Helm chart and deploy it to your Kubernetes cluster:
$ helm package . 
$ helm install helm_app ./helm_app-0.1.0.tgz

