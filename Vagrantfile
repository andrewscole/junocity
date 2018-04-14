# -*- mode: ruby -*-
# vi: set ft=ruby :

#this sets up vagrant
Vagrant.configure("2") do |config|
  config.vm.box = "bento/ubuntu-16.04"
  config.vm.define "junocity" do |junocity|
    junocity.vm.hostname = "junocity"
    junocity.vm.box = "bento/ubuntu-16.04"
    junocity.vm.network "forwarded_port", guest: 80, host:8080
  end
end
