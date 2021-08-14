# AndroidMining
 This small project is to share how  an approach to mine XMR etc on many android phones
 
 Welcome to the AndroidMining wiki!

-  This small project is to share how  i successfully started  mining XMR/RVN 
- download Termux on to your **android** phone from the google play store
- create a Monero wallet. here is MyMonero [https://mymonero.com](mymonero). this app all$
- open the Termux app
- **Install required packages**
- pkg install cmake git libuv1 openssl unstable-repo -y
- pkg install libmicrohttpd

- clone the xmrig project [XMRig](https://github.com/xmrig/xmrig) https://github.com/xmrig
- Big thanks to @xmrig for their FOSS project.
- cd xmrig-6.14.0
-  mkdir build && cd build
- **prepare the project**
- cmake .. -DWITH_HWLOC=OFF -DCMAKE_BUILD_TYPE=Release -DARM_TARGET=8 -DWITH_OP$
- build the project make -j$(nproc)
- OR make -j2 
- email at alexcarll@yahoo.com with questions or concerns
- Donations welcome! 

>
>
>-**XMR:** 45bJkL5UQgDUcQGkDjCHFHioMwDnM3J5KRDYSErQP1NpeYCvadP4CVabWdYUQzZkBaJAqG1bcuDAh3pVC49TSHJQ8HdGzVL
>
>
>-**BTC:** 3CKS6bpExsGxSmcJDYSeTL8zNYdZnh6u7Z
>
>
>-**ETH:** 0x46669245653c609BE6dbfCc900cfF2669c3157D7
>
>
>-**BCH:** qrqmkmjz09hq9vpl2yhxqdqx03z70730tcl3kn76c4

