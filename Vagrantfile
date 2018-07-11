ENV['VAGRANT_DEFAULT_PROVIDER'] = 'virtualbox'

Vagrant.configure("2") do |config|
    config.vm.box = "hashicorp/precise32"
    config.vm.define :alura do |web_config|
        config.vm.network "private_network", ip: "10.0.0.10"
    end
end
