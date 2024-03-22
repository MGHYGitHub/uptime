来自于 [site-status](https://github.com/MGHYGitHub/site-status) 项目

## 如何使用

- 按照下方部署操作来安装依赖
- 在 `.env` 文件中进行配置修改
- 将打包后的文件上传至网站空间或者直接使用 `Vercel` 或者 `Cloudflare` 直接部署该项目
- 在src/components/footer.jsx 修改页面的一些显示内容`可自定义修改`

## 部署

### 安装依赖

```bash
# 若没有 pnpm
npm install pnpm -g

# 安装依赖
pnpm install
```

### 开发

```bash
pnpm dev
```

### 打包

```bash
pnpm build
```