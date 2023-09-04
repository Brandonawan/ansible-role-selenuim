# Vagrantfile

Vagrant.configure("2") do |config|
    # Define the virtual machine box and settings
    config.vm.box = "ubuntu/bionic64"
    config.vm.network "private_network", type: "dhcp"
  
    # Provision the virtual machine using Ansible
    config.vm.provision "ansible" do |ansible|
      ansible.playbook = "here.yml" # Specify your Ansible playbook
    end
  
    # You can customize other Vagrant settings here, such as memory and CPU
    config.vm.provider "virtualbox" do |vb|
      vb.memory = 1024
      vb.cpus = 2
    end
  end