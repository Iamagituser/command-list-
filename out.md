    1  clear
    2  cd
    3  apt-get install b43-fwcutter
    4  ls
    5  cd .
    6  cd /
    7  cd etc
    8  ls
    9  cd apt
  ''' 
  10  ls
   11  clear
   12  nano sources.list
   13  clear
   14  apt-get update
   15  apt-get upgrade
   16  clear
   17  nano sources.list
   18  clear
   19  apt-get update
   20  clear
   21  apt-get install b43-fwcutter
   22  clear
   23  apt-get update
   24  nano sources.list
   25  apt-get update
   26  modprobe -r b44 b43 b43legacy ssb brcmsmac bcma
   27  modprobe wl
   28  apt-get install modprobe
   29  apt-get install linux-image-$(uname -r|sed 's,[^-]*-[^-]*-,,') linux-headers-$(uname -r|sed 's,[^-]*-[^-]*-,,') broadcom-sta-dkms
   30  modprobe -r b44 b43 b43legacy ssb brcmsmac bcma
   31  apt-get install network-manager-gnome
   32  reboot
   33  poweroff
   34  apt-get install zsh
   35  zsh
   36  reboot
   37  systemctl reboot
   38  cd
   39  sudo adduser brar
   40  ls
   41  apt install fuse libfuse-dev libicu-dev bzip2 libbz2-dev cmake clang git libattr1-dev
   42  git clone https://github.com/sgan81/apfs-fuse.git
   43  cd apfs-fuse
   44  git submodule init
   45  git submodule update
   46  mkdir build
   47  cd build
   48  cmake
   49  apt-get install cmake
   50  cmake
   51  cmake ..
   52  make
   53  cp apfs-* /usr/local/bin
   54  ls
   55  cd ..
   56  ls
   57  cp apfs-* /usr/local/bin
   58  cp apfs* /usr/local/bin
   59  cp -r apfs* /usr/local/bin
   60  ls
   61  clear
   62  cd
   63  fdisk -l
   64  apt-get install fdisk
   65  fdisk 
   66  fdisk man
   67  man fdisk
   68  fdisk -l
   69  exit
   70  clear
   71  cd
   72  ls
   73  clear
   74  sl
   75  ls
   76  clear
   77  cd /etc
   78  cd sudoers
   79  ls sudo*
   80  nano sudoers
   81  adduser brar admin
   82  apt-get install sudo -y
   83  clear
   84  chmod  0440  /etc/sudoers
   85  cd ..
   86  ls
   87  clear
   88  apfs-fuse
   89  gdisk
   90  fdisk
   91  zsh
   92  systemctl reboot
   93  clear
   94  cd 
   95  whoami
   96  exot
   97  exit
   98  clear
   99  s
  100  ls
  101  adduser brar admin
  102  adduser brar
  103  removeuser brar
  104  exit
  105  clear
  106  usermod -aG sudo brar
  107  exit
  108  ls
  109  clear
  '''
  110  ls
  111  ls
  112  cd Documents
  113  history >> out.md
