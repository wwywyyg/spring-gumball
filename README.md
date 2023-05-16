# spring-gumball
CMPE-172 Lab 10
# spring-gumball
CMPE-172 Lab 10

## CI Workflow 
first i install the gradle by using SDK man and check is the gradle is working
![install_gradle](https://github.com/wwywyyg/spring-gumball/blob/main/images/sdk_gradle.png)

After that i setup the gradle workflow.
![add_workflow](https://github.com/wwywyyg/spring-gumball/blob/main/images/add_gradle_workflow.png)

Then i upload all the file in to github spring-gumball repositories.
change some content in deployment.yaml file and commit the change.
These images is ation about the commit changes for lab 10.

![update_commit_1](https://github.com/wwywyyg/spring-gumball/blob/main/images/CI_Workflow.png)
![update_commit_2](https://github.com/wwywyyg/spring-gumball/blob/main/images/CI_Workflow_2.png)
![update_commit_3](https://github.com/wwywyyg/spring-gumball/blob/main/images/CI_Workflow_3.png)
![update_commit_4](https://github.com/wwywyyg/spring-gumball/blob/main/images/CI_Workflow_4.png)

![update_commit_1](https://github.com/wwywyyg/spring-gumball/blob/main/images/update_deployment.png)
![update_commit_2](https://github.com/wwywyyg/spring-gumball/blob/main/images/update_deployment_2.png)
![update_commit_3](https://github.com/wwywyyg/spring-gumball/blob/main/images/update_deployment_3.png)




## CD Workflow (Part 2)
first i create cluster and name with cmpe172 and connect it.
![create_cmpe172_cl](https://github.com/wwywyyg/spring-gumball/blob/main/images/GKE_services.png)
![create_cmpe172](https://github.com/wwywyyg/spring-gumball/blob/main/images/connect_cmpe172.png)

then i enable project API
![api_enable](https://github.com/wwywyyg/spring-gumball/blob/main/images/enable_api.png)
![api_enable_2](https://github.com/wwywyyg/spring-gumball/blob/main/images/enable_api.png)

get project id
![project_id](https://github.com/wwywyyg/spring-gumball/blob/main/images/project_id.png)

create service account spring-gumball, add service key and save the json file to local.
![service_acc](https://github.com/wwywyyg/spring-gumball/blob/main/images/service_account.png)
![service_acc](https://github.com/wwywyyg/spring-gumball/blob/main/images/server_account_2.png)

grant access services account spring-gumball, and add Kubernetes Engine Developer , Storage Admin role.
![grant_access](https://github.com/wwywyyg/spring-gumball/blob/main/images/grant_acess.png)
![grant_access_2](https://github.com/wwywyyg/spring-gumball/blob/main/images/grant_acess_2.png)
![grant_acc_3](https://github.com/wwywyyg/spring-gumball/blob/main/images/grant_acess_3.png)

create Github secrets
![git_sec](https://github.com/wwywyyg/spring-gumball/blob/main/images/git_secret.png)

create GKE workflow

![GKE_Workflow](https://github.com/wwywyyg/spring-gumball/blob/main/images/gke_workflow.png)

create a test release

![git_release](https://github.com/wwywyyg/spring-gumball/blob/main/images/git_release.png)
![git_release_2](https://github.com/wwywyyg/spring-gumball/blob/main/images/git_release_2.png)
![git_release_3](https://github.com/wwywyyg/spring-gumball/blob/main/images/git_release_3.png)
![git_release_4](https://github.com/wwywyyg/spring-gumball/blob/main/images/git_release_4.png)
![git_release_5](https://github.com/wwywyyg/spring-gumball/blob/main/images/git_release_5.png)

create sping-gumball-lb in ingress
![gumball_lb](https://github.com/wwywyyg/spring-gumball/blob/main/images/ingress.png)
![gumball_lb2](https://github.com/wwywyyg/spring-gumball/blob/main/images/ingress_2.png)

test gumbal page 
![gumball_web](https://github.com/wwywyyg/spring-gumball/blob/main/images/result.png)
![gumball_web](https://github.com/wwywyyg/spring-gumball/blob/main/images/result_2_withoutIP.png)
