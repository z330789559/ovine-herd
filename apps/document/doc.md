### BUG

- 切换账号/登录页面无法跳转，只有刷新页面才能跳转
- 子应用相互切换导致无法 顺利跳转
- 应用 APP 项目，路由跳转，路由组件，在 qiankun 模式下会刷新两次。（赞未找到有原因）

### 优化

- 应用切换有短暂白屏
- 页面初始化 loading，显示/隐藏 有点突兀
- 应用 配置的页面，切换时有闪动。因为先读接口，再渲染页面
