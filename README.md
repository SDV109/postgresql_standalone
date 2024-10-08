# postgresql_standalone
This repository is designed to install and manage a single PostgreSQL instance

# quick start

sudo apt update && sudo apt install -y python3-pip sshpass git

pip3 install ansible

git clone https://github.com/SDV109/postgresql_standalone.git

cd postgresql_standalone

nano inventory.txt.

nano vars/main.yml

nano vars/system.yml

ansible-playbook deploy_postgresql.yml
