Vagrant.configure("2") do |config|

  config.vm.provider "virtualbox" do |vbox|
  vbox.name = "Projeto01_VM_Ubuntu_20.04"  
  vbox.memory = 1024
  vbox.cpus = 1
  end
  config.vm.box = "ubuntu/focal64"
  config.vm.network "public_network"
  config.vm.synced_folder "fotos/", "/var/www/html/"

end
