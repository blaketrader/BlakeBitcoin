Forked from Bitcoin reference wallet 0.8.6, Blakecoin and Photon

BlakeBitcoin was inspired and requested by the Blake community and is a cryptocurrency designed to use the Blake 256 algorithm based on Blakecoin and Photon with AuxPow and is merge mined with them.

Blake-256(optimized) is faster than Scrypt, SHA-256D, Keccak, Groestl

The algorithm was written as a candidate for sha3, Based on round one candidate code from the sphlib 2.1 and reduced rounds to 8 aka blake256r8.

Current developers:
BlueDragon747 and Cinnamon Carter

What is BlakeBitcoin?

A Blake256 version of Bitcoin same reward structure Starting with 50 coins per block and a total of 21 million coins 
The Block target time is 1/4 of Bitcoin's to account for extra hashing speed of Blake-256
The difficulty retarget is at 8064 blocks and the reward halving every 210,000 blocks ~ 1 year
The difficulty ajustment is also same as per Bitcoin
  

Ubuntu 12.04 dependancies that are used on the Linux build machine:

`git software-properties-common libqt4* libqtcore4 libqtgui4 libqtwebkit4 qt4* libqt4-dev libminiupnpc-dev mingw-w64 build-essential libboost-dev libssl-dev libdb-dev libdb++-dev openssl-1.1.1.g`

Running blakebitcoind: In 'BlakeBitcoin/src' folder, just run: `make -f makefile.unix` `./blakebitcoind --daemon`

Running blakebitcoin-qt: In 'BlakeBitcoin' folder, just run: `qmake` `make` `sudo QT_X11_NO_MITSHM=1 ./blakebitcoin-qt`

License:

Blakecoin is released under the terms of the MIT license. See `COPYING` for more
information or see http://opensource.org/licenses/MIT.



