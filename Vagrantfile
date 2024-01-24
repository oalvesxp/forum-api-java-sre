Vagrant.configure("2") do |config|

    config.vm.box = "bento/ubuntu-22.04"
    config.vm.define :forum do |forum_config|
      forum_config.vm.hostname = "vm-forum-api"
      forum_config.vm.network :private_network,
                               :ip => "192.168.33.80"
    end
  
  end
  