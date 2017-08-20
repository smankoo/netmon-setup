# netmon-setup

Step 1: Ensure that you have git installed. If not, run the following

    sudo apt-get update  && sudo apt-get install -y git

Step 2: Clone the setup repo

    git clone --hard https://github.com/smankoo/netmon-setup netmon-setup

Step 3: Install ansible

    chmod +x netmon-setup/install_ansible.sh && netmon-setup/install_ansible.sh

Step 4: Time to rock!!

    ansible-pull -U https://github.com/smankoo/netmon-setup -i "localhost," netmon-playbook.yml


If all goes well, you should start seeing logs in `/netmon-logs` directory
