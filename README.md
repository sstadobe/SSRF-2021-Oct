# SSRF-2021-Oct

# Schedule

<!-- <details> -->
<!-- <summary>时间表</summary> -->

<!-- ![Alt][schedule] -->

<!-- </details> -->

```
SSRF-快速成像线站 10.29-10.31 (3)
```

---
---

</details>

# 设备Checklist

### 加载
- [ ] 垂直炮
  - [ ] PC窗口问题
  - [ ] 电探针触发/磁测速触发问题?
  - [ ] Fire 2 Impact delay
  - [ ] 弹托 铜环触发
  - [ ] 样品架
- [ ] 霍普金森杆
  - [ ] 触发问题
  - [ ] 时序问题

### 诊断
- [ ] 超快成像
  - [ ] 成像一套（匹配PI?/ SAZ?）
  - [ ] 闪烁体 LuAG:Ce（15x15 多带几片，容易碎）
- [ ] 超快衍射
  - [ ] **衍射一套（匹配PI + MCP?） @北京，邮寄去上海？**
  - [ ] MCP适配？
    - [ ] MCP电源及其接线
  - [ ] PI分幅？
  - [ ] 打孔闪烁体？
  - [ ] 近摄镜
  - [ ] 镜头
  - [ ] Canon/Nikon口适配
  - [ ] 固定板
  - [ ] 分光板

### 时序
- [ ] 示波器（至少2个）
- [ ] **DG535x5至少? + DG645?@北京？**
- [ ] PDV? rc盒子？
- [ ] 快慢门控制?
- [ ] **超多BNC线（以及长度）@北京**
- [ ] BNC <-> SMA

### 样品
- [ ] 静态测试
  - [ ] 标样
  - [ ] 强织构AZ31
  - [ ] 弱织构Al
  - [ ] 粗晶Co
  - [ ] 单晶Si
  - [ ] 多晶Diamond

### 配件
- [ ] **位移台及其控制@北京**
- [ ] **pinhole/slits@北京**
- [ ] 阻抗匹配
- [ ] **burnpaper@北京?**
- [ ] 吸收Al片
- [ ] 网线
- [ ] USB延长线

### 注意问题
- [ ] 有些信号多路连接带不动，需要DG转一下
- [ ] DG535低电平inhibit


[schedule]:data:image/png;base64,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