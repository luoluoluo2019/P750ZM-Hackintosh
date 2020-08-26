# 适用于蓝天 P750ZM / Clevo P750ZM / 未来人类 X599

#### 0) 前置条件

* 使用 OC
   * Disable 掉 BIOS 中 **CFG_LOCK**
   * 如不能关闭掉 **CFG_LOCK**, 请将 config.split 中以下两项 Quirks 开启:
      * **AppleCpuPmCfgLock**
      * **AppleXcpmCfgLock**

#### 1) 平台信息

* 平台: Z97
* CPU:  E3-1231 V3
* GPU:  Nvidia K3100M (GK104)
* 声卡: ALC892(AppleALC 为自编译 layout-id: 7)
* 网卡：RTL8111/8168, Bcrm1820A

#### 2) 已知未完善问题

* 亮度
* AppleALC 略微有毛病, 耳机得插数字输出才出声(接口弄错了懒得修 233333)
