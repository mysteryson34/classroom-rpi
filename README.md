# ***classroom-rpi*** : a companion for teachers

**Dependencies**

    sudo useradd -m -d /home/teacher -s /bin/bash -c "Teacher" -U teacher
    sudo passwd teacher
    sudo usermod -aG sudo teacher
    su root
    visudo
    
    
    sudo apt-get install bc git hwinfo nmap neofetch raspberrypi-kernel-headers
