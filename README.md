# learning-hypervisor-record-from-yao-li-xing

![hypervisor](picture/logo.jpg)

> 学习 hypervisor 相关内容的记录仓库。
> - 暑期日志：`docs/logs/summer-2025.md`，记录龙芯实习的日报
> - 2025 年 11 月日志：`docs/logs/2025-11.md`，从 0 构建精简化的 RISC-V hypervisor，学习 hypervisor 机理

## 快速导航

- [学习日志 Logs](#学习日志-logs)
- [专题笔记 Notes](#专题笔记-notes)
- [资料 / 链接 Resources](#资料--链接-resources)

## 学习日志 Logs

记录不同阶段的 hypervisor 学习进展，详细内容在对应日志文件中。

- [2025-summer（暑期学习日志，LoongArch 实习）](docs/logs/summer-2025.md)
- [2025-11（月度日志，RISC-V hypervisor 从 0 实验）](docs/logs/2025-11.md)

## 专题笔记 Notes

与具体主题相关的笔记，位于 `docs/notes/` 目录。

- [LoongArch 虚拟化环境开启（hvisor 提取）](docs/notes/hvisor_note.md)
- [LoongArch 启动流程 boot.rs 分析](docs/notes/boot.md)
- [两阶段地址翻译与嵌套页表（LoongArch）](docs/notes/spt.md)
- [RISC-V Hypervisor 实验笔记](docs/notes/riscv_hypervisor.md)
- [Axvisor main.rs 启动分析](docs/notes/axvisor_start.md)
- [月报(7.10 - 8.10)](docs/notes/monthly_report_(7.10-8.10).md)
- jailhouse 学习过程中未整理的一些笔记: docs/notes/jailhouse_hivisor

## 资料 / 链接 Resources

收集和 hypervisor / virtualization 相关的书籍、论文和白皮书（本地 pdf）：

- [ACRN: a big little hypervisor for IoT development (Li et al., 2019)](docs/resources/2019-li-acrn-big-little-hypervisor-iot.pdf)
- [Understanding Full Virtualization, Paravirtualization, and Hardware Assist](docs/resources/Understanding%20Full%20Virtualization,%20Paravirtualization,%20and%20Hardware%20Assist.pdf)
- [KVM virt book](docs/resources/virt_book.pdf)
