# HashiCorp Consul Server - Post Provisioning Ansible

The content of this project is part of the post on blog https://red-devops.pl/<br>

HasiCorp Consul cluster is automatically configured using Ansible Playbook. The repository is automatically executed on instance startup by HashiCorp Terraform, which can be found in the repository https://github.com/red-devops/Workout-recorder-consul ( path 100-app-infra/160-consul-cluster ). It is possible to run cluster configuration manualy using GitHub Action workflow consul-server-{env}.yaml