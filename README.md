# 中文-印尼语语音翻译

一个支持两种语音输入模式的实时翻译应用。

## 功能

### 双模式语音输入
- **按住说话**: 按住按钮说话，松开后自动翻译
- **实时监听**: 点击开始后持续监听语音，自动分段翻译

### 语言支持
- 中文 ↔ 印尼语 互译
- 可一键切换翻译方向

### 其他功能
- 自动朗读翻译结果
- 翻译历史记录
- 完全免费使用

## 如何使用

### 方法 1: 直接打开（推荐）
```bash
open /Users/wanghuajie/tmp/indo-translator/index.html
```

### 方法 2: 本地服务器
```bash
cd /Users/wanghuajie/tmp/indo-translator
python3 -m http.server 8000
# 然后访问 http://localhost:8000
```

## 浏览器要求
- Chrome/Edge (推荐)
- Safari (iOS 14.2+)

## 注意事项
1. 首次使用需要允许麦克风权限
2. 翻译服务使用 MyMemory 免费 API
3. 语音识别质量取决于设备和环境