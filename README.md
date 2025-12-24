# English Streak

一个用于记录英语学习时间的日历应用，配合李笑来的「Enjoy」使用。

## 功能特性

- 📅 **月历视图** - 查看每日学习时长，支持直接编辑
- 📊 **统计仪表盘** - 展示 streak、总时长、学习趋势等
- 🗓️ **年历视图** - 12 个月概览，一目了然
- 🔥 **连续打卡** - 自动计算连续学习天数
- 🏆 **成就系统** - 达成目标解锁成就徽章
- 📱 **响应式设计** - 完美支持手机和桌面端
- 💾 **数据持久化** - 本地存储，支持导出导入

## 在线访问

**https://yingyujilu.netlify.app**

## 技术栈

- React 18
- Babel (JSX 编译)
- Tailwind CSS (样式)
- localStorage (数据存储)

## 部署说明

### 方法一：Netlify（推荐，最简单）

1. 注册 [Netlify](https://netlify.com)
2. 将本项目拖拽到 Netlify 面板
3. 自动部署完成，获得访问链接

### 方法二：GitHub Pages

1. 将项目上传到 GitHub 仓库
2. 进入仓库 Settings > Pages
3. 选择 `main` 分支，保存
4. 访问 `https://你的用户名.github.io/仓库名`

### 方法三：本地运行

```bash
# 直接用浏览器打开 index.html
open index.html

# 或使用本地服务器
npx serve .
```

## 数据备份

点击右上角设置按钮，可导出/导入数据：

- **导出数据** - 复制 JSON 数据到剪贴板
- **导入数据** - 粘贴 JSON 数据恢复

建议定期导出备份，防止数据丢失。

## 文件结构

```
english-streak/
├── index.html      # 主应用文件
├── README.md       # 说明文档
└── .gitignore      # Git 忽略文件
```

## 自定义

### 修改每日目标

点击右下角 `Goal: 30m` 按钮设置。

### 添加更多名言

在代码中搜索 `quotes` 数组，添加你喜欢的句子。

## 许可证

MIT
