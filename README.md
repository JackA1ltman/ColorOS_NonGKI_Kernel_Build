| 内核作者 | 对应系统 | 设备 | 命名 |
|---|---|---|---|
| toraidl | ColorOS 16 | 一加8系列 | original |
| JackA1ltman - toraidl | ColorOS 15/16 | 一加8系列 | upstream-dev |
| JackA1ltman - Wcedla | ColorOS 16 | 一加8系列 | original, upstream-dev |

### 必读事项
1. DTB版本一加8全系可刷入
2. Anykernel3包命名规则：
    - 设备名称-系统版本-内核作者-内核说明/分支名称-时间-无/DTB
    - 内核说明/分支名称中
        - original 代表该内核为作者的原始版本，即除了为编译通过所做修改外，无其他任何修改
        - 其他名称均为个人维护的版本
3. KernelSU
    - AK3包命名存在-ksu则为携带KernelSU的版本
    - 管理器为[ReSukiSU](https://github.com/ReSukiSU/ReSukiSU)
4. KPM
    - 支持ReSukiSU
