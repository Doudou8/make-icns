# make-icns

[![npm version](https://badge.fury.io/js/make-icns.svg)](https://www.npmjs.com/package/make-icns) [![license](https://img.shields.io/github/license/Doudou8/make-icns)](https://github.com/electron-userland/electron-forge/blob/master/LICENSE) [![dependencies](https://david-dm.org/Doudou8/make-icns.svg?theme=shields.io)](https://david-dm.org/Doudou8/make-icns.svg)

**make-icns** is a cli that converts a single PNG image into a ICNS image. It does very quickly with very good quality! It is designed to be simple to use on your local machine and to implement in other projects.

## Installation

```bash
$ npm i -g make-icns
```

After installing the cli globally or on your project, you are ready to use it.

## Usage

> In order to get a good quatlity icon, the picture must be at least 1024x1024 pixels.

This command will convert your PNG into an ICNS and move it to the destination directory. The generated ICNS file will automatically take the name of the PNG file. The new image will also override any ICNS file with the same name in the destination directory.

```bash
$ mk-icns PNG_FILE_PATH DESTINATION_DIRECTORY
```

Example:

```bash
$ mk-icns /path/to/pngFile.png /destination/directory
```

## Author

- **Vu Dang Khoa Chiem** - Doudou8

## License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details
