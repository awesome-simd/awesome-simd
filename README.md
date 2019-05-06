# awesome-simd

A curated list of awesome SIMD frameworks, libraries and software.

This list showcases projects that have achieved 10x performance improvements using [SIMD](https://en.wikipedia.org/wiki/SIMD) (Single Instruction Multiple Data) instructions. In general this should lead to execution speeds of GBs per second on modern CPUs for that task at hand.

## Parsing

* [simdjson](https://github.com/lemire/simdjson) - C++: Parsing gigabytes of JSON per second
* [dictionary](https://github.com/lemire/dictionary) - C++: High-performance dictionary coding
* [simdcomp](https://github.com/lemire/SIMDcomp) - C: A simple library for compressing lists of integers using binary packing
* [SIMDCompressionAndIntersection](https://github.com/lemire/SIMDCompressionAndIntersection) - C++: A library to compress and intersect sorted lists of integers using SIMD instructions
* [Hyperscan](https://github.com/intel/hyperscan) - C++: High-performance regular expression matching library
* [Various string algo's](https://github.com/WojciechMula/toys) - C: Repository for string algorithms, snippets, toy programs, etc.
* [sse-popcount](https://github.com/WojciechMula/sse-popcount) - SIMD (SSE) population count

## Erasure Coding and Hashing

- [Reed-Solomon](https://github.com/klauspost/reedsolomon) - Go: Erasure Coding in Go
- [highwayhash](https://github.com/minio/highwayhash) - Go: Optimized HighwayHash implementation for Intel (over 10 GB/sec), ARM and Power9
- [sha256-simd](https://github.com/minio/sha256-simd) - Go: Optimized SHA256 computations for Intel, ARM and Power9

## Neural Network

- [ncnn](https://github.com/Tencent/ncnn) - C++: High-performance NN inference framework optimized for mobile
- [mkl-dnn](https://github.com/intel/mkl-dnn) - C++: Math Kernel Library for Deep Neural Networks
- [nnpack](https://github.com/Maratyszcza/NNPACK) - C/c++: Acceleration package for neural networks on multi-core CPUs

## Image processing

* [Simd](https://github.com/ermig1979/Simd) - C++: image processing library making use of SIMD
* [Pillow-SIMD](https://github.com/uploadcare/pillow-simd) - Python: SIMD version of PIL (Python Imaging Library)
* [ComputeLibrary](https://github.com/ARM-software/ComputeLibrary) - C++: Library for Computer Vision and Machine Learning (ARM only)

## Cool

* [SIMD-Visualiser](https://github.com/piotte13/SIMD-Visualiser) - Javascript: Graphically visualize SIMD code
* [faster](https://github.com/AdamNiederer/faster) - Rust: SIMD for humans
* [Vectorized Emulation](https://gamozolabs.github.io/fuzzing/2018/10/14/vectorized_emulation.html) - Accelerated taint tracking at 2 trillion instructions per second

## Blogs

* [Daniel Lemire](https://lemire.me/blog/)
* [Geoff Langdale](https://branchfree.org/)
* [Wojciech Muła](http://0x80.pl/notesen.html)

## Links

* [Agner Fog](https://www.agner.org/optimize/) - Software optimization resources
* [uops.info](http://uops.info/index.html) - Latency, throughput, and port usage information
* [Felix Cloutier](https://www.felixcloutier.com/x86/index.html) - x86 and amd64 instruction reference
* [Compiler Explorer](https://go.godbolt.org/) - Run compilers interactively from the browser and interact with the assembly
* [awesome-asm](https://github.com/MorgaJoyce/awesome-asm) - A curated list of awesome Assembler
* [awesome-llvm](https://github.com/HongxuChen/awesome-llvm) - Curated list of awesome LLVM related docs, tools, and other resources
* [Intel Manual vol 1 (HTML)](http://xem.github.io/minix86/manual/intel-x86-and-64-manual-vol1/o_7281d5ea06a5b67a.html)
* [Intel Manual vol 2 (HTML)](http://xem.github.io/minix86/manual/intel-x86-and-64-manual-vol2/o_b5573232dd8f1481.html)
* [Intel Manual vol 3 (HTML)](http://xem.github.io/minix86/manual/intel-x86-and-64-manual-vol3/o_fe12b1e2a880e0ce.html)
* [x86 documentation](https://github.com/xem/minix86) - x86 documentation

## Tools

* [avo](https://github.com/mmcloughlin/avo) - Go: Generate x86 Assembly with Go
* [PeachPy](https://github.com/Maratyszcza/PeachPy) - Python: x86-64 assembler embedded in Python
* [c2goasm](https://github.com/minio/c2goasm) - Go: C to Go Assembly
* [LLVM MCA](https://llvm.org/docs/CommandGuide/llvm-mca.html) - LLVM Machine Code Analyzer
* [xsimd](https://github.com/QuantStack/xsimd) - C++: Wrappers for SIMD intrinsics and math implementations (SSE, AVX, NEON, AVX512)
* [Intel SDE debugging](https://software.intel.com/en-us/articles/debugging-applications-with-intel-sde#DEBUG-AVX512) - Debugging with AVX-512
* [Asm-Due](https://github.com/HJLebbink/asm-dude) - VS extension for assembly syntax highlighting and code completion
* [Intrinsics-Dude](https://github.com/HJLebbink/intrinsics-dude) - VS extension for compiler instrinsics in C/C++

## Online tools

* [Online (dis-)assembler](http://shell-storm.org/online/Online-Assembler-and-Disassembler/) - Online assembler and disassembler
* [ODA](https://onlinedisassembler.com/odaweb/) - Online disassembler (disassembler.io)

## AVX-512

* [x86/x64 SIMD Instructions (AVX512)](https://www.officedaytime.com/simd512e/simd.html) - AVX-512 overview
* [Golang's AVX512](https://github.com/golang/go/wiki/AVX512) - Go 1.11 introduction of AVX-512 support
* [alexcrichton](https://gist.github.com/alexcrichton/3281adb58af7f465cebee49759ae3164) - AVX-512 overview

## License

[![Creative Commons License](http://i.creativecommons.org/l/by/4.0/88x31.png)](http://creativecommons.org/licenses/by/4.0/)
