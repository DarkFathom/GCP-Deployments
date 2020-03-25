# GCP-Deployments

Deployment for app server vm

Edit /home/deployments/startup-script.sh to update installs.

cd into /home/deployments/jinja

Run following command where DEPLOYMENT NAME = the name of the deployment and will append the vm name.
Example: "...create deployment..." will result in
    deployment name:    deployment1
    vm name:            app-svr-deployment1

run:
"gcloud deployment-manager deployments create [DEPLOYMENT NAME] --config config.yaml"
