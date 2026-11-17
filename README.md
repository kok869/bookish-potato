# html-practice

《创新实践1》第 3—4 周的前端练习：两个用 HTML / CSS / JavaScript 写成的单文件页面，双击即可在浏览器打开，无需安装任何环境。

## 两个页面

| 文件 | 页面 | 涉及的技术点 |
|---|---|---|
| `index.html` | 个人主页 | 语义化标签、Flex 居中布局、Grid 双列、盒模型（`padding` / `border-radius` / `box-shadow`）、`@media` 响应式、`@keyframes` 进度条动画 |
| `todo.html` | 待办清单 | DOM 查询（`getElementById`）、动态创建元素（`createElement` / `appendChild`）、事件绑定（`onclick` / `keydown`）、`classList.toggle` 切换样式、`textContent` 防止 HTML 注入 |

## 怎么打开

直接双击 HTML 文件，浏览器就会渲染；或用 VS Code 的 Live Server 插件打开，改动后自动刷新。

## 学习进度说明

个人主页里的"学习进度"条不是熟练度评分，而是 8 周计划的实际推进程度，用来诚实地记录自己站在哪一步：

- **已动手改写**：HTML / CSS —— 能改结构、改样式，看得懂盒模型
- **能读懂 AI 代码**：JavaScript / DOM —— 能讲清"选中元素 → 绑定事件 → 改页面"这条链路
- **概念在读**：Vue、后端接口、MySQL —— 讲得清各自解决什么问题，代码尚未跑通
- **已接入工具链**：Git / GitHub —— 通过 WorkBuddy 的 GitHub 连接器完成授权与提交

## 后续计划

1. 用 Vue 重写待办清单，对比两版各写多少行，看清框架的价值
2. 写后端接口把待办存进 MySQL，跑通"页面 → 接口 → 数据库"的完整闭环
3. 用 Docker 把项目跑起来，得到一个可以访问的部署地址

## 关于代码来源

两个页面都是在 AI 生成的初版基础上改写而成。改写原则是：**没读懂、没改动过的代码不算学会**，每一处改动都能说清为什么改。
