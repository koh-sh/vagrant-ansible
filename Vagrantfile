# -*- mode: ruby -*-
# vi: set ft=ruby :

Vagrant.configure("2") do |config|

  config.vm.define "vag1" do |node|
    node.vm.box = "bento/centos-7.5"
    node.vm.hostname = "Vag1"
    node.vm.network :private_network, ip: "192.168.33.11"
    node.vm.provider :virtualbox do |vb|
      vb.customize ["modifyvm", :id, "--memory", "1024"]
      vb.customize ["modifyvm", :id, "--cpus", "1"]
      vb.customize ["modifyvm", :id, "--ioapic", "on"]
    end
    node.vm.synced_folder "./syncdir", "/vagrant",
      create: true, owner: "vagrant", group: "vagrant"
    node.vbguest.auto_update = false
  end

  config.vm.define "vag2" do |node|
    node.vm.box = "bento/centos-7.5"
    node.vm.hostname = "Vag2"
    node.vm.network :private_network, ip: "192.168.33.12"
    node.vm.provider :virtualbox do |vb|
      vb.customize ["modifyvm", :id, "--memory", "1024"]
      vb.customize ["modifyvm", :id, "--cpus", "1"]
      vb.customize ["modifyvm", :id, "--ioapic", "on"]
    end
    node.vm.synced_folder "./syncdir", "/vagrant",
      create: true, owner: "vagrant", group: "vagrant"
    node.vbguest.auto_update = false
  end

  config.vm.define "vag3" do |node|
    node.vm.box = "bento/centos-7.5"
    node.vm.hostname = "Vag3"
    node.vm.network :private_network, ip: "192.168.33.13"
    node.vm.provider :virtualbox do |vb|
      vb.customize ["modifyvm", :id, "--memory", "1024"]
      vb.customize ["modifyvm", :id, "--cpus", "1"]
      vb.customize ["modifyvm", :id, "--ioapic", "on"]
    end
    node.vm.synced_folder "./syncdir", "/vagrant",
      create: true, owner: "vagrant", group: "vagrant"
    node.vbguest.auto_update = false
  end

  config.vm.define "vag4" do |node|
    node.vm.box = "bento/centos-7.5"
    node.vm.hostname = "Vag4"
    node.vm.network :private_network, ip: "192.168.33.14"
    node.vm.provider :virtualbox do |vb|
      vb.customize ["modifyvm", :id, "--memory", "1024"]
      vb.customize ["modifyvm", :id, "--cpus", "1"]
      vb.customize ["modifyvm", :id, "--ioapic", "on"]
    end
    node.vm.synced_folder "./syncdir", "/vagrant",
      create: true, owner: "vagrant", group: "vagrant"
    node.vbguest.auto_update = false
  end

  config.vm.define "vag5" do |node|
    node.vm.box = "bento/centos-7.5"
    node.vm.hostname = "Vag5"
    node.vm.network :private_network, ip: "192.168.33.15"
    node.vm.provider :virtualbox do |vb|
      vb.customize ["modifyvm", :id, "--memory", "1024"]
      vb.customize ["modifyvm", :id, "--cpus", "1"]
      vb.customize ["modifyvm", :id, "--ioapic", "on"]
    end
    node.vm.synced_folder "./syncdir", "/vagrant",
      create: true, owner: "vagrant", group: "vagrant"
    node.vbguest.auto_update = false
#    node.vm.network "forwarded_port", guest: 4000, host: 34000
  end

  config.vm.define "vag6" do |node|
    node.vm.box = "bento/centos-7.5"
    node.vm.hostname = "Vag6"
    node.vm.network :private_network, ip: "192.168.33.16"
    node.vm.provider :virtualbox do |vb|
      vb.customize ["modifyvm", :id, "--memory", "1024"]
      vb.customize ["modifyvm", :id, "--cpus", "1"]
      vb.customize ["modifyvm", :id, "--ioapic", "on"]
    end
    node.vm.synced_folder "./syncdir", "/vagrant",
      create: true, owner: "vagrant", group: "vagrant"
    node.vbguest.auto_update = false
  end

  config.vm.define "vag7" do |node|
    node.vm.box = "bento/centos-7.5"
    node.vm.hostname = "Vag7"
    node.vm.network :private_network, ip: "192.168.33.17"
    node.vm.provider :virtualbox do |vb|
      vb.customize ["modifyvm", :id, "--memory", "1024"]
      vb.customize ["modifyvm", :id, "--cpus", "1"]
      vb.customize ["modifyvm", :id, "--ioapic", "on"]
    end
    node.vm.synced_folder "./syncdir", "/vagrant",
      create: true, owner: "vagrant", group: "vagrant"
    node.vbguest.auto_update = false
  end

  config.vm.define "vag8" do |node|
    node.vm.box = "bento/centos-7.5"
    node.vm.hostname = "Vag8"
    node.vm.network :private_network, ip: "192.168.33.18"
    node.vm.provider :virtualbox do |vb|
      vb.customize ["modifyvm", :id, "--memory", "1024"]
      vb.customize ["modifyvm", :id, "--cpus", "1"]
      vb.customize ["modifyvm", :id, "--ioapic", "on"]
    end
    node.vm.synced_folder "./syncdir", "/vagrant",
      create: true, owner: "vagrant", group: "vagrant"
    node.vbguest.auto_update = false
  end

end
