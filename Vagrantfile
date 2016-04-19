# -*- mode: ruby -*-
# vi: set ft=ruby :

Vagrant.configure(2) do |config|
  config.vm.box_check_update = false

  config.vm.network "public_network", bridge: "p4p1"

  config.vm.define "trusty" do |trusty|
    trusty.vm.box = "ubuntu/trusty64"
    trusty.vm.provider "virtualbox" do |vb|
      vb.gui = false
      vb.name = "trusty"
      vb.memory = "1024"
    end
  end

  config.vm.define "wily" do |wily|
    wily.vm.box = "ubuntu/wily64"
    wily.vm.provider "virtualbox" do |vb|
      vb.gui = false
      vb.name = "wily"
      vb.memory = "1024"
    end
  end

end
