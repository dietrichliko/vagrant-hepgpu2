# -*- mode: ruby -*-
# vi: set ft=ruby :


Vagrant.configure("2") do |config|

  config.vm.box = "bento/ubuntu-24.04"

    config.vm.provision "ansible" do |ansible|
    ansible.playbook = "playbook.yml"
    
  end


end
