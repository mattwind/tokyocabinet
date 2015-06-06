# tokyocabinet
Tokyo Cabinet is a library of routines for managing a database.

Based on version 1.4.48, compiles on linux and windows (cygwin)

###Fixed
Fixed compile errors, P_tmpdir and iprintf to my_iprintf not defined correctly.

### How to compile and install

    git clone https://github.com/mattwind/tokyocabinet.git
    cd ./tokyocabinet/src
    ./configure --disable-zlib --disable-bzip
    make
    make install
