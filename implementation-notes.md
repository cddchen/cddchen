# Implementation Notes

## 布局与结构精简记录

### 变更详情
1. **删除顶部横幅图片**：完全去除 `Featured Projects · 精选置顶` 上方的图片组件（`assets/liquid-banner.svg` 及居中容器），使主页一进入直接以代表作项目为第一视觉焦点。
2. **删除技术栈与工具链模块**：移除了全部第三方 Badges 徽章。
3. **删除研发活跃度与提交统计模块**：移除了 Streak Stats 外部卡片。
4. **删除访问量计数器**：移除了 Profile Views 计数徽章。
5. **当前最终呈现**：
   - 纯粹聚焦于 4 个核心置顶开源项目（`antigravityide2api`、`cursoride2api`、`codex2claude`、`bilibili-study`）。
   - 保持极客极简质感，零外部第三方图片依赖，首屏即为高价值项目。
