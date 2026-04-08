# 01-Tokens: 设计原子 (Apple Style)

## 1. 色彩系统 (Color Tokens in Tailwind)
* **背景色 (Backgrounds)**：
    * 浅色模式：主背景使用极致纯白 `bg-white`，次要卡片背景使用极浅灰 `bg-zinc-50` 或 `bg-[#F5F5F7]`。
    * 深色模式：主背景使用纯黑 `dark:bg-black`，次要卡片使用深灰 `dark:bg-[#1D1D1F]`。
* **文字色 (Typography)**：
    * 主要文字：`text-zinc-900` (暗黑: `text-white`)
    * 次要/辅助文字：`text-zinc-500` (暗黑: `text-zinc-400`)
* **强调色/链接色 (Accent/CTA)**：
    * 经典的“苹果蓝”：`bg-blue-600` / `text-blue-600`。

## 2. 排版系统 (Typography)
* **字体族**：强制优先使用系统默认无衬线字体（San Francisco）：`font-sans`。
* **字阶对比**：
    * Hero大标题（如展示健身房 Slogan）：`text-5xl md:text-7xl font-bold tracking-tight`
    * 模块标题（如“我的课程”）：`text-2xl font-semibold tracking-tight`
    * 正文：`text-base font-normal leading-relaxed`

## 3. 形状与材质 (Shapes & Materials)
* **圆角**：卡片使用大圆角 `rounded-2xl` 或 `rounded-3xl`；按钮使用胶囊圆角 `rounded-full`。
* **毛玻璃 (Glassmorphism)**：顶部导航栏或弹窗背景强制使用 `bg-white/70 backdrop-blur-md border-b border-zinc-200/50`。