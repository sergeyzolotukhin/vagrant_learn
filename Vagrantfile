# -*- mode: ruby -*-
# vi: set ft=ruby :

Vagrant.configure("2") do |config|
    config.vm.define "database" do |d|
        d.vm.box = "ubuntu/bionic64"
        d.vm.provider "virtualbox" do |vb|
            vb.name = "database"
            vb.gui = true
            vb.memory = "1024"
        end
    end

    config.vm.define "frontend" do |f|
        f.vm.box = "ubuntu/bionic64"
        f.vm.provider "virtualbox" do |vb|
            vb.name = "frontend"
            vb.gui = true
            vb.memory = "1024"
        end
    end
end
