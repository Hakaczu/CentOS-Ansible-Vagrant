
Vagrant.configure("2") do |config|

  config.vm.box = "centos/7"
  config.ssh.username = "vagrant"
  config.ssh.password = "vagrant"
  config.ssh.insert_key = false
  config.vm.provision "shell",
    inline: "yum update -y; yum install epel-release -y; yum install ansible -y"
end
