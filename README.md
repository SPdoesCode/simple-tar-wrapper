# simple-tar-wrapper
a small C++ wrapper for libarchive to do simple stuff with tar files
## functions:
```cpp
void tar::makeDirTar(const std::string source, const std::string output) // Makes a directory (const std::string source) into a tar (const std::string output).
```
```cpp
std::vector<std::string> tar::readTar(const std::string tarfile) // Returns a vector of the contents of a tar (const std::string tarfile).
```
