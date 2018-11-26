1.
git clone --depth 1 -b stable https://github.com/jedisct1/libsodium.git
cd libsodium\builds\msvc\build
buildall.bat
cd ..\..\..\..

2.
git clone https://github.com/certik/uuid.git

3.
git clone https://github.com/systemd/systemd.git

4.
git clone https://github.com/lz4/lz4.git

5.
git clone https://github.com/curl/curl.git

6
git clone git://github.com/zeromq/libzmq.git
cd libzmq\builds\msvc
configure.bat
cd build
buildall.bat
cd ..\..\..\..

4.
git clone git://github.com/zeromq/czmq.git
cd czmq\builds\msvc
configure.bat
cd build
buildall.bat
cd ..\..\..\..
