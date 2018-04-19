# gopjnath
a go wrapper of gopjnath

# how to use
 ## build
 ### 1. build pjsip
 ```
 wget http://www.pjsip.org/release/2.7.2/pjproject-2.7.2.tar.bz2
tar xjf pjproject-2.7.2.tar.bz2
cd pjproject-2.7.2
./configure --disable-sound --disable-video --disable-ssl
make dep && make && make install
 ```
### 2. build example
    ```
    cd cmd
    go build
    ```    
you can find how to use the export api in the cmd/main.go