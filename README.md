# ansible-role-grafana

This Ansible role is designed to automate the installation and setup of Grafana on a server with SSH access.

## Usage

To run this Ansible playbook, follow these steps:

1. Set up a server with SSH access where Grafana is to be installed.

2. Modify the IP address in the `inventory/hosts` file to match the server's IP.

3. Execute the following command to run the Ansible playbook:

```shell
ansible-playbook -i inventory/ play.yml
```

This playbook will automate the installation and configuration of Grafana on the specified server.

Feel free to customize the playbook or role parameters in the `play.yml` file and other configuration files as needed for your specific Grafana setup.

## License

This project is open-source and available under the [MIT License](LICENSE). You are free to use and modify the Ansible role as needed.

Enjoy automating your Grafana setup with ansible-role-grafana!
