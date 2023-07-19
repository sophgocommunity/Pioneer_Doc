## Story About Our External developers and Partners

- [ZCC toolchain from Terapines has fully supported SG2042 RISC-V chip](./Partner/Terapines.pdf)

Terapines have also benchmarked some popular AI kernels in addition to SPECInt2006. As shown in below, we have evaluated the auto-vectorization performance of zcc, LLVM, EPI LLVM, GCC against 4 kernels includes psroi,
warp, resize and correlation, we have also compared the dynamic instruction count agaist hand optimized kernels written with RVV builtins. zcc shows 18% average better performance against hand optimized kernels, at most 10
times faster than EPI LLVM (9cfcff6873), 100 times faster than LLVM 16 and 69 times faster than GCC 12.2. You can find the source code and build commands of these 4 kernels from [https://github.com/dodohack/rv_lib](https://github.com/dodohack/rv_lib).


<div align="center">
<img src= ./zcc_demo.png
 width="60%"/>
</div>
