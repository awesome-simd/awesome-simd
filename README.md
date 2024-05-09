# awesome-simd

A curated list of awesome SIMD frameworks, libraries and software.

This list showcases projects that have achieved 10x performance improvements using [SIMD](https://en.wikipedia.org/wiki/SIMD) (Single Instruction Multiple Data) instructions. In general this should lead to execution speeds of GBs per second on modern CPUs for that task at hand.

## Database / Structures

* [sneller](https://github.com/SnellerInc/sneller) - Fast SQL for JSON in Go with AVX-512: fast, simple, schemaless
* [bitmap](https://github.com/kelindar/bitmap) - Go: Dense, zero-allocation, SIMD-enabled bitmap/bitset

## Parsing

* [simdjson](https://github.com/lemire/simdjson) - C++: Parsing gigabytes of JSON per second
* [dictionary](https://github.com/lemire/dictionary) - C++: High-performance dictionary coding
* [simdjson-go](https://github.com/minio/simdjson-go) - Go: Parsing gigabytes of JSON per second
* [simdcomp](https://github.com/lemire/SIMDcomp) - C: A simple library for compressing lists of integers using binary packing
* [SIMDCompressionAndIntersection](https://github.com/lemire/SIMDCompressionAndIntersection) - C++: A library to compress and intersect sorted lists of integers using SIMD instructions
* [simdutf](https://github.com/simdutf/simdutf) - C++: Unicode routines (UTF8, UTF16, UTF32)
* [Ada](https://github.com/ada-url/ada) - C++: WHATWG-compliant and fast URL parser
* [StringZilla](https://github.com/ashvardanian/StringZilla) - C: Substring search, edit-distances, sorting, fuzzy matching, etc.
* [Hyperscan](https://github.com/intel/hyperscan) - C++: High-performance regular expression matching library
* [Various string algo's](https://github.com/WojciechMula/toys) - C: Repository for string algorithms, snippets, toy programs, etc.
* [sse-popcount](https://github.com/WojciechMula/sse-popcount) - SIMD (SSE) population count

## Erasure Coding and Hashing
- [xxHash](https://github.com/Cyan4973/xxHash) - C:  Extremely fast Hash algorithm, processing at RAM speed limits.
- [Reed-Solomon](https://github.com/klauspost/reedsolomon) - Go: Erasure Coding in Go
- [highwayhash](https://github.com/minio/highwayhash) - Go: Optimized HighwayHash implementation for Intel (over 10 GB/sec), ARM and Power9
- [sha256-simd](https://github.com/minio/sha256-simd) - Go: Optimized SHA256 computations for Intel, ARM and Power9

## Neural Network

- [ncnn](https://github.com/Tencent/ncnn) - C++: High-performance NN inference framework optimized for mobile
- [mkl-dnn](https://github.com/intel/mkl-dnn) - C++: Math Kernel Library for Deep Neural Networks
- [nnpack](https://github.com/Maratyszcza/NNPACK) - C/c++: Acceleration package for neural networks on multi-core CPUs
- [SimSIMD](https://github.com/ashvardanian/SimSIMD) - C: Similarity measures for high-dimensional vectors

## Image processing

* [Simd](https://github.com/ermig1979/Simd) - C++: image processing library making use of SIMD
* [Pillow-SIMD](https://github.com/uploadcare/pillow-simd) - Python: SIMD version of PIL (Python Imaging Library)
* [ComputeLibrary](https://github.com/ARM-software/ComputeLibrary) - C++: Library for Computer Vision and Machine Learning (ARM only)

## Classes

* [HPC-Class](https://scalable.uni-jena.de/opt/hpc/index.html) -  High Performance Computing (HPC) class taught at FSU Jena by the Scalable Data- and Compute-intensive Analyses lab

## Cool

* [CPUlator](https://cpulator.01xz.net/?sys=arm) - CPUlator Computer System Simulator (ARMv7, MIPS, RISC-V)
* [SIMD-Visualiser](https://github.com/piotte13/SIMD-Visualiser) - Javascript: Graphically visualize SIMD code
* [Visual ARM emulator](https://salmanarif.bitbucket.io/visual/index.html) - VisUAL: a highly visual ARM emulator
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
* [awesome-decompilation](https://github.com/nforest/awesome-decompilation) - Curated list of awesome decompilation resources and projects.
* [Intel Manual vol 1 (HTML)](http://xem.github.io/minix86/manual/intel-x86-and-64-manual-vol1/o_7281d5ea06a5b67a.html)
* [Intel Manual vol 2 (HTML)](http://xem.github.io/minix86/manual/intel-x86-and-64-manual-vol2/o_b5573232dd8f1481.html)
* [Intel Manual vol 3 (HTML)](http://xem.github.io/minix86/manual/intel-x86-and-64-manual-vol3/o_fe12b1e2a880e0ce.html)
* [x86 documentation](https://github.com/xem/minix86) - x86 documentation
* [Go assembly reference](https://quasilyte.dev/blog/post/go-asm-complementary-reference/) - Go assembly language complementary reference
* [Intel® Intrinsics Guide](https://www.intel.com/content/www/us/en/docs/intrinsics-guide/index.html) - A list of all Intel® intrinsic functions for x86.

## Tools

* [avo](https://github.com/mmcloughlin/avo) - Go: Generate x86 Assembly with Go
* [PeachPy](https://github.com/Maratyszcza/PeachPy) - Python: x86-64 assembler embedded in Python
* [c2goasm](https://github.com/minio/c2goasm) - Go: C to Go Assembly
* [LLVM MCA](https://llvm.org/docs/CommandGuide/llvm-mca.html) - LLVM Machine Code Analyzer
* [Highway](https://github.com/google/highway) - C++: Performance-portable, length-agnostic SIMD with runtime dispatch
* [Eve](https://github.com/jfalcou/eve) - C++: Expressive Vector Engine
* [SIMDe](https://github.com/simd-everywhere/simde) - C++: Header-only implementations of SIMD instruction sets (SSE*, AVX{,2,512}, Neon, and more) for systems which don't natively support them.
* [xsimd](https://github.com/QuantStack/xsimd) - C++: Wrappers for SIMD intrinsics and math implementations (SSE, AVX, NEON, AVX512)
* [Intel SDE debugging](https://software.intel.com/en-us/articles/debugging-applications-with-intel-sde#DEBUG-AVX512) - Debugging with AVX-512
* [Asm-Dude](https://github.com/HJLebbink/asm-dude) - VS extension for assembly syntax highlighting and code completion
* [Intrinsics-Dude](https://github.com/HJLebbink/intrinsics-dude) - VS extension for compiler instrinsics in C/C++
* [Intel® Implicit SPMD Program Compiler](https://ispc.github.io/) - An LLVM compiler for a C like language, with C linkage, that generates very good SIMD instructions for a wide range of platforms and ISAs.  (Windows, iOS, Linux, ARM, PS5, Xbox, SSE, AVX, AVX2, AVX-512, ARM NEON.)

## Online tools

* [Online (dis-)assembler](http://shell-storm.org/online/Online-Assembler-and-Disassembler/) - Online assembler and disassembler
* [ODA](https://onlinedisassembler.com/odaweb/) - Online disassembler (disassembler.io)

## AVX-512

* [x86/x64 SIMD Instructions (AVX512)](https://www.officedaytime.com/simd512e/simd.html) - AVX-512 overview
* [Golang's AVX512](https://github.com/golang/go/wiki/AVX512) - Go 1.11 introduction of AVX-512 support
* [Golang AVX512 test data](https://github.com/golang/go/tree/master/src/cmd/asm/internal/asm/testdata/avx512enc) - Golang AVX-512 test instructions
* [alexcrichton](https://gist.github.com/alexcrichton/3281adb58af7f465cebee49759ae3164) - AVX-512 overview
* [Colfax: Capabilities of Intel AVX-512](https://colfaxresearch.com/skl-avx512/) - Capabilities of AVX-512

## ARM64 NEON

* [Golang's ARM64 NEON support](https://golang.org/pkg/cmd/internal/obj/arm64/) - Intro to arm64 assembler for Golang
* [Golang ARM64 test data](https://github.com/golang/go/blob/master/src/cmd/asm/internal/asm/testdata/arm64enc.s) - Golang ARM64 (incl. NEON) test instructions

## ARM64 SVE

* [SVE overview](https://dougallj.github.io/asil/) - SVE overview

## License

[![Creative Commons License](http://i.creativecommons.org/l/by/4.0/88x31.png)](http://creativecommons.org/licenses/by/4.0/)
