# -*- mode: ruby -*-
# vi: set ft=ruby :
Vagrant.configure(2) do |config|
  config.vm.define  "docker" do |host|
    host.vm.box = "centos/7"
    host.vm.hostname = "docker"
    host.vm.network "private_network", ip: "192.168.50.17"
    host.vm.provision "shell", path: "bootstrap"
  end
end
