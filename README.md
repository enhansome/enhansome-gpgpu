# Awesome GPGPU with stars

[![Awesome](https://awesome.re/badge.svg)](https://awesome.re)

A curated list of awesome GPGPU (CUDA/OpenCL/Vulkan) resources

## Contents

* [CUDA](#cuda)
  * [Libraries](#libraries)
    * [C++](#c)
  * [Tutorials](#tutorials)
* [OpenCL](#opencl)
  * [Libraries](#libraries)
    * [C++](#c)
    * [Rust](#rust)
  * [Applications](#applications)
  * [Tutorials](#tutorials)
* [Vulkan](#vulkan)
  * [Libraries](#libraries)
    * [C++](#c)

> **Legend**: 🟢 Active (<1yr) · 🟡 Slow (1-2yr) · 🔴 Stale (>2yr) · 💀 Archived

## [CUDA](#contents)

### Libraries

#### C++

* 💀 [Thrust](https://github.com/NVIDIA/thrust) ⚠️ Archived - The C++ parallel algorithms library [⭐ 5k](https://github.com/NVIDIA/thrust) ⚠️ Archived
* 🟢 cuda-api-wrappers - Thin, unified, C++-flavored wrappers for the CUDA APIs [⭐ 885](https://github.com/eyalroz/cuda-api-wrappers) ⭐ 902 | 🐛 117 | 🌐 C++ | 📅 2026-07-16

### Tutorials

* [CMake setup for CUDA](https://cliutils.gitlab.io/modern-cmake/chapters/packages/CUDA.html)

## [OpenCL](#contents)

### Libraries

#### C++

* 🟢 [ArrayFire](https://arrayfire.com/) - A general-purpose GPU library [⭐ 4.9k](https://github.com/arrayfire/arrayfire) ⭐ 4,900 | 🐛 318 | 🌐 C++ | 📅 2026-03-07
* 🟢 [Boost.Compute](http://boostorg.github.io/compute/) - A C++ GPU Computing Library for OpenCL [⭐ 1.7k](https://github.com/boostorg/compute) ⭐ 1,661 | 🐛 157 | 🌐 C++ | 📅 2026-08-12
* 🟢 [VexCL](http://vexcl.readthedocs.org) - VexCL is a C++ vector expression template library for OpenCL/CUDA [⭐ 719](https://github.com/ddemidov/vexcl) ⭐ 721 | 🐛 31 | 🌐 C++ | 📅 2025-07-19
* 🔴 [Chlorine](http://polytonic.github.io/Chlorine/) - Dead Simple OpenCL [⭐ 429](https://github.com/Polytonic/Chlorine) ⭐ 429 | 🐛 5 | 🌐 C++ | 📅 2016-04-10
* 🔴 EasyOpenCL - The easiest way to get started with OpenCL! [⭐ 310](https://github.com/Gladdy/EasyOpenCL) ⭐ 309 | 🐛 0 | 🌐 C++ | 📅 2015-09-06
* 🟡 EasyCL - Easy to run kernels using OpenCL [⭐ 188](https://github.com/hughperkins/EasyCL) ⭐ 188 | 🐛 10 | 🌐 C++ | 📅 2025-04-22
* 🔴 clpp - Lightweight and easy to use the OpenCL C++ wrapper in single file [⭐ 5](https://github.com/matszpk/clpp) ⭐ 5 | 🐛 0 | 🌐 C++ | 📅 2020-02-25

#### Rust

* 🔴 [Emu](https://calebwin.github.io/emu/) - Emu is a high-level language that compiles to OpenCL and provides a procedural macro for embedding code in Rust [⭐ 1.6k](https://github.com/calebwin/emu) ⭐ 1,604 | 🐛 29 | 🌐 Rust | 📅 2023-01-20

### Applications

* 🟢 [Bullet](http://bulletphysics.org/wordpress/) - Real-Time Physics Simulation (Bullet 3 includes the optional work-in-progress GPU pipeline.) [⭐ 14.5k](https://github.com/bulletphysics/bullet3) ⭐ 14,670 | 🐛 423 | 🌐 C++ | 📅 2025-10-22
* 🔴 MACE - Deep learning inference framework optimized for mobile heterogeneous computing platforms [⭐ 5k](https://github.com/XiaoMi/mace) ⭐ 5,045 | 🐛 62 | 🌐 C++ | 📅 2024-06-17
* 🟢 [CLBlast](https://cnugteren.github.io/clblast/clblast.html) - Modern, lightweight, performant and tunable OpenCL BLAS library written in C++11 [⭐ 1.2k](https://github.com/CNugteren/CLBlast) ⭐ 1,187 | 🐛 51 | 🌐 C++ | 📅 2026-04-13
* 🔴 DeepCL - OpenCL library to train deep convolutional neural networks [⭐ 881](https://github.com/hughperkins/DeepCL) ⭐ 882 | 🐛 33 | 🌐 C++ | 📅 2018-01-05
* 🔴 OpenCL-caffe - OpenCL version of caffe developed by AMD research lab [⭐ 526](https://github.com/amd/OpenCL-caffe) ⭐ 529 | 🐛 33 | 🌐 C++ | 📅 2018-08-31
* 🟢 Sol-R - CUDA/OpenCL-based realtime ray-tracer [⭐ 306](https://github.com/favreau/Sol-R) ⭐ 305 | 🐛 0 | 🌐 C++ | 📅 2025-10-07
* 🔴 libclsph - OpenCL based GPU accelerated SPH fluid simulation library [⭐ 52](https://github.com/libclsph/libclsph) ⭐ 53 | 🐛 11 | 🌐 C++ | 📅 2016-03-19

### Tutorials

* 🔴 [Basic examples of OpenCL with the C++ API](https://github.com/Dakkers/OpenCL-examples) ⭐ 180 | 🐛 3 | 🌐 C | 📅 2019-03-26 [⭐ 180](https://github.com/Dakkers/OpenCL-examples) ⭐ 180 | 🐛 3 | 🌐 C | 📅 2019-03-26

## [Vulkan](#contents)

### Libraries

#### C++

* 🟢 [Kompute](https://kompute.cc/) - The general purpose GPU compute framework for cross vendor graphics cards [⭐ 2.5k](https://github.com/KomputeProject/kompute) ⭐ 2,553 | 🐛 77 | 🌐 C++ | 📅 2026-07-26

## [Contributing](#contents)

Contributions are very welcome. Please read the [contribution guidelines](CONTRIBUTING.md) first. Also, please feel free to report any error.

## [License](#contents)

[![CC0](https://licensebuttons.net/p/zero/1.0/88x31.png)](http://creativecommons.org/publicdomain/zero/1.0/)

***

> _Enhansomed by [enhansome](https://github.com/enhansome) on 2026-08-13._
