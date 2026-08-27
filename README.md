# Custom Merch Landing Page

一个适用于商品主图展示与店铺引流的极简响应式落地页模板。

## 在线访问

https://tommylee1208com-666.github.io/test1/

## 功能

- GitHub 图床图片展示
- 图片保持原始比例，不裁剪、不变形
- 顶部公告文字自动轮播及左右切换
- 桌面端和移动端自适应
- Shop 按钮跳转至指定店铺
- 支持 GitHub Pages 静态托管

## 修改内容

日常使用只需要编辑 `config.js`：

```js
const SITE_CONFIG = {
  imageUrl: '你的图片URL',
  shopUrl: '你的店铺URL',
  announcements: [
    '第一条轮播文字',
    '第二条轮播文字',
    '第三条轮播文字'
  ],
  announcementInterval: 3500
};
```

- `imageUrl`：页面中央展示的图片地址
- `shopUrl`：点击 Shop 后打开的店铺地址
- `announcements`：顶部轮播文案，可自由增删
- `announcementInterval`：轮播间隔，单位为毫秒

## GitHub Pages

仓库的 GitHub Pages 发布地址：

https://tommylee1208com-666.github.io/test1/
