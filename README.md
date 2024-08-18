![首页]

* **最新技术栈**：使用 Vue3、Vite4 等前端前沿技术开发
* **TypeScript**: 应用程序级 JavaScript 的语言
* **主题**: 可配置的主题
* **国际化**：内置完善的国际化方案
* **权限**：内置完善的动态路由权限生成方案
* **组件**：二次封装了多个常用的组件
* **示例**：内置丰富的示例

## 技术栈

| 框架                                                                   | 说明               | 版本     |
|----------------------------------------------------------------------|------------------|--------|
| [Vue](https://staging-cn.vuejs.org/)                                 | Vue 框架           | 3.3.8 |
| [Vite](https://cn.vitejs.dev//)                                      | 开发与构建工具          | 4.5.0  |
| [Element Plus](https://element-plus.org/zh-CN/)                      | Element Plus     | 2.4.2 |
| [TypeScript](https://www.typescriptlang.org/docs/)                   | JavaScript 的超集   | 5.2.2  |
| [pinia](https://pinia.vuejs.org/)                                    | Vue 存储库 替代 vuex5 | 2.1.7 |
| [vueuse](https://vueuse.org/)                                        | 常用工具集            | 10.6.1 |
| [vue-i18n](https://kazupon.github.io/vue-i18n/zh/introduction.html/) | 国际化              | 9.6.5  |
| [vue-router](https://router.vuejs.org/)                              | Vue 路由           | 4.2.5  |
| [unocss](https://uno.antfu.me/)                                      | 原子 css          | 0.57.4  |
| [iconify](https://icon-sets.iconify.design/)                         | 在线图标库            | 3.1.1  |
| [wangeditor](https://www.wangeditor.com/)                            | 富文本编辑器           | 5.1.23 |

## 开发工具

推荐 VS Code 开发，配合插件如下：

| 插件名                           | 功能                  |
|-------------------------------|---------------------|
| Vue - Official                | Vue 与 TypeScript 支持 |
| unocss                        | unocss for vscode   |
| Iconify IntelliSense          | Iconify 预览和搜索       |
| i18n Ally                     | 国际化智能提示             |
| Stylelint                     | Css    格式化          |
| Prettier                      | 代码格式化               |
| ESLint                        | 脚本代码检查              |
| DotENV                        | env 文件高亮            |


## 启动
npm install --legacy-peer-deps --registry https://registry.npmmirror.com/
## npm install -g pnpm
npm run dev

## 拉取代码
git pull https://github.com/wenly84/bjzjf-boot-front.git
git add .
git commit -m "init
git branch -M master
git remote add origin https://github.com/wenly84/bjzjf-boot-front.git
git push -u origin master


## 设置代理和取消设置代理
git config --global http.proxy 用户名:密码@IP:端口
git config --global https.proxy 用户名:密码@IP:端口

git config --global https.proxy  wenly84:密码@127.0.0.1:7890
git config --global --unset http.proxy
git config --global --unset https.proxy

git config --global --list