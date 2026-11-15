# popstar cheat — 发布页

## 下载

- [popstar-cheat.ipa](https://github.com/niulailab/ps-release/releases/download/v2.0/popstar-cheat.ipa) — 19,865 字节
- [popstar.dylib](https://github.com/niulailab/ps-release/releases/download/v2.0/popstar.dylib) — 97,056 字节

sha256：
```
ipa    1beceeda5e163170a2e8d50c2176979324d2ae82fa4f6cace3eb774c4a1064b9
dylib  1954074be816c2f0fa98e7862b23130799c8becb3f43d8de1bca117f50277f10
```

## 装法

1. 全能签 → 导入 → 选 `popstar-cheat.ipa`
2. 选你的证书 → 签名 → 安装
3. 打开后看到黑底绿字 + 右上角蓝色「消」球 = dylib 在无 substrate 环境加载成功

## 说明

- 这是**宿主验证包**，不是天天爱消除本体，用于验证注入链路
- dylib 为 arm64，依赖只有系统库，不需要 CydiaSubstrate
- 源码在私有仓库，不在此处
