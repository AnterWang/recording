# vscode的自定义设置(个人)
### 安装eslint插件、vetur插件，设置的主题为Monokai
```javascript
{
    "files.autoSave": "onFocusChange",
    "workbench.colorTheme": "Monokai",
    "editor.fontSize": 14,
    "workbench.tree.indent": 24,
    "vetur.validation.template": false,
    "vetur.experimental.templateInterpolationService": false,
    "eslint.enable": false,
    "vetur.format.options.tabSize": 4,
    "vetur.format.defaultFormatterOptions": {
        "prettier": {
            // 格式化不加分号
            "semi": false,
            // 格式化为单引号
            "singleQuote": true
        }
    },
    "vetur.format.defaultFormatter.js": "vscode-typescript", // 不默认对JS使用了prettier,(解决js自动换行)
    // 在方法括号之间插入空格
    "javascript.format.insertSpaceBeforeFunctionParenthesis": true,
    "explorer.confirmDelete": false
}
```
