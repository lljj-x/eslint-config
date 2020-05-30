# eslint-config-lj
## 说明
基于 eslint-config-airbnb-base 结合个人习惯的eslint风格

## 安装
npm
``` bash
npm install eslint-config-lj -D
```

yarn 
``` bash
yarn add eslint-config-lj --dev
```

### 启用
在项目根目录添加 `.eslintrc` 文件
``` json
{
    "extends": "eslint-config-lj",
    "plugins": [
    ],
    "rules": [
    ]
}
```

### 集成
1. Webpack 需要安装 [eslint-loader](https://www.npmjs.com/package/eslint-loader)
2. Rollup 需要安装 [rollup-plugin-eslint](https://www.npmjs.com/package/rollup-plugin-eslint)
