# Ansible Role: Selenium

Installs and configures Selenium on Debian/Ubuntu servers.

## Table of Contents

- [Overview](#overview)
- [Prerequisites](#prerequisites)
- [Getting Started](#getting-started)
  - [Installation](#installation)
  - [Usage](#usage)
  - [Variables](#variables)
- [Configuration](#configuration)
- [Troubleshooting](#troubleshooting)
- [Contributing](#contributing)
- [License](#license)
- [Acknowledgments](#acknowledgments)

## Overview

This repository provides Ansible roles and playbooks to set up Selenium with Google Chrome and ChromeDriver on a target machine. Selenium is a powerful tool for automating web browsers, and this Ansible setup makes it easy to configure a testing environment.

## Prerequisites

Before using this Ansible playbook, make sure you have the following prerequisites in place:

- [Ansible](https://www.ansible.com/): Version 2.9 or higher.
- A target VM or machine where you want to set up Selenium. You can use Vagrant or any other VM provider.

## Getting Started

Follow these steps to get started with setting up Selenium using Ansible:

### Installation

1. Clone this repository to your local machine:

   ```bash
   git clone https://github.com/your-username/ansible-selenium-setup.git
   cd ansible-selenium-setup

### Usage
```
ansible-playbook -i your_inventory.ini playbook_with_selenium_role.yml
```

### Role Variables

Available variables are listed below, along with default values (see `defaults/main.yml`):

## Configuration

You can customize the setup by modifying the following variables in the playbook and role:

- URLs for downloading Chrome, ChromeDriver, and Selenium Server.
- Versions of Chrome, ChromeDriver, and Selenium Server.
- Paths and directories for installation.
- Additional configuration options as needed.

## Troubleshooting

If you run into any issues while setting up Selenium, try the following:

- Make sure you have the latest version of Ansible installed.
- Check if the target machine has access to the URLs for downloading Chrome, ChromeDriver, and Selenium Server.
- Use the sample vagrant file, make sure you have vagrant installed and configure it to use your ansible playbook and run the following command:

  ```bash
  vagrant up
  ```

```
vagrant provision
```

## Contributing

If you find any problems or have suggestions for improving the setup, please create a GitHub issue or pull request.

## License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

## Acknowledgments

- [Ansible](https://www.ansible.com/)
- [Selenium](https://www.selenium.dev/)
- [Google Chrome](https://www.google.com/chrome/)
- [ChromeDriver](https://chromedriver.chromium.org/)
- [Vagrant](https://www.vagrantup.com/)
- [Ubuntu](https://ubuntu.com/)

