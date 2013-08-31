Learn C The Hard Way
=

Description
-
Going through the [Learn C The Hard Way](http://c.learncodethehardway.org/book) Tutorial by Zed A. Shaw

Hiccups
-

* ####MD5checksum
I am running on Mac OSX, which does not include md5checksum.  I found a helpful blog post on how to install 
md5sum/sha1sum [here](http://raamdev.com/2008/howto-install-md5sum-sha1sum-on-mac-os-x/).  These are the steps I took:
      1. Download the source:
      
      ```
      curl -O http://www.microbrew.org/tools/md5sha1sum/
      ```
      2. Unpack the compressed files: *(note: your version may differ)*
      
      ```
      tar -xf md5sha1sum-0.9.5.tar.gz 
      ```
      3. Change into that directory: *(note: your version may differ)*
      
      ```
      cd md5sha1sum-0.9.5
      ```
      4. Configure the files:
      
      ```
      ./conifgure
      ```
      5. Make it:
      
      ```
      make
      ```
      6. Install it: *(requires your password)*
      
      ```
      sudo make install
      ```

* ####Valgrind
With md5checksum installed, you next need to install valgrind.  These are the steps I took:
       1. Download the soure: *(note: your version may differ)*
       
       ```
       curl -O http://valgrind.org/downloads/valgrind-3.8.1.tar.bz2
       ```
       2. Ensure it matches the one on the site:
       
       ```
       md5sum valgrind-3.8.1.tar.bz2
       ```
       3. Unpack the files: *(note: your version may differ)*
       
       ```
       tar -xjvf valgrind-3.8.1.tar.bz2
       ```
       4. Change into the valgrind directory: *(note: your version may differ)*
       
       ```
       cd valgrind-3.8.1
       ```
       5. Configure the files:
       
       ```
       ./configure
       ```
       6. Make the files:
       
       ```
       make
       ```
       7. Install the files:
       
       ```
       sudo make install
       ```
