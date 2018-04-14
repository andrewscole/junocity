# -*- mode: ruby -*-
# vi: set ft=ruby :

#this sets up vagrant
Vagrant.configure("2") do |config|
  config.vm.box = "andrewscole/junocity"
  config.vm.box_version = "0.0.1"
  config.vm.define "junocity" do |junocity|
    junocity.vm.hostname = "junocity"
    junocity.vm.box = "andrewscole/junocity"
    junocity.vm.network "forwarded_port", guest: 80, host:8080
  end
end
