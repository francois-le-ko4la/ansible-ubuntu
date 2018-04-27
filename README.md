# ansible-ubuntu

Setup Ubuntu Desktop with Ansible
This ansible playbook replace my python script.

## Why ?
This script makes it possible to automate the tasks to be performed after a fresh ubuntu installation therfore you can homogenize the configuration of several Ubuntu PCs.

This script allows you to:
- Update/upgrade
- Make a "virtual drive (TMPFS)" in order to store apt archives
- Disable the swap
- Install packages

You can use, modify, change, do your coffee,... ON YOUR OWN RISKS !!!
This script is provided in the hope that it will be useful,
but WITHOUT ANY WARRANTY; without even the implied warranty of
MERCHANTABILITY or FITNESS FOR A PARTICULAR PURPOSE.  See the GNU
Lesser General Public License for more details.

## How ?
### Install ansible
    sudo apt-get install ansible
### Clone git repository
    cd /tmp
    git clone https://github.com/francois-le-ko4la/ansible-ubuntu.git
### Use playbook
    cd ansible-ubuntu
    ansible-playbook playbook_ubuntu.yml -K

## Ubuntu release
17.10/18.04 tested/validated
