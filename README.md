# CSV worker
by Vladimir Adamskiy ([@vadamsky](https://github.com/vadamsky))

CSV worker is a small C++ library for working with csv files. The alpha version supports the standard syntax only (with a comma as delimiters).

To install the class as a library, follow the commands listed bellow in linux.

-  navigate to the project's folder and make a build directory
```
mkdir build
cd build
```
-  configure the CMake
```
cmake -DCMAKE_BUILD_TYPE=Release -DCMAKE_INSTALL_PREFIX=/usr/local ..
```
-  make it and install it as a static lib under `/usr/local/lib/git_downloads`
```
make
sudo make install
```
