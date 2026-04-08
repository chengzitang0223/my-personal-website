# 02-Components: 基础组件库 (Apple Style)

## 1. 按钮 (Buttons)
* **主按钮 (Primary Action)**：如“立即选课”、“预约私教”。必须是胶囊形状、苹果蓝背景、白色文字。
    * Tailwind 类名约束：`bg-blue-600 text-white px-6 py-2 rounded-full font-medium hover:bg-blue-700 transition-colors`
* **次级按钮 (Secondary Action)**：如“了解更多”。通常是浅灰色胶囊，或者单纯的蓝色文字链接带箭头 (Learn more >)。

## 2. 数据输入 (Inputs & Forms)
* **极简输入框**：摒弃四周的粗边框。使用浅色背景填充、超大圆角、或者仅底部边框的极简样式。
* **交互反馈**：Focus 状态下，边框或外发光需变为 `ring-blue-500`，过渡动画必须平滑。

## 3. 数据展示卡片 (Cards)
* **无边框卡片**：依靠背景色差（`bg-[#F5F5F7]`）和轻微的阴影来区分卡片，禁止使用生硬的 `border`。
* **内边距**：必须极其充裕，通常使用 `p-8` 或更大，让内容“呼吸”。