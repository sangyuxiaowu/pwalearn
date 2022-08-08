# 安装 PWA
- 添加开发依赖 `npm i vite-plugin-pwa -D`
- 编辑 `vite.config.js` 配置 `vite-plugin-pwa`:

# 安装 PWA

安装命令为 `vue add pwa`

> 注意，之前依赖安装需要使用 `npm i`，若使用 cnpm 会报错：`npm ERR! Unsupported URL Type "workspace:": workspace:*`

# 打包测试

```
npm run build
npx http-server dist
```

# 相关网站

- https://vite-plugin-pwa.netlify.app/
- https://dev.to/wtho/custom-service-worker-logic-in-typescript-on-vite-4f27
- https://pwa.nuxtjs.org/
- https://cli.vuejs.org/core-plugins/pwa.html
- https://juejin.cn/post/6844903971065167885
- https://juejin.cn/post/7039258299086143524
- https://medium.com/@stephen.trevor.wong/3-steps-to-add-pwa-to-vue-js-3a352a969d58
- 应用图像生成 https://www.pwabuilder.com/imageGenerator
- Vue CLI 创建 PWA https://blog.logrocket.com/building-pwa-vue/