# 入门用 CPU

该项目同时包含主板与 CPU 的电路逻辑，以 Verilog HDL 写成，仅供用于测试。

使用近似 X86/64 指令集的自定指令集架构（会给参考文档），在做到实现 X86/64 大部分功能的基础上尽可能简单，以方便作硬件设计迁移。
（例如迁移到 Minecraft 下，以红石电路实现）

参考了 AZ Processor。