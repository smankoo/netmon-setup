# netmon-setup

Ensure that you have git installed. If not, run the following

    sudo apt-get update  && sudo apt-get install -y git

Clone the setup repo

    git clone https://github.com/smankoo/netmon-setup netmon-setup

Install ansible

    netmon-setup/install_ansible.sh

Time to rock!!

    ansible-pull -U https://github.com/smankoo/netmon-setup -i "localhost," vm-rebecca.yml
