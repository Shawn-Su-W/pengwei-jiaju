# 鹏伟家居订单后台版

包含：
- index.html：客户浏览商品、加入购物车、填写姓名电话地址并提交订单
- admin.html：订单管理后台，查看订单、销售金额、浏览次数、商品点击
- config.js：填写 Supabase 数据库连接信息
- setup.sql：创建订单表和访问统计表
- images：商品图片

## 使用步骤

1. 上传本文件夹内的 `index.html`、`admin.html`、`config.js`、`setup.sql` 和 `images` 文件夹到 GitHub。
2. 打开 Supabase，新建项目。
3. 在 Supabase 的 SQL Editor 里执行 `setup.sql`。
4. 在 Supabase 的 Authentication → Users 中创建一个管理员用户。
5. 在 Supabase 的 Project Settings → API 中复制 Project URL 和 anon public key。
6. 修改 `config.js`，填入你的 Project URL 和 anon public key。
7. 访问网站首页：`https://你的用户名.github.io/pengwei-jiaju/`。
8. 访问后台：`https://你的用户名.github.io/pengwei-jiaju/admin.html`。

说明：这是 GitHub Pages + Supabase 的轻量订单后台方案，不需要自己买服务器。真正自动在线支付仍需要微信支付/支付宝商户号和后端支付接口。
