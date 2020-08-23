# vscode的自定义设置(工作或项目用，需配置项目中elint文件)
### 安装eslint插件、vetur插件，设置的主题为Monokai
```javascript
{
    "files.autoSave": "onFocusChange",
    "workbench.colorTheme": "Monokai",
    "editor.fontSize": 14,
    "workbench.tree.indent": 24,
    "eslint.enable": false,
    // 添加 vue 支持
    "eslint.validate": [
        "javascript",
        "javascriptreact",
        "vue",
    ],
    // #让prettier使用eslint的代码格式进行校验
    "prettier.eslintIntegration": true,
    "vetur.format.defaultFormatter.html": "js-beautify-html",
    // #让vue中的js按编辑器自带的ts格式进行格式化
    "vetur.format.defaultFormatter.js": "vscode-typescript",
    "vetur.format.defaultFormatterOptions": {
        "js-beautify-html": {
            "wrap_attributes": "force-aligned"
            // #vue组件中html代码格式化样式
        }
    }
}
```
