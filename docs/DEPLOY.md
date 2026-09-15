# 部署说明

目标地址：`https://leoncheung033.github.io`

## 费用

使用公开仓库部署 GitHub Pages 不需要付费。GitHub Free 支持公开仓库的
Pages；若希望源代码和照片所在仓库保持私有，则需要支持 private repository
Pages 的付费方案。使用默认的 `github.io` 域名也不需要购买域名。

自定义域名是可选项，费用仅来自域名注册商；GitHub Pages 本身仍可免费托管，
并支持 HTTPS。

## 首次发布

以下操作只有在 Leon 明确授权发布后才能执行：

1. 在 GitHub 账号 `LeonCheung033` 下创建公开仓库
   `leoncheung033.github.io`，不要初始化 README、license 或 `.gitignore`。
2. 在本地检查待发布内容，特别是个人照片和 Reze 图片。
3. 将个人仓库添加为 `origin`，保留 al-folio 模板为只读 `upstream`。
4. 创建首次 commit，并推送到 `main`。
5. 等待 **Deploy site** workflow 创建 `gh-pages` 分支。
6. 在仓库 **Settings → Pages** 中选择 **Deploy from a branch**，发布分支设为
   `gh-pages`，目录设为 `/ (root)`，然后访问目标地址。

## 发布前检查

- 再次取得 Leon 对公开上传个人照片和整个站点的明确授权。
- 确认 Reze 图片的来源、公开使用权限与必要署名。
- 确认页面没有公司内部信息、未公开研究内容、密钥或个人隐私数据。
- 运行格式检查、Jekyll build 和 al-folio upgrade audit。
