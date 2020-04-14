### Update repositories list
sudo apt update

### Install git e pip
sudo apt install -y git python-pip

### Install setuptools ant ansible with pip
sudo pip install setuptools
sudo pip install ansible

### Clone repository
git clone https://github.com/carreirorco/ansible-playbooks.git

### Execute the playbook 
ansible-playbook ansible-playbooks/setup-ubuntu/install-tools.yml -e "user=vanessa" -K
