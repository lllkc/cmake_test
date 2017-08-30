## t2:
cmake -DCMAKE_INSTALL_PREFIX=/tmp/t2/usr ..
make
make install

## t3:
cmake -DCMAKE_INSTALL_PREFIX=/usr ..
make
make install
