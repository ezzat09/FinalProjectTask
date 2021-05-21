<<<<<<< HEAD
# FinalProjectTask
# steps
- installing git ,terraform.
$ sudo apt-get update && sudo apt-get install -y gnupg software-properties-common curl
$ curl -fsSL https://apt.releases.hashicorp.com/gpg | sudo apt-key add -
$ sudo apt-add-repository "deb [arch=amd64] https://apt.releases.hashicorp.com $(lsb_release -cs) main"
$ sudo apt-get update && sudo apt-get install terraform
- Creating a local repo for the project, and new repo on github
$ git init -b main
$ git add .
$ git commit -m "Final project Commit"
$ git remote add origin https://github.com/ezzat09/FinalProjectTask.git
$ git push origin main
3- terraform init, terraform apply
tf files are in the repo for creating the resources.
-for the third task i have created nodes and installed on node ansible and the worker node, playbook in the repo
for the last task i have created 4 branches and jenkins file in the repo ci/cid branch
after installing jenkins I have created a multibranch pipeline.

