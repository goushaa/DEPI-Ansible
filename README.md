# Install Docker and Jenkins with Ansible

This Ansible playbook installs Docker and Jenkins on the localhost using the `iam-surya369.java-jenkins-docker` role.

## Requirements

- Ansible must be installed on your machine.
- You need root privileges to execute the playbook.

## Usage

1. Clone this repository or create a new file for the playbook:

    ```bash
    git clone <your-repo-url>
    cd <your-repo-directory>
    ```

2. Install the required Ansible roles:

    ```bash
    ansible-galaxy install iam-surya369.java-jenkins-docker
    ```

3. Run the playbook with the following command:

    ```bash
    ansible-playbook playbook.yml
    ```

## Playbook Details

This playbook runs on `localhost` and performs the following tasks:

- Installs Docker
- Installs Jenkins
- Uses the Ansible Galaxy role `iam-surya369.java-jenkins-docker`