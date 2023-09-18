<h2 align="center">archy - zip archive compressor/extraction using c++</h2>

###

<div align="center">
  <img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/cplusplus/cplusplus-original.svg" height="150" alt="cplusplus logo"  />
</div>

###

## project structure:

```rust
├── LICENSE
├── archy.cpp
└── README.md
```

## installation

```shell
git clone https://github.com/kenjitheman/archy
```

## usage

- **modify main function to use this tool**

```c++
std::vector<std::string> filesToCompress = {"your_file_path.txt", "your_file_path_1.txt"}; // can be any number of files
std::string zipFilename = "your_zip_archive.zip";
```

- compile c++

```shell
g++ archy.cpp -o archy
```

- run:

```shell
./archy
```

## contributing

- pull requests are welcome, for major changes, please open an issue first to
  discuss what you would like to change

## license

- [MIT](https://choosealicense.com/licenses/mit/)
