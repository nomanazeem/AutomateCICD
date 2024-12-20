# Create branch name with ticket no, 
# checkout branch create .circleci/config.yml, DockerFile, and Deploy.yml file

# AutomateCICD
Automate CI / CD
# Install ansible

# Run ansible
ansible-playbook playbook.yml --extra-vars "GIT_USER=nomanazeem GIT_EMAIL=noman_azeem@yahoo.com GIT_PAT= app_name=application1 jira_ticket=TKT-001 github_url=https://github.com/nomanazeem/app1" 