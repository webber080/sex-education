# sex-education

青春期性教育成长课单页（家长陪同阅读向）。线上地址：https://sex.supertato.top

纯静态 HTML + 教科书医学插画。部署到 Cloudflare Pages（项目名 `sex`）：

```bash
npx wrangler pages deploy . --project-name sex --branch main
```

注意：部署目录只放 index.html 与 img/，不要把构建脚本带上线上。
