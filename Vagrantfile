Vagrant.configure("2") do |config|
	config.vm.box = "ubuntu/focal64"  
	
	
	config.vm.network "private_network", ip: "192.168.56.10"
	
	config.vm.provider "virtualbox" do |vb|
	  vb.memory = "2048"  
	  vb.cpus = 2         
	  vb.gui = false
	  
	  
	  vb.customize ["modifyvm", :id, "--natdnshostresolver1", "on"]
	  vb.customize ["modifyvm", :id, "--natdnsproxy1", "on"]
	end

	
	config.vm.box_check_update = false
end