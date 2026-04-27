# 发票侦探官网

这是一个可直接静态部署的产品官网目录，适合先快速上线，再补充正式域名、下载地址、产品截图和法务文本。

## 当前特点

- SEO 友好的静态首页
- 已包含 `title`、`description`、关键词、Open Graph、JSON-LD
- 已包含下载入口、FAQ、隐私政策、用户协议、`robots.txt`、`sitemap.xml`
- 使用酒红色品牌方向，贴合你们现有强调色 `#92000D`

## 上线前需要替换的内容

1. `index.html` 里的 `https://www.example.com/` 为正式域名
2. `APP_STORE_URL` 为 iOS 下载地址
3. `ANDROID_DOWNLOAD_URL` 为 Android 应用市场或 APK 地址
4. `mailto:hello@example.com` 为正式商务邮箱
5. 若拿到真实 App 截图，可替换首页的示意卡片区域

## 模板参考方向

当前页面结构参考了 GitHub 上常见的 SaaS / startup landing page 模板信息架构，尤其适合功能清晰、需要下载转化和 SEO 的工具型产品。

- `NextJSTemplates/startup-nextjs`
- `onwidget/astrowind`
- `web3templates/nextly-template`

由于当前工作区没有直接拉取 GitHub 依赖，这里采用了可离线编辑和部署的静态实现方式，方便你们马上继续填内容和上线。