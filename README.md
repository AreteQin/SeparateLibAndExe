Create you own library and use it in another project

## build library first
```bash
mkdir build && cd build
cmake ..
make install
```

## build executable to use library
```bash
mkdir build && cd build
cmake ..
make
./my_exe
```