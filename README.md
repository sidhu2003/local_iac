## Local IAC Environment Setup for Multi-tier Java Spring Web Application

This repository contains configurations and scripts for setting up a local Infrastructure as Code (IAC) environment using Vagrant. The environment is deployed with a multi-tier Java Spring web application utilizing the following technology stack:

- MySQL
- RabbitMQ
- Memcached
- Apache Tomcat
- Nginx

### Prerequisites

Before you begin, ensure you have the following installed on your system:

- [Vagrant](https://www.vagrantup.com/downloads)
- [VirtualBox](https://www.virtualbox.org/wiki/Downloads)

### Setup Instructions

1. Clone this repository to your local machine:

    ```bash
    git clone https://github.com/sidhu2003/local_iac
    ```

2. Navigate to the cloned directory:

    ```bash
    cd local_iac
    ```

3. Run Vagrant to provision the environment:

    ```bash
    vagrant up
    ```


### Notes

- This setup is for local development and testing purposes only.
- Adjust configuration files and settings as needed for your specific application requirements.
- Make sure to clean up resources properly after use by running `vagrant destroy`.

### Contributing

Contributions are welcome! Feel free to open issues or submit pull requests for any improvements or fixes.


Feel free to customize this README according to your specific project's details and requirements.
