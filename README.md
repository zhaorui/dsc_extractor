# dsc_extractor
A tool by apple to extracting libraries from dyld_shared_cache. It's part of dyld project.

**macOS10.13.2/dyld-519.2.2** [Download](https://github.com/apple-oss-distributions/dyld/archive/dyld-519.2.2.tar.gz) [Github](https://github.com/apple-oss-distributions/dyld/tree/dyld-519.2.2)

## Build
```
clang++ -o dsc_extractor ./dsc_extractor.cpp dsc_iterator.cpp
```

## Install
```
cp dsc_extractor /usr/local/bin
```

## Example
```
dsc_extractor /System/Library/dyld/dyld_shared_cache_arm64e ~/armlibs
```
