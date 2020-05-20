*creating Vagrant server
vagrant init ubuntu/bionic64

 config.vm.provider :virtualbox do |vb|
   vb.gui = true
end

*Vagrant up
	Vagrant Reload

*initialize git
	git init
	git add .
	git commit -am ""
	git push origin

*First time git set up for a  machine
	ls ~/.ssh
	ssh-keygen -t rsa -b 4096 -C "karbho2@gmail.com"
	take the public key and
	Create repo in github
* push an existing repository from the command line
	git remote add origin https://github.com/karjain/profiles_rest_api2.git
	git push -u origin master
