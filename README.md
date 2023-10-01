# capstone1newdevops
1. forked from https://github.com/rushtoakshay/DevOpsProfessional.git - this repo has only html and image and all other codes are coded by me.
2. First the website is deployed via docker container in  port number 85.
3. If docker deployment succeeds then it will trigger the deployment of that website via K8S in NodePort at 31010.
4. devops-caps-new-pipe1 is for docker deployment.
5. devops-caps-new-pipe2 is for K8S deployment.
6. GIT PULL BY JENKINS DEPLOY VIA DOCKER IF SUCCESS; JENKINS TRIGGER DEPLOY VIA K8S.
7. Bastion was created and Terraform and Ansible was installed in them.
8. Terraform executes main.tf to create infrastructure for 3 new VMs.
9. Ansible remotely configured java installation to all 3 VMs.
10. Webhooks used to pull any latest commit in repo - https://github.com/DevGitRemote/capstone1newdevops .
11. All tasks completed and feel free to contact for queries.
