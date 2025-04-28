# SDR++ (Enable USRP)

The [official](https://github.com/AlexandreRouma/SDRPlusPlus) build has USRP disabled, so enable USRP and perform the build.

<br>

<div align="center">

[![Weekly Build](https://github.com/fksms/SDRPlusPlusBuilder/actions/workflows/weekly_build.yml/badge.svg)](https://github.com/fksms/SDRPlusPlusBuilder/actions/workflows/weekly_build.yml)

<img src="./assets/Screenshot.png" width="800">
</div>

## How to build

### MacOS

#### Install dependencies
```sh
brew install cmake pkgconf fftw glfw volk uhd portaudio
```

#### Building
```sh
sh build.sh
```