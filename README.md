# Birthday Celebration Webpage

一个充满爱意的生日祝福网页，采用现代化设计风格，融合了 Apple 风格的简约美学。

## 功能特点

### 1. 视觉设计
- 现代简约的界面设计
- 温暖的配色方案
- 流畅的动画效果
- 响应式布局，适配各种设备

### 2. 交互功能
- 浮动爱心背景动画
- 照片墙画廊展示
- 时间轴记忆墙
- 互动记忆配对游戏
- 生日愿望许愿功能

### 3. 音乐播放器
- 唱片机风格设计
- 平滑的淡入淡出效果
- 播放/暂停/静音控制
- 动态旋转动画

### 4. 页面板块
- 主页欢迎区
- 照片墙区域
- 爱的留言区
- 音乐播放区
- 记忆游戏区

## 技术栈
- HTML5
- CSS3 (动画, Flexbox, Grid)
- JavaScript (原生)
- Font Awesome 图标库

## 项目结构
```
birthday-celebration/
├── README.md
├── .gitignore
├── modern-birthday.html
└── assets/
    └── bgm.mp3
```

## 使用说明

1. 克隆仓库：
```bash
git clone [repository-url]
```

2. 准备音乐文件：
- 在项目根目录创建 `assets` 文件夹
- 将背景音乐文件重命名为 `bgm.mp3` 并放入 `assets` 文件夹

3. 运行：
- 使用现代浏览器直接打开 `modern-birthday.html` 文件
- 或通过本地服务器访问（推荐）

## 自定义修改

### 更换图片
1. 在 HTML 文件中找到 `gallery` 部分
2. 替换 `img` 标签的 `src` 属性为新的图片 URL

### 修改文字内容
1. 可以修改各个部分的文字内容
2. 时间轴事件可以根据实际情况调整

### 更换音乐
1. 将新的音乐文件命名为 `bgm.mp3`
2. 替换 `assets` 文件夹中的原文件

## 注意事项
- 建议使用现代浏览器访问（Chrome, Firefox, Safari 等）
- 音乐自动播放可能需要用户手动触发
- 图片建议使用 CDN 或压缩后的本地文件

## License
MIT License 