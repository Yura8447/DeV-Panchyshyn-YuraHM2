Vagrant.configure("2") do |config|

  config.vm.define "ubuntu" do |ubuntu|
    ubuntu.vm.box = "ubuntu/focal64"
  end

  config.vm.define "centos" do |centos|
    centos.vm.box = "centos/7"
  end

  config.vm.provider "virtualbox" do |vb|
  vb.memory = 2048
  end
 
end
