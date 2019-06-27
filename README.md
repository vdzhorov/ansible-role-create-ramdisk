# ramdisk

Role which creates and mounts a ramdisk.

### Prerequisites

* Change your vars in defaults to what suits you best. You can change the ramkdisk path, size, and mount options. Can be changed via group_vars as well.

## Deployment

Run ```ansible-playbook -i '<IP>,' playbooks/ramdisk.yml ``` (You will need to create your playbook first.)
## Built With

* [Ansible 2.8](https://docs.ansible.com/ansible/latest/roadmap/ROADMAP_2_8.html) - Ansible 2.8

## Authors

* **Valentin Dzhorov** - *Initial work* - [vdzhorov](https://github.com/vdzhorov)

## Company
* **Delta.BG**

## License

This project is licensed under the MIT License.
