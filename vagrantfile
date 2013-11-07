Vagrant::Config.run do |config|

  config.vm.box = "precise32"
  config.vm.box_url = "http://files.vagrantup.com/precise32.box"
  config.vm.forward_port 4000, 4000
  config.vm.provision :shell,
    :inline => "sudo apt-get -y install build-essential && sudo /opt/vagrant_ruby/bin/gem install jekyll rdiscount --no-ri --no-rdoc"

end