

---
title: vscode奇怪的error
date: 2022-05-25
tags:
- IDE

categories:
- IDE
---
装饰器上面 vscode 报错
Experimental support for decorators is a feature that is subject to change in a future release. Set the 'experimentalDecorators' option in your 'tsconfig' or 'jsconfig' to remove this warning.ts(1219)
```

解决方法:

settings上面加上

```javascript
"js/ts.implicitProjectConfig.experimentalDecorators": true,
```

