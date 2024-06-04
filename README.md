# KGM Decrypt

`kgm-decrypt` 是一个用 Go 编写的工具，用于解密 KGM 音频文件并将其转换为 MP3 文件。

## 特性

- 读取指定目录下的所有 `.kgm` 文件
- 解密并生成同名的 `.mp3` 文件

## 安装

确保您已安装 Go 编译器。

克隆此存储库：

```sh
git clone https://github.com/bluegitter/kgm-decrypt.git
cd kgm-decrypt
```

## 编译项目：

```sh
go build -o kgm-decrypt

```

## 使用方法

运行程序并提供包含 .kgm 文件的目录路径：

```sh
./kgm-decrypt <directory-path>
```
