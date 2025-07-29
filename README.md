# simple-tar-wrapper
a small C++ wrapper for libarchive to do simple stuff with tar files
## functions:
```cpp
void makeDirTar(const std::string source, const std::string output) // Makes a directory into a tar.
```
```cpp
std::vector<std::string> readTar(const std::string tarfile) // Returns a vector of the contents of a tar.
```
