Intel MPSS kernel module
========================

`mpss-modules` 3.8.6 source patched to compile on newer `elrepo-lt` 4.4 kernels.

Build with `make MIC_CARD_ARCH=k1om`.


///////////////
make MIC_CARD_ARCH=k1om -j 64
sudo make install

sudo depmod
sudo modprobe mic
////////////////////

