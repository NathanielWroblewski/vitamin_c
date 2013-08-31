# md5checksum http://raamdev.com/2008/howto-install-md5sum-sha1sum-on-mac-os-x/

curl -O http://www.microbrew.org/tools/md5sha1sum/ #download
tar -xf md5sha1sum-0.9.5.tar.gz #unpack
cd md5sha1sum-0.9.5
./configure #configure it
make #make it
sudo make install #install it

curl -O http://valgrind.org/downloads/valgrind-3.8.1.tar.bz2

md5sum valgrind-3.8.1.tar.bz2

tar -xjvf valgrind-3.8.1.tar.bz2
cd valgrind-3.8.1
./configure
make
sudo make install
