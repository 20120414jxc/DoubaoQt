<a href="https://space.bilibili.com/1524901776"><img src="https://img.shields.io/badge/Bilibili-关注我-pink?logo=bilibili" alt="Bilibili"></a>   
# Doubao Client

## Project Introduction

This is a Doubao web wrapper application developed based on Qt WebEngineWidgets, which can load the official Doubao webpage and save login status, providing a desktop application-like experience.

## Features

- Loads Doubao official webpage (https://www.doubao.com)
- Persistent login status storage, no need to log in again every time
- Support for high-DPI screens
- Responsive window size

## Technical Implementation

- Developed using Qt 6 framework
- Loads webpages based on WebEngineWidgets
- Uses QWebEngineProfile to implement login status persistence
- Storage path: DoubaoClient folder in the temporary directory

## Build Method

1. Ensure Qt 6 development environment is installed
2. Build the project using CMake:

```bash
mkdir build
cd build
cmake ..
make
```

3. Run the application:

```bash
./DoubaoClient
```

## Notes

- A storage folder will be created in the temporary directory when running for the first time
- Login status will be saved locally, ensuring privacy and security
- If encountering permission issues, you may need to run with administrator privileges

## License

MIT License