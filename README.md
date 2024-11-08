# How to deploy:
Clone the repository:
```git clone https://github.com/chipatredhat/install_gitea.git```
Change into the direcory:
```cd install_gitea```
Make sure you gave the podman collection installed:
```ansible-galaxy collection install containers.podman```
## Edit variables in install_gitea.yml for your installation
Run the playbook:
```ansible-playbook install_gitea.yml -i localhost,```
