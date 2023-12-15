
Vue + SpringBoot实现的博客系统

线上地址：<a target="_blank" href="http://blog.shiminghui.top">For Fun</a>

## ssr 服务端渲染版本 

<a href="https://github.com/shimh-develop/blog-vue-springboot/tree/ssr" target="_blank">ssr分支</a>

# 技术

## 前端  blog-app

- Vue
- Vue-router
- Vuex
- ElementUI
- mavon-editor
- lodash
- axios
- Webpack

## 后端  blog-api

- SpringBoot
- Shiro
- Jpa
- Redis
- Fastjson
- Druid
- MySQL
- Maven

# 运行

将项目clone到本地

## 方式一  直接运行SpringBoot项目（已将打包的静态文件放到了 resources/static下）
1. 将blog-api导入到IDE工具中
2. resources/sql/blog-schema.sql、blog-data.sql导入MySQL数据库
3. 打开Redis数据库
4. resources/application.properties 修改MySQL、Redis连接
5. Runas运行,访问：http://localhost:8888

## 方式二  前后分离（开发方式）
1. 按方式一运行blog-api，提供api数据接口
2. 打开命令行
	> cd blog-app

	> npm install

	> npm run dev

3. 访问：http://localhost:8080
4. 修改blog-app/src 下的文件进行开发
5. npm run build 生成最终静态文件



