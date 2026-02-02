# RISC-V 软件生态进展 · 第 78 期·2026 年 1 月汇总

## 本期亮点

## RuyiSDK IDE / Eclipse Plugin

## RuyiSDK IDE / VSCode Plugin

## RuyiSDK 包管理器

## RuyiSDK 网站更新

## V8 / Chromium
- 7508964: [riscv]Eliminate -Wexit-time-destructors warnings | https://chromium-review.googlesource.com/c/v8/v8/+/7508964 
- 7502457: [riscv] Implement AssembleArchSelect | https://chromium-review.googlesource.com/c/v8/v8/+/7502457 
- 7484947: [riscv] Fix  incorrect code gen | https://chromium-review.googlesource.com/c/v8/v8/+/7484947 
- 实现wasm解释器 
   7364683: [riscv] Support Wasm interpreter drumbrake | https://chromium-review.googlesource.com/c/v8/v8/+/7364683 


Upstream Port
- 7495671: [riscv][sandbox] Migrate TrustedPointerTable to range-based type checks | https://chromium-review.googlesource.com/c/v8/v8/+/7495671
- 7489051: [riscv][acqrel] Added atomic acquire load and release store instructions | https://chromium-review.googlesource.com/c/v8/v8/+/7489051
- 7417239: [riscv][wasmfx] Fix cmp width in WasmFXResumeThrow | https://chromium-review.googlesource.com/c/v8/v8/+/7417239
- 7412876: [riscv] [wasmfx] Implement resume_throw | https://chromium-review.googlesource.com/c/v8/v8/+/7412876
- 7365201: [riscv] Enable trap handling for memory64 | https://chromium-review.googlesource.com/c/v8/v8/+/7365201


## Spidermonkey / Firefox

## OpenJDK

## Go

## GNU Toolchain

## LLVM Team
 ## LLVM Team
- Upstream llvm-project 合并的patch:
  - [RISCV]Remove experimental from Zalasr  https://github.com/llvm/llvm-project/pull/177120 
  - [DAG]Add ISD::SPLAT_VECTOR to TargetLowering::getNegatedExpression https://github.com/llvm/llvm-project/pull/173967
  - [RISCV] Fold (fma (splat (fneg X)), Y, Z) -> (fma (fneg (splat X)), Y, Z) https://github.com/llvm/llvm-project/pull/173808

- ruyisdk llvm-project
  - [LLVM][Clang][MC][XTHeadVector] add missing vncvt.x.x.w ：https://github.com/ruyisdk/llvm-project/pull/167

## MLIR / Buddy Compiler

## opensbi

## 罗云翔测试团队

## LuaJIT

## The Aya Theorem Prover

默认无更新。目前无员工或实习生投入。

## 参考链接
