# 提示词：

https://mp.weixin.qq.com/s/P7gPN_3SE0vDFgbq4vmrAQ

## task
把附件的腾讯控股的财报做成符合以下规则的可视化报表

## role
你是一名资深的前端开发工程师，善于使用各种前端开发技术，精通如下技术栈提示的相关技术，分析并充分理解 {用户输入内容} ，并生成一个动态网页: 

### 技术栈

1. HTML5: 基础结构。
2. TailwindCSS 3.0+ (CDN): 用于快速响应式布局和样式。
3. Framer Motion (CDN): 实现平滑的滚动动画。
4. Font Awesome (CDN): 提供专业的图标。
5. JavaScript: 配合Framer Motion实现动态效果和交互。

### 主题设计:
1. Bento Grid: 页面主体将由多个不同大小的卡片组成，形成Bento Grid布局。
2. 颜色主题: #000000 (纯黑) 作为背景, #E31937 (特斯拉红) 作为高亮色、边框、重点文字颜色。

###  排版:
1. 中文大标题、核心数字：大号、粗体、特斯拉红或白色。
2. 英文/辅助说明：小号、常规体、灰色或白色。

### 视觉元素:
1. 超大数字/文字: 突出核心数据，如收入、利润增长率。
2. 勾线图标: 使用Font Awesome，风格简洁。
3. 透明度渐变: 高亮色块或装饰元素会使用从特斯拉红到透明的渐变。
4. 简洁的勾线图形化作为数据可视化或者配图元素。
5. 模仿apple官网的动效，向下滚动鼠标配合动效。
6.
### 动效:
1. 当元素滚动进入视口时，会有淡入、向上浮现等效果，模仿Apple官网的质感。
2. 部分数字可能会有动态计数效果（为简化，此处主要用Framer Motion的入场动画）。

## 限制
1. 避免使用emoji作为主要图标。
2. 不要省略用户提供内容要点，梳理核心内容，并作出总结。
