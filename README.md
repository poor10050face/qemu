# qemu

sudo apt-get install qemu-kvm qemu virt-manager virt-viewer libvirt-bin
sudo wget https://cdimage.kali.org/kali-2021.3/kali-linux-2021.3-installer-amd64.iso
sudo wget https://tails.braingap.uk/tails/stable/tails-amd64-4.21/tails-amd64-4.21.iso 
sudo qemu-img create ubuntu.img 20G
sudo qemu-img create -f qcow2 ubuntu.qcow 20G
sudo qemu-system-x86_64 -curses -hda ubuntu.qcow -boot d -cdrom tails-amd64-4.21.iso -m 3G
apt-get install qemu-kvm qemu virt-manager virt-viewer libvirt-bin




!wget https://cdimage.kali.org/kali-2021.3/kali-linux-2021.3-installer-amd64.iso
!wget https://tails.braingap.uk/tails/stable/tails-amd64-4.21/tails-amd64-4.21.iso 
!qemu-img create ubuntu.img 20G
!qemu-img create -f qcow2 ubuntu.qcow 20G
!qemu-system-x86_64 -curses -hda ubuntu.qcow -boot d -cdrom tails-amd64-4.21.iso -m 3G


