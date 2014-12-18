This repo contains ansible code to execute a jenkins job

When cloning from github, simply run:

    rake

When using galaxy, simply run:

    ansible-galaxy install Azulinho.azulinho-jenkins-kick-pipelines


To consume this role, add the following variables to group_vars/all or
into a wrapper_role <wrapper_role/vars/main.yaml>


VARIABLES:

    azulinho_jenkins_kick_pipeline:
      pipeline_first_jobs:
        - jinja2_deploy_zabbix

