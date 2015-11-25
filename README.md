### deb8-appium

#### setup kvm
    aptitude -y install qemu-kvm libvirt-bin virtinst 
    modprobe kvm-intel
    echo "modprobe kvm-intel" >> /etc/modules
    apt-get install -y build-essential git
    curl -sL https://deb.nodesource.com/setup_5.x |  bash -
    apt-get install nodejs

