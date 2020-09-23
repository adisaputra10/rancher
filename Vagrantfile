Vagrant.configure("2") do |config|

 config.vm.define "dash" do |dash|
    dash.vm.box = "ubuntu/xenial64"
    dash.vm.network "private_network",ip: "10.168.12.10"
      dash.vm.provider "virtualbox" do |v|
        v.memory = 2024
        v.cpus = 2
     end
  end


  config.vm.define "master" do |master|
    master.vm.box = "ubuntu/xenial64"
    master.vm.network "private_network",ip: "10.168.12.2"
      master.vm.provider "virtualbox" do |v|
        v.memory = 2024
        v.cpus = 2
     end
  end



  config.vm.define "node1" do |node1|
    node1.vm.box = "ubuntu/xenial64"
    node1.vm.network "private_network",ip: "10.168.12.3"
      node1.vm.provider "virtualbox" do |v|
        v.memory = 2024
        v.cpus = 2
     end
  end

 config.vm.define "node2" do |node2|
    node2.vm.box = "ubuntu/xenial64"
    node2.vm.network "private_network",ip: "10.168.12.4"
      node2.vm.provider "virtualbox" do |v|
        v.memory = 2024
        v.cpus = 2
     end
  end



end
