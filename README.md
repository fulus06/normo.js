## 还在开发中，请不要再生产环境中使用

# normojs

#### 介绍 - 开发中，请不要在开发环境中使用... ...
一个类似nuxtjs的框架，基于vue3、vite2



## monorepo

```js
|- root
	|- packages
		|- nomorjs
		|- @normojs-component // @normojs/component
        |- @normojs-html		// @normojs/html
        |- @normojs-layout	// @normojs/layout
        |- @normojs-package // 主要的，整合各个内置模块
        |- @normojs-page		// @normojs/page
        |- @normojs-plugin // @normojs/plugin
        |- @normojs-store // @normojs/store
        index.ts
        type.ts
	|- pnpm-workspace.yaml
	
```





## Template

branch: [template](./tree/template )



## Framework



## Framework

branch: [master](./tree/master)





#### 软件架构
*  [Vue3](https://github.com/vuejs/vue-next), [Vite2](https://github.com/vitejs/vite), [ESBuild](https://github.com/evanw/esbuild)
* [基于文件系统的路由](https://github.com/hannoeru/vite-plugin-pages)
* [按需自动导入组件](https://github.com/antfu/vite-plugin-components)
* TypeScript
* [standardjs](https://github.com/standard/standard) - 代码规范

#### X 安装教程

```shell
# 下载代码
git clone https://gitee.com/source-code-online/normojs.git

cd normojs

# 安装依赖包
yarn i

# 本地调试normojs
npm link

# 运行normojs
yarn run dev

# 运行demo
yarn run example:dev
```



#### 使用说明

1.  xxxx
2.  xxxx
3.  xxxx



doc: https://juejin.cn/post/6844903702453551111

#### 参与贡献

1.  Fork 本仓库
2.  新建 Feat_xxx 分支
3.  提交代码
4.  新建 Pull Request