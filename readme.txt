Fedora 14.0

Install:
1. su-> enter your root password(if need to do 2. and 3.)
2. yum install gcc(if necessary)
3. yum install kernel-PAE-devel(if kernel doesn't support PAE, type : yum install kernel-devel)(if necessary)
4. tar zxvf 20140812_rtl8192EU_linux_v4.3.1.1_11320.tar.gz
   and cd to 20140812_rtl8192EU_linux_v4.3.1.1_11320
5. make
6. su-> enter your root password(if not do 1. 2. 3.)
7. make install

Uninstall:
1. su-> enter your root password
2. make uninstall
3. make clean

Ubuntu 10.04.2

Install:
1. tar zxvf 20140812_rtl8192EU_linux_v4.3.1.1_11320.tar.gz
   and cd to 20140812_rtl8192EU_linux_v4.3.1.1_11320
2. make
3. su-> enter your root password
4. make install

Uninstall:
1. su-> enter your root password
2. make uninstall
3. make clean