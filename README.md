# Prototype

这是一个高保真原型设计项目，使用 HTML + Tailwind CSS 实现，旨在提供接近真实 App 的用户界面和交互体验。


## 如何复刻？
### 进入Deepseek https://chat.deepseek.com/
### 指令
```
我想开发一个{类似小宇宙的播客app}，现在需要输出高保真的原型图，请通过以下方式帮我完成所有界面的原型设计，并确保这些原型界面可以直接用于开发：

1、用户体验分析：先分析这个 App 的主要功能和用户需求，确定核心交互逻辑。

2、产品界面规划：作为产品经理，定义关键界面，确保信息架构合理。

3、高保真 UI 设计：作为 UI 设计师，设计贴近真实 iOS/Android 设计规范的界面，使用现代化的 UI 元素，使其具有良好的视觉体验。

4、HTML 原型实现：使用 HTML + Tailwind CSS（或 Bootstrap）生成所有原型界面，并使用 FontAwesome（或其他开源 UI 组件）让界面更加精美、接近真实的 App 设计。

拆分代码文件，保持结构清晰：

5、每个界面应作为独立的 HTML 文件存放，例如 home.html、profile.html、settings.html 等。

- index.html 作为主入口，不直接写入所有界面的 HTML 代码，而是使用 iframe 的方式嵌入这些 HTML 片段，并将所有页面直接平铺展示在 index 页面中，而不是跳转链接。

- 真实感增强：

- 界面尺寸应模拟 iPhone 15 Pro，并让界面圆角化，使其更像真实的手机界面。

- 使用真实的 UI 图片，而非占位符图片（可从 Unsplash、Pexels、Apple 官方 UI 资源中选择）。

- 添加顶部状态栏（模拟 iOS 状态栏），并包含 App 导航栏（类似 iOS 底部 Tab Bar）。

请按照以上要求生成完整的 HTML 代码，并确保其可用于实际开发。
```

## 项目特点

- 基于 iOS 设计规范的现代化界面
- 使用 Tailwind CSS 构建响应式布局
- FontAwesome 图标集成
- 模拟 iPhone 15 Pro 尺寸和界面特征
- 集成真实 UI 资源和图片
- iframe 方式组织多页面展示
