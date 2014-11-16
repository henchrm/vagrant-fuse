Vagrant.configure("2") do |config|

  #---Puppet Lab's CentOS Boxes---
  #https://github.com/puppetlabs/puppet-vagrant-boxes


  config.vm.box = "centos-65-x64-virtualbox-nocm"
  config.vm.box_url = "http://puppet-vagrant-boxes.puppetlabs.com/centos-65-x64-virtualbox-nocm.box"

  config.vm.provision :shell, path: "bootstrap.sh"
  
  
end