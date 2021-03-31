Vagrant.configure("2") do |config|


  config.vm.define "machine" do |machine|
    machine.vm.box = "centos/7"
    machine.vm.network "private_network", ip: "192.168.60.10"

  end

   config.vm.provision "ansible" do |ansible|
      ansible.playbook = "ansible/playbook.yml"

    end

end
