# GCP-Deployments

Deployment for app server vm

Edit startup-script.sh to update installs.


Running following command where [DEPLOYMENT NAME] = the name of the deployment and will append the vm name.

cd into /jinja

run:
"gcloud deployment-manager deployments create [DEPLOYMENT NAME] --config config.yaml"


Example: "...create my-deployment1 --config..." will result in

deployment name:    my-deployment1

vm name:            app-svr-my-deployment1
